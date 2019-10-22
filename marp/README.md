# Marp TFUG Theme

This is a slide theme for [Marpit](https://github.com/marp-team/marpit)

## Example

This is a simple example generated from [example.md](example.dm).

[![example](example.png)](example.html)

## Usage

### With VSCode

TFUG Theme is available at <https://ohtaman.github.io/marp/themes/tfug/theme.css>.
You can register the theme as follows.

1. Install the extension: [marp-vscode](https://github.com/marp-team/marp-vscode)
2. Add the url to the .vscode/settings.json

```json
{
  "markdown.marp.themes": [
    "https://ohtaman.github.io/marp/themes/tfug/theme.css"
  ]
}
```

### With Marp CLI

Prease clone this repository and run `marp-cli` as follows

```bash
$ git clone https://github.com/ohtaman/tfug-themes.git
$ npx @marp-team/marp-cli --html --allow-local-files --theme <path_to_the_theme.css> --pdf <path_to_the_md_file>
```
