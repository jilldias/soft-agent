
# Especificação de Requisitos — Soft Agente

## 1. Introdução

Este documento apresenta os requisitos funcionais e não funcionais preliminares do Soft Agente.

Os requisitos representam capacidades esperadas do sistema e deverão ser refinados durante a análise e modelagem do produto.

## 2. Requisitos funcionais

| ID | Requisito | Descrição |
|---|---|---|
| RF001 | Gerenciar projetos | O sistema deverá permitir cadastrar, consultar, atualizar e selecionar projetos. |
| RF002 | Associar documentação | O sistema deverá permitir associar arquivos de documentação aos projetos. |
| RF003 | Interpretar requisitos | O agente deverá analisar requisitos e regras de negócio documentados. |
| RF004 | Gerenciar estado | O sistema deverá acompanhar a etapa atual de desenvolvimento de cada projeto. |
| RF005 | Receber eventos da IDE | O backend deverá receber eventos relevantes enviados pela extensão do VS Code. |
| RF006 | Avaliar intervenções | O sistema deverá identificar quando um evento representa uma oportunidade de orientação pedagógica. |
| RF007 | Gerar sugestões | O agente deverá produzir orientações considerando o contexto disponível do projeto. |
| RF008 | Interagir com sugestões | O usuário deverá poder visualizar, aceitar, ignorar ou avaliar sugestões. |
| RF009 | Oferecer assistência progressiva | O agente deverá fornecer dicas em diferentes níveis de detalhamento. |
| RF010 | Registrar sessões | O sistema deverá registrar sessões de interação com o agente. |
| RF011 | Registrar feedback | O sistema deverá armazenar avaliações das orientações apresentadas. |
| RF012 | Acompanhar aprendizagem | O sistema deverá registrar indicadores de evolução do desenvolvedor. |
| RF013 | Consultar histórico | O usuário deverá poder consultar sugestões e interações anteriores. |
| RF014 | Configurar proatividade | O usuário deverá configurar a frequência e o comportamento das intervenções. |

## 3. Requisitos não funcionais

| ID | Requisito | Descrição |
|---|---|---|
| RNF001 | Segurança da comunicação | A comunicação entre interfaces e backend deverá utilizar mecanismos seguros. |
| RNF002 | Proteção de credenciais | Chaves de API e credenciais deverão ser armazenadas de maneira protegida. |
| RNF003 | Controle de acesso | O acesso aos projetos deverá respeitar as permissões do usuário. |
| RNF004 | Eficiência de recursos | O backend deverá operar considerando as limitações de hardware da infraestrutura de hospedagem. |
| RNF005 | Privacidade do código | O sistema deverá minimizar a transmissão de código-fonte e solicitar autorização quando necessário. |
| RNF006 | Disponibilidade | O backend deverá funcionar independentemente da disponibilidade da IDE. |
| RNF007 | Rastreabilidade | As intervenções pedagógicas deverão possuir registros que permitam compreender sua origem e contexto. |

## 4. Regras gerais de comportamento

- O agente deverá priorizar a orientação em vez da implementação automática.
- O agente deverá considerar a documentação disponível antes de recomendar soluções.
- O agente deverá diferenciar erros confirmados de possíveis problemas.
- O agente deverá respeitar o nível de assistência configurado.
- O agente deverá evitar intervenções repetitivas ou desnecessárias.
- O usuário deverá manter o controle sobre alterações no código.

## 5. Priorização inicial

### Prioridade alta

- RF001, RF002, RF003, RF005, RF006, RF007, RF009 e RF010.
- RNF001, RNF002, RNF004 e RNF005.

### Prioridade média

- RF004, RF008, RF011, RF013 e RF014.
- RNF003, RNF006 e RNF007.

### Evolução futura

- RF012 e funcionalidades avançadas de acompanhamento de aprendizagem.

## 6. Observação

Esta especificação é preliminar. Cada requisito deverá ser refinado com critérios de aceitação, regras de negócio, casos de uso e cenários de teste antes de sua implementação.
