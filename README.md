# 🚀 Desafio DIO - AWS CloudFormation  

Este repositório faz parte do **Bootcamp [Santander Code Girls 2025](https://web.dio.me/track/santander-code-girls-2025)** da **DIO (Digital Innovation One)**, no qual implementei minha primeira Stack utilizando **AWS CloudFormation**.  
O objetivo foi aplicar conceitos aprendidos durante o curso, documentar o processo e organizar os artefatos para futuras referências.  

---

## 📌 Entendendo o Desafio
O desafio consiste em:
- Criar uma stack na **AWS** utilizando **CloudFormation**;
- Utilizar templates em **YAML/JSON** para provisionar recursos;
- Documentar as etapas e aprendizados;
- Publicar no GitHub com README bem estruturado.

---

## ⚙️ Recursos Criados

Durante a prática foram provisionados os seguintes recursos via **CloudFormation**:

1. **EC2 Instance (YAML/JSON pronto)**  
   - Instância criada a partir de um modelo pronto para testes.  

2. **Apache WebServer**  
   - Template configurado para iniciar um servidor Apache, permitindo acesso a um webservice.  

3. **WebServer com Firewall**  
   - Servidor com regras de segurança (Security Group) que libera **somente a porta 80 (HTTP)**.  

4. **User Group**  
   - Grupo de usuários no IAM para gerenciamento de permissões.  

---

## 📝 Objetivos de Aprendizagem
Ao concluir este desafio, pratiquei:
- 🚀 Provisionamento de recursos com **CloudFormation**;
- 📑 Documentação clara e organizada de processos técnicos;
- 🌐 Uso do **GitHub** como portfólio para projetos de Cloud.  

---

## 📂 Estrutura do Repositório

```
📁 DIO-GirlsCode-Desafio-AWS-CoudFormation
┣ 📁 templates/
┣ 📜 01-EC2.yaml
┣ 📜 02-Apache.yaml
┣ 📜 03-Firewall.yaml
┣ 📜 04-EC2_S3_UserGroup.yaml
┗ 📜 README.md
```
---

## ▶️ Como Reproduzir

## 🚀 Como Usar

1.  **Clone este repositório:**
    ```bash
    git clone https://github.com/EvelynSantos6/DIO-GirlsCode-Desafio-AWS-CoudFormation.git
    ```

2.  **Acesse o console da AWS** e vá para o serviço **CloudFormation**.

3.  **Faça o upload do template** desejado (arquivos `.json` ou `.yaml`) diretamente do seu computador.

4.  **Execute a stack** e aguarde a criação dos recursos.

5.  **Teste o projeto** acessando a instância ou o webserver criado.

---

## 📚 Recursos Úteis

* [AWS CloudFormation - Documentação Oficial](https://aws.amazon.com/cloudformation/resources/templates/)
* [Guia de Markdown no GitHub](https://guides.github.com/features/mastering-markdown/)
* [GitHub Quick Start](https://docs.github.com/en/get-started/on-your-own/about-github)

---

## ✅ Conclusão

Este desafio foi fundamental para reforçar conceitos de **Infraestrutura como Código (IaC)**, além de demonstrar a importância de estruturar e documentar projetos técnicos no GitHub.
