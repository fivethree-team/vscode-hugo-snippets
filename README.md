# Hugo Snippets

[![Visual Studio Marketplace](https://vsmarketplacebadge.apphb.com/version/fivethree.vscode-hugo-snippets.svg?style=flat-square)](https://marketplace.visualstudio.com/items?itemName=fivethree.vscode-hugo-snippets)
[![Visual Studio Marketplace](https://vsmarketplacebadge.apphb.com/installs/fivethree.vscode-hugo-snippets.svg?style=flat-square)](https://marketplace.visualstudio.com/items?itemName=fivethree.vscode-hugo-snippets)

Visual Studio Code Extension that adds Hugo snippets to your favorite IDE.

All code snippets are based on and follow the official hugo documentation.

## Using Snippets in VS Code

Type part of a snippet, press enter, and the snippet unfolds.

## Trigger Markdown

To trigger the snippets in Markdown you can use `^Space` [Snippets for Markdown](https://code.visualstudio.com/docs/languages/markdown#_snippets-for-markdown).

### Snippet Prefix

| Prefix | Description   |
| ------ | ------------- |
| `h-`   | Hugo Snippets |

<!-- Auto Generated Below -->

# Table of Content

- [Markdown](#markdown)
- [Function](#function)
- [Templates](#templates)
- [Variables](#variables)

## Markdown

| Prefix            | Description                 |
| ----------------- | --------------------------- |
| h-figure          | Figure Shortcode            |
| h-gist            | Gist Shortcode              |
| h-highlight       | Highlight Shortcode         |
| h-instagram       | Instagram Shortcode         |
| h-shortcode       | Shortcode Template          |
| h-shortcode-param | Shortcode Template w/ param |
| h-ref             | Ref Shortcode               |
| h-tweet           | Tweet Shortcode             |
| h-vimeo           | Vimeo Shortcode             |
| h-youtube         | Youtube Shortcode           |

## Function

| Prefix      | Description                                                                                          |
| ----------- | ---------------------------------------------------------------------------------------------------- |
| h-absURL    | `absURL` creates an absolute URL based on the configured baseURL                                     |
| h-add       | `add`ing numbers                                                                                     |
| h-anchorize | `anchorize` sanitizes a string the same way as Blackfriday does for markdown headers                 |
| h-lt        | `lt` comparing numbers                                                                               |
| h-relURL    | `relURL` prepends the relative URL according to a page’s position in the project directory structure |
| h-title     | `title` Converts all characters in the provided string to title case                                 |

## Templates

| Prefix                           | Description                                                                                                 |
| -------------------------------- | ----------------------------------------------------------------------------------------------------------- |
| h-block                          | `block` allows you to define the outer shell of your pages’                                                 |
| h-block-default                  | `block` may include default content                                                                         |
| h-define                         | `define` page variable                                                                                      |
| h-if                             | `if` conditional                                                                                            |
| h-if-else                        | `if-else` conditional                                                                                       |
| h-partial                        | Partial Template                                                                                            |
| h-partial-path                   | Partial Template w/ path                                                                                    |
| h-range-pages                    | `range`s through pages w/ default order                                                                     |
| h-range-pages-by-weight          | `range`s through pages by weight, content with lower weight will come first                                 |
| h-range-pages-by-date            | `range`s through pages by date, orders content according to the 'date' field in front matter                |
| h-range-pages-by-publish-date    | `range`s through pages by publish date, orders content according to the 'publishdate' field in front matter |
| h-range-pages-by-expiration-date | `range`s through pages by publish date, orders content according to the 'expirydate' field in front matter  |
| h-range-pages-by-lastmod-date    | `range`s through pages by lastmod date, orders content according to the 'lastmod' field in front matter     |
| h-range-pages-by-length          | `range`s through pages by lastmod date, the shortest content will be listed first                           |
| h-range-pages-by-title           | `range`s through pages by lastmod date, orders according to the 'title' field set in front matter           |
| h-range-pages-reverse            | `range`s through pages in reversed order, reversing order can be applied to any range method                |
| h-with                           | `with` skips the block if the variable is absent, or if it evaluates to “false”                             |
| h-with-else                      | `with-else`                                                                                                 |

## Variables

| Prefix              | Description                                              |
| ------------------- | -------------------------------------------------------- |
| h-description       | Description page variable                                |
| h-lastmod           | Date the content was last modified                       |
| h-params            | Params variable                                          |
| h-publish-date      | Date on which the content was or will be published       |
| h-reading-time      | Estimated time, in minutes, it takes to read the content |
| h-summary           | Summary page variable                                    |
| h-table-of-contents | TableOfContents page variable                            |
| h-title             | Title page variable                                      |
| h-word-count        | Number of words in the content                           |

**[⬆ back to top](#table-of-content)**
