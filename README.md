# Next Course - Next.js + Convex

Projeto criado para acompanhar o curso de Next.js do **Jan Marshal** no YouTube.

Aqui estou configurando a base com:

- Next.js (App Router)
- React
- TypeScript
- Tailwind CSS
- shadcn/ui
- Convex (BaaS)

## Objetivo

Montar uma aplicação moderna com Next.js, evoluindo passo a passo junto com as aulas e usando o Convex como backend.

## Tecnologias

- `next@16`
- `react@19`
- `typescript@5`
- `tailwindcss@4`
- `shadcn/ui`
- `convex`
- `zod`
- `react-hook-form`

## Como rodar o projeto

1. Instale as dependências:

```bash
pnpm install
```

2. Inicie o projeto em modo desenvolvimento:

```bash
pnpm dev
```

3. Abra no navegador:

```text
http://localhost:3000
```

## Convex

Este projeto já possui a estrutura inicial do Convex na pasta `convex/`.

Para usar as rotas/funções do Convex durante o desenvolvimento, rode também:

```bash
pnpm dlx convex dev
```

## Scripts disponíveis

- `pnpm dev` - inicia o projeto em desenvolvimento
- `pnpm build` - gera build de produção
- `pnpm start` - roda a versão de produção
- `pnpm lint` - executa o lint

## Status

Projeto em andamento, sendo construído durante o curso.
