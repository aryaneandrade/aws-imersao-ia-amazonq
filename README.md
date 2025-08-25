# Projeto Prático – Imersão AWS & IA com Henrylle Maia

Este repositório contém a documentação e recursos do projeto prático desenvolvido durante a **Imersão AWS & IA**, conduzida por **Henrylle Maia**. O objetivo do projeto foi criar e gerenciar uma **infraestrutura em nuvem na AWS**, integrando **Docker, ECS, RDS, CI/CD e Inteligência Artificial** para deploy de aplicações de alta disponibilidade.

---

## Tecnologias e Ferramentas Utilizadas

- **AWS Services:** ECS, RDS, ECR, ALB, Security Groups, SSM, CloudShell
- **Containers:** Docker
- **CI/CD:** Pipeline automático de deploy
- **Linguagens:** Node.js, React
- **Automação e IA:** MCP Server e agente de IA para suporte e troubleshooting
- **Boas práticas:** Alta disponibilidade (High Availability), deploy sem downtime, HTTPS, domínio personalizado

---

## Estrutura do Projeto

1. **Ambiente AWS Seguro**
   - Configuração de **SSM** e **CloudShell** para acesso remoto seguro
   - Integração do **agente de IA e MCP Server**

2. **Infraestrutura de Containers**
   - Criação e gerenciamento do **cluster ECS**
   - Provisionamento de banco **RDS**
   - Configuração de **Security Groups**
   - Deploy de imagens Docker no **ECR** com automação e troubleshooting via IA

3. **Aplicação Node + React**
   - Deploy em **alta disponibilidade** usando **ALB e Target Groups**
   - **Pipeline CI/CD** para deploy automático após push
   - Configuração de **domínio personalizado e HTTPS**

---

## Resultados e Aprendizados

- Orquestração de containers com ECS
- Automação de deploy e troubleshooting com integração de IA
- Criação de aplicações escaláveis e seguras na AWS
- Implementação de infraestrutura como código (IaC) e melhores práticas de DevOps
- Experiência prática em **deploy Desafiocontínuo sem downtime** e gestão de ALB/Target Groups

---

## Como Executar / Reproduzir

> Este projeto é de caráter didático e prático para aprendizado na Imersão AWS & IA.  
> Para reproduzir o ambiente, é necessário ter uma conta AWS e acesso aos serviços utilizados (ECS, RDS, ECR, ALB, SSM).

1. Clone este repositório:
```bash
git clone https://github.com/seu-usuario/projeto-aws-ia.git
````

2. Configure sua conta AWS com credenciais apropriadas.
3. Siga as instruções de deploy em cada módulo:

   * ECS / Containers
   * Banco de dados RDS
   * Pipeline CI/CD
   * ALB / Target Group / HTTPS

---

## Capturas de Tela / Evidências

* Acesso via **SSM / CloudShell**
* Agente de IA e **MCP Server** configurados
* **Cluster ECS** ativo e tarefas rodando
* **RDS** provisionado e configurado
* **Deploy Docker** realizado via ECR
* **ALB e Target Groups** configurados
* Aplicação **Node + React** em produção com domínio e HTTPS
* Pipeline CI/CD disparando deploy automático

---

## Autor

**Aryane Andrade**

* Participante da **Imersão AWS & IA** conduzida por Henrylle Maia
* Experiência em **Cloud Computing, DevOps, Docker, ECS, CI/CD e Inteligência Artificial aplicada à infraestrutura**

