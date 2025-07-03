# 🚀 Desafio Técnico de Estágio de TI

Bem-vindo ao desafio técnico para a vaga de Estagiário(a) de Desenvolvimento na Haytek! Este desafio foi criado para avaliar suas habilidades técnicas e sua capacidade de resolver problemas reais que enfrentamos no nosso dia a dia.

## 🌟 Sobre a Haytek

Somos uma empresa líder no mercado de lentes oftálmicas, fornecendo produtos de alta qualidade para óticas em todo o Brasil. Nosso e-commerce processa centenas de pedidos diariamente, e estamos constantemente buscando melhorar nossa plataforma.

## 🎯 Objetivo do Desafio

Desenvolver um sistema de gestão de produtos para nosso e-commerce, implementando operações CRUD (Create, Read, Update, Delete). Segue abaixo o modelo de exemplo que precisará ser criado:


| Field               | Type      | Example Value                                | Technical Notes                  |
|---------------------|-----------|----------------------------------------------|----------------------------------|
| `id`                | UUID v4   | `"a3d9f1b0-5c72-4e3d-8c55-2f1e8d4b6a7f"`     | **RFC 4122 compliant**           |
| `model`             | String    | `"Nikon NIKKOR Z 24-70mm f/2.8 S"`          | Include full product name        |
| `brand`             | String    | `"Nikon"`                                   | Use official brand casing        |
| `type`              | String    | `"Zoom"`                                    | Prime/Zoom/Macro/Tilt-Shift      |
| `focalLength`       | String    | `"24-70mm"`                                 | Single value for primes          |
| `maxAperture`       | String    | `"f/2.8"`                                   | Include f/ prefix                |
| `mount`             | String    | `"Nikon Z Mount"`                           | Official mount name              |
| `weight`            | Integer   | `805`                                       | Always in grams                 |
| `hasStabilization`  | Boolean   | `true`                                      | Vibration Reduction (VR) enabled |
| `active`            | Boolean   | `true`                                      | Soft-delete flag                |

## Exemplo de JSON

```json
{
  "id": "a3d9f1b0-5c72-4e3d-8c55-2f1e8d4b6a7f",
  "model": "Nikon NIKKOR Z 24-70mm f/2.8 S",
  "brand": "Nikon",
  "type": "Zoom",
  "focalLength": "24-70mm",
  "maxAperture": "f/2.8",
  "mount": "Nikon Z Mount",
  "weight": 805,
  "hasStabilization": true,
  "active": true
}
```

## 💻 Tecnologias Recomendadas

### Backend (Escolha uma)
- [Node.js](https://nodejs.org/en/) (Diferencial se usar TypeScript)
- [NestJS](https://nestjs.com/) (Framework preferencial)
- [Golang](https://go.dev/) 

### Frontend
- [React](https://react.dev/) (Preferencial com TypeScript)
- [Vite](https://vitejs.dev/) (Como alternativa para configuração rápida)

### Banco de Dados (Sugestões)
- PostgreSQL
- MongoDB
- SQLite (para testes locais)

## 📋 Requisitos Técnicos

### Backend
- API RESTful ou GraphQL
- Validação de dados
- Tratamento de erros adequado
- Documentação da API (Swagger/OpenAPI)
- Testes unitários (será um diferencial)

### Frontend
- Interface responsiva e acessível
- Formulários para CRUD de produtos
- Listagem paginada de produtos
- Filtros e busca
- Feedback visual para ações do usuário

## 📌 Critérios de Avaliação

Seu projeto será avaliado considerando:

1. **Funcionalidade** (40%)
   - Todas as operações CRUD implementadas
   - Interface funcional e intuitiva

2. **Qualidade de Código** (30%)
   - Boas práticas de programação
   - Código limpo e organizado
   - Padrões de projeto adequados

3. **Documentação** (20%)
   - README completo e claro
   - Instruções de instalação e execução
   - Exemplos de chamadas API (se aplicável)

4. **Diferenciais** (10%)
   - Testes automatizados
   - Dockerização do projeto
   - UI/UX cuidadosa

## 📂 Entrega

1. Crie um repositório público no GitHub
2. Documente todo o processo no README.md
3. Inclua um arquivo `.gitignore` apropriado
4. Envie o link do repositório para nosso time de recrutamento
5. Prazo 1 semana

## 🔧 Configuração do Ambiente (Exemplo)

```bash
# Clone o repositório
git clone [seu-repositorio]
cd [nome-do-projeto]

# Backend (exemplo Node.js)
cd backend
npm install
npm run dev

# Frontend (exemplo React)
cd frontend
npm install
npm start
```

## ⁉️ Dúvidas?

Em caso de dúvidas sobre o desafio, entre em contato com [rosemberg.paz@haytek.com.br] com o assunto "Dúvida Desafio Estágio Haytek".

Boa sorte! Estamos ansiosos para ver sua solução criativa e técnica para este desafio.
