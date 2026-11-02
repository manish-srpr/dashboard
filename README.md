# InkWell Blog

A polished, responsive blogging platform built with semantic HTML, CSS, and vanilla JavaScript. InkWell lets visitors discover stories and lets registered writers draft, publish, and manage their own posts. Demo accounts and blog data persist in browser localStorage.

## Features

- Responsive landing page with search, category filters, story detail view, and newsletter interaction.
- Registration, login, logout, password visibility, validation, duplicate email checks, and protected writer pages.
- Dashboard with per-user story counts and create, edit, and delete actions.
- Blog editor with category, description, image preview, draft, and publish support.
- Seeded sample stories make Explore useful on first launch.

## Technologies

HTML5, CSS3, vanilla JavaScript, and localStorage. No frontend framework or build step is required. Google Fonts and Unsplash are used for typography and sample photography when online.

## Project structure

```text
index.html
login.html
register.html
dashboard.html
create-blog.html
css/style.css
js/app.js
js/auth.js
js/blogs.js
js/dashboard.js
```

## Run locally

Open `index.html` in a browser, or serve the folder with any static file server (for example, `python -m http.server 8000`) and visit `http://localhost:8000`. A local server is recommended for consistent browser behavior.

## Try the features

1. Register a new account and you will land in your workspace.
2. Log out, then log back in using the same credentials. Try an incorrect password and a duplicate registration to see validation.
3. Create a story, add an image URL, and save it as a draft or publish it. Refresh to confirm the data persists.
4. Edit or delete a story from the dashboard. Published stories appear on Home.
5. Search for a story or choose a category on Home, then open a story with “Read story.”
6. Resize the browser to check the mobile navigation and layouts.

## Screenshots

Add screenshots here after capturing the app, for example `![Home page](assets/images/home.png)`.

## Future improvements

Add a backend and secure authentication, image uploads, rich text editing, comments, reader accounts, and server-side search.

## GitHub and deployment

To publish, initialize a Git repository, commit the project, create a GitHub repository, and push your branch. For deployment, import the repository into Vercel with the framework preset set to “Other” and no build command, or enable GitHub Pages from the repository’s Settings → Pages and publish the root folder. The project is static and needs no build step.

Demo passwords are stored in localStorage and are not secure. Do not use real credentials; use a proper backend for production authentication.
