This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.

Dependencies:

Create a project: npx create-next-app ([1] name the project, [2] accept all the default values for the project)

Install the following VS Code extensions:
1. ES7+React/Redux/React-Native
2. JavaScript and TypeScript Nightly
3. Tailwind CSS IntelliSense
4. Prisma

To use react-icons library: npm install react-icons
To use reach-hooks: npm install react-hook-form
To use simpleMDE: npm install --save react-simplemde-editor easymde
To use axios instead of fetch: npm install axios
To use radix ui: npm install @radix-ui/themese
To use zod: npm install zod (zod is for form validation)
To use classnames: npm install classnames

To install prisma:
1. npm install prisma
2. npx install prisma init (creates prisma client)
3. npx prisma format (do this after creating your models)
4. npx prisma migrate dev (to migrate prisma model to database)
