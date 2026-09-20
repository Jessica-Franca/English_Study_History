# English Study History

Histórico pessoal do meu aprendizado de inglês.

Este repositório não é um diário genérico. É o registro contínuo das aulas de conversação com o ChatGPT, atualizado pelo Cursor e versionado no Git.

**Idioma dos arquivos:** explicações em português. Frases de estudo em inglês, sempre com tradução e contexto.

## Objetivo

Registrar a evolução do inglês ao longo do tempo para conseguir responder, com base no histórico:

- Como está meu inglês hoje?
- O que eu mais erro?
- O que eu já aprendi?
- O que melhorou?
- O que devo praticar agora?
- Quais perguntas de entrevista já pratiquei?
- Quais respostas profissionais já construí?

## Foco do estudo

- Conversação
- Inglês profissional
- Entrevistas de emprego
- BI, Data Analytics, SQL, Power BI, Python, Databricks e tecnologia
- Confiança para falar de forma espontânea
- Gramática e vocabulário
- Reduzir a tradução mental do português para o inglês

## Como as aulas funcionam

A aula acontece no ChatGPT. O repositório guarda o antes, o durante e o depois.

Prioridade da aula:

**SPEAKING > CORRECTION > EXPLANATION**

Ou seja: falar primeiro, corrigir com clareza, explicar só o necessário. Sem aula excessivamente teórica.

## Como o ChatGPT será utilizado

O ChatGPT é o professor de conversação profissional.

Ele deve:

- deixar eu tentar responder primeiro
- corrigir de forma clara e objetiva
- não interromper excessivamente
- fazer perguntas que obriguem respostas espontâneas
- no final, gerar um relatório em Markdown para o Cursor atualizar este repositório

Prompts prontos:

- início: `prompts/prompt_inicio_aula.md` (o Cursor gera um prompt com o contexto do histórico)
- final: `prompts/prompt_final_aula.md` (colar no ChatGPT no fim da aula)

## Como o Cursor será utilizado

O Cursor é o arquivista do histórico.

Ele deve:

- ler as aulas e os arquivos de vocabulário, gramática, speaking e progresso
- gerar o prompt de contexto da próxima aula
- receber o resumo do ChatGPT e atualizar os arquivos
- não inventar notas nem apagar o passado
- não duplicar vocabulário ou erros já registrados

## Fluxo completo

1. Antes da aula: o Cursor analisa o histórico.
2. O Cursor gera um prompt de contexto (a partir de `prompts/prompt_inicio_aula.md`).
3. Eu envio esse prompt para o ChatGPT.
4. Faço a aula de conversação.
5. No final, colo `prompts/prompt_final_aula.md` no ChatGPT e ele gera o resumo estruturado.
6. Eu envio esse resumo para o Cursor.
7. O Cursor atualiza os arquivos do histórico.
8. Eu faço commit no Git.

## Como registrar uma nova aula

1. Peça ao Cursor: **gerar prompt de início de aula**.
2. Copie o prompt gerado e cole no ChatGPT.
3. Faça a aula.
4. Cole no ChatGPT o conteúdo de `prompts/prompt_final_aula.md`.
5. Envie o Markdown gerado ao Cursor.
6. Confira os arquivos atualizados.
7. Faça o commit.

O arquivo da aula deve ficar em:

`aulas/YYYY/MM/YYYY-MM-DD.md`

Use o formato de `templates/template_aula.md`.

## Como acompanhar a evolução

- **Por aula:** `aulas/YYYY/MM/`
- **No tempo:** `progress/progress.md`
- **O que eu erro:** `grammar/recurring_mistakes.md`
- **O que eu já aprendi:** `vocabulary/`
- **O que eu já consigo dizer:** `speaking/useful_sentences.md`
- **Entrevistas:** `speaking/interview_answers.md`

Não inventar métricas. Se não houver nota, usar `N/A`.

## Como atualizar o histórico

Quando a aula terminar, eu forneço ao Cursor o resumo gerado pelo ChatGPT.

O Cursor deve:

1. Criar o arquivo da nova aula em `aulas/YYYY/MM/YYYY-MM-DD.md`.
2. Atualizar, se houver conteúdo novo:
   - `vocabulary/general.md`
   - `vocabulary/professional.md`
   - `grammar/recurring_mistakes.md`
   - `speaking/useful_sentences.md`
   - `speaking/interview_answers.md`
   - `progress/progress.md`
3. Não apagar informações antigas.
4. Não duplicar vocabulário já registrado.
5. Não duplicar erros já conhecidos; só atualizar a frequência ou acrescentar exemplo novo.
6. Manter o histórico cronológico.
7. Se houver conflito entre informação antiga e nova, preservar o histórico e registrar a evolução — não substituir.

Regras:

- Não inventar desempenho.
- Não reescrever aulas antigas só para deixar o histórico mais bonito.
- Priorizar continuidade.
- Sempre considerar as aulas anteriores antes de sugerir a próxima atividade.
- Evitar repetir a mesma atividade, a menos que seja reforço de erro recorrente.

## Estrutura

```text
English_Study_History/
├── README.md
├── aulas/
│   └── 2026/
│       └── 09/
├── vocabulary/
│   ├── general.md
│   └── professional.md
├── grammar/
│   └── recurring_mistakes.md
├── speaking/
│   ├── useful_sentences.md
│   └── interview_answers.md
├── progress/
│   └── progress.md
├── prompts/
│   ├── prompt_inicio_aula.md
│   └── prompt_final_aula.md
└── templates/
    └── template_aula.md
```

## Status atual (com base no histórico)

- **Última aula registrada:** 2026-09-19
- **Nível estimado (aula 19/09):** A2, caminhando para B1 profissional
- **Próximo foco:** conversação profissional + entrevista; estrutura Problema → Investigação → Solução
