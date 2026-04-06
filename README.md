# Backend HTML → PDF

## Como rodar
```bash
npm install
npm start
```
Servidor em http://localhost:3001

## POST /generate-pdf
Body: `{ "html": "<html>...</html>" }`
Retorna: arquivo PDF

## Integração
1. Rode este backend
2. No frontend, configure URL como http://localhost:3001
3. Clique "Gerar PDF"
# generate-pdf-backend
