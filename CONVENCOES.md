# Convenções do dossiê

## Variáveis

```text
REPOS_BASE=/repos
REPO_ALVO=<NOME_DO_REPO>
REPO_PATH=/repos/<NOME_DO_REPO>
DOSSIER_PATH=/repos/_analises-privadas/<NOME_DO_REPO>
```

Se `_analises-privadas` estiver dentro de um repositório Git pai, escolha outro diretório privado fora desse Git.

## Evidência e confiança

Toda conclusão relevante deve usar um destes rótulos:

- **Confirmado:** demonstrado por código, configuração ou teste.
- **Inferido:** conclusão provável a partir de indícios citados.
- **Não confirmado:** falta evidência ou execução segura.

Nunca invente endpoints, variáveis, comandos, portas, dependências ou comportamento. Use `NÃO IDENTIFICADO` quando necessário.

## Mermaid

- Todo documento temático deve conter ao menos um diagrama Mermaid útil.
- Use `flowchart` para processos, `sequenceDiagram` para chamadas, `C4Context`/`C4Container` somente se o renderizador suportar, `stateDiagram-v2` para estados e `erDiagram` para dados.
- Nomes curtos, sem secrets, URLs privadas, tokens ou dados pessoais.
- Inclua uma explicação textual curta abaixo do diagrama.
- Se o diagrama for inferido, escreva isso no título ou na legenda.

## Formato padrão dos documentos

1. Objetivo e escopo
2. Resumo executivo
3. Evidências
4. Diagrama(s) Mermaid
5. Detalhes
6. Hipóteses e lacunas
7. Como validar
8. Próximos passos

## Segurança operacional

Comandos permitidos por padrão são somente de inspeção. Antes de build, testes, rede, containers ou serviços, explique impacto e peça autorização. Nunca execute comandos destrutivos, migrações ou chamadas a produção. Arquivos experimentais pertencem exclusivamente ao dossiê.

