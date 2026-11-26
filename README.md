# Christine McManus Multimedia Portfolio

Nine static HTML pages, with local images and shared styling. Open `index.html` to preview the site. No build step or package installation is required.

## Publish with GitHub Pages

1. Extract the ZIP to a folder on your computer.
2. Open a GitHub repository and choose **Add file → Upload files**. Upload the extracted HTML files and the entire `assets` folder. Keep `index.html` at the top level. If you use Git, commit the full extracted contents, including `.nojekyll`.
3. Commit the files to `main`. In **Settings → Pages**, choose **Deploy from a branch**, select **main** and **/(root)**, then **Save**.
4. When the deployment finishes, open **Visit site** in the Pages settings. The relative links work under a repository name such as `https://USERNAME.github.io/portfolio/`.

[GitHub Pages publishing documentation](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)

## Update the site

Edit each page's HTML to update its content. Shared layout rules live in `assets/site.css`. Keep the same paths when moving files into GitHub. The Contact page includes the mailing address and professional references from the saved site.

| Feature | How it works |
| --- | --- |
| Résumé | The ZIP contained the PDF viewer and its original external document URL. To host the document yourself, save it as `assets/resume.pdf` and replace the PDF URL in all links and the object in `resume.html`. |
| Contact form | **Open email draft** opens the visitor’s email app with the fields filled in. The visitor sends the message there. The displayed email address is also a direct link. |
| Video | Three YouTube players use the original video IDs and include direct watch links. |
| Education and work samples | The teaching license page remains on Wix. The linked Weebly sites, transcripts, and production credits retain their original external destinations. |
| Software lists | Program names appear throughout. The lists include the corresponding icon whenever it was present in the export. |
