# Zola Resume

<p align="">
  <img src="https://img.shields.io/github/languages/code-size/semanticdata/zola-resume" />
  <img src="https://img.shields.io/github/repo-size/semanticdata/zola-resume" />
  <img src="https://img.shields.io/github/commit-activity/t/semanticdata/zola-resume" />
  <img src="https://img.shields.io/github/last-commit/semanticdata/zola-resume" />
  <img src="https://img.shields.io/website/https/zola-resume.svg" />
</p>

A simple resume for Zola.

Check out the [demo](https://semanticdata.github.io/zola-resume/).

## Running the Site Locally

Tips that will help you develop and preview the site locally.

### Requirements

Before using the theme, you need to install [Zola](https://www.getzola.org/documentation/getting-started/installation/) ≥ 0.18.0.

### Quick Start

```sh
# Clone the repo
git clone git@github.com:semanticdata/zola-resume.git

# Change directory into the cloned folder
cd zola-resume

# Serve the site locally
zola serve

# Open http://127.0.0.1:1111/ in the browser
```

For more detailed instructions, visit the [Documentation](https://www.getzola.org/documentation/themes/installing-and-using-themes/) page about installing and using themes.

### Useful Commands

A short list of commands that will help you develop your own version of the theme.

| Command                 | Description            |
| ----------------------- | ---------------------- |
| `zola init <repo-name>` | Initiate new Zola site |
| `zola build`            | Build only             |
| `zola serve`            | Build and Serve        |

## Customization

You can changed the configuration, templates and content yourself. Refer to the `config.toml`, and templates files for ideas. In most cases you only need to modify the contents of `config.toml` to customize the appearance of your blog. Make sure to visit tyhe [Zola Documentation](https://www.getzola.org/documentation/getting-started/overview/).

### Custom CSS Styles

Adding custom CSS is as easy as adding your styles to `sass/_custom.scss`. This is made possible because SCSS files are backwards compatible with CSS. This means you can type normal CSS code into a SCSS file and it will be valid.

## License

Source code in this repository is available under the [MIT License](LICENSE).
