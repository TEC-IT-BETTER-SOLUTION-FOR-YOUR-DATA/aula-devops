# aula-devops

1. Introdução ao DevOps

1.1 O que é DevOps?

DevOps é um conjunto de práticas que integra desenvolvimento (Dev) e operações (Ops) para automatizar e melhorar processos dentro do ciclo de vida do software. Seu objetivo principal é entregar software de forma rápida, segura e com qualidade, promovendo a colaboração entre equipes de desenvolvimento e infraestrutura.

1.2 Benefícios do DevOps

Entrega Contínua e Rápida

Melhor Qualidade de Software

Redução de Erros em Produção

Automatização de Processos

Maior Colaboração entre Equipes

2. Princípios do DevOps

Integração Contínua (CI - Continuous Integration): Desenvolvedores integram código frequentemente em um repositório compartilhado.

Entrega Contínua (CD - Continuous Delivery): Código pronto para ser liberado a qualquer momento.

Monitoramento e Feedback Contínuo: Monitoramento constante da aplicação e dos processos.

Automatização de Infraestrutura: Uso de ferramentas para configurar e gerenciar infraestrutura de forma automática.

3. Ferramentas do DevOps

3.1 Controle de Versão

Git

GitHub / GitLab / Bitbucket

3.2 Integração Contínua e Entrega Contínua

Jenkins

GitHub Actions

GitLab CI/CD

CircleCI

3.3 Gerenciamento de Configuração e Infraestrutura como Código

Ansible

Terraform

Puppet

Chef

3.4 Monitoramento e Logging

Prometheus

Grafana

ELK Stack (Elasticsearch, Logstash e Kibana)

3.5 Contêineres e Orquestração

Docker

Kubernetes

4. Pipeline DevOps na Prática

Um pipeline DevOps pode ser estruturado em diferentes estágios:

Desenvolvimento - Escrever código e usar controle de versão (Git).

Build - Compilar e criar pacotes de software.

Testes Automatizados - Rodar testes para validar funcionalidade.

Integração Contínua - Unir códigos e rodar testes continuamente.

Entrega Contínua - Disponibilizar versão estável para produção.

Monitoramento e Feedback - Acompanhar performance e corrigir problemas.

5. Exemplo Prático: Configurando um Pipeline CI/CD

Criar um repositório no GitHub.

Criar um arquivo Jenkinsfile ou configurar GitHub Actions.

Configurar passos de build, testes e deploy automático.

Integrar com um ambiente de produção (AWS, Azure, GCP).

6. Conclusão

DevOps é essencial para equipes que buscam entregar software com eficiência e confiabilidade. Com a combinação de práticas, ferramentas e cultura colaborativa, é possível melhorar todo o ciclo de desenvolvimento e operação de sistemas.

7. Exercício Prático

Criar um repositório Git e subir um projeto simples.

Configurar um pipeline básico de CI/CD com GitHub Actions ou Jenkins.

Executar e validar o pipeline.
