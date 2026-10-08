# AA No Reset Stats Website

Make your own stats website for 1.16.1 All Advancements Runs, like
[Zesskyo's AA No Reset Log](https://zesskyo.github.io/aa-stats-no-reset-zesskyo-log/)

The code comes from [aa-stats](https://github.com/zesskyo/aa-stats), so new features show up on your site **automatically**.

## Setup

1. **Copy this template.** At the top of this page click **Use this template → Create a new repository**.
   Pick any name (it becomes part of your site's address, e.g. `aa-stats`) and keep it **Public**.
2. **Turn on the website.** In your new repository go to **Settings → Pages**, and under
   **Build and deployment → Source** choose **GitHub Actions**.
3. **Build it for the first time.** Go to the **Actions** tab, click **Build and publish the site** on the left,
   then **Run workflow → Run workflow**. Wait for the green tick.
4. **Open your site** at `https://<your-username>.github.io/<repository-name>/`
   (also shown under **Settings → Pages**).
5. **Click "Set up this site"** on the welcome card. It walks you through:
   - **Signing in**: you make a GitHub token that can only save to this one repository and paste it in once.
     The steps are on screen. The token stays in your browser, and only you can edit your site.
   - **Naming your site**: type your title and subtitle, e.g. *AA No Reset Solo* and *(Your Name's Log)*.
   - **Adding your first run** (see below).

## Add, edit and delete runs

Signed in on your site, click **+ Add run** at the top:

- **With a Hermes log:** drop in the run's `play.log`. The date, time, 100% and deaths are read from it.
  Tick the deaths that were on purpose, and add a seed, proof or notes.
- **Without a log** (older runs, or not played with Hermes): fill in whatever you have, like the final time,
  whether it was 100%, splits and the date. It all shows on the site; the graphs need a log.
- **Proof:** a video link or a screenshot (a link, or upload the image).
- **Elytra distance:** type it in, or pick the world's `stats/<uuid>.json` file.

Click **Save**, and the site updates by itself about a minute later. To change a run, pick it at the top of
the form (or use **Edit** on its page); that's also where you delete it. **Site settings** (at the bottom of the site) changes the title later on.
