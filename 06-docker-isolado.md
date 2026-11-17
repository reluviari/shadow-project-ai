# Prompt 06 — Docker isolado

```md
Desenhe uma estratégia para executar a aplicação isoladamente em Docker. Gere `05-plano-docker.md` e, se houver evidência suficiente, protótipos de `Dockerfile`, `compose.yaml`, `.env.example` e scripts somente dentro de `DOSSIER_PATH/laboratorio-docker/`.

Não altere o repo e não faça build/pull/up sem autorização. Minimize serviços, use imagens não privilegiadas quando possível, healthchecks, rede privada, volumes descartáveis e configurações fictícias. Nunca copie secrets.

Documente contexto de build necessário, entrypoint, portas, dependências, mocks, persistência, readiness, shutdown, limitações e comandos propostos. Inclua flowchart Mermaid da topologia e sequenceDiagram do startup. Se arquivos do repo precisarem ser copiados para um build futuro, explique uma estratégia segura sem executá-la agora.
```

