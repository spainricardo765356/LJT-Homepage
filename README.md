# LJT-Homepage

Personal academic homepage of **Junteng Liu**, a first-year Ph.D. candidate in Computer Science at the HKUST NLP Group, supervised by Professor Junxian He. His research focuses on natural language processing and machine learning, with interests in LLM reasoning and reinforcement learning, hallucination in vision-language models (VLM), and LLM truthfulness and interpretability.

The site is a fork of the [Academic Pages template](https://github.com/academicpages/academicpages.github.io) (Jekyll / GitHub Pages).

## Pages

| Page | URL | Source file |
| --- | --- | --- |
| About (home): personal details, academic background, research interests, research experience, skills, publications, honors and contact | `/` | `_pages/about.md` |
| Publications | `/publications/` | `_pages/publications.html` + `_publications/` |
| CV: contact, education, research experience, skills, publications, honors and awards | `/cv/` | `_pages/cv.md` |

Each publication also has its own page under `/publication/`, generated from the Markdown files in `_publications/`.

## Configuration

* `_config.yml` &mdash; site title, URL/baseurl, author sidebar (name, bio, employer, email, GitHub, Google Scholar, X) and publication categories (Preprints, Conference Papers).
* `_data/navigation.yml` &mdash; header menu (About, Publications, CV).
* `_data/authors.yml` &mdash; author metadata.
* `_publications/` &mdash; one Markdown file per publication.

Template developer docs and tooling (`AGENTS.md`, `README.md`, `markdown_generator/`, `scripts/`, `talkmap*`) are excluded from the site build in `_config.yml`, so only the pages above are published.

## Publishing

The `.github/workflows/jekyll.yml` workflow builds the site and deploys it to GitHub Pages on every push to `master` (it can also be started manually from the Actions tab).

One-time repository setting required: open **Settings &rarr; Pages** and set **Build and deployment &rarr; Source** to **GitHub Actions**. Until Pages is enabled, the build job succeeds but the deploy job fails with `Creating Pages deployment failed ... Ensure GitHub Pages has been enabled`. After changing the setting, re-run the workflow (or push a commit) to publish.

The published site will be available at <https://spainricardo765356.github.io/LJT-Homepage/>.

## Local preview

```bash
bundle install
bundle exec jekyll serve -l -H localhost
```

## Contact

* Email: jliugi@connect.ust.hk
* GitHub: [Vicent0205](https://github.com/Vicent0205)
* Google Scholar: [Junteng Liu](https://scholar.google.com/citations?hl=en&user=tbK9jl4AAAAJ&view_op=list_works&sortby=pubdate)
* X (Twitter): [@junteng88716710](https://twitter.com/junteng88716710)

Template license: see [LICENSE](LICENSE).
