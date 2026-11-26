
# Roadmap de Desenvolvimento — Soft Agente

## 1. Objetivo

Organizar a evolução do Soft Agente em etapas incrementais, garantindo que cada fase produza resultados verificáveis e documentados.

## 2. Fases do projeto

### Fase 1 — Concepção e especificação

- [x] Definir a proposta inicial do produto.
- [x] Definir a visão do produto.
- [x] Delimitar o escopo preliminar.
- [x] Identificar requisitos funcionais.
- [x] Identificar requisitos não funcionais.
- [ ] Refinar requisitos e critérios de aceitação.
- [ ] Documentar regras de negócio.
- [ ] Elaborar casos de uso.

### Fase 2 — Análise e arquitetura

- [ ] Identificar atores e interações do sistema.
- [ ] Modelar os principais processos.
- [ ] Definir componentes e responsabilidades.
- [ ] Elaborar a arquitetura lógica.
- [ ] Modelar o banco de dados.
- [ ] Definir contratos da API.
- [ ] Registrar decisões arquiteturais (ADRs).
- [ ] Avaliar segurança, privacidade e implantação.

### Fase 3 — Backend inicial

- [ ] Preparar ambiente de desenvolvimento.
- [ ] Criar estrutura inicial do backend.
- [ ] Configurar FastAPI.
- [ ] Configurar persistência com MariaDB.
- [ ] Implementar gerenciamento de projetos.
- [ ] Implementar associação de documentação.
- [ ] Criar integração com modelo de linguagem.
- [ ] Implementar registro de sessões.

### Fase 4 — Motor pedagógico

- [ ] Definir modelo de estado do desenvolvimento.
- [ ] Implementar processamento de contexto.
- [ ] Implementar sistema progressivo de dicas.
- [ ] Implementar avaliação de intervenções.
- [ ] Implementar controle de frequência das sugestões.
- [ ] Implementar histórico e feedback.

### Fase 5 — Extensão VS Code

- [ ] Criar extensão em TypeScript.
- [ ] Implementar observação controlada do workspace.
- [ ] Identificar eventos relevantes.
- [ ] Implementar comunicação com backend.
- [ ] Apresentar sugestões na IDE.
- [ ] Implementar configurações de proatividade.

### Fase 6 — Dashboard e CLI

- [ ] Desenvolver gerenciamento visual de projetos.
- [ ] Apresentar requisitos e tarefas.
- [ ] Disponibilizar histórico de interações.
- [ ] Implementar configurações do agente.
- [ ] Desenvolver interface CLI.

### Fase 7 — Testes e validação

- [ ] Implementar testes unitários.
- [ ] Implementar testes de integração.
- [ ] Validar segurança e permissões.
- [ ] Avaliar qualidade das intervenções pedagógicas.
- [ ] Avaliar consumo de recursos.
- [ ] Validar funcionamento em projetos reais.

### Fase 8 — Implantação

- [ ] Preparar ambiente Debian.
- [ ] Configurar containers com Podman.
- [ ] Configurar persistência e backups.
- [ ] Configurar acesso privado via Tailscale.
- [ ] Documentar instalação e manutenção.
- [ ] Publicar a primeira versão funcional.

## 3. Critério de evolução

Uma fase deverá avançar quando seus principais objetivos estiverem implementados, testados e documentados.

A conclusão de uma funcionalidade deverá considerar:

- Requisito associado.
- Regras de negócio atendidas.
- Implementação validada.
- Testes executados.
- Documentação atualizada.

## 4. Estratégia de desenvolvimento

O desenvolvimento será incremental. Cada funcionalidade deverá ser dividida em tarefas pequenas, com implementação, testes e revisão antes da evolução para a próxima etapa.

O roadmap poderá ser atualizado conforme novas descobertas técnicas e necessidades do produto.
