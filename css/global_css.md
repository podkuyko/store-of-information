# Global css

```css
  :root {
    --accent: turquoise;
    --accent-highlight: rgb(173, 255, 247);
    --accent-muted: teal;
    --app-background: black;
    --app-text: white;
    --app-text-dark: black;
    --error: #ff3915;
    --footer-height: 64px;
    --header-height: 48px;
    --input-background: #353535;
    --input-background-disabled: #121212;
    --row-width: 1024px;
  }

  * {
    box-sizing: border-box;
    font-family: -apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Oxygen,
      Ubuntu, Cantarell, Fira Sans, Droid Sans, Helvetica Neue, sans-serif;
    margin: 0;
    padding: 0;
  }

  html, body {
    background-color: var(--app-background);
    color: var(--app-text);
  }

  a, a:visited {
    color: var(--accent);
  }

  .noselect {
    -webkit-touch-callout: none;
    -webkit-user-select: none;
    -moz-user-select: none;
    -ms-user-select: none;
    user-select: none;
  }

  .w100 {
    width: 100%;
  }

  .centered {
    display: flex;
    flex-direction: column;
    height: calc(100vh - (var(--footer-height) + var(--header-height) + 16px));
    justify-content: center;
    margin: 0 auto;
  }
```
