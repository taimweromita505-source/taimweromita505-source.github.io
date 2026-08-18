# Taimwe — Portfolio

Personal portfolio site hosted free on **GitHub Pages**.

**🌐 Live at:** `https://taimweromita505-source.github.io/`

## About this repo

- Account: `taimweromita505-source`
- Repo: `taimweromita505-source.github.io` (the `<username>.github.io` name is what makes it a Pages user site)
- `index.html` is the whole site — it's a static single-page portfolio

## Updating the site

1. Edit `index.html` locally.
2. Commit and push (`git add index.html && git commit -m "update" && git push`).
3. GitHub Pages rebuilds automatically in ~1 minute.

## Customize

Open `index.html` and replace everything marked `<!-- TODO: ... -->`:

- Your real intro in **About me**
- Your actual skills
- 3 real projects (name, description, tags, link)

Already done: contact email (`taimweromita505@gmail.com`) and the GitHub link.

## Optional upgrade: free "real" domain — `taimwe.is-a.dev`

The `.github.io` URL works, but `taimwe.is-a.dev` looks more professional. It's free —
you claim it by submitting a pull request to the `is-a-dev/register` GitHub repo.

### Step A — submit the registration PR

1. Go to **github.com/is-a-dev/register** and click **Fork**.
2. In your fork, open the `domains/` folder → **Add file** → **Upload files**.
3. Upload the prepared file **`is-a-dev-registration/taimwe.json`** (in this project) to `domains/`.
   - Your email and GitHub username are **already filled in** — just review it once before submitting.
   - Schema (verified against the official docs): key is `records` (plural),
     `proxied: false` lets GitHub Pages issue its own HTTPS certificate.
4. Create a **Pull Request** back to `is-a-dev/register` with a short title like
   `feat(domain): add taimwe.is-a.dev`.
5. A bot + human maintainer review it; approval usually takes 1–3 days.
   Fix anything they ask about, and it merges. Don't ping maintainers to speed it up —
   that earns a "low priority" label.

### Step B — connect it to your GitHub Pages site

1. In your `taimweromita505-source.github.io` repo, add a file named **`CNAME`** (no extension)
   containing exactly one line: `taimwe.is-a.dev`
2. Repo → **Settings** → **Pages** → **Custom domain**: type `taimwe.is-a.dev` → **Save**
3. Tick **Enforce HTTPS** (their FAQ explicitly says this resolves SSL issues).
   Visit **https://taimwe.is-a.dev** 🎉

> Note: your old URL `taimwe.github.io` keeps working too — both serve the same site.

## Other free upgrades

| Want | How |
|---|---|
| Custom email | `you@taimwe.com` forwarding via a free Mailgun/Cloudflare account |
| Preview on phone | It's already responsive — no work needed |
