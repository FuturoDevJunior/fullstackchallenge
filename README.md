# Full Stack Challenge

## Setup
1. Clone o repositório: `git clone <link>`
2. Entre no diretório: `cd fullstack-challenge`
3. Suba os serviços: `docker-compose up --build`
4. Popule o banco: `python backend/scripts/populate_db.py` (execute localmente com MongoDB rodando)
5. Acesse:
   - Backend: `http://localhost:8000/docs`
   - Frontend: `http://localhost:3000`
   - Storybook: `cd frontend && npm run storybook`

## Estrutura
- `backend/`: FastAPI com MongoDB e upload para S3.
- `frontend/`: React com Material UI e Storybook.
- `lambda/`: Função Lambda com Serverless Framework.
- `docker-compose.yml`: Configuração dos serviços.

## Funcionalidades
- CRUD para Products, Categories e Orders.
- Dashboard com métricas básicas.
- Upload de imagens para S3 (LocalStack).
- Script de dados fictícios.
- Componentes documentados no Storybook.#   s t a c k c h a l l e n g e  
 # -
