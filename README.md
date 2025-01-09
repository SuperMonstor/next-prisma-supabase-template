Simple To-Do app template built with Next.JS, supabase, Prisma, and Tailwind 

## Getting Started

To set up prisma

```bash
npm install @prisma/client

npx prisma init
```

Then, copy URI from the Supabase dashboard and paste into the `.env` file. Replace `[password]` with your database password.


## To deploy a model 
```bash
 npx prisma migrate dev --name init               
```

where `[init]` is the name of the migration.