# Overview

This repository contains an overview about the TabletopManager project.

## TabletopManager

This project is aiming to provide a tool to manage tabletop games. It is intended to be used by players and game-masters alike. It is currently in a very early stage of development. The first version will be able to only manage a single character sheet, but the goal is to provide a tool to manage multiple characters, campaigns, and even whole universes.

### Project divisions

The project is divided into multiple parts:

- [ttm-types](https://github.com/TabletopManager/ttm-types/blob/main/README.md): This project contains all the types shared between the different parts of the project. It is written in rust and is not yet published on crates.io.
- [ttm-frontend](https://github.com/TabletopManager/ttm-frontend/blob/main/README.md): This project contains the frontend of the project. It is written in rust using the yew library. It is not yet published on crates.io.
- [ttm-backend](https://github.com/TabletopManager/ttm-backend/blob/main/README.md): This project contains the backend of the project. It is written in rust using the actix-web library. It is not yet published on crates.io.

### Future plans for content

The following is a list of planned content for the project:

- Character manager
- Resource fetcher (spells, items, etc.)
- Campaign manager
- Game master tools (dice roller, etc.)
- Generators (random names, terrains, etc.)
- Consent tools (consent sheets, etc.)

## Maintainers

- [Nyaleph](mailto:contact@nyaleph.com)

## License

This entire project is licensed under the [GNU General Public License v3.0](LICENSE).
