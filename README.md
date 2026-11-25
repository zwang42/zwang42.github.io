# Personal website

A single-page portfolio with sections for a bio, experience, publications, projects, and interests. The site uses plain HTML and CSS and is ready for GitHub Pages.

## Customize

- In `index.html`, replace the name, page title, meta description, bio, and sample entries. Duplicate an experience row or work entry to add another item, or remove sections you do not use and their matching navigation links.
- Replace contact and resource labels with links as you add destinations. For example, change `<li>Email</li>` to `<li><a href="mailto:you@example.com">Email</a></li>` and remove any unused labels.
- To add a thumbnail, place the image in an `images/` folder and insert `<img class="work-thumbnail" src="images/project.jpg" alt="Describe what the image shows" loading="lazy">` before the text `div` inside a work entry. Use descriptive alternative text and keep image paths relative.
- Edit the custom properties at the top of `styles.css` to change the palette or fonts.

## Preview locally

From the repository root, run:

```sh
python -m http.server --bind 127.0.0.1 8000
```

Open [http://127.0.0.1:8000/](http://127.0.0.1:8000/) and refresh after edits.

## Publish on GitHub Pages

1. Push `main` to a public repository named `<username>.github.io` for a site at `https://<username>.github.io/`. If you use another repository name, the site URL will include that name as a path.
2. In the repository’s **Settings → Pages**, choose **Deploy from a branch** and select **main** and **/(root)**. Save the setting.
3. Open the live URL shown in Pages once the deployment succeeds. Future pushes to `main` update the site.

See the [GitHub Pages quickstart](https://docs.github.com/en/pages/quickstart) for more details.
