# Contributing

## Table of contents

* [Tools](#tools)
* [Add new concert dates](#add-new-concert-dates)
* [Update `CODEOWNERS`](#update-code-owners)
* [Update vcards](#update-vcards)
* [Update member pages](#update-member-pages)
* [Update members](#update-members)
* [Update colors](#update-colors)

## Tools

| Tool                | Reference                                      |
|---------------------|------------------------------------------------|
| Zensical            | <https://zensical.org/>                        |
| GitHub actions      | <https://github.com/features/actions/>         |
| GitHub pages        | <https://pages.github.com/>                    |

## Add new concert dates

* add info to [`./docs/src/markdown/tour.md`](https://github.com/SalonBaden/salonbaden.github.io/blob/main/docs/src/markdown/tour.md)
* add SEO metadata for `ld-json` to [`./docs/overrides/main.html`](https://github.com/SalonBaden/salonbaden.github.io/blob/main/docs/overrides/main.html)

## Update code owners

* update [`./.github/CODEOWNERS`](https://github.com/SalonBaden/salonbaden.github.io/blob/main/.github/CODEOWNERS)

## Update images

Images are located at: [`./docs/src/markdown/assets/images/`](https://github.com/SalonBaden/salonbaden.github.io/tree/main/docs/src/markdown/assets/images)

## Update vcards

> <https://en.wikipedia.org/wiki/VCard>

Visit cards are located at: [`./docs/src/markdown/assets/vcards/`](https://github.com/SalonBaden/salonbaden.github.io/tree/main/docs/src/markdown/assets/vcards)

## Update member pages

Member pages are located in the subfolder: [`./docs/src/markdown/members/`](https://github.com/SalonBaden/salonbaden.github.io/tree/main/docs/src/markdown/members)

## Update members

When adding or removing orchestra members:

* member pages are located in the subfolder: [`./docs/src/markdown/members/`](https://github.com/SalonBaden/salonbaden.github.io/tree/main/docs/src/markdown/members)
* general navigation needs to be updated in the `nav` section of [`./zensical.toml`](https://github.com/SalonBaden/salonbaden.github.io/blob/main/zensical.toml)
* (optionally) compare [updating images](#update-images)
* (optionally) compare [updating vcards](#update-vcards)

## Update colors

> Documentation: <https://zensical.org/docs/setup/colors/>

Theme colors can be adjusted by updating the `project.theme` section of [`./zensical.toml`](https://github.com/SalonBaden/salonbaden.github.io/blob/main/zensical.toml).
