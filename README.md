onboarding/
├── backend/ # Aqui fica o NestJS
├── frontend/ # Aqui fica o React/Vite
├── .env # Variáveis de ambiente globais (banco)
└── docker-compose.yml # Orquestração dos containers

## Documentação de comandos usados

- npx @nestjs/cli new backend --package-manager npm (Cria o diretório do backend)
- npm create vite@latest frontend -- --template react-ts (Cria o diretório do frontend)
- cd backend | npm run start (Inicializa o Nest)
- cd frontend | npm run dev (Inicializa o Vite+React)
- docker-compose up -d (Sobe o docker-compose)
