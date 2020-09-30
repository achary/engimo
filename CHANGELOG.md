# Changelog


- ...

## [2.9.0] - 2020-07-18

### Added

- Indonesian translation
- Ukrainian translation
- Arabic translation
- Support `.Site.Language.LanguageDirection`

### Fixed

- MathJax integration
- Issues #256, #260, #264, #285

## [2.8.0] - 2019-09-08

### Added

- RTL support
- Staticman comments reCAPTCHA support
- Shortcode: `katex`
- Mermaid.js support

### Changed

- Minimum Hugo version requirement: `v0.55`

### Fixed

- Deprecation warnings
- Problem related to Hugo canonifyurls for demo site
- Some styles for colors and layouts
- Issues #218, #219, #222, #223, #228, #229, #230, #234, #237

## [2.7.0] - 2019-05-01

### Added

- Spanish translation improvements
- KaTeX support
- Lastmod in entry footer (config option: `params.settings.showLastmod`)
- German translation improvements
- French translation improvements
- Isso comment system support
- Option to hide entry meta: `hideEntryMeta`
- Header widget area: `header`
- Breadcrumbs widget: `breadcrumbs`
- Vietnamese translation
- Task list styling

### Changed

- Removed forced capitalization (function: `title`)
- Tweak Staticman comment system

### Fixed

- Broken taxonomy term links (Issue #160)
- Search index generation scripts
- Checkbox & Radio input styling

## [2.6.0] - 2018-07-24

### Added

- French translation improvements
- "extra" placeholder partial for `head` and `footer`
- Italian translation

### Changed

- Minimum Hugo version requirement: `v0.45`

### Fixed

- "Search: Fuse.js" documentation

## [2.5.0] - 2018-07-06

### Added

- Add `.alternate` text param for cover image
- YouTube icon in Social Menu
- German translation improvements
- Utterances comment system support
- Search Support: Algolia, Fuse.js, Lunr.js

### Changed

- Refactor Widget Area

### Fixed

- Issue #150

## [2.4.0] - 2018-05-30

### Added

- Chinese translation improvements
- Support for any widgets in Footer widget area
- Nested items support in Sidebar Menu

### Fixed

- Staticman comments `comments_depth` count

## [2.3.0] - 2018-05-09

### Added

- Staticman comment system support
- Catalan translation
- Spanish translation improvements
- Sidebar Menu within `sidebar_menu` widget
- Option to hide Main Menu: `hideMainMenu`
- Footer widget area (supports only `social_menu` widget)

### Changed

- Improved & Simplified Sidebar
- Stylesheet tweaks

### Fixed

- homeURL for multilingual site in About widget
- Recent Posts widget's title config priority

### Removed

- `hideSocialMenu` config option

## [2.2.0] - 2018-03-28

### Added

- Spanish translation
- Customizable `accentColor`
- Series taxonomy support

### Changed

- Forms & Buttons stylesheets
- Minor changes to Main Menu
- Refactor Social Menu template
- Refactor Homepage & Sidebar templates

### Fixed

- Public path for script chunks
- Sidebar stylesheets bug

## [2.1.0] - 2018-02-27

### Added

- `archive` layout for `page` type
- Social Menu widget ( `social_menu` )
- Colorful emoji support
- MathJax support

### Changed

- Change, Fix & Refactor stylesheets
- Codes stylesheet enhancement
- Move Widget areas' configuration to `config.toml` ( `.Site.Params.widgets` )
- Refactor Widgets' configuration structure
- Update linkedin, google_scholar, gitlab SVG icons
- Social Menu converted to widget
- Update project dependencies ( `package.json` )
- Split scripts into multiple chunks

### Fixed

- relURL for logo in `about` widget
- Shuffle option for `taxonomy_cloud` widget

## [2.0.0] - 2018-02-08

### Added

- Sidebar support
- Widgets support ( About, Recent Posts, Taxonomy Cloud )

### Changed

- Forked from [Minimo project][minimo-github] and branded.


[unreleased]: https://github.com/MunifTanjim/minimo/compare/v2.9.0...HEAD
[2.9.0]: https://github.com/MunifTanjim/minimo/compare/v2.8.0...v2.9.0
[2.8.0]: https://github.com/MunifTanjim/minimo/compare/v2.7.0...v2.8.0
[2.7.0]: https://github.com/MunifTanjim/minimo/compare/2.6.0...v2.7.0
[2.6.0]: https://github.com/MunifTanjim/minimo/compare/2.5.0...2.6.0
[2.5.0]: https://github.com/MunifTanjim/minimo/compare/2.4.0...2.5.0
[2.4.0]: https://github.com/MunifTanjim/minimo/compare/v2.3.0...2.4.0
[2.3.0]: https://github.com/MunifTanjim/minimo/compare/v2.2.0...v2.3.0
[2.2.0]: https://github.com/MunifTanjim/minimo/compare/v2.1.0...v2.2.0
[2.1.0]: https://github.com/MunifTanjim/minimo/compare/v2.0.0...v2.1.0
[2.0.0]: https://github.com/MunifTanjim/minimo/compare/v1.6.0...v2.0.0
[1.6.0]: https://github.com/MunifTanjim/minimo/compare/v1.5.0...v1.6.0
[1.5.0]: https://github.com/MunifTanjim/minimo/compare/v1.4.0...v1.5.0
[1.4.0]: https://github.com/MunifTanjim/minimo/compare/v1.3.0...v1.4.0
[1.3.0]: https://github.com/MunifTanjim/minimo/compare/v1.2.1...v1.3.0
[1.2.1]: https://github.com/MunifTanjim/minimo/compare/v1.2.0...v1.2.1
[1.2.0]: https://github.com/MunifTanjim/minimo/compare/v1.1.0...v1.2.0
[1.1.0]: https://github.com/MunifTanjim/minimo/compare/v1.0.0...v1.1.0
