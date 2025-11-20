# TODO: Remove Backend from Next.js App

## Step 1: Remove Backend Files and Directories
- [x] Delete app/auth/ directory (API routes)
- [x] Delete prisma/ directory (Prisma schema and config)
- [x] Delete prisma.config.ts
- [x] Delete app/lib/prisma.ts
- [x] Delete app/lib/auth.ts
- [x] Delete app/lib/email.ts

## Step 2: Update package.json
- [x] Remove backend dependencies: @auth/prisma-adapter, @next-auth/prisma-adapter, @prisma/client, bcryptjs, next-auth, nodemailer, prisma

## Step 3: Clean Up Frontend Pages
- [x] Edit app/login/page.tsx: Remove NextAuth logic, make static
- [x] Edit app/register/page.tsx: Remove API fetch, make static
- [x] Edit app/profile/page.tsx: Remove useSession and API calls, make static
- [x] Edit app/admin/page.tsx: Remove API fetches and auth, make static

## Step 4: Install and Build
- [ ] Run npm install
- [ ] Run npm run build to verify
