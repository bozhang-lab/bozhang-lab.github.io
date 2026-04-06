# Bo Zhang Lab Website

**bozhang-lab.github.io**

Lab website for the Bo Zhang Lab, Department of Biomedical Engineering, Southern University of Science and Technology (SUSTech).

## Structure

```
index.html        ← Home
people.html       ← PI + lab members
publications.html ← Papers + patents
research.html     ← Research directions
news.html         ← News + activities
joinus.html       ← Recruitment + contact
style.css         ← All styles
nav.js            ← Mobile nav toggle
```

## How to Update Content

All content is plain HTML. To update:

1. Open the relevant `.html` file
2. Edit the text directly
3. Commit and push — GitHub Pages rebuilds automatically

### Adding a new publication
Open `publications.html` and copy an existing `<div class="pub-item">` block.

### Adding a news item
Open `news.html` and copy an existing `<div class="news-full-item">` block.

### Adding a team member
Open `people.html` and copy an existing `<div class="member-card">` block.

## Custom Domain (future)

To bind a custom domain (e.g. via Cloudflare):
1. Go to repo Settings → Pages → Custom domain
2. Enter your domain
3. Add a CNAME record in Cloudflare pointing to `bozhang-lab.github.io`

No code changes required.
