## Next.js App Router Course - Starter

This is the starter template for the Next.js App Router Course. It contains the starting code for the dashboard application.

For more information, see the [course curriculum](https://nextjs.org/learn) on the Next.js Website.


env

# Copy from .env.local on the Vercel dashboard
# https://nextjs.org/learn/dashboard-app/setting-up-your-database#create-a-postgres-database
POSTGRES_URL="postgres://default:r8Q2ZIpmTYAs@ep-ancient-truth-a4pb6ow6-pooler.us-east-1.aws.neon.tech:5432/verceldb?sslmode=require"
POSTGRES_PRISMA_URL="postgres://default:r8Q2ZIpmTYAs@ep-ancient-truth-a4pb6ow6-pooler.us-east-1.aws.neon.tech:5432/verceldb?sslmode=require&pgbouncer=true&connect_timeout=15"
POSTGRES_URL_NO_SSL="postgres://default:r8Q2ZIpmTYAs@ep-ancient-truth-a4pb6ow6-pooler.us-east-1.aws.neon.tech:5432/verceldb"
POSTGRES_URL_NON_POOLING="postgres://default:r8Q2ZIpmTYAs@ep-ancient-truth-a4pb6ow6.us-east-1.aws.neon.tech:5432/verceldb?sslmode=require"
POSTGRES_USER="default"
POSTGRES_HOST="ep-ancient-truth-a4pb6ow6-pooler.us-east-1.aws.neon.tech"
POSTGRES_PASSWORD="r8Q2ZIpmTYAs"
POSTGRES_DATABASE="verceldb"

# `openssl rand -base64 32`
AUTH_SECRET=
AUTH_URL=http://localhost:3000/api/auth