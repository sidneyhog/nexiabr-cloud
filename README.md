# ☁️ Nexiabr Cloud - Infraestrutura Automatizada

## 🚀 Sobre o Projeto

O **Nexiabr Cloud** é um repositório dedicado à automação da infraestrutura para clientes da **Nexiabr**. Utilizando **GitHub Actions**, **Docker Swarm**, **Traefik** e **Portainer**, essa stack permite provisionar e gerenciar serviços de forma eficiente em **VPS da Contabo**.

Nosso objetivo é criar uma infraestrutura escalável, automatizada e segura, facilitando a implementação de soluções como **n8n, Chatwoot, WordPress, PostgreSQL** e muito mais.

---

## 🛠️ Tecnologias Utilizadas

- **Orquestração de Containers**: Docker Swarm, Portainer, Traefik  
- **Infraestrutura como Código**: Terraform  
- **Automatização e CI/CD**: GitHub Actions  
- **Monitoramento**: Grafana, Prometheus  
- **Aplicativos e Stacks**: n8n, Chatwoot, WordPress, PostgreSQL  
- **VPS**: Contabo  

---

## 📁 Estrutura do Repositório

- **/.github/workflows/** → Pipelines do GitHub Actions para deploy automatizado  
- **/stacks/** → Definição das stacks para deploy via Portainer  
- **/infra/** → Configurações Terraform para infraestrutura  
- **/monitoramento/** → Configurações do Grafana e Prometheus  

---

## 🚀 Como Usar

### 1️⃣ Requisitos

Antes de iniciar, certifique-se de ter:
- Uma VPS configurada na **Contabo**
- **Docker** e **Docker Swarm** instalados
- **GitHub Actions** configurado com as credenciais corretas
- **Portainer** instalado e acessível

### 2️⃣ Clonar o Repositório
```bash
git clone https://github.com/nexiabr/nexiabr-cloud.git
cd nexiabr-cloud
```

### 3️⃣ Configurar Variáveis de Ambiente
Edite o arquivo **.env** para definir as credenciais e configurações da sua infraestrutura.

### 4️⃣ Deploy da Infraestrutura
Utilize os workflows do **GitHub Actions** para provisionar e atualizar os serviços automaticamente.

---

## 📊 Monitoramento

A infraestrutura conta com **Grafana** e **Prometheus** para monitoramento da performance e dos logs das aplicações. Para acessar o painel do Grafana:
```bash
http://SEU_IP:3000
```
Usuário padrão: `admin`  
Senha padrão: `admin`

---

## 🤝 Contribuição

Se quiser contribuir, siga os passos:
1. Fork este repositório
2. Crie uma branch (`git checkout -b minha-feature`)
3. Commit suas alterações (`git commit -m 'Adicionando nova feature'`)
4. Envie um push (`git push origin minha-feature`)
5. Abra um Pull Request

---

## 📬 Contato

Se precisar de suporte ou quiser colaborar com o projeto, me encontre nas redes sociais:

[<img src='https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white' alt='LinkedIn' height='30'>](https://www.linkedin.com/in/sidneyhog)  
[<img src='https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=WhatsApp&logoColor=white' alt='WhatsApp' height='30'>](https://wa.me/5519997339377)  
[<img src='https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white' alt='Instagram' height='30'>](https://www.instagram.com/sidneyhoginsanos)  

---

### 🚀 Desenvolvido por **SidneyHoG** | Nexiabr
