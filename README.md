# Summit & Pine Outfitters – Company Home Page with Flexbox

A responsive company homepage for an imagined outdoor-gear company, "Summit & Pine Outfitters". The page is built with plain HTML and CSS and uses flexbox for all of its layout: a centered navbar, a product grid that collapses into a single column on narrow screens, and a flexible team section.

## Motivation

This is a learning project for practicing CSS flexbox. The assignment was to build a homepage for a real or imagined company, with a title and logo, a mission statement, a set of products and a team section, laid out with flexbox. It also had to use custom styles: a color scheme, Google Fonts and custom images.

## Features

- Title and SVG logo in a centered splash header
- Centered flexbox navbar with anchor links to each section
- Mission statement section
- Product section: a two-column flex grid on wide screens that becomes a single-column list below 600px
- Team section: flexible cards that grow, shrink and wrap with the page width
- Color scheme defined as CSS variables using named colors
- Headings in Montserrat and body text in Open Sans from Google Fonts
- Custom SVG images for the logo, products and team members

## Tech/framework used

**Built with:**

- HTML5
- CSS3 (flexbox, CSS custom properties, media queries)
- [Google Fonts](https://fonts.google.com/) (Montserrat, Open Sans)

## Code style

No linter or formatter is configured. Commit messages follow the [Conventional Commits](https://www.conventionalcommits.org/) specification (for example `feat: add centered navigation bar`).

## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd Company-Home-Page-with-Flexbox
   ```
2. There are no dependencies to install and no build step.
3. Open `index.html` in a browser, or serve the folder locally:
   ```bash
   python3 -m http.server 8000
   ```
   Then visit <http://localhost:8000>.

An internet connection is needed to load the Google Fonts.

## Usage examples

- Open `index.html` and use the navbar links (Home, Mission, Products, Team) to jump between sections.
- Resize the browser window to see the layout respond:
  - Products show as a two-column grid on wide screens and as a single column below 600px.
  - Team cards wrap onto new rows and shrink as the window narrows.