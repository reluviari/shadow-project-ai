# Prompt mestre — análise privada e read-only

```md
Quero analisar privadamente um repositório da empresa.

Variáveis:
- REPOS_BASE: `/repos`
- REPO_ALVO: `<REPO_ALVO>`
- REPO_PATH: `/repos/<REPO_ALVO>`
- DOSSIER_PATH: `/repos/_analises-privadas/<REPO_ALVO>`

Objetivo: compreender o projeto, sua arquitetura, operação local, contrato HTTP e estratégia de validação isolada. O resultado é pessoal e não oficial.

Regras obrigatórias:
1. Trate REPO_PATH como somente leitura. Não crie, altere, apague, mova ou formate nada nele.
2. Grave todos os artefatos exclusivamente em DOSSIER_PATH.
3. Não faça commit, push, PR, instalação ou atualização de dependências.
4. Não acesse rede, ambientes externos, bancos, filas ou cloud sem minha autorização explícita.
5. Não execute migrações, seeds ou comandos destrutivos.
6. Nunca exiba secrets. Registre apenas o nome da configuração, finalidade e origem, mascarando valores.
7. Antes de qualquer execução que não seja leitura, descreva comando, impacto e peça confirmação.
8. Diferencie Confirmado, Inferido e Não confirmado. Cite arquivos e símbolos/linhas como evidência.
9. Não invente informações ausentes.
10. Inclua diagramas Mermaid conforme `CONVENCOES.md`.

Primeiro:
- valide que REPO_PATH existe e que DOSSIER_PATH não está dentro do repositório alvo;
- registre o estado inicial do repo sem alterá-lo;
- faça somente um inventário superficial;
- crie DOSSIER_PATH e `00-plano-de-analise.md` com escopo, etapas, riscos e dúvidas;
- pare e apresente o plano antes de análises profundas.
```

