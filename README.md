> [!WARNING]
> **This repository is deprecated and no longer maintained.**

# latex-resume

A LaTeX document class (`resume.cls`) for typesetting a CV or résumé. Must be compiled with XeLaTeX and requires the [Fontin](https://www.exljbris.com/fontin.html) font.

## Files

- `resume.cls` — the document class
- `sample.tex` — example résumé using the class
- `sample.pdf` — compiled output of the sample

## Usage

1. Place `resume.cls` in the same directory as your `.tex` file.
2. Set your document class to `resume`:
   ```latex
   \documentclass[letterpaper,10pt]{resume}
   ```
3. Compile with XeLaTeX:
   ```
   xelatex your-resume.tex
   ```

See `sample.tex` for a full working example.

## License

Copyright (c) 2011 Joel Goguen. Licensed under [Creative Commons Attribution-ShareAlike 3.0 Unported](http://creativecommons.org/licenses/by-sa/3.0/).
