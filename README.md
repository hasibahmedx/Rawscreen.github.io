# Rawscreen website

- `index.html` is the website. You do not need to edit it.
- `content/work.json` is the list of recent work. Edit this file to add, remove or reorder projects.
- `images/work/` is the folder for project thumbnail images.
- `admin.html` is a form that builds the work.json text for you. Open it at `https://YOUR-USERNAME.github.io/YOUR-REPO/admin.html`.

Each project in work.json:

    { "title": "Harbour Coffee", "client": "Brand film", "platform": "youtube",
      "url": "https://www.youtube.com/watch?v=VIDEO_ID", "dur": "1:48", "thumb": "" }

- `platform` is `youtube`, `facebook` or `video`.
- YouTube links get their thumbnail automatically. For other links set `thumb` to `images/work/name.jpg`.
- The first 5 projects show first. The rest sit behind "See more work".

