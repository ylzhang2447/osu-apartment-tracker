# OSU Math Department — Apartment Tracker

A self-contained single-page tracker for apartment hunting near The Ohio State University Math Department (Math Tower, 231 W 18th Ave, Columbus, OH).

## Live page

Once GitHub Pages is enabled, the tracker will be at:
`https://<your-github-username>.github.io/<repo-name>/`

## How notes work

- Notes, tour dates, and statuses save to **your own browser** (localStorage).
- They do **not** sync between devices or users automatically.
- To share your notes with someone else: click **Export notes (JSON)**, send them the file, they click **Import notes (JSON)**.

## Editing the apartment list

Apartments live in the `APARTMENTS` array near the top of the `<script>` block in `index.html`. Each entry has: `id`, `rank`, `name`, `address`, `distance`, `bus`, `rent`, `floorplans`, `gym`, `safety`, `tags`, `website`, `maps`.

To add a property, copy an existing entry, change the fields, commit, and push — GitHub Pages will redeploy automatically (usually within ~1 min).

## Letting friends edit

- Add them as **collaborators** in your repo settings, or
- They fork the repo and submit pull requests.
