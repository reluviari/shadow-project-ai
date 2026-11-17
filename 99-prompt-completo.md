# Prompt completo — dossiê em uma execução

```md
Crie um dossiê privado completo para o repositório abaixo.

REPO_PATH=`/repos/<REPO_ALVO>`
DOSSIER_PATH=`/repos/_analises-privadas/<REPO_ALVO>`

REPO_PATH é estritamente somente leitura. Todo arquivo gerado deve ficar em DOSSIER_PATH. Não faça commits, instalações, rede, builds, testes, containers, migrações ou chamadas externas sem autorização. Não revele secrets. Registre fatos como Confirmado, Inferido ou Não confirmado e cite caminhos/símbolos/linhas. Não invente dados.

Execute em fases e mantenha um log de progresso:
1. validar caminhos, registrar estado inicial e criar plano;
2. inventário e contexto;
3. Project Spec;
4. arquitetura;
5. dependências e integrações;
6. runbook local;
7. plano e protótipos Docker privados;
8. reverse engineering OpenAPI;
9. harness privado;
10. fluxos críticos, riscos e lacunas;
11. relatório final e verificação de que o repo não mudou.

Crie os artefatos com os nomes definidos no README deste kit. Cada documento temático deve conter ao menos um diagrama Mermaid útil, evidências, hipóteses, lacunas, como validar e próximos passos. OpenAPI e protótipos devem ser conservadores e rastreáveis à evidência.

Pare antes de qualquer ação mutável e peça autorização informando comando, impacto, destino e rollback. Ao final, apresente o índice do dossiê, nível de confiança por área, arquivos criados e validações pendentes.
```
