
# Escopo do Produto — Soft Agente

## 1. Objetivo

Definir as funcionalidades contempladas pelo produto, suas prioridades e as limitações da primeira versão.

## 2. Escopo geral

O Soft Agente deverá oferecer um ambiente integrado de mentoria para projetos de software, utilizando documentação, contexto de desenvolvimento e interação com modelos de linguagem.

O sistema será organizado em três interfaces principais:

### 2.1. Extensão VS Code

Responsável por acompanhar eventos relevantes no ambiente de desenvolvimento.

Funcionalidades previstas:

- Identificar arquivos criados e modificados.
- Reconhecer a linguagem e tecnologias do projeto.
- Identificar oportunidades de orientação.
- Apresentar sugestões pedagógicas.
- Permitir interação com o agente diretamente na IDE.

### 2.2. Web Dashboard

Responsável pelo gerenciamento e visualização das informações dos projetos.

Funcionalidades previstas:

- Cadastro e gerenciamento de projetos.
- Visualização de requisitos e documentação.
- Acompanhamento de tarefas.
- Histórico de interações.
- Configuração do comportamento do agente.
- Acompanhamento da evolução do desenvolvedor.

### 2.3. CLI

Interface complementar para operações diretamente pelo terminal.

Funcionalidades futuras:

- Consultar projetos.
- Iniciar sessões de mentoria.
- Consultar tarefas e progresso.
- Interagir com o agente.
- Consultar informações de Git e testes.

## 3. Escopo do MVP

A primeira versão deverá priorizar:

1. Cadastro e seleção de projetos.
2. Associação e leitura de documentação.
3. Interpretação de requisitos e regras de negócio.
4. Interação com um modelo de linguagem externo.
5. Identificação do estado de desenvolvimento.
6. Orientação por perguntas e explicações.
7. Sistema progressivo de dicas.
8. Divisão de funcionalidades em tarefas.
9. Registro de sessões e progresso.
10. Diagnóstico de erros apresentados pelo desenvolvedor.

A integração com o VS Code será desenvolvida incrementalmente, priorizando a captura controlada de eventos e a apresentação de sugestões.

## 4. Funcionalidades fora do escopo inicial

Não serão implementadas inicialmente:

- Edição autônoma de arquivos.
- Execução arbitrária de comandos.
- Commits automáticos.
- Implementação integral de funcionalidades sem autorização.
- Substituição das decisões do desenvolvedor.
- Execução de modelos de linguagem pesados no servidor pessoal.
- Suporte simultâneo a múltiplas IDEs.

Esses recursos poderão ser avaliados em versões futuras.

## 5. Limites de autonomia

O agente deverá operar em três níveis:

### Orientação

Explicações, perguntas, conceitos e direcionamentos.

### Assistência

Pistas, pseudocódigo, exemplos parciais e análise de alternativas.

### Demonstração

Apresentação de uma implementação de referência quando explicitamente solicitada.

A orientação será o comportamento padrão.

## 6. Restrições operacionais

- O código não deverá ser transmitido sem necessidade e autorização adequada.
- Sugestões não deverão ser apresentadas como erros confirmados sem evidências.
- A execução de alterações deverá permanecer sob controle do desenvolvedor.
- A documentação do projeto deverá ser considerada fonte de contexto.
- O agente deverá respeitar as permissões e configurações definidas pelo usuário.

## 7. Critério de conclusão do MVP

O MVP será considerado funcional quando conseguir acompanhar um projeto cadastrado, interpretar sua documentação, receber contexto de desenvolvimento, oferecer orientação pedagógica relevante e registrar as interações e o progresso do usuário.
