# PhytoID - Rede Inteligente de Análise Fitoplanctônica
Kickoff Meeting: https://tldv.io/app/meetings/673237da770b470014d12266/

Sistema Web colaborativo para identificação automatizada de fitoplâncton através de imagens microscópicas, utilizando machine learning e análise de metadados ambientais.

### Contexto
O PhytoID é uma solução para automatizar e otimizar o processo de identificação de fitoplâncton, criando uma base de dados global para análise da qualidade da água. O sistema permite que taxonomistas, laboratórios e consultores ambientais colaborem e compartilhem conhecimento.

### Principais Funcionalidades
- Upload e análise de imagens microscópicas
- Identificação automatizada via ML
- Gestão de metadados ambientais
- Validação por especialistas
- Análise geoespacial de amostras
- Dashboard analítico

### Personas
- **Taxonomistas**: Validação e confirmação de identificações
- **Laboratórios**: Automação de processos de análise
- **Consultores**: Análise de dados agregados

### Sistemas Semelhantes

- [plankton net](https://planktonnet.awi.de/)
- [NMFS-COPEPOD: The Global Plankton Database, WEBSEC Sub-Collection](https://obis.org/dataset/5cfef543-d293-45b8-b656-c3628ff34b7c)
- [AODN Open Access to Ocean Data](https://portal.aodn.org.au/search)
- [ICES]([./CHANGELOG.md](https://data.ices.dk/view-map))

## Tecnologias

### Frontend
- Vue.js
- Vuetify CSS
- TypeScript

### Backend
- Python
- FastAPI
- JWT Authentication

### Cloud
- AWS (Infraestrutura)
- Google Vertex AI (ML)
- PostgreSQL (Dados)
- S3 (Armazenamento)

## Arquitetura

### Componentes Principais
- **Web Interface**: Aplicação Vue.js para interação com usuários
- **API REST**: Backend Python para processamento e orquestração
- **ML Service**: Integração com Google Vertex AI
- **Data Store**: Sistema de armazenamento distribuído

