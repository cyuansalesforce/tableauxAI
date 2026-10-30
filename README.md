# Tableau x AI workshop microsite

Static one-page site (`public/workshopguide.html`) served by a tiny Express server, same setup as the workshop guide repo.

    npm install
    npm start        # http://localhost:3000

- Slides are deep-linkable: `/#1` welcome, `/#2` agenda, `/#3` Tableau Cloud, and so on.
- `public/data/AI Workshop - Saas Dataset.csv` is the outdated CSV that attendees download in the Headless section.
- To deploy to Heroku: `heroku create`, then `git push heroku main` (the `Procfile` runs `node server.js`).
