# Catálogo de Carros

Listagem de carros, onde ao clicar no card consigo ver detalhes e preencher um formulário de contato.

## Tecnologias

- React 18.3.1
- TypeScript 5.6.3
- Vite 5.4.11
- React Router DOM 6.26.2
- TanStack Query 5.59.20
- Tailwind CSS 4.1.17
- Axios 1.7.7
- Zustand 5.0.1
- React Hook Form 7.53.2
- Zod 4.1.11

## Estrutura do Projeto

```
src/
├── assets/          # Recursos estáticos (estilos, imagens)
├── core/            # Componentes e utilitários compartilhados
│   ├── components/  # Componentes genéricos reutilizáveis
│   ├── lib/         # Configurações de bibliotecas
│   ├── types/       # Tipos TypeScript globais
│   └── utils/       # Funções utilitárias
├── domain/          # Domínios de negócio
├── layouts/         # Layouts da aplicação
├── pages/           # Páginas da aplicação
├── router/          # Configuração de rotas
├── App.tsx          # Componente raiz
└── main.tsx         # Ponto de entrada
```

## Configuração

1. Instale as dependências:
```bash
npm install
```

2. Configure as variáveis de ambiente:
```bash
cp .env.example .env
```

3. Inicie o servidor de desenvolvimento:
```bash
npm run dev
```

## Scripts Disponíveis

- `npm run dev` - Inicia o servidor de desenvolvimento
- `npm run build` - Gera build de produção
- `npm run preview` - Visualiza o build de produção
- `npm run lint` - Executa o linter

## Funcionalidades

- **Listagem de carros**: Exibição de todos os veículos disponíveis no catálogo
- **Visualização de detalhes**: Página com informações detalhadas do veículo
- **Formulário de contato**: Formulário para manifestar interesse no veículo

## API

O frontend se conecta com a API REST em:
- Base URL: `http://localhost:3000/api/v1`
- Endpoints públicos: `/external`
- Endpoints autenticados: `/internal`