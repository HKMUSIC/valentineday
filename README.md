# valentineday
# AnimeToons

)

---

## Deployment

### Deploy Frontend on Vercel

You can deploy this React frontend directly to Vercel using the button below:

[![Deploy to Vercel](https://vercel.com/button)](https://vercel.com/import/project?template=https://github.com/hkmusic/valentineday>)

**Important:** Replace `<YOUR-GITHUB-USERNAME>` and `<YOUR-REPO-NAME>` with your actual GitHub username and repo name.

#### Fixing Peer Dependency Conflicts

Since `react-hls-player` has a peer dependency on React 16, Vercel build may fail. To fix it:

1. Add a **Vercel-specific build script** in `package.json`:

```json
"scripts": {
