# Anime File Naming

Rename anime media files ripped from discs.

## Installation

```sh
yarn install
yarn dlx @yarnpkg/sdks vscode
```

## Usage

> Many anime come on multiple disc, so it requires a bit of manual work to get this setup.

Make sure you only put episodes in this directory and that, when ordered alphabetically, they're in episode-order. Then the tool can take over the rest of the work.

```sh
yarn start FOLDER_LOCATION SEASON_NUMBER SEARCH_TERM
```

- `FOLDER_LOCATION`: The absolute path of the directory with your demo media.
- `SEASON_NUMBER` (optional & default `1`): If you do use Seasons, this should be set to the correct season number. With Absolute Series Scanner and HamaTV, they usually want `1` because they uses Collections rather than actual Seasons.
- `SEARCH_TERM` (optional): Optional helper text if the filename can't be matched. This is useful when the list of 10 anime doesn't include the one you're renaming.

### EXAMPLE

```sh
yarn start 'G:\Disc-Rips\One Punch Man- Season 2 Disc 1'
```
