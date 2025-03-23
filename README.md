# Welth - Finance Tracking Application

![Welth Logo](path/to/logo.png)

**Welth** is an AI-powered financial management platform designed to help users track their income and expenses efficiently. With intuitive visualizations like pie charts and histograms, Welth provides a clear overview of your spending patterns and financial health. It offers features like budget planning, multi-account support, receipt scanning, and automated insights to optimize your financial decisions.

## Features

### Core Features
- **Expense & Income Tracking**: Easily add and categorize transactions (e.g., groceries, housing, entertainment) to monitor your financial activity.
- **Visualizations**:
  - **Pie Chart**: Displays a breakdown of monthly expenses by category (e.g., housing: $4454.48, groceries: $1515.50).
  - **Histogram**: Shows daily income and expenses over a selected period (e.g., total income: $5236.66, total expenses: $1750.54, net: $3467.12 for the last month).
- **Budget Planning**: Set monthly budgets and track your spending (e.g., $17663.50 spent out of $100,000.00, 11.7% used).
- **Multi-Account Support**: Manage multiple accounts and credit cards in one place (e.g., Personal Account: $145,590.51, Stocks Account: $110,000.00).
- **Receipt Scanning with AI**: Automatically extract transaction data from receipts using Google Gemini API.
- **Automated Insights**: Get AI-powered financial recommendations to optimize spending.
- **Multi-Currency Support**: Handle transactions in multiple currencies with real-time conversion.

### Additional Features
- **Recent Transactions Overview**: View a list of recent transactions with details like date, description, category, and amount (e.g., Paid for groceries: -$479.29 on Mar 21, 2025).
- **Recurring Transactions**: Set up recurring transactions for regular expenses or income.
- **Advanced Analytics**: Gain insights into spending patterns with AI-powered analytics.

## Screenshots

### Dashboard
![Dashboard](path/to/dashboard-screenshot.png)  
*The dashboard provides an overview of your monthly budget, recent transactions, expense breakdown via pie chart, and account balances.*

### Personal Account Transactions
![Personal Account](path/to/personal-account-screenshot.png)  
*View your personal account balance, transaction history with a histogram of daily income/expenses, and a detailed transaction list.*

### Add Transaction
![Add Transaction](path/to/add-transaction-screenshot.png)  
*Add new transactions with fields for type (expense/income), amount, account, category, date, and description. Includes an AI-powered receipt scanning option.*

### Landing Page
![Landing Page](path/to/landing-page-screenshot.png)  
*The landing page highlights Welth’s key stats (50K+ active users, $2B+ transactions tracked, 99.9% uptime, 4.9/5 user rating) and core features.*

## Tech Stack

### Frontend
- **Next.js**: React framework for building the user interface.
- **Tailwind CSS**: Utility-first CSS framework for styling.
- **Shadcn UI**: Component library for a consistent and modern UI design.

### Backend
- **Prisma & Supabase**: Database management and ORM for handling user data and transactions.
- **Inngest**: For email sending and automation.
- **Arject**: Protection against spam bots.

### Authentication
- **Clerk**: Secure user authentication and session management.

### AI Integration
- **Google Gemini API**: Used for AI-powered receipt scanning to extract transaction data.

## Installation

### Prerequisites
- Node.js (v16 or higher)
- npm or Yarn
- Supabase account for database setup
- Clerk account for authentication
- Google Gemini API key for receipt scanning
- Inngest account for email sending

### Steps
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/welth.git
   cd welth
