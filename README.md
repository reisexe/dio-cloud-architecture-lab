# AWS Cloud Architectures: DIO Challenge

## Sobre o Projeto
Repositório dedicado à documentação de arquiteturas em nuvem, desenvolvidas como parte dos desafios práticos da DIO para o curso de GFT - Fundamentos de Cloud com AWS. O foco foi explorar dois modelos distintos de infraestrutura AWS: **Serverless** (orientada a eventos) e **IaaS** (Infraestrutura como Serviço).

## Tecnologias Utilizadas
* **Draw.io:** Modelagem e documentação visual.
* **AWS S3:** Armazenamento de objetos e gatilho de eventos.
* **AWS Lambda:** Computação serverless.
* **AWS DynamoDB:** Banco de dados NoSQL.
* **AWS EC2:** Instâncias de computação.
* **AWS EBS:** Armazenamento em blocos para instâncias.

## Diagramas de Arquitetura

### 1. Arquitetura Serverless (S3, Lambda, DynamoDB)
<img width="901" height="475" alt="Diagrama EBS" src="https://github.com/user-attachments/assets/23ee8e5c-7ed8-46bb-9c40-2363b67179c5" />

* **Fluxo:** Upload de Arquivo → Trigger S3 → Processamento Lambda → Persistência no DynamoDB.

### 2. Arquitetura de Instância (EC2, EBS)
<img width="1019" height="504" alt="Diagrama S3" src="https://github.com/user-attachments/assets/1110e468-2e78-4de9-a68a-61c0536cec6c" />

* **Fluxo:** Usuário/Aplicação → Instância EC2 → Armazenamento em Volumes EBS.

---
*Desenvolvido por reisexe :D*
