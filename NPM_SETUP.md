# Financial Survival Toolkit — npm run setup

## Requirements
- Node.js + npm
- Java (the backend currently targets Java 17; your Fedora Java 25 is also able to compile this project successfully)

## One-command start
From this project root:

```bash
npm install
npm start
```

This starts:
- Frontend: http://localhost:5500
- Spring Boot backend: http://localhost:8080

Keep the terminal running while using the app.

## Useful commands
```bash
npm run frontend
npm run backend
./backend/mvnw test
```

The existing UI files (`index.html`, `style.css`, `script.js`) are kept as-is apart from the existing API integration already present in this project.
