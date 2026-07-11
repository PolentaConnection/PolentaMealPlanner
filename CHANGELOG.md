# Changelog



All notable changes to Polenta Meal Planner are documented in this file.



The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/).



## [Unreleased]



## [1.0] - 2026-07-12



### Added

- Initial public release

- Desktop meal planning application with food database and daily menus

- Macro and nutrient totals per meal and per day

- Drag-and-drop meal editor with breakfast, lunch, dinner and snacks

- Multi-language UI (English, Italian, French, Spanish, German, Arabic, Chinese)

- Nations filter for foods and menu validation hints

- Export daily menus to text

- Classic Windows-inspired themes plus Bootstrap 5 look

- Deployment config file `PolentaMealPlanner.deploy.json` with `portable` or `installed` mode

- Installed builds store user data under `%LOCALAPPDATA%\Polenta Connection\PolentaMealPlanner`

- Portable zip includes a portable deployment config; Inno Setup installs the installed config



### Changed

- Foods, menus, app state, and optional `Nations.json` resolve through `data_dir()` instead of always using the exe folder



