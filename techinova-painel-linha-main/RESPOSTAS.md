# Respostas do LAB 01

Nome:Murilo Abila Fernandes
Matricula: Não tenho acesso
Dupla (M2 em diante):Lucas Daniel Rodrigues

---

## M2 - Quem quebrou o painel

**Hash curto do commit que introduziu o erro:**
7ad68265c1a0f5701f137ba4f0281126f2b7e3cb
**Autor:**
Diego Ferraz
**Data:**
22 maio
**Linha alterada (antes e depois):**

```
antes:  function converterTemperatura(leitura) {
  return (leitura - 32) * 5 / 9;
}

depois: function converterTemperatura(leitura) {
  return leitura * 9 / 5 + 32;
}
```

---

## M3 - O segredo vazado

**O que voce esperava ver no `git status` e o que apareceu:**
Achei que seria feito um código base para depois do comando, mas apareceu um erro dizendo que não havia oque ser commitado pois ele excluiu

**Depois do push, alguem que clonar o repositorio ainda consegue ler a chave?
Responda em duas linhas, explicando o motivo:**
Sim ainda dá para ler a chave, pois o git salva todas as alterações 
mesmo com os arquivos escondidos ou apagados eles ficam guardados.
---

## M4 - Colisao

**NÃO CONSEGUIMOS FAZER O FORK COLABORADO**

**O que significavam os marcadores que apareceram dentro do arquivo:**

- `<<<<<<<` :
- `=======` :
- `>>>>>>>` :

**Qual pedaco veio de quem, e qual titulo voces decidiram manter:**

---

## Casa - Incidente na linha 3

**Hash do commit que quebrou o painel:**

**Hash do commit de revert:**

**Por que `git revert` e nao `git reset` neste caso:**
