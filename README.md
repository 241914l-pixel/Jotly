# Jotly
This is the Jotly project for the Computing Forum. Pls do not abuse my api key pretty pls

# Jotly on GitHub Pages

1. Open `index.html`, find the line `const API_KEY='';` near the top of the script, and paste your OpenRouter key between the quotes.
2. Create a GitHub repository (public, for free Pages hosting) and upload `index.html` to the root.
3. Go to **Settings > Pages**, set **Source** to "Deploy from a branch", branch `main`, folder `/ (root)`, and save.
4. After a minute the site is live at `https://YOURUSERNAME.github.io/REPONAME/`.

## Notes
- The key is visible to anyone who views the page source, so keep the quota strict (a spending limit, or no credit on the account) and use only free models.
- If the AI suddenly stops replying, check on openrouter.ai whether the key was disabled or has run out.
- When the shared usage runs out, the app asks the visitor for their own OpenRouter key and uses it directly. That key stays in their browser.
- Journal entries are stored in each visitor's browser (localStorage). The text of an entry is sent to OpenRouter when the AI replies.

