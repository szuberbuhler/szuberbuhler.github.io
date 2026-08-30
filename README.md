# szuberbuhler.com

Personal site: cybersecurity writeups (HTB retired machines), Linux and networking notes.

**Live at [szuberbuhler.com](https://szuberbuhler.com)**

## Stack

- [Hugo](https://gohugo.io), static site generator
- [PaperModX](https://github.com/reorx/hugo-PaperModX) theme, pinned as a git submodule
- Deployed to GitHub Pages via GitHub Actions

## Local development

Requires Hugo (extended) >= 0.162.

```bash
git clone --recurse-submodules git@github.com:szuberbuhler/szuberbuhler.github.io.git
cd szuberbuhler.github.io
hugo server
```

Site is served at `http://localhost:1313`.

## Writing

Posts live in `content/writeups/` as Markdown. To publish, commit to `main`, the deploy workflow builds and publishes automatically.

## Contributing

This is a personal portfolio, I don't accept pull requests. If you spot an error, feel free to open an issue.

## License

Code: [MIT](LICENSE)
