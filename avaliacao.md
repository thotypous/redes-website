---
layout: page
title: Avaliação
permalink: /avaliacao/
---

# Política sobre plágio e direitos autorais

Não é permitido plágio em quaisquer das atividades avaliativas. Durante as provinhas, é admitido consultar material impresso ou escrito, mas não é permitido qualquer tipo de comunicação ou uso de qualquer dispositivo capaz de conectar-se à rede. No projeto, será aplicado o verificador de similaridade [Moss](https://theory.stanford.edu/~aiken/moss/). Além dos trabalhos dos demais grupos, serão fornecidos ao Moss trabalhos entregues em ofertas anteriores da disciplina e códigos disponíveis na Internet. **Será considerado plágio qualquer resultado com alto índice de similaridade.**


# Projeto

O Projeto é dividido nas seguintes etapas:

 * Etapa 1 (camada de aplicação)
 * Etapa 2 (camada de transporte)
 * Etapa 3 (camada de rede)
 * Etapa 4 (camada de enlace)
 * Etapa 5 (etapa final / integração)

Descrições detalhadas serão disponibilizadas no Autolab no dia de lançamento de cada etapa.

**IMPORTANTE**: Sempre antes de entregar cada uma das etapas, os grupos devem ser **cadastrados novamente** no Autolab e todos os integrantes **devem aceitar** novamente o convite. Essa exigência existe para assegurar que todos os alunos inseridos em um grupo estejam realmente participando daquele grupo, e para permitir que os alunos troquem de grupo ao longo da disciplina se assim desejarem.

## Etapas de 1 a 4

As etapas intermediárias do projeto podem ser realizadas em grupos de até 4 alunos.

## Etapa 5

A etapa final pode ser desenvolvida em grupos de até 8 alunos. Ou seja, é possível juntar diferentes grupos das etapas intermediárias em um único grupo para a etapa final. Haverá uma apresentação do projeto final. Essa apresentação poderá ser seguida de perguntas individuais a integrantes do grupo. **Todos os integrantes do grupo precisam estar presentes em um mesmo horário para a apresentação do projeto**.


# Cálculo das notas

## Nota Teórica

A Nota Teórica (NT) é calculada como a média das 5 melhores notas em provinhas:

```python
NT = sum(sorted([P1, P2, P3, P4, P5, P6])[-5:]) / 5
```

## Nota Prática

A Nota Prática (NP) é calculada de acordo com a seguinte média ponderada:

```python
NL = (1.5*Etapa1 + 1.5*Etapa2 + 1.5*Etapa3 + 1.5*Etapa4 + 4*Etapa5) / 10
```

## Nota Final

A Nota Final (NF) é a média da Nota Teórica (NT) com a Nota Prática (NP):

```python
NF = (NT + NP) / 2
```
