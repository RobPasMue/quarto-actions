# Usage

```yaml
- name: Render Quarto Project
  uses: quarto-dev/quarto-actions/render@v2
  with:
    to: html # If set, it will be equivalent to `quarto render --to html`
    path: source-folder # By default, the current working dir is used i.e `quarto render .`
```

`path:` can be a path to a subdirectory containing the quarto project to be rendered or a path to a single .qmd file
