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
yarn start FOLDER_LOCATION
```

- `FOLDER_LOCATION`: The absolute path of the directory with your demo media.

### EXAMPLE

```sh
yarn start 'G:\Disc-Rips\One Punch Man- Season 2 Disc 1'
```
