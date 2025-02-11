# Changelog

All notable changes to TailPress will be documented in this file.

## Unreleased changes

- Update screenshot.png.

## 1.0.0 - 2021-08-25

- Replace `tailpress.json` with `theme.json` as used by WordPress core.
- Move template files into `theme` subdirectory.
- Move tailwind plugin to a [separate repository](https://github.com/jeffreyvr/tailwindcss-tailpress).
- Update readme and adding section on using installer.

## 0.1.0 - 2021-06-17

- No longer depending on jQuery.
- Fixes text color classes for the Block Editor.
- Use safelist.txt to prevent WP classes from being purged.
- Readme changes.
- MIT License.

## 0.0.9 - 2021-04-05

- Updating to Tailwind CSS v2.1 which includes the JIT engine in core among other things.

## 0.0.8 - 2021-03-23

- Using TailwindCSS JIT for way faster compiling.
- Updated readme.
- Fix loading styling in block editor.
- Check if mix-manifest.json file exists to prevent warning message.

## 0.0.7 - 2021-02-15

- Adding the option to apply submenu_class to the wp_nav_menu args.
- Adding the option to apply classes on li_class and submenu_class on specific depths, like: li_class_0.

### 0.0.6 - 2021-02-08

- Fixes issue on Windows.

## 0.0.5 - 2020-12-24

- Set selectors on single line since this seems to cause issues (nested CSS) with production build (#241a612).

## 0.0.4 - 2020-12-23

- Add nested CSS support for PostCSS.
- Minor readme changes.

## 0.0.3 - 2020-12-22

- Update Laravel Mix from version 5^ to 6^.
- Removing Laravel Mix Tailwind, defining plugins within webpack.mix.js instead.
- Switching from Sass to PostCSS for faster compiling.
- Moved TailPress colors and font size settings to tailpress.json file.
- Use tailpress.json to populate editor-color-palette and editor-font-sizes theme support automatically.
- New screenshot.
- Update readme.
- Other minor fixes and improvements.

## 0.0.2 - 2020-11-24

- Adding basic support for the block editor Gutenberg by generating alignment, font size and color classes.
Contains four theme colors out of the box, being primary, secondary, dark and light. This is adjustable of course.
- Loading a editor-style.css.
- Removing double slashes on resulting manifest asset URLs.
- Modified template files to have a better starting point (including horizontal main navigation, footer always at the bottom for short pages).
- Added a basic 404 page template.

## 0.0.1 - 2020-11-19

- Init release.
