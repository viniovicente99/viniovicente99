
Vinícius Vicente — Full Stack Developer

Desenvolvedor Full Stack com foco em APIs, integrações e arquitetura de sistemas distribuídos, atuando na construção de soluções que conectam serviços, processam dados e lidam com falhas em cenários reais.

Experiência com desenvolvimento backend em múltiplas stacks, construção de integrações entre sistemas, automações e arquiteturas assíncronas, além de participação em evolução de produtos e sistemas internos.

🚀 Stack Tecnológica

Backend

Java (Spring Boot)
Python (FastAPI)
Node.js (Express / Fastify)


Frontend

React (experiência prática)
Angular (experiência profissional)


Dados

PostgreSQL / MySQL
Modelagem relacional


Infra & DevOps

Docker / Docker Compose
Git
Execução e configuração de ambientes
Outros


REST APIs

Integrações com serviços externos
Arquitetura em camadas
Mensageria (RabbitMQ)
Debugging e análise de falhas


🔧 Projetos Relevantes

🚀 FlowOrder (Java + Spring Boot + RabbitMQ)

Sistema distribuído baseado em microsserviços para processamento assíncrono de pedidos.

Arquitetura:

Microsserviços independentes (Order, Payment, Notification)
Comunicação via mensageria (RabbitMQ)
Arquitetura orientada a eventos (event-driven)

Destaques:

Pipeline completo assíncrono de pedidos
Publicação e consumo de eventos (order.created, payment.created)
Uso de Dead Letter Queues (DLQ) para tratamento de falhas
Persistência isolada por serviço
Containerização com Docker

Fluxo:
Order → publica evento → Payment consome/processa → publica novo evento → Notification consome

Stack:
Java 17 • Spring Boot • RabbitMQ • PostgreSQL • Docker • JUnit • Swagger

🔗 API: https://order-service-2fg6.onrender.com/
🔗 Repositório: https://github.com/viniovicente99/flowOrder

Foco: microsserviços, mensageria, resiliência e processamento assíncrono


🔐 Sentinel API (Python + FastAPI)

API para ingestão e enriquecimento de eventos com integração externa.

Destaques:

Integração com API de geolocalização por IP
Tratamento de falhas com fallback controlado
Persistência em PostgreSQL
Estrutura em camadas
Containerização com Docker

Foco: integração, resiliência e consistência de dados

🔗 https://github.com/viniovicente99/sentinel-api


📦 Stokup (Node.js + Python + PostgreSQL)

Sistema de gestão de estoque com foco em regras de negócio e integração.

Destaques:

API REST com regras reais de negócio
Modelagem relacional
Integração com serviço externo (IA)
Comunicação entre serviços

Foco: integração + automação + regras de negócio

🔗 https://stokup.vercel.app/login
🔗 https://github.com/viniovicente99/stokup


🎬 Media Catalog API (Node.js + Fastify)

API para gerenciamento de catálogo com foco em organização e qualidade.

Destaques:

Arquitetura em camadas
Validação com Zod
ORM com Prisma
Testes com Vitest
Tratamento de erros centralizado


Infra:

Docker + docker-compose

Foco: boas práticas, testes e manutenção

🔗 https://github.com/viniovicente99/cinemais-api


💼 Experiência Profissional

Atuação em ambiente corporativo com sistemas utilizados por grandes redes varejistas.

Responsabilidades:

Desenvolvimento e manutenção de aplicações web
Integrações entre sistemas via APIs (JSON)
Correção de bugs em produção
Evolução de funcionalidades existentes
Participação em discussões técnicas

Projeto interno:

API REST em Node.js para gestão de conteúdo
Interface Angular com formulários dinâmicos
Upload de arquivos com AWS S3


⚙️ Práticas de Engenharia

Versionamento com Git
Estruturação em camadas e organização de código
Tratamento de erros e falhas de integração
Desenvolvimento orientado à manutenção e evolução
Participação em fluxos colaborativos

📌 Foco Atual

Arquitetura de microsserviços
Sistemas orientados a eventos
Integrações entre APIs e plataformas
Automação de processos
Evolução em boas práticas e arquitetura limpa

📫 Contato

LinkedIn: https://www.linkedin.com/in/vinicius-vicente-developer
