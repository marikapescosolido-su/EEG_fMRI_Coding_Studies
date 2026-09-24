# Quarto research paper template

Edit `index.qmd` to write the paper and add coding instructions. Site-wide design and behavior live in `_quarto.yml` and `styles.css`.

## Preview locally

Install [Quarto](https://quarto.org/docs/get-started/), then run:

```bash
quarto preview
```

## Publish with GitHub Pages

1. Put these files at the root of the GitHub repository.
2. Push the repository to the `main` branch.
3. In **Settings → Pages**, set **Source** to **GitHub Actions**.
4. Open the **Actions** tab to follow the `Publish Quarto site` workflow.

The workflow renders the document without executing its code. To run code during publication, install the required language and packages in the workflow and set `execute.enabled` to `true` in `_quarto.yml`.
