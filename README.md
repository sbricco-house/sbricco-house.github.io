## Prerequisites

Install Hugo, extended version. Most Linux distributions have it ready in default repositories and can be installed via package manager.

## How to contribute

1. Fork this repository, and open a pull request when you are done. **DO NOT** push branches here directly, even though you may well have the power to do so.
2. Clone your fork. Use the option to checkout submodules as well: `git clone --recurse-submodules <URI> <TARGET>`
3. Edit the website as you please, with the following caveats:
  * **DO NOT** commit anything inside `public`. The folder is ignored and nothing should be stored there
  * **DO NOT** change anything inside `themes`. The theme maintenance is "outsourced"
  * Navigation and menus are configured inside `config.toml`
  * The homepage is customized inside `data/homepage.yml`
  * All the contents are (you don't say) inside `content`
  * **DO NOT** add HTML files
  * Try to avoid HTML snippets inside markdown files. Most of what you want to embed is dealt with Hugo's shortcodes. If there is no shortcode, we can develop one.
4. Test the website locally, by running `hugo server`. It will serve the website for you (look at the output for the URL)
5. When satisfied, push on your fork
6. Open a Pull Request from your fork to this repository
