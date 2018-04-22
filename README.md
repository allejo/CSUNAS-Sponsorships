# CSUN AS Sponsorships Page

The website for [CSUN Associated Students Sponsorship information](https://csunas.org/sponsorship/) built with [stakx](https://stakx.io/).

## Building

This is a standard stakx website and is compiled normally. This website is built with [0.1.x of stakx](https://github.com/stakx-io/stakx/releases), however it should be forwards compatible with the 0.2.x development version of stakx.

1. Download the latest stable release of stakx
2. Build the site   
   ```
   stakx build
   ```

## Structure

- `_layouts` - The base Twig templates that other pages or templates should extend
- `_macros` - Helper Twig macros for to avoid repetition
- `_sections` - Generic partial Twig templates used on the site
- `_pages` - Contains all of the stakx PageViews

## License

All rights reserved.
