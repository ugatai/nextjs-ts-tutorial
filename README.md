<p align="center">
  <img width="110" height="110" src="https://img.icons8.com/fluency/128/nextjs.png" alt="nextjs"/>
  <img width="110" height="110" src="https://img.icons8.com/color/128/typescript.png" alt="typescript"/>
</p>

# NextJs13 Tutorial App with TypeScript

* [NextJs Document](https://nextjs.org/docs)
* [TypeScript Document](https://www.typescriptlang.org/)

## Environments

- Node: v16.14.0
- NextJs: v13.4.16

## Additional Node Modules

* [json-server](https://www.npmjs.com/package/json-server)
* [uuid](https://www.npmjs.com/package/uuid)
* [@types/uuid](https://www.npmjs.com/package/@types/uuid)
* [@heroicons/react](https://www.npmjs.com/package/@heroicons/react)

## Directory Structure

```
src/
|-- pages/
|   |-- api/             # Page api aysc function files
|   |   |-- todo.ts
|-- pubclic/             # Static file installation
|-- src/        
|   |-- app/
|   |   |-- components/  # Installation of component files
|   |   |　　|-- Todo/   
|   |   |   |   |-- index.tsx
|   |   |   |   |-- Todo.module.css (or Button.styles.ts)
|   |   |   |   |-- Todo.test.tsx
|   |   |-- types/       # Installation of type definition files
|   |   |-- layout.tsx   # Layout files common to all pages
|   |   |-- page.tsx     # Application entry point
|   |-- data/
|   |   |-- todos.json
|-- .eslintrc.json       
```

## Getting Started

First, run the development server:

```bash
npx next dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

Second, run the json server:

```bash
npm run mock
```

* [Documentation](https://www.npmjs.com/package/json-server)

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.