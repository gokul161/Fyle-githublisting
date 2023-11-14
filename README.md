# GitHubListing

- Frontend
  - Angular single-page application (SPA) that takes a GitHub username as input and displays the public Github repositories belonging to the user.
  - If the username is invalid, should show an error page indicating an invalid GitHub username.
- Backend
  - REST API service (NodeJS)
  - Each endpoint has to internally call Github’s APIs to fetch the data required for the frontend application to work.

## Run Locally

1. Clone the project

```bash
  git clone https://github.com/Gopi1422/github-repo-listing.git
```

2. Go to the project directory

```bash
  cd github-repo-listing
```

3. Install dependencies

> Install Server dependencies

```bash
  npm install
```

> Install Client dependencies

```bash
  cd frontend/
  npm install –g @angular/cli
  npm install
```

4. Start the server

```bash
  npm start
```

5. Start the client

```bash
  cd frontend/
  ng serve
```
