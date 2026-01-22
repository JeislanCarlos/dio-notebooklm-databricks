# Pergunta 5 - Diferenças entre Lakehouse e abordagens tradicionais

## Pergunta
Quais são as principais diferenças entre a arquitetura Lakehouse e abordagens tradicionais de dados?

## Prompt utilizado
Com base na fonte [S1], quais são as principais diferenças entre a arquitetura Lakehouse e abordagens tradicionais de dados?
Inclua a referência no formato [S1].

## Resposta do NotebookLM
Com base na fonte fornecida, as principais diferenças entre a arquitetura Lakehouse e as abordagens tradicionais (como a separação entre data warehouses e data lakes) são:
• Unificação de Estruturas: Ao contrário das abordagens tradicionais que geralmente separam o armazenamento de dados estruturados e não estruturados, o Lakehouse combina elementos de data warehouses e data lakes para gerenciar ambos em um único ambiente.
• Flexibilidade de Esquema: Enquanto bancos de dados tradicionais exigem um esquema rígido, a plataforma Lakehouse permite realizar consultas analíticas em dados semiestruturados sem a necessidade de um esquema de banco de dados tradicional.
• Confiabilidade (Transações ACID): O Lakehouse introduz suporte a transações ACID em ambientes de data lake (através do projeto Delta Lake), oferecendo uma confiabilidade que tradicionalmente era exclusiva dos data warehouses.
• BI Direto no Data Lake: Em modelos tradicionais, a inteligência de negócios (BI) geralmente requer a migração de dados para um armazém específico. O Lakehouse permite executar BI e relatórios analíticos diretamente sobre o data lake usando SQL padrão.
• Plataforma Integrada para IA e Analytics: Diferente de abordagens fragmentadas, o Lakehouse unifica diversas cargas de trabalho, como engenharia de dados, ciência de dados, aprendizado de máquina e armazenamento, em uma única base tecnológica.

## Referência
[S1] Databricks — Wikipedia
