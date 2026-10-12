# Rocket_League-Website

A simple, responsive web page about **Rocket League**, my favourite hobby. It was built as a two-part exercise: first structuring the page with semantic HTML5, then styling it with CSS.

## About the page

The page covers:

- **About the game**: when it was released, how matches work and where it came from
- **Mechanics I love**: boost, aerials and flip resets
- **The arena**: a top-down SVG diagram of the pitch, plus a quick facts sidebar
- **Why I play**: what I enjoy most about the game

## Project structure

```
rocket-league/
├── index.html   # Page content and semantic structure
├── styles.css   # All styling and layout
└── README.md
```

## Semantic HTML used

| Element | Where it's used |
|---|---|
| `<header>` | Page title and tagline |
| `<nav>` | Links that jump to each section |
| `<main>` | The page's main content |
| `<section>` | About, Mechanics, Arena and Why I play |
| `<article>` | The three mechanics cards |
| `<aside>` | Quick facts sidebar |
| `<figure>` / `<figcaption>` | The pitch diagram and its caption |
| `<footer>` | Link to the official Rocket League website |

## CSS features

- Custom font families (Verdana and Trebuchet MS)
- A heading colour and size hierarchy (`h1`, `h2`, `h3`)
- Light paragraph text on a dark background for good contrast
- Background colours on the page, header, nav, cards and footer
- Centred header and footer text
- Bold (`<b>`) and italic (`<em>`) highlights in the text
- Margin and padding to keep the layout uncluttered
- Styled links, with underlines removed in the nav and added on hover
- CSS Grid and Flexbox for layout, with a responsive breakpoint for the arena section

## Running it locally

No build tools or dependencies are needed.

1. Download or clone this repository.
2. Open `index.html` in any web browser.

Keep `index.html` and `styles.css` in the same folder so the styles load.

## Viewing it on GitHub Pages

1. Push the files to a GitHub repository.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, then select your main branch and the `/ (root)` folder.
4. Save. Your page will be live at `https://<your-username>.github.io/<repository-name>/`.

If the project sits inside a `rocket-league/` subfolder of a larger repository, the URL will end in `/rocket-league/`.

## Accessibility

- Proper heading order and landmark elements
- An `aria-label` on the navigation
- A text description (`aria-label`) on the SVG diagram
- Visible focus outlines on links

## Credits

Rocket League is a trademark of Psyonix. This is an unofficial fan page made for learning purposes and is not affiliated with Psyonix or Epic Games.
