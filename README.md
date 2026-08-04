# Insurance Management Platform

A full-stack internship MVP for managing insurance customers, policies, claims, premium payments, and documents.

## Start locally

1. Copy `server/.env.example` to `server/.env` and set `DATABASE_URL`.
2. Run `npm install`.
3. Run `npm run prisma:generate --workspace server` and `npm run prisma:migrate --workspace server`.
4. Seed sample data with `npm run seed --workspace server`.
5. Start both apps with `npm run dev`.

The frontend runs at `http://localhost:5173` and API at `http://localhost:4000`.

Demo login: `admin@securelife.test` / `Password123!`
