 # FinVision 🚀

**FinVision** is a production-level wealth management application designed to provide users with deep insights into their financial health through visual analytics, automated tracking, and AI-driven forecasting.

## 🏗️ Tech Stack

- **Framework**: [Next.js 15 (App Router)](https://nextjs.org/)
- **Language**: [TypeScript](https://www.typescriptlang.org/)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/)
- **Database ORM**: [Prisma](https://www.prisma.io/)
- **Database**: PostgreSQL (Recommended)
- **Formatting**: Prettier with Tailwind Plugin



## ✨ Key Features (Planned)

1.  **Wealth Dashboard**: Real-time overview of net worth, assets, and liabilities.
2.  **Transaction Tracking**: Automated categorization of spending across all accounts.
**Visual Analytics**: Interactive charts for spending trends and investment performance.
.  **Budget Management**: Set and track monthly limits for different categories.
5.  **Secure Auth**: Multi-factor authentication for data protection.

## 📂 Project Structure

- `src/app`: Application routes and pages.
- `src/components`: UI components (layout, features, shadcn/ui).
- `src/lib`: Shared utilities and Prisma client.
- `src/services`: Business logic and third-party API integrations (e.g., Plaid).
- `src/hooks`: Custom React hooks for state and data fetching.
- `prisma/`: Database schema and migrations.

## 🚀 Getting Started

### 1. Install Dependencies
```bash
npm install
```

### 2. Environment Setup
Copy the `.env` file and add your database credentials:
```bash
DATABASE_URL="postgresql://johndoe:randompassword@localhost:5432/finvision?schema=public"
```

### 3. Database Migration
```bash
npx prisma generate
```

### 4. Run Development Server
```bash
npm run dev
```

## 🛠️ Current Progress

- ✅ Initialized Next.js project with TypeScript and Tailwind.
- ✅ Established professional folder architecture.
- ✅ Configured Prettier and developer tools.
- ✅ Defined core database schema (Users, Accounts, Transactions, Budgets).
