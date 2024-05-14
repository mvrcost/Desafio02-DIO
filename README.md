# Desafio do Módulo 3: Processamento de Dados Simplificado com Power BI

Este é um desafio que visa realizar o processamento de dados utilizando o Power BI em conjunto com uma instância MySQL na Azure. O objetivo é integrar dados, transformá-los e prepará-los para análise. Abaixo estão as etapas principais do desafio:

## Etapas do Desafio:

1. **Criação de Instância MySQL na Azure**: Uma instância MySQL foi na plataforma Azure para armazenar os dados.

2. **Criação do Banco de Dados**: Utilizando os dados disponíveis no repositório do GitHub, o banco de dados foi criado.

3. **Integração do Power BI com MySQL na Azure**: O Power BI foi integrado com a instância MySQL criada na Azure para permitir o acesso e a análise dos dados.

4. **Verificação e Transformação dos Dados**: Foram realizadas diversas etapas de transformação nos dados para garantir sua integridade e adequação para análise. Algumas diretrizes para esta etapa incluiram:

    - Verificação dos cabeçalhos e tipos de dados.
    - Conversão dos valores monetários para o tipo double preciso.
    - Análise e tratamento de valores nulos.
    - Identificação e preenchimento de colaboradores sem gerente.
    - Verificação de departamentos sem gerente e preenchimento das lacunas.
    - Verificação do número de horas dos projetos.
    - Separação de colunas complexas.
    - Mesclagem de consultas para criar uma tabela de colaboradores associados aos departamentos.
    - Mesclagem das colunas de Nome e Sobrenome.
    - Mesclagem dos nomes de departamentos e localizações.
    - Agrupamento de dados para saber quantos colaboradores existem por gerente.

5. **Limpeza de Dados**: Eliminação de colunas desnecessárias que não serão utilizadas no relatório final, visando a simplificação e a otimização do modelo de dados.

## Observações Adicionais:

- **Mesclar vs. Atribuir**: No caso específico da mesclagem de nomes de departamentos e localizações, a utilização de mesclar é preferível a atribuir, devido à necessidade de criar combinações únicas, o que facilita a criação de um modelo estrela em módulos futuros.

# Ferramentas utilizadas
---------------------------------------------
![Power Bi](https://img.shields.io/badge/power_bi-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Azure](https://img.shields.io/badge/azure-%230072C6.svg?style=for-the-badge&logo=microsoftazure&logoColor=white)
![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)
---

