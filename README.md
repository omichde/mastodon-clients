# Comparison chart of (iOS) Mastodon clients

This is a chart driven by obersvations of using each client within the last weeks for some hours. My reading habit is mostly driving the points listed here, as such I'm mostly reading for around 30mins in the morning and evening through a single accounnt [@omich@mastodon.social](https://mastodon.social/@omich) only.

Each client fullfills the basic features like a timeline view of each account, a thread list view seeing a selected post in context, personal post/direct messages views and some kind of account/setup views.

# Comparison chart

## General

|                      | Ice Cubes                                         | Ivory                       | Metatext                                  | Mammoth                                        | Mercury | Mast | Mastoot | tooot | Toot! | Tusker | Woolly |
| -------------------- | ------------------------------------------------- | --------------------------- | ----------------------------------------- | ---------------------------------------------- | ------- | ---- | ------- | ----- | ----- | ------ | ------ |
| Tab Bar              | Timeline, Notifications, Search, Messages, Profil | 5 customizable Icons        | TImeline, Search, Notifications, Messages | 5 customizable Icons + Profile                 |         |      |         |       |       |        |        |
| Navigation Bar       | Settings, Source, Post                            | Settings, Source, Search(-) | Settings, 3 Sources                       | Search(?), Source, Post                        |         |      |         |       |       |        |        |
| Button to write/post | :white_check_mark: top-right in navigation bar    | :warning: FAB               | :warning: FAB                             | :white_check_mark: top-right in navigation bar |         |      |         |       |       |        |        |

## Timeline

|                                    | Ice Cubes                               | Ivory                                 | Metatext                      | Mammoth                       | Mercury | Mast | Mastoot | tooot | Toot! | Tusker | Woolly |
| ---------------------------------- | --------------------------------------- | ------------------------------------- | ----------------------------- | ----------------------------- | ------- | ---- | ------- | ----- | ----- | ------ | ------ |
| Sync on Launch                     | :white_check_mark:                      | :zap: fast (pre-)fetching and refresh | :white_check_mark:            | :white_check_mark:            |         |      |         |       |       |        |        |
| Count of unread post               | top-right, tap jumps one page           | top-right, tap hides counter          | "new toots", tap jumps to now | top-right, tap jumps one page |         |      |         |       |       |        |        |
| Tap title jumps to now             | :white_check_mark:                      | :white_check_mark:                    | :white_check_mark:            | :white_check_mark:            |         |      |         |       |       |        |        |
| Re-tap on title jumps to last read | :x:                                     | :white_check_mark:                    | :x:                           | :x:                           |         |      |         |       |       |        |        |
| Scrolling behaviour                | :warning: haptics for passing each post | :zap: fast scrolling                  | :white_check_mark:            | :zap:                         |         |      |         |       |       |        |        |

## Entry

|                     | Ice Cubes                                             | Ivory                                                                                 | Metatext                                                                          | Mammoth                                                                           | Mercury | Mast | Mastoot | tooot | Toot! | Tusker | Woolly |
| ------------------- | ----------------------------------------------------- | ------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------- | --------------------------------------------------------------------------------- | ------- | ---- | ------- | ----- | ----- | ------ | ------ |
| vertical content    | (sender), author (+ actions) , text, preview, actions | (sender), author, text, preview, actions                                              | (sender), author, text, preview, actions                                          | - author, text, preview, actions, (sender)                                        |         |      |         |       |       |        |        |
| horizontal content  | :hearts: wide, images are fully visible               | :white_check_mark: author icon column, images with max height, preview is cut off     | :white_check_mark: author icon column, images with max height, preview is cut off | :white_check_mark: author icon column, images with max height, preview is cut off |         |      |         |       |       |        |        |
| Text length limited |                                                       | ~500 chars, then tap to see complete post in thread view                              |                                                                                   |                                                                                   |         |      |         |       |       |        |        |
| action icons        | :warning: outline icons                               | :-1: 4 actions, "gear" submenu, custom outline icons with cutouts (hard to recognize) | :warning: 4 outline icons, "..." submenu                                          | :warning: 3 outline icons, "..." submenu                                          |         |      |         |       |       |        |        |
| counter at icons    | :white_check_mark:                                    | :white_check_mark:                                                                    | :white_check_mark:                                                                | :white_check_mark:                                                                |         |      |         |       |       |        |        |

## External Content

|                      | Ice Cubes                                             | Ivory                                                              | Metatext                                    | Mammoth                                     | Mercury | Mast | Mastoot | tooot | Toot! | Tusker | Woolly |
| -------------------- | ----------------------------------------------------- | ------------------------------------------------------------------ | ------------------------------------------- | ------------------------------------------- | ------- | ---- | ------- | ----- | ----- | ------ | ------ |
| Images               | :warning: loading blocks scrolling, choppy dismissing | :white_check_mark: fast appearance, delayed closing                | :white_check_mark: fast preview and dismiss | :white_check_mark: fast preview and dismiss |         |      |         |       |       |        |        |
| Inline image preview | :white_check_mark: multiple side-by-side              | :white_check_mark: multiple side-by-side                           | :white_check_mark: multiple side-by-side    | :white_check_mark: inline horizontal paging |         |      |         |       |       |        |        |
| Fullscreen view      | :white_check_mark: with OCR text                      | :white_check_mark:                                                 | :white_check_mark: with ALT text            | :white_check_mark: ALT text on top          |         |      |         |       |       |        |        |
| Fullscreen zoom      | :white_check_mark: with OCR text                      | :white_check_mark:                                                 | :white_check_mark:                          | :white_check_mark:                          |         |      |         |       |       |        |        |
| Chromeless view      | :white_check_mark:                                    | :white_check_mark:                                                 | :white_check_mark:                          | :white_check_mark:                          |         |      |         |       |       |        |        |
|                      |                                                       |                                                                    |                                             |                                             |         |      |         |       |       |        |        |
| Video preview        | :white_check_mark:                                    | :white_check_mark: autoplay                                        | :white_check_mark:                          | :white_check_mark:                          |         |      |         |       |       |        |        |
| Images               |                                                       |                                                                    |                                             |                                             |         |      |         |       |       |        |        |
| Videos               |                                                       | :white_check_mark: automatic (configurable), fullscreen, landscape |                                             |                                             |         |      |         |       |       |        |        |
| Links                |                                                       |                                                                    |                                             |                                             |         |      |         |       |       |        |        |

## App-info

|   | Ice Cubes | Ivory | Metatext | Mammoth | Mercury | Mast | Mastoot | tooot | Toot! | Tusker | Woolly |
| - | --------- | ----- | -------- | ------- | ------- | ---- | ------- | ----- | ----- | ------ | ------ |
|   |           |       |          |         |         |      |         |       |       |        |        |

## Notes

:zap:
:hearts:
:white_check_mark:
:warning:
:-1:
:x:

(c) oliver@werk01.de
