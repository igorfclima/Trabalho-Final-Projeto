# 🎮 OnlyBasic 👨‍💻

> [!NOTE]
> Plataforma educacional para jogadores de jogos competitivos que desejam evoluir de rank ou se profissionalizar, combinando conteúdo educacional, analytics com IA e conexão com coaches especializados.

<table>
  <tr>
    <td width="800px">
      <div align="justify">
        O <b>OnlyBasic</b> é uma plataforma educacional voltada para jogadores de jogos competitivos como <i>League of Legends</i>, <i>Valorant</i> e <i>Overwatch</i>. Seu objetivo é ajudar jogadores casuais e semi-profissionais a evoluírem dentro dos seus respectivos jogos, oferecendo três pilares principais: <b>conteúdo educacional</b> sobre mecânicas e estratégias, <b>análise inteligente de desempenho</b> gerada por IA com base nos dados reais das partidas do jogador via APIs oficiais das publishers, e <b>conexão com coaches e mentores</b> especializados para sessões de treinamento personalizadas. A plataforma opera no modelo <i>freemium</i>, permitindo acesso gratuito a recursos básicos e planos pagos para funcionalidades avançadas.
      </div>
    </td>
    <td>
      <div align="center">
        <img src="https://via.placeholder.com/120x120?text=OB" alt="Logo OnlyBasic" width="120px"/>
      </div>
    </td>
  </tr>
</table>

---

## 🚧 Status do Projeto

