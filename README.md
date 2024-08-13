# Nick Lyon's SCSS Stylesheet Extension For Quarto

This extension includes a custom light and dark mode SCSS stylesheet for Quarto projects (e.g., websites, books, etc.). Rules are included both for easy text styling and for small quality of life improvements (e.g., increased contrast between page background color and tabset panel background, etc.). I'll update this as needed for my own projects so check back in for updates periodically!

## Installing

```bash
quarto add njlyon0/lyon_scss-theme
```

This will install the extension under the `_extensions` subdirectory.
If you're using version control, **you will want to check in this directory**.

## Using

Once you've installed the extension, replace your 'theme' specification in the `_quarto.yml` with `_extensions/njlyon0/lyon_theme/lyon_<type>.scss` (where `<type>` is either `light` or `dark`).
