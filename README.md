# AyoEngine Legal Microsite

This repository hosts universal legal documents used across AyoEngine projects under the domain **ayoengine.online**.

## Structure

```
docs/
  index.html
  privacy.html
  terms.html
  cookies.html
CNAME
README.md
```

## Deployment

### GitHub Pages
1. Push the repository to GitHub.
2. In repository **Settings → Pages**, choose **Deploy from a branch**.
3. Select the `main` branch and set the folder to `/docs`.
4. Ensure the `CNAME` file contains `ayoengine.online` to use the custom domain.

### Cloudflare Pages
1. Create a new project and connect this repository.
2. Set **Build command** to `None` and **Build output directory** to `docs`.
3. Deploy the site and add the custom domain `ayoengine.online` in the Pages dashboard.

## Contact

For questions or updates, reach out at [contact@ayoengine.online](mailto:contact@ayoengine.online).
