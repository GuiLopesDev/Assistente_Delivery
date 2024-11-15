# StepFunctionsSample - Projeto de Sugestões de Jantar Romântico

## Descrição do Projeto

Este projeto foi desenvolvido para demonstrar a integração entre a AWS Step Functions e a IA Haiku 3.0. O objetivo do projeto é fornecer sugestões baseadas em prompts inseridos previamente, com foco em um jantar romântico com base em macarrão. As sugestões incluem acompanhamentos para o prato principal, bebidas que combinam com a ocasião e recomendações de locais em Paris para realizar o jantar.

## Funcionalidades

- **Sugestões de Acompanhamentos:** A IA Haiku 3.0 analisa o prato principal (macarrão) e sugere outros alimentos ou pratos que complementam a refeição.
- **Recomendações de Bebidas:** Baseado no prato principal e no tema do jantar, a IA sugere bebidas adequadas.
- **Sugestão de Locais:** Utilizando dados de restaurantes em Paris, a IA recomenda locais ideais para um jantar romântico.

## Estrutura do Projeto

1. **Definição de Prompts:** Os prompts são inseridos para orientar a IA sobre o tipo de sugestões necessárias.
2. **Conexão com Haiku 3.0:** O projeto utilizou a IA Haiku 3.0 para processar os prompts e gerar respostas.
3. **Processamento com AWS Step Functions:** Utilizamos a AWS Step Functions para orquestrar o fluxo de trabalho e garantir que cada etapa seja executada corretamente.

## Exemplo de Uso

### Prompt Inicial

O prompt inicial inserido no repositório foi:
"Estou programando um jantar romantico, nesse jantar irei pedir um macarrão me de uma lista de 3 itens que combinam em uma experiencia gastronomica"

### Resultado

A partir deste prompt, o Haiku 3.0 gerará opções de acordo com o solicitado, apresentando sugestões de acompanhamentos, bebidas e locais que se encaixem no contexto fornecido. O objetivo é fornecer recomendações personalizadas e adequadas ao tema do jantar romântico.

## Licença
Este projeto está licenciado sob a Licença MIT. Veja o arquivo LICENSE para mais detalhes.

Espero que este projeto sirva como um exemplo útil de integração entre AWS Step Functions e a IA Haiku 3.0, oferecendo sugestões personalizadas e de alta qualidade para diversas ocasiões.