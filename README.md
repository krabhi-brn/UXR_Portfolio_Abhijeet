# UXR Portfolio — Kumar Abhijeet

## Structure

```
UXR Portfolio/
├── website/                  # The portfolio site
│   ├── index.html            # Home
│   ├── about.html            # About + experience
│   ├── paypal.html           # Case Study 01 — PayPal Everywhere
│   ├── roadrunner.html       # Case Study 02 — RoadRunner Scene Builder
│   ├── adt.html              # Case Study 03 — ADT Reference Apps
│   ├── styles.css            # Shared styles
│   └── images/               # All site imagery
├── documents/                # Résumé + portfolio PDF
│   ├── Kumar_Abhijeet_Resume.docx
│   ├── Kumar_Abhijeet_UXR_Portfolio.pdf
│   └── backups/              # Dated résumé backups
└── .venv/                    # Unused Python env (only pip) — safe to delete
```

## Preview locally

Open `website/index.html` in a browser, or serve the folder:

```bash
cd website
python3 -m http.server 8000
```

Then visit http://localhost:8000.

All links and asset paths inside `website/` are relative, so the site works from any location.
