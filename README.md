## Goals from this Projects
The application shall enable internal employees to complete mandatory or voluntary training and instruction based on SCORM-compliant content. Additionally, managers and evaluators receive an overview of which employees have already completed training and which training courses are still outstanding, and, where needed, they receive automated notifications about overdue participation.

The target group consists exclusively of internal users within a company

## Techstack
* Frontend/Backend: Next.js 15 (App Router) by Vercel/ Nodejs
* Database: MongoDB
* Auth: Kerberos / LDAP
* Email-dispatch: SMTP-based mail service
* SCORM-support: SCORM 1.2, SCORM 2004

> Note: During development, well-established open-source libraries for Next.js and Node.js are used to minimize development and maintenance effort. The libraries used can be viewed in the package file

## Getting Started
Renamed **.env-template** to **.env** and fill the variables out.

Only then run the development server:

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