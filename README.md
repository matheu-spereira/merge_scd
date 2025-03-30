# Implementação de Tabelas SCD 1 e SCD 2 usando Delta Lake e Spark

Este repositório contém a implementação de tabelas Slowly Changing Dimensions (SCD) Tipo 1 e Tipo 2 utilizando o Delta Lake e Apache Spark. O Delta Lake é uma solução de armazenamento de dados transacionais que fornece escalabilidade e confiabilidade, enquanto o Apache Spark é uma poderosa ferramenta de processamento de dados distribuídos.

## Objetivo

O objetivo deste repositório é demonstrar como aplicar as estratégias de SCD Tipo 1 e SCD Tipo 2 em um ambiente de processamento de dados, utilizando Delta Lake para garantir a consistência e integridade dos dados em processos de atualização e histórico.

- **SCD Tipo 1**: Substitui o valor antigo por um novo, sem preservar o histórico dos dados.
![SCD1](https://github.com/user-attachments/assets/4d7533b5-8c65-48de-92db-d213d5415e86)
- **SCD Tipo 2**: Mantém o histórico de mudanças, criando uma nova linha para cada alteração no registro.
![SCD2](https://github.com/user-attachments/assets/ce7487f3-7185-4320-b4f5-fca31f631186)

## Estrutura do Projeto

O projeto é composto por três partes principais:

1. **Configuração do Delta Lake**: Configuração do ambiente para usar Delta Lake com Apache Spark.
2. **Implementação do SCD Tipo 1**: Código responsável por aplicar o SCD Tipo 1, onde os registros são atualizados substituindo os valores antigos pelos novos.
3. **Implementação do SCD Tipo 2**: Código responsável por aplicar o SCD Tipo 2, onde as mudanças nos dados são mantidas com a criação de novos registros.



