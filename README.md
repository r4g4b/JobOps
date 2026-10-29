# JobOps

JobOps is a web app that helps you manage your job search in one place.
You can track job applications, keep your profile up to date, and adjust
your settings.

## Project Structure

```
JobOps/
├── backend/         Server-side code and API
├── frontend/        User interface (Tailwind CSS)
│   ├── src/         Styles and source files
│   └── dist/        Built CSS output
├── docs/            Project documentation
│   └── wireframes/  UI designs for desktop and mobile
├── deployment/      Deployment configs and scripts
└── tests/           Project tests
```

## Main Screens

- **Dashboard** – Overview of your job search.
- **Applications** – List of jobs you applied to.
- **Profile** – Personal info, preferences, work and education.
- **Settings** – Account and app settings.
- **Register** – Create a new account.

## Frontend

The frontend uses Tailwind CSS. From the `frontend` folder:

- `npm install` – install dependencies
- `npm run dev` – build CSS in watch mode
- `npm run build` – build minified CSS
