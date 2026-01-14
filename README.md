# RULE_KGR

Static HTML deployment on Vercel.

## Deploy on Vercel (web)
1. Go to https://vercel.com/new
2. Import this GitHub repository.
3. Framework preset: **Other**
4. Build command: *(leave empty)*
5. Output directory: *(leave empty)*
6. Deploy.

The root path `/` will serve `iklc_scoring_summary.html` via `vercel.json`.

## Deploy on Vercel (CLI)
```bash
npm i -g vercel
vercel
```
Accept defaults. No build step is required.
