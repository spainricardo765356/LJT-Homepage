# LJT-Homepage

Personal academic homepage of **Junteng Liu**, a first-year Ph.D. candidate in Computer Science at the HKUST NLP Group, supervised by Professor Junxian He. His research focuses on natural language processing and machine learning, with interests in LLM reasoning and reinforcement learning, hallucination in vision-language models (VLM), and LLM truthfulness and interpretability.

The site is a fork of the [Academic Pages template](https://github.com/academicpages/academicpages.github.io) (Jekyll / GitHub Pages).

## Pages

| Page | URL | Source file |
| --- | --- | --- |
| About (home): personal details, academic background, research interests, research experience, skills, publications, honors and contact | `/` | `_pages/about.md` |
| Publications | `/publications/` | `_pages/publications.html` + `_publications/` |
| CV: education, research experience, skills, publications, honors and contact | `/cv/` | `_pages/cv.md` |

## Configuration

* `_config.yml` &mdash; site title, URL/baseurl, author sidebar (name, bio, employer, email, GitHub, Google Scholar, X) and publication categories.
* `_data/navigation.yml` &mdash; header menu (About, Publications, CV).
* `_data/authors.yml` &mdash; author metadata.
* `_publications/` &mdash; one Markdown file per publication.

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
