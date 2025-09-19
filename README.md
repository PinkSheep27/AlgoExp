# AlgoExp

## Overview
Learning Platform for anyone that is interested in developing their algorithm skills.
Built upon Tailwind, Canvas API, TypeScript, React, AWS, etc. Users can interact with
the website to choose different algorithms, adjust speed, go step-by-step, & perhaps 
even practice (TBD).

## Problem Statement
Algorithms can be extremely hard to learn and students going through this struggle usually want a way to easily understand them.

## Technical Architecture
- **Frontend**: React 18 with TypeScript
- **Styling**: Tailwind CSS for responsive design
- **Backend**: Next.js API routes with AWS Lambda
- **Database**: PostgreSQL with Drizzle ORM
- **Cloud**: AWS (S3, Lambda, Aurora DSQL)
- **Testing**: Vitest with 70% coverage target
- **Deployment**: GitHub Actions CI/CD

## Prerequisites
- Node.js 18.17.0 or higher
- npm 9.6.7 or higher
- Git configured with your credentials
- GitHub account with Copilot access

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/[yourusername]/expense-tracker
   cd expense-tracker
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Set up environment variables:
   ```bash
   cd .env.example .env.local
   # Add your confuguration values
   ```
4. Start development server:
   ```bash
   npm run dev
   ```
## Contributing
Please read our Contributing Guidelines and Code of Conduct before submitting PRs.

## Architecture Decision Records
See docs/ADR/ for technical decision documentation.

## License
MIT License - see LICENSE for details.