## Next.js App Router Course - Starter

This is the starter template for the Next.js App Router Course. It contains the starting code for the dashboard application.

For more information, see the [course curriculum](https://nextjs.org/learn) on the Next.js Website.

### Create a .env file with these parameters:
```env
# Copy from .env.local on the Vercel dashboard
# https://nextjs.org/learn/dashboard-app/setting-up-your-database#create-a-postgres-database
POSTGRES_URL="postgres://default:AMyW1C6RBDOo@ep-round-recipe-24420130-pooler.us-east-1.postgres.vercel-storage.com:5432/verceldb"
POSTGRES_PRISMA_URL="postgres://default:AMyW1C6RBDOo@ep-round-recipe-24420130-pooler.us-east-1.postgres.vercel-storage.com:5432/verceldb?pgbouncer=true&connect_timeout=15"
POSTGRES_URL_NON_POOLING="postgres://default:AMyW1C6RBDOo@ep-round-recipe-24420130.us-east-1.postgres.vercel-storage.com:5432/verceldb"
POSTGRES_USER="default"
POSTGRES_HOST="ep-round-recipe-24420130-pooler.us-east-1.postgres.vercel-storage.com"
POSTGRES_PASSWORD="AMyW1C6RBDOo"
POSTGRES_DATABASE="verceldb"

# `openssl rand -base64 32`
AUTH_SECRET=
AUTH_URL=http://localhost:3000/api/auth
```