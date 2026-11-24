# Aurora Strategy Global website

Source for Aurora Strategy Global’s website, built with Astro and Tailwind CSS.

## Run locally

1. Install Node.js (current LTS recommended).
2. Run `npm install` in this folder.
3. Run `npm run dev` and open the local address Astro prints.
4. Run `npm run check` and `npm run build` to validate changes.

Pages are in `src/pages/`, shared components in `src/components/`, styles in `src/styles/`, and static images and public files in `public/`.

The repository excludes local environment files and secrets. The hosted contact form relies on a platform-provided `PENNY_API_KEY`; local submissions need an equivalent authorized configuration. Publishing and connecting the domain are managed separately by the website hosting workspace.