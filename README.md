# Team Budget

Team Budget is a web app for monthly zero-based budgeting. Users enter their planned income, create their own categories, and assign every dollar to a category. The final project is due December 15, 2026.

## Project requirements

- Let users enter the total income they expect for a month.
- Let users create their own budget categories and set an amount for each category.
- Show the difference between planned income and the total assigned to categories. A positive balance means there is money left to assign. A negative balance means the plan is over budget. The budget is balanced when the difference is zero.
- Save each monthly budget so users can open it again.

## Technical plan

- Use React Router v7 in Framework Mode for the frontend and backend. The starter includes TypeScript, Vite, Tailwind CSS, and server-side rendering.
- Use Firebase for budget storage. Cloud Firestore is the starting choice. The team can consider a relational option if the data model calls for it.

The first version focuses on planning a monthly budget. Bank transaction imports and recurring bill calculations by payday are ideas for later. Offline PWA support and WebSockets were discussed as optional course features. The team still needs to confirm the course rubric and divide the work.

## Local development

Use Node.js 24 and npm. Install dependencies and start the development server.

```bash
npm ci
npm run dev
```

Open [http://localhost:5173](http://localhost:5173). The starter displays the default React Router welcome page and runs without Firebase credentials.

To check types, build the app, and run the production build locally, use these commands.

```bash
npm run typecheck
npm run build
npm start
```
