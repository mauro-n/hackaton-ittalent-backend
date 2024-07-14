# Hackathon IT Talent - Desafio DevOps

## Descrição
Este repositório contém os arquivos e documentação referentes ao desafio de Hackathon para a disciplina de DevOps. O desafio é dividido em duas partes principais: Kubernetes e Terraform, com o objetivo de aplicar conceitos de orquestração de containers e infraestrutura como código.

## Parte 1: Kubernetes

### Objetivos
- Criar um ReplicaSet com 1 instância do Banco de Dados e 2 do backend.
- Utilizar os seguintes repositórios:
  - [Projeto de Banco de Dados](https://github.com/moisesAlc/Banco-IT_Talent)
  - [Projeto de Backend](https://github.com/moisesAlc/Backend-IT_Talent)

### Arquivos
- `replicaset.yaml`: Arquivo para criação do ReplicaSet.

### Instruções
1. Aplicar o ReplicaSet utilizando `kubectl apply -f replicaset.yaml`.
2. Adicionar prints de:
   - Execução do ReplicaSet.
   - Exclusão de um dos pods do ReplicaSet.
   - Subida de um novo pod para normalização do ReplicaSet pelo K8S.
