# LinkedIn Tone & Style Questionnaire

Pretzl-branded questionnaire for capturing client voice preferences for LinkedIn content.

## Deployment

### Via Netlify (Recommended)

1. Push this folder to a GitHub repository
2. Log into [Netlify](https://netlify.com)
3. Click "Add new site" → "Import an existing project"
4. Connect to your GitHub repo
5. Deploy settings are auto-configured via `netlify.toml`
6. Click "Deploy"

### Accessing Form Submissions

Form responses are stored in Netlify:

1. Go to your site dashboard in Netlify
2. Click **Forms** in the sidebar
3. Select **linkedin-tone** to view all submissions
4. Export as CSV if needed

### Optional: Email Notifications

To get notified when someone submits:

1. In Netlify, go to **Site settings** → **Forms** → **Form notifications**
2. Add an **Email notification**
3. Select the `linkedin-tone` form
4. Enter your email address

## Local Development

Just open `index.html` in a browser. Form submission won't work locally (requires Netlify), but you can preview the UI.

## Customization

- Colors: Edit CSS variables in `:root` (accent colors are `--accent-blue`, `--accent-red`, `--accent-yellow`)
- Questions: Edit the `<section class="panel">` elements
- Logo text: Change the `.logo` div content

## Files

- `index.html` — Main questionnaire
- `success.html` — Post-submission thank you page
- `netlify.toml` — Netlify build/deploy config
- `orb_offwhite.svg` — Pretzl orb logo
- `wordmark_offwhite.svg` — Pretzl wordmark logo
