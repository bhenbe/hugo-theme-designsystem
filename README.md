# hugo-theme-designsystem
A Hugo theme to create and manage your Design System

## Installation
1. You can add this theme in your themes folder. For more informations about theme installation, take a look [at the Hugo official documentation](https://gohugo.io/themes/installing-and-using-themes/). 

2. You also need to copy the `default.md` file in the theme archetype folder in the Hugo archetype folder.

## Page parameters
The parameters listed below comes with the archetype `default.md`.  

1. Status is used to show you the current status of a page: `draft` `wip` `ready` or `deleted`.

2. Description used as an excerpt in the list subpages nav.

3. Menu Sidenav, the main menu of this theme.

## Shortcodes
I'm currently working on shortcodes to enhance this theme.

### page-title
Page-title is defined in the archetype `default.md` to directly show the page title and the status label.

Example: `{{<page-title>}}news-card{{</page-title>}}`

### alert
You can add three kind of alerts on your pages: `info`, `do` and `dont`.

Example: `{{<alert class="info" label="info">}}ceci est juste une information{{</alert>}}`

### color-card
Color-card render a block to preview a color by an HEX code. The javascript plugin Color2Color also show RGB and HSL code on each card. 

Example: `{{< color-card name="gray-light" color="#ccc" >}}`

### code
Code render a preview of your code. The javascript plugin Highlight.js is the current tool to highlight your code.

Example: `{{<code language="html">}}your code{{</code>}}`

### google-font
Google-font allow you to render a preview of the fonts used in your design system.

Example: `{{<google-font font="IBM Plex Sans Condensed" sizes="400,700,300,400italic,700italic,300italic">}}`

## About this theme
This theme is currently in beta. Help and comments are really appreciated !