[![Versão](https://img.shields.io/badge/Versão-v1.0.0-blue?style=for-the-badge)](https://github.com/igorfclima/onlybasic/releases)
![Status](https://img.shields.io/badge/Status-Em%20Desenvolvimento-orange?style=for-the-badge)
![React](https://img.shields.io/badge/React-19.0.0-007ec6?style=for-the-badge&logo=react&logoColor=white)
![React Native](https://img.shields.io/badge/React_Native-0.73-007ec6?style=for-the-badge&logo=react&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-20.x-007ec6?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Python](https://img.shields.io/badge/Python-3.11-007ec6?style=for-the-badge&logo=python&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-16-007ec6?style=for-the-badge&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-24.x-007ec6?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-EKS-007ec6?style=for-the-badge&logo=kubernetes&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-Cloud-007ec6?style=for-the-badge&logo=amazonaws&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-MSK-007ec6?style=for-the-badge&logo=apachekafka&logoColor=white)
![GitHub license](https://img.shields.io/github/license/igorfclima/Trabalho-Final-Projeto?style=for-the-badge&color=007ec6&logo=opensourceinitiative)

---

## 📚 Índice
- [Links Úteis](#-links-úteis)
- [Sobre o Projeto](#-sobre-o-projeto)
- [Funcionalidades Principais](#-funcionalidades-principais)
- [Tecnologias Utilizadas](#-tecnologias-utilizadas)
- [Arquitetura](#-arquitetura)
- [Instalação e Execução](#-instalação-e-execução)
  - [Pré-requisitos](#pré-requisitos)
  - [Variáveis de Ambiente](#-variáveis-de-ambiente)
  - [Instalação de Dependências](#-instalação-de-dependências)
  - [Como Executar a Aplicação](#-como-executar-a-aplicação)
  - [Execução com Docker Compose](#-execução-local-completa-com-docker-compose)
- [Deploy](#-deploy)
- [Estrutura de Pastas](#-estrutura-de-pastas)
- [Testes](#-testes)
- [Documentações Utilizadas](#-documentações-utilizadas)
- [Autores](#-autores)
- [Contribuição](#-contribuição)
- [Agradecimentos](#-agradecimentos)
- [Licença](#-licença)

---

## 🔗 Links Úteis

* 🌐 **Demo Online:** [Acesse a Plataforma](https://onlybasic.gg)
  > 💻 Aplicação web em produção hospedada na AWS com CloudFront + ALB.
* 📱 **Download Mobile:** [App Store](#) | [Google Play](#) | [APK Direto](#)
  > 📱 Disponível para iOS e Android via React Native.
* 📖 **Documentação da API:** [Swagger/OpenAPI](#)
  > 📚 Documentação completa dos endpoints REST disponível via Swagger UI.

---

## 📝 Sobre o Projeto

O **OnlyBasic** nasceu da necessidade de oferecer ao jogador brasileiro de jogos competitivos uma plataforma unificada que vai além de tutoriais genéricos no YouTube. O projeto resolve três dores principais: a falta de feedback personalizado sobre o desempenho do jogador, a dificuldade de encontrar coaches qualificados e acessíveis, e a ausência de conteúdo educacional estruturado em português.

A plataforma consome as APIs oficiais das publishers — **Riot Games API** para League of Legends e Valorant, e **Battle.net API** para Overwatch — para coletar dados reais de partidas e processar insights via **IA Engine** próprio. O resultado é um relatório de desempenho personalizado que aponta os pontos fracos do jogador e recomenda conteúdos e coaches alinhados ao que ele precisa melhorar.

O modelo de negócio **freemium** permite que qualquer jogador acesse funcionalidades básicas gratuitamente, com planos pagos desbloqueando analytics avançados e sessões com coaches. Coaches podem se cadastrar, criar pacotes de sessões e monetizar seu conhecimento diretamente pela plataforma.

---

## ✨ Funcionalidades Principais

- 🔐 **Autenticação Segura:** Cadastro, login com JWT e confirmação por e-mail.
- 🎮 **Vinculação de Conta do Jogo:** Integração com Riot Games API e Battle.net para coleta automática de dados.
- 📊 **Analytics com IA:** Relatórios personalizados de desempenho com identificação de pontos fracos e recomendações.
- 🎓 **Conteúdo Educacional:** Catálogo de aulas e estratégias filtradas por jogo, nível e plano do jogador.
- 👨‍🏫 **Marketplace de Coaches:** Busca, perfil completo, avaliações e agendamento de sessões com coaches aprovados.
- 📅 **Agendamento Integrado:** Agenda sincronizada entre jogador e coach com notificações automáticas.
- 💳 **Pagamentos e Assinaturas:** Planos freemium, básico e pro com suporte a PIX e cartão via Stripe/Mercado Pago.
- 💰 **Repasse Financeiro:** Cálculo automático e transferência de repasse ao coach após sessão concluída.
- 🔔 **Notificações:** Push, e-mail e in-app via Firebase e SendGrid.
- 🛡️ **Painel Administrativo:** Aprovação de coaches, moderação de conteúdo e relatórios operacionais/financeiros.

---

## 🛠 Tecnologias Utilizadas

### 💻 Front-end

* **Framework:** React 19.0 (Web) / React Native 0.73 (Mobile)
* **Linguagem:** TypeScript
* **Estilização:** Tailwind CSS
* **Gerenciamento de Estado:** Zustand
* **Build Tool:** Vite

### 🖥️ Back-end

* **Linguagem/Runtime:** Node.js 20.x (TypeScript) / Python 3.11 (IA Engine)
* **Framework:** Express (Node.js) / FastAPI (Python)
* **Banco de Dados Principal:** PostgreSQL 16 (Amazon RDS)
* **Banco de Analytics:** MongoDB (Atlas)
* **Cache:** Redis (Amazon ElastiCache)
* **ORM:** Prisma (Node.js)
* **Autenticação:** JWT + Bcrypt

### 📱 Mobile

* **Framework:** React Native 0.73
* **Ferramentas:** Expo, Android Studio, Xcode

### ⚙️ Infraestrutura & DevOps

* **Containerização:** Docker + Docker Compose
* **Orquestração:** Kubernetes (AWS EKS)
* **Mensageria:** Apache Kafka (Amazon MSK)
* **Storage:** Amazon S3
* **CDN:** Amazon CloudFront
* **Segurança:** AWS WAF + ALB
* **API Gateway:** Kong
* **Cloud:** AWS (EKS, RDS, S3, MSK, ElastiCache, CloudFront)
* **CI/CD:** GitHub Actions + Amazon ECR + Helm
* **Monitoramento:** Prometheus + Grafana + Loki + Jaeger

---

## 🏗 Arquitetura

O OnlyBasic adota uma **arquitetura de microsserviços** hospedada na AWS com orquestração via Kubernetes (EKS), escolhida pela necessidade de escalar componentes de forma independente — especialmente o IA Engine, que possui custo computacional elevado em relação aos demais serviços. A comunicação entre serviços segue dois padrões complementares: **REST/HTTP** para chamadas síncronas via API Gateway Kong, centralizando autenticação, rate limiting e roteamento em um único ponto; e **Event-Driven Architecture com Kafka** para operações assíncronas e de longa duração, como geração de relatórios de analytics e processamento de repasses financeiros, evitando acoplamento e timeouts entre serviços. Para persistência, foi adotado o padrão **Database per Service**, onde cada domínio utiliza o banco mais adequado ao seu contexto — PostgreSQL para dados relacionais, MongoDB para documentos de analytics e Redis para cache —, garantindo autonomia e isolamento entre os serviços. A camada de borda conta com WAF, CDN e Load Balancer para segurança e disponibilidade, enquanto o ciclo de entrega é automatizado via CI/CD com GitHub Actions e monitoramento completo com Prometheus, Grafana, Loki e Jaeger.

### Diagramas

| Diagrama | Descrição |
| :---: | :---: |
| **Arquitetura Geral** | **Diagrama de Componentes** |
| <img src="https://via.placeholder.com/300x200?text=Arquitetura" alt="Arquitetura Geral" width="300px"> | <img src="https://via.placeholder.com/300x200?text=Componentes" alt="Componentes" width="300px"> |
| **Modelo de Dados** | **Diagrama de Implantação** |
| <img src="https://via.placeholder.com/300x200?text=Modelo+de+Dados" alt="Modelo de Dados" width="300px"> | <img src="https://via.placeholder.com/300x200?text=Implantação" alt="Implantação" width="300px"> |
| **Diagrama de Sequência** | **Diagrama de Classes** |
| <img src="https://via.placeholder.com/300x200?text=Sequência" alt="Sequência" width="300px"> | <img src="https://via.placeholder.com/300x200?text=Classes" alt="Classes" width="300px"> |

---

## 🔧 Instalação e Execução

### Pré-requisitos

* **Node.js:** v20.x ou superior
* **Python:** 3.11 ou superior
* **Docker** e **Docker Compose** (recomendado)
* **npm** ou **yarn**

---

### 🔑 Variáveis de Ambiente

#### 1. Back-end (Node.js — Microsserviços)

Crie um arquivo **`.env`** na raiz de cada serviço em `/backend/<nome-do-servico>/.env`:

| Variável | Descrição | Exemplo |
| :--- | :--- | :--- |
| `PORT` | Porta do serviço | `3001` |
| `DATABASE_URL` | URL de conexão PostgreSQL | `postgresql://user:pass@localhost:5432/onlybasic` |
| `REDIS_URL` | URL de conexão Redis | `redis://localhost:6379` |
| `JWT_SECRET` | Chave secreta JWT | `chave_super_segura_base64` |
| `JWT_EXPIRES_IN` | Expiração do token | `7d` |
| `KAFKA_BROKER` | URL do broker Kafka | `localhost:9092` |

#### 2. IA Engine (Python — FastAPI)

Crie um arquivo **`.env`** em `/ia-engine/.env`:

| Variável | Descrição | Exemplo |
| :--- | :--- | :--- |
| `PORT` | Porta do serviço | `8000` |
| `MONGODB_URI` | URL de conexão MongoDB | `mongodb+srv://user:pass@cluster.mongodb.net` |
| `RIOT_API_KEY` | Chave da Riot Games API | `RGAPI-xxxxxxxx` |
| `BLIZZARD_CLIENT_ID` | Client ID Battle.net | `seu_client_id` |
| `BLIZZARD_CLIENT_SECRET` | Client Secret Battle.net | `seu_client_secret` |

#### 3. Front-end (React/Vite)

Crie um arquivo **`.env`** em `/frontend/.env`:

| Variável | Descrição | Exemplo |
| :--- | :--- | :--- |
| `VITE_API_URL` | URL base do API Gateway | `http://localhost:8080/api` |
| `VITE_FIREBASE_API_KEY` | Chave Firebase (Push) | `AIzaSy...` |
| `VITE_STRIPE_PUBLIC_KEY` | Chave pública Stripe | `pk_test_...` |

---

### 📦 Instalação de Dependências

1. **Clone o Repositório:**

```bash
git clone https://github.com/igorfclima/onlybasic.git
cd onlybasic
```

2. **Front-end (React):**

```bash
cd frontend
npm install
cd ..
```

3. **Back-end (Node.js — cada serviço):**

```bash
cd backend/auth-service && npm install && cd ../..
cd backend/user-service && npm install && cd ../..
cd backend/coach-service && npm install && cd ../..
# repita para cada serviço
```

4. **IA Engine (Python):**

```bash
cd ia-engine
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
pip install -r requirements.txt
cd ..
```

---

### ⚡ Como Executar a Aplicação

#### Terminal 1: Infraestrutura (PostgreSQL, Redis, Kafka, MongoDB)

```bash
docker-compose up -d postgres redis kafka mongodb
```

#### Terminal 2: Back-end (Microsserviços)

```bash
cd backend/auth-service && npm run dev
```

#### Terminal 3: IA Engine (Python)

```bash
cd ia-engine
source venv/bin/activate
uvicorn main:app --reload --port 8000
```

#### Terminal 4: Front-end (React)

```bash
cd frontend
npm run dev
```

🎨 *Front-end disponível em **http://localhost:5173***
🚀 *API Gateway disponível em **http://localhost:8080***

---

### 🐳 Execução Local Completa com Docker Compose

Para subir toda a stack com um único comando:

```bash
# Build e inicialização de todos os serviços
docker-compose up --build -d

# Verificar containers rodando
docker ps

# Verificar logs de um serviço específico
docker logs onlybasic-auth-service

# Parar todos os containers
docker-compose down
```

> [!NOTE]
> O parâmetro `--build` garante que as imagens mais recentes sejam geradas. O `-d` executa em segundo plano.

---

## 🚀 Deploy

1. **Build dos artefatos:**

```bash
# Front-end
cd frontend
npm run build

# Back-end (cada serviço gera sua imagem Docker)
docker build -t onlybasic/auth-service ./backend/auth-service
docker build -t onlybasic/ia-engine ./ia-engine
```

2. **Push para Amazon ECR:**

```bash
aws ecr get-login-password --region us-east-1 | docker login --username AWS --password-stdin <account>.dkr.ecr.us-east-1.amazonaws.com
docker push <account>.dkr.ecr.us-east-1.amazonaws.com/onlybasic/auth-service
```

3. **Deploy no Kubernetes (EKS) via Helm:**

```bash
helm upgrade --install onlybasic ./helm/onlybasic \
  --namespace onlybasic \
  --set image.tag=latest \
  -f helm/values.production.yaml
```

> 🔑 **Variáveis Cruciais:** Configure as variáveis de ambiente no AWS Secrets Manager e referencie-as nos manifestos Kubernetes via `ExternalSecret`.

---

## 📂 Estrutura de Pastas

```
.
├── .github/                        # 🤖 CI/CD (GitHub Actions), templates de PR
├── .gitignore                       # 🧹 Arquivos não versionados
├── docker-compose.yml               # 🐳 Orquestração local completa
├── README.md                        # 📘 Documentação principal
│
├── /frontend                        # 📁 Web App (React + Vite)
│   ├── /src
│   │   ├── /components              # 🧱 Componentes reutilizáveis
│   │   ├── /pages                   # 📄 Páginas da aplicação
│   │   ├── /services                # 🔌 Chamadas HTTP aos microsserviços
│   │   ├── /hooks                   # 🎣 Hooks personalizados
│   │   ├── /store                   # 🗃️ Estado global (Zustand)
│   │   └── /utils                   # 🛠️ Funções utilitárias
│   └── package.json
│
├── /mobile                          # 📱 App Mobile (React Native)
│   ├── /src
│   │   ├── /screens                 # 📄 Telas do app
│   │   ├── /components              # 🧱 Componentes reutilizáveis
│   │   └── /services                # 🔌 Chamadas HTTP
│   └── package.json
│
├── /backend                         # 📁 Microsserviços (Node.js)
│   ├── /auth-service                # 🔐 Autenticação e JWT
│   ├── /user-service                # 👤 Perfis e vinculação de contas
│   ├── /coach-service               # 👨‍🏫 Coaches, pacotes e candidaturas
│   ├── /content-service             # 🎓 Conteúdo educacional
│   ├── /scheduling-service          # 📅 Agendamento de sessões
│   ├── /payment-service             # 💳 Pagamentos e repasses
│   ├── /notification-service        # 🔔 Notificações push e e-mail
│   └── /admin-service               # 🛡️ Painel administrativo
│
├── /ia-engine                       # 🤖 IA Engine (Python + FastAPI)
│   ├── /analyzers                   # 📊 Analisadores de partida por jogo
│   ├── /collectors                  # 📡 Coletores de dados das APIs externas
│   ├── /models                      # 🧠 Modelos de ML e recomendação
│   └── requirements.txt
│
├── /helm                            # ☸️ Charts Helm para deploy no EKS
│   └── /onlybasic
│
├── /k8s                             # ☸️ Manifestos Kubernetes
│   ├── /namespaces
│   ├── /deployments
│   └── /services
│
└── /docs                            # 📚 Documentação técnica e diagramas
    ├── /diagramas
    └── /api
```

---

## 🎥 Demonstração

### 🌐 Aplicação Web

| Tela | Captura de Tela |
| :---: | :---: |
| **Página Inicial (Home)** | **Dashboard do Jogador** |
| <img src="https://via.placeholder.com/400x250?text=Home" alt="Home" width="400px"> | <img src="https://via.placeholder.com/400x250?text=Dashboard" alt="Dashboard" width="400px"> |
| **Relatório de Analytics** | **Busca de Coaches** |
| <img src="https://via.placeholder.com/400x250?text=Analytics" alt="Analytics" width="400px"> | <img src="https://via.placeholder.com/400x250?text=Coaches" alt="Coaches" width="400px"> |
| **Agendamento de Sessão** | **Painel Administrativo** |
| <img src="https://via.placeholder.com/400x250?text=Agendamento" alt="Agendamento" width="400px"> | <img src="https://via.placeholder.com/400x250?text=Admin" alt="Admin" width="400px"> |

### 📱 Aplicativo Mobile

| Tela Inicial | Analytics | Coaches | Perfil |
|:---:|:---:|:---:|:---:|
| <img src="https://via.placeholder.com/180x320?text=Home" alt="Home Mobile" height="320"> | <img src="https://via.placeholder.com/180x320?text=Analytics" alt="Analytics Mobile" height="320"> | <img src="https://via.placeholder.com/180x320?text=Coaches" alt="Coaches Mobile" height="320"> | <img src="https://via.placeholder.com/180x320?text=Perfil" alt="Perfil Mobile" height="320"> |

### 💻 Exemplo de Saída da API

```bash
curl -X GET 'http://localhost:8080/api/analytics/{jogadorId}' \
     -H 'Authorization: Bearer <jwt-token>'
```

**Saída Esperada:**
```json
{
  "jogadorId": "uuid-jogador",
  "jogo": "LOL",
  "dataGeracao": "2026-06-10T12:00:00Z",
  "pontosFracos": [
    "CS abaixo da média nos primeiros 10 minutos",
    "Alta taxa de mortes no early game"
  ],
  "pontosFortes": [
    "Boa visão de mapa",
    "KDA acima da média do rank"
  ],
  "recomendacoes": [
    "Assistir aula: Fundamentos de CS no Early Game",
    "Coach recomendado: CoachX — especialista em early game LoL"
  ],
  "rankComparativo": "Top 35% do seu elo"
}
```

---

## 🧪 Testes

### Testes Unitários e de Integração

```bash
# Back-end (cada serviço)
cd backend/auth-service
npm run test

# IA Engine
cd ia-engine
pytest tests/
```

### Testes End-to-End (E2E)

```bash
cd frontend
npm run test:e2e
```

*Ferramentas utilizadas: Jest (unitários), Supertest (integração), Playwright (E2E), Pytest (Python).*

---

## 🔗 Documentações Utilizadas

* 📖 **Riot Games API:** [developer.riotgames.com](https://developer.riotgames.com/docs/lol)
* 📖 **Battle.net API:** [develop.battle.net](https://develop.battle.net/documentation)
* 📖 **Stripe Payments:** [stripe.com/docs](https://stripe.com/docs/api)
* 📖 **Mercado Pago API:** [mercadopago.com.br/developers](https://www.mercadopago.com.br/developers/pt/docs)
* 📖 **Apache Kafka:** [kafka.apache.org/documentation](https://kafka.apache.org/documentation/)
* 📖 **FastAPI:** [fastapi.tiangolo.com](https://fastapi.tiangolo.com/)
* 📖 **Prisma ORM:** [prisma.io/docs](https://www.prisma.io/docs)
* 📖 **Kong API Gateway:** [docs.konghq.com](https://docs.konghq.com/)
* 📖 **AWS EKS:** [docs.aws.amazon.com/eks](https://docs.aws.amazon.com/eks/latest/userguide/what-is-eks.html)
* 📖 **Conventional Commits:** [conventionalcommits.org](https://www.conventionalcommits.org/en/v1.0.0/)

---

## 👥 Autores

| 👤 Nome | 🖼️ Foto | :octocat: GitHub | 💼 LinkedIn | 📤 Gmail |
|---------|----------|-----------------|-------------|-----------|
| Igor | <div align="center"><img src="https://github.com/igorfclima.png" width="70px" height="70px" style="border-radius:50%"></div> | <div align="center"><a href="https://github.com/igorfclima"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github" width="100px"></a></div> | <div align="center"><a href="https://linkedin.com/in/igorfclima"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin" width="100px"></a></div> | <div align="center"><a href="mailto:igorfclima@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail" width="100px"></a></div> |

---

## 🤝 Contribuição

1. Faça um `fork` do projeto.
2. Crie uma branch para sua feature (`git checkout -b feature/minha-feature`).
3. Commit suas mudanças (`git commit -m 'feat: Adiciona nova funcionalidade X'`). **(Utilize [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/))**
4. Faça o `push` para a branch (`git push origin feature/minha-feature`).
5. Abra um **Pull Request (PR)**.

> [!IMPORTANT]
> 📝 Por favor, verifique o arquivo [`CONTRIBUTING.md`](./CONTRIBUTING.md) para detalhes sobre o guia de estilo de código e o processo de submissão de PRs.

---

## 🙏 Agradecimentos

* [**Riot Games Developers**](https://developer.riotgames.com/) — Pela API pública que torna possível a coleta de dados de partidas de LoL e Valorant.
* [**Blizzard Entertainment**](https://develop.battle.net/) — Pela Battle.net API com dados de Overwatch.
* [**Comunidade brasileira de esports**](https://www.instagram.com/) — Pela inspiração e validação da proposta de valor da plataforma.

---

## 📄 Licença

Este projeto é distribuído sob a **[Licença MIT](./LICENSE)**.

---
