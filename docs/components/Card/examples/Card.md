---
id: Card
section: components
cssPrefix: pf-v6-c-card
---import './Card.css'

## Examples

### Basic

```html
<div class="pf-v6-c-card" id="card-basic-example">
  <div class="pf-v6-c-card__title">
    <h2 class="pf-v6-c-card__title-text">Title</h2>
  </div>
  <div class="pf-v6-c-card__body">Body</div>
  <div class="pf-v6-c-card__footer">Footer</div>
</div>

```

### With image and action

```html
<div class="pf-v6-c-card" id="card-action-example-1">
  <div class="pf-v6-c-card__header">
    <div class="pf-v6-c-card__header-main">
      <svg
        height="70px"
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 40 40"
      >
        <path
          fill="var(--pf-t--global--text--color--regular)"
          fill-rule="evenodd"
          d="M37.03 25.32c.57 0 1.47.66 1.47 2.26 0 1.58-.65 3.38-.8 3.77C35.32 37.03 29.7 40.2 23 40c-6.24-.19-11.57-3.5-13.9-8.9a6.13 6.13 0 0 1-3.97-1.6 5.9 5.9 0 0 1-2.02-3.78 6.5 6.5 0 0 1 .37-2.99l-1.31-1.11C-3.83 16.52 14.92-4.42 20.9.84l2.04 2.01 1.12-.47c5.26-2.2 9.52-1.14 9.53 2.36 0 1.81-1.15 3.93-3 5.85.67.62 1.2 1.6 1.52 2.7.25.83.3 1.67.32 2.2l.07 2.5.74.2c1.42.4 2.42.93 2.91 1.45.5.52.73 1.02.82 1.6a3.1 3.1 0 0 1-.55 2.26s.16.35.32.85l.28.97zm-14.56 2.63zm14.63.16c.15-.95-.06-1.31-.35-1.49-.3-.19-.66-.12-.66-.12s-.17-1.13-.63-2.16a13.83 13.83 0 0 1-4.53 2.26c-1.56.45-3.68.8-6.04.65-1.31-.1-2.18-.49-2.5.58 2.99 1.1 6.16.63 6.16.63.06 0 .11.04.12.1 0 .05-.02.1-.07.12 0 0-2.43 1.13-6.3-.07.1.91.99 1.32 1.41 1.49.53.2 1.12.3 1.12.3 4.79.83 9.27-1.92 10.28-2.62.07-.05.12 0 .06.1l-.1.13c-1.23 1.6-4.55 3.46-8.87 3.46-1.88 0-3.76-.67-4.45-1.7-1.08-1.58-.06-3.9 1.73-3.66l.78.09a16.3 16.3 0 0 0 8.13-1.31c2.44-1.14 3.36-2.4 3.22-3.4a1.46 1.46 0 0 0-.42-.83 5.25 5.25 0 0 0-2.3-1.1c-.39-.1-.65-.18-.93-.27-.5-.17-.76-.3-.81-1.25l-.13-2.47c-.04-1.05-.17-2.48-1.05-3.07a1.48 1.48 0 0 0-.76-.25c-.26 0-.4.04-.45.05-.5.08-.8.35-1.18.67A4.04 4.04 0 0 1 24.51 14c-.62-.03-1.28-.13-2.03-.17l-.44-.03c-1.73-.08-3.6 1.42-3.9 3.56-.44 2.98 1.7 4.52 2.33 5.43.08.1.17.26.17.4 0 .17-.11.31-.22.43a7.66 7.66 0 0 0-1.36 8.03c1.57 3.68 6.43 5.4 11.18 3.84.63-.21 1.23-.47 1.8-.77 1.07-.52 2-1.24 2.76-2.07a8.27 8.27 0 0 0 2.3-4.54zm-7.9-9.2a3.23 3.23 0 0 1-.52-1.28c-.2-.96-.18-1.65.37-1.74.56-.09.82.49 1.02 1.44.14.64.11 1.23-.04 1.57a3.2 3.2 0 0 0-.82 0zm-4.74.75c-.4-.18-.91-.37-1.53-.34-.88.06-1.65.45-1.87.42-.09-.01-.13-.05-.14-.1-.04-.17.22-.44.48-.63.8-.58 1.84-.71 2.72-.33.42.18.82.5 1.02.83.1.15.11.27.05.33-.1.1-.34-.01-.73-.18zm-.8.45c.71-.08 1.23.25 1.35.45.05.08.03.14.02.16-.06.1-.18.08-.44.05a3.27 3.27 0 0 0-1.66.17s-.26.1-.38.1a.12.12 0 0 1-.12-.12c0-.1.1-.26.25-.4.18-.16.46-.33.98-.4zm3.94 1.68c-.35-.17-.53-.52-.4-.78.12-.26.5-.32.86-.15.35.17.53.52.4.78-.12.25-.5.32-.86.15zm2.25-1.98c.29 0 .51.33.5.72 0 .4-.23.7-.52.7-.28 0-.5-.32-.5-.72 0-.39.24-.7.52-.7zm-14.77-8.58c-.06.06.02.15.09.1A15.1 15.1 0 0 1 27.1 8.94c.07.02.12-.11.05-.15-1-.57-2.54-.95-3.63-.96-.06 0-.09-.06-.05-.1.19-.26.44-.51.68-.7.05-.04.02-.12-.05-.12-1.55.1-3.32.84-4.34 1.54-.05.04-.12 0-.1-.07.07-.38.32-.89.45-1.13.04-.05-.03-.11-.08-.08a17.67 17.67 0 0 0-4.95 4.06zm-7.72 8.2c1.71-4.61 4.57-8.87 8.35-11.8 2.81-2.35 5.84-4.04 5.84-4.04s-1.63-1.9-2.12-2.04C16.4.73 9.85 5.26 5.67 11.25c-1.69 2.43-4.1 6.73-2.95 8.94.14.27.95.97 1.38 1.34a5.15 5.15 0 0 1 3.26-2.1zm2.26 10.14c2.19-.37 2.76-2.76 2.4-5.1-.4-2.66-2.2-3.6-3.4-3.66-.34-.02-.65.01-.9.06-2.17.44-3.39 2.29-3.15 4.7.22 2.16 2.4 4 4.43 4.05.2 0 .41-.01.62-.05zm.83-2.72c.1-.03.22-.06.3.03.02.03.06.1.01.21-.08.19-.4.44-.85.43-.47-.04-1-.38-1.06-1.23-.04-.42.12-.94.22-1.2a1.12 1.12 0 0 0-1.3-1.52c-.3.07-.54.24-.7.5a2.64 2.64 0 0 0-.3.7c-.1.27-.25.35-.36.33-.05 0-.12-.04-.17-.16-.12-.34-.02-1.29.61-1.98a1.9 1.9 0 0 1 1.63-.6c.63.09 1.16.47 1.48 1.09.43.82.05 1.68-.18 2.2l-.06.15c-.15.34-.16.64-.03.84.1.15.28.24.49.24.1 0 .19-.02.27-.03z"
        />
      </svg>
    </div>
    <div class="pf-v6-c-card__actions">
      <button
        class="pf-v6-c-menu-toggle pf-m-plain"
        type="button"
        aria-expanded="false"
        aria-label="Menu toggle"
        id="card-action-example-1-menu-toggle-kebab"
      >
        <span class="pf-v6-c-menu-toggle__icon">
          <i class="fas fa-ellipsis-v" aria-hidden="true"></i>
        </span>
      </button>
      <div class="pf-v6-c-check pf-m-standalone">
        <input
          class="pf-v6-c-check__input"
          type="checkbox"
          aria-label="Standalone check"
          id="card-action-example-1-check"
          name="card-action-example-1-check"
          aria-labelledby="card-action-example-1"
        />
      </div>
    </div>
  </div>
  <div class="pf-v6-c-card__title">
    <h2
      class="pf-v6-c-card__title-text"
      id="card-action-example-1-check-label"
    >Title</h2>
  </div>
  <div class="pf-v6-c-card__body">Body</div>
  <div class="pf-v6-c-card__footer">Footer</div>
</div>

```

### With title in head

```html
<div class="pf-v6-c-card" id="card-action-example-2">
  <div class="pf-v6-c-card__header">
    <div class="pf-v6-c-card__actions">
      <button
        class="pf-v6-c-menu-toggle pf-m-plain"
        type="button"
        aria-expanded="false"
        aria-label="Menu toggle"
        id="card-action-example-2-menu-toggle-kebab"
      >
        <span class="pf-v6-c-menu-toggle__icon">
          <i class="fas fa-ellipsis-v" aria-hidden="true"></i>
        </span>
      </button>
      <div class="pf-v6-c-check pf-m-standalone">
        <input
          class="pf-v6-c-check__input"
          type="checkbox"
          aria-label="Standalone check"
          id="card-action-example-2-check"
          name="card-action-example-2-check"
          aria-labelledby="card-action-example-2"
        />
      </div>
    </div>
    <div class="pf-v6-c-card__header-main">
      <div class="pf-v6-c-card__title">
        <h2
          class="pf-v6-c-card__title-text"
          id="card-action-example-2-check-label"
        >This is a really really really really really really really really really really long title</h2>
      </div>
    </div>
  </div>
  <div class="pf-v6-c-card__body">Body</div>
  <div class="pf-v6-c-card__footer">Footer</div>
</div>

```

### With only actions in head (no title/footer)

```html
<div class="pf-v6-c-card" id="card-action-example-3">
  <div class="pf-v6-c-card__header">
    <div class="pf-v6-c-card__actions">
      <button
        class="pf-v6-c-menu-toggle pf-m-plain"
        type="button"
        aria-expanded="false"
        aria-label="Menu toggle"
        id="card-action-example-3-menu-toggle-kebab"
      >
        <span class="pf-v6-c-menu-toggle__icon">
          <i class="fas fa-ellipsis-v" aria-hidden="true"></i>
        </span>
      </button>
      <div class="pf-v6-c-check pf-m-standalone">
        <input
          class="pf-v6-c-check__input"
          type="checkbox"
          aria-label="Standalone check"
          id="card-action-example-3-check"
          name="card-action-example-3-check"
          aria-labelledby="card-action-example-3"
        />
      </div>
    </div>
  </div>
  <div
    class="pf-v6-c-card__body"
    id="card-action-example-3-check-label"
  >This is the card body. There are only actions in the card head.</div>
</div>

```

### Card with header that wraps

```html
<div class="pf-v6-c-card">
  <div class="pf-v6-c-card__header pf-m-wrap">
    <div class="pf-v6-c-card__actions pf-m-no-offset">
      <button class="pf-v6-c-button pf-m-primary" type="button">
        <span class="pf-v6-c-button__text">Primary action</span>
      </button>

      <button class="pf-v6-c-button pf-m-secondary" type="button">
        <span class="pf-v6-c-button__text">Secondary action</span>
      </button>

      <button class="pf-v6-c-button pf-m-tertiary" type="button">
        <span class="pf-v6-c-button__text">Tertiary action</span>
      </button>
    </div>
    <div class="pf-v6-c-card__title">
      <h2
        class="pf-v6-c-card__title-text"
      >This is a longer card title that takes up more space</h2>
    </div>
  </div>
  <div class="pf-v6-c-card__body">This is the card body</div>
</div>

```

### Actions with no offset

```html
<div class="pf-v6-c-card" id="card-action-no-offset">
  <div class="pf-v6-c-card__header">
    <div class="pf-v6-c-card__actions pf-m-no-offset">
      <button class="pf-v6-c-button pf-m-primary" type="button">
        <span class="pf-v6-c-button__text">Action</span>
      </button>
    </div>
    <div class="pf-v6-c-card__header-main">
      <h1
        class="pf-v6-c-title pf-m-2xl"
        id="card-action-no-offset-check-label"
      >This is a card title</h1>
    </div>
  </div>
  <div class="pf-v6-c-card__body">Body</div>
  <div class="pf-v6-c-card__footer">Footer</div>
</div>

```

### With only image in head

```html
<div class="pf-v6-c-card" id="card-image-head-example">
  <div class="pf-v6-c-card__header">
    <div class="pf-v6-c-card__header-main">
      <svg
        height="70px"
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 40 40"
      >
        <path
          fill="var(--pf-t--global--text--color--regular)"
          fill-rule="evenodd"
          d="M37.03 25.32c.57 0 1.47.66 1.47 2.26 0 1.58-.65 3.38-.8 3.77C35.32 37.03 29.7 40.2 23 40c-6.24-.19-11.57-3.5-13.9-8.9a6.13 6.13 0 0 1-3.97-1.6 5.9 5.9 0 0 1-2.02-3.78 6.5 6.5 0 0 1 .37-2.99l-1.31-1.11C-3.83 16.52 14.92-4.42 20.9.84l2.04 2.01 1.12-.47c5.26-2.2 9.52-1.14 9.53 2.36 0 1.81-1.15 3.93-3 5.85.67.62 1.2 1.6 1.52 2.7.25.83.3 1.67.32 2.2l.07 2.5.74.2c1.42.4 2.42.93 2.91 1.45.5.52.73 1.02.82 1.6a3.1 3.1 0 0 1-.55 2.26s.16.35.32.85l.28.97zm-14.56 2.63zm14.63.16c.15-.95-.06-1.31-.35-1.49-.3-.19-.66-.12-.66-.12s-.17-1.13-.63-2.16a13.83 13.83 0 0 1-4.53 2.26c-1.56.45-3.68.8-6.04.65-1.31-.1-2.18-.49-2.5.58 2.99 1.1 6.16.63 6.16.63.06 0 .11.04.12.1 0 .05-.02.1-.07.12 0 0-2.43 1.13-6.3-.07.1.91.99 1.32 1.41 1.49.53.2 1.12.3 1.12.3 4.79.83 9.27-1.92 10.28-2.62.07-.05.12 0 .06.1l-.1.13c-1.23 1.6-4.55 3.46-8.87 3.46-1.88 0-3.76-.67-4.45-1.7-1.08-1.58-.06-3.9 1.73-3.66l.78.09a16.3 16.3 0 0 0 8.13-1.31c2.44-1.14 3.36-2.4 3.22-3.4a1.46 1.46 0 0 0-.42-.83 5.25 5.25 0 0 0-2.3-1.1c-.39-.1-.65-.18-.93-.27-.5-.17-.76-.3-.81-1.25l-.13-2.47c-.04-1.05-.17-2.48-1.05-3.07a1.48 1.48 0 0 0-.76-.25c-.26 0-.4.04-.45.05-.5.08-.8.35-1.18.67A4.04 4.04 0 0 1 24.51 14c-.62-.03-1.28-.13-2.03-.17l-.44-.03c-1.73-.08-3.6 1.42-3.9 3.56-.44 2.98 1.7 4.52 2.33 5.43.08.1.17.26.17.4 0 .17-.11.31-.22.43a7.66 7.66 0 0 0-1.36 8.03c1.57 3.68 6.43 5.4 11.18 3.84.63-.21 1.23-.47 1.8-.77 1.07-.52 2-1.24 2.76-2.07a8.27 8.27 0 0 0 2.3-4.54zm-7.9-9.2a3.23 3.23 0 0 1-.52-1.28c-.2-.96-.18-1.65.37-1.74.56-.09.82.49 1.02 1.44.14.64.11 1.23-.04 1.57a3.2 3.2 0 0 0-.82 0zm-4.74.75c-.4-.18-.91-.37-1.53-.34-.88.06-1.65.45-1.87.42-.09-.01-.13-.05-.14-.1-.04-.17.22-.44.48-.63.8-.58 1.84-.71 2.72-.33.42.18.82.5 1.02.83.1.15.11.27.05.33-.1.1-.34-.01-.73-.18zm-.8.45c.71-.08 1.23.25 1.35.45.05.08.03.14.02.16-.06.1-.18.08-.44.05a3.27 3.27 0 0 0-1.66.17s-.26.1-.38.1a.12.12 0 0 1-.12-.12c0-.1.1-.26.25-.4.18-.16.46-.33.98-.4zm3.94 1.68c-.35-.17-.53-.52-.4-.78.12-.26.5-.32.86-.15.35.17.53.52.4.78-.12.25-.5.32-.86.15zm2.25-1.98c.29 0 .51.33.5.72 0 .4-.23.7-.52.7-.28 0-.5-.32-.5-.72 0-.39.24-.7.52-.7zm-14.77-8.58c-.06.06.02.15.09.1A15.1 15.1 0 0 1 27.1 8.94c.07.02.12-.11.05-.15-1-.57-2.54-.95-3.63-.96-.06 0-.09-.06-.05-.1.19-.26.44-.51.68-.7.05-.04.02-.12-.05-.12-1.55.1-3.32.84-4.34 1.54-.05.04-.12 0-.1-.07.07-.38.32-.89.45-1.13.04-.05-.03-.11-.08-.08a17.67 17.67 0 0 0-4.95 4.06zm-7.72 8.2c1.71-4.61 4.57-8.87 8.35-11.8 2.81-2.35 5.84-4.04 5.84-4.04s-1.63-1.9-2.12-2.04C16.4.73 9.85 5.26 5.67 11.25c-1.69 2.43-4.1 6.73-2.95 8.94.14.27.95.97 1.38 1.34a5.15 5.15 0 0 1 3.26-2.1zm2.26 10.14c2.19-.37 2.76-2.76 2.4-5.1-.4-2.66-2.2-3.6-3.4-3.66-.34-.02-.65.01-.9.06-2.17.44-3.39 2.29-3.15 4.7.22 2.16 2.4 4 4.43 4.05.2 0 .41-.01.62-.05zm.83-2.72c.1-.03.22-.06.3.03.02.03.06.1.01.21-.08.19-.4.44-.85.43-.47-.04-1-.38-1.06-1.23-.04-.42.12-.94.22-1.2a1.12 1.12 0 0 0-1.3-1.52c-.3.07-.54.24-.7.5a2.64 2.64 0 0 0-.3.7c-.1.27-.25.35-.36.33-.05 0-.12-.04-.17-.16-.12-.34-.02-1.29.61-1.98a1.9 1.9 0 0 1 1.63-.6c.63.09 1.16.47 1.48 1.09.43.82.05 1.68-.18 2.2l-.06.15c-.15.34-.16.64-.03.84.1.15.28.24.49.24.1 0 .19-.02.27-.03z"
        />
      </svg>
    </div>
  </div>
  <div class="pf-v6-c-card__title">
    <h2 class="pf-v6-c-card__title-text">Title</h2>
  </div>
  <div class="pf-v6-c-card__body">Body</div>
  <div class="pf-v6-c-card__footer">Footer</div>
</div>

```

### With no footer

```html
<div class="pf-v6-c-card" id="card-no-footer-example">
  <div class="pf-v6-c-card__title">
    <h2 class="pf-v6-c-card__title-text">Title</h2>
  </div>
  <div class="pf-v6-c-card__body">This card has no footer</div>
</div>

```

### With no title

```html
<div class="pf-v6-c-card" id="card-no-title-example">
  <div class="pf-v6-c-card__body">This card has no title</div>
  <div class="pf-v6-c-card__footer">Footer</div>
</div>

```

### With only a content section

```html
<div class="pf-v6-c-card" id="card-body-example">
  <div class="pf-v6-c-card__body">Body</div>
</div>

```

### With multiple body sections

```html
<div class="pf-v6-c-card" id="card-multiple-body-example">
  <div class="pf-v6-c-card__title">
    <h2 class="pf-v6-c-card__title-text">Title</h2>
  </div>
  <div class="pf-v6-c-card__body">Body</div>
  <div class="pf-v6-c-card__body">Body</div>
  <div class="pf-v6-c-card__body">Body</div>
  <div class="pf-v6-c-card__footer">Footer</div>
</div>

```

### With only one body that fills

```html
<div class="pf-v6-c-card" id="card-body-fill-example">
  <div class="pf-v6-c-card__title">
    <h2 class="pf-v6-c-card__title-text">Title</h2>
  </div>
  <div class="pf-v6-c-card__body pf-m-no-fill">Body pf-m-no-fill</div>
  <div class="pf-v6-c-card__body pf-m-no-fill">Body pf-m-no-fill</div>
  <div class="pf-v6-c-card__body">Body</div>
  <div class="pf-v6-c-card__footer">Footer</div>
</div>

```

### Compact

```html
<div class="pf-v6-c-card pf-m-compact" id="card-compact-example">
  <div class="pf-v6-c-card__title">
    <h2 class="pf-v6-c-card__title-text">Title</h2>
  </div>
  <div class="pf-v6-c-card__body">Body</div>
  <div class="pf-v6-c-card__footer">Footer</div>
</div>

```

### Large

```html
<div class="pf-v6-c-card pf-m-display-lg" id="card-display-lg-example">
  <div class="pf-v6-c-card__title">
    <h2 class="pf-v6-c-card__title-text">Title</h2>
  </div>
  <div class="pf-v6-c-card__body">Body</div>
  <div class="pf-v6-c-card__footer">Footer</div>
</div>

```

### Selectable

```html
<div class="pf-v6-l-gallery pf-m-gutter">
  <div class="pf-v6-c-card pf-m-selectable" id="card-selectable-example">
    <div class="pf-v6-c-card__header">
      <div class="pf-v6-c-card__actions pf-m-no-offset">
        <div class="pf-v6-c-card__selectable-actions">
          <div class="pf-v6-c-check">
            <input
              class="pf-v6-c-check__input"
              type="checkbox"
              id="card-selectable-example-check"
              name="card-selectable-example-check"
              aria-labelledby="card-selectable-example"
            />
            <label
              class="pf-v6-c-check__label"
              for="card-selectable-example-check"
              id="card-selectable-example-check-label"
              name="card-selectable-example-check"
            ></label>
          </div>
        </div>
      </div>
      <div class="pf-v6-c-card__header-main">
        <div class="pf-v6-c-card__title">
          <h2 class="pf-v6-c-card__title-text">Title</h2>
        </div>
      </div>
    </div>
    <div class="pf-v6-c-card__body">Body</div>
    <div class="pf-v6-c-card__footer">Footer</div>
  </div>

  <div
    class="pf-v6-c-card pf-m-selectable pf-m-disabled"
    id="card-selectable-example-disabled"
  >
    <div class="pf-v6-c-card__header">
      <div class="pf-v6-c-card__actions pf-m-no-offset">
        <div class="pf-v6-c-card__selectable-actions">
          <div class="pf-v6-c-check">
            <input
              class="pf-v6-c-check__input"
              type="checkbox"
              disabled
              id="card-selectable-example-disabled-check"
              name="card-selectable-example-disabled-check"
              aria-labelledby="card-selectable-example-disabled"
            />
            <label
              class="pf-v6-c-check__label pf-m-disabled"
              for="card-selectable-example-disabled-check"
              id="card-selectable-example-disabled-check-label"
              name="card-selectable-example-disabled-check"
            ></label>
          </div>
        </div>
      </div>
      <div class="pf-v6-c-card__header-main">
        <div
          class="pf-v6-c-card__title"
          id="card-selectable-example-disabled-title"
        >
          <h2 class="pf-v6-c-card__title-text">Disabled card</h2>
        </div>
      </div>
    </div>
    <div class="pf-v6-c-card__body">Body</div>
    <div class="pf-v6-c-card__footer">Footer</div>
  </div>

  <div
    class="pf-v6-c-card pf-m-selectable pf-m-selected pf-m-disabled"
    id="card-selectable-example-selected-disabled"
  >
    <div class="pf-v6-c-card__header">
      <div class="pf-v6-c-card__actions pf-m-no-offset">
        <div class="pf-v6-c-card__selectable-actions">
          <div class="pf-v6-c-check">
            <input
              class="pf-v6-c-check__input"
              type="checkbox"
              checked
              disabled
              id="card-selectable-example-selected-disabled-check"
              name="card-selectable-example-selected-disabled-check"
              aria-labelledby="card-selectable-example-selected-disabled"
            />
            <label
              class="pf-v6-c-check__label pf-m-disabled"
              for="card-selectable-example-selected-disabled-check"
              id="card-selectable-example-selected-disabled-check-label"
              name="card-selectable-example-selected-disabled-check"
            ></label>
          </div>
        </div>
      </div>
      <div class="pf-v6-c-card__header-main">
        <div
          class="pf-v6-c-card__title"
          id="card-selectable-example-selected-disabled-title"
        >
          <h2 class="pf-v6-c-card__title-text">Selected but disabled card</h2>
        </div>
      </div>
    </div>
    <div class="pf-v6-c-card__body">Body</div>
    <div class="pf-v6-c-card__footer">Footer</div>
  </div>
</div>

```

### Selectable secondary style

```html
<div class="pf-v6-l-gallery pf-m-gutter">
  <div
    class="pf-v6-c-card pf-m-selectable pf-m-secondary"
    id="card-selectable-secondary-example"
  >
    <div class="pf-v6-c-card__header">
      <div class="pf-v6-c-card__actions pf-m-no-offset">
        <div class="pf-v6-c-card__selectable-actions">
          <div class="pf-v6-c-check">
            <input
              class="pf-v6-c-check__input"
              type="checkbox"
              id="card-selectable-secondary-example-check"
              name="card-selectable-secondary-example-check"
              aria-labelledby="card-selectable-secondary-example"
            />
            <label
              class="pf-v6-c-check__label"
              for="card-selectable-secondary-example-check"
              id="card-selectable-secondary-example-check-label"
              name="card-selectable-secondary-example-check"
            ></label>
          </div>
        </div>
      </div>
      <div class="pf-v6-c-card__header-main">
        <div class="pf-v6-c-card__title">
          <h2 class="pf-v6-c-card__title-text">Title</h2>
        </div>
      </div>
    </div>
    <div class="pf-v6-c-card__body">Body</div>
    <div class="pf-v6-c-card__footer">Footer</div>
  </div>

  <div
    class="pf-v6-c-card pf-m-selectable pf-m-disabled pf-m-secondary"
    id="card-selectable-secondary-example-disabled"
  >
    <div class="pf-v6-c-card__header">
      <div class="pf-v6-c-card__actions pf-m-no-offset">
        <div class="pf-v6-c-card__selectable-actions">
          <div class="pf-v6-c-check">
            <input
              class="pf-v6-c-check__input"
              type="checkbox"
              disabled
              id="card-selectable-secondary-example-disabled-check"
              name="card-selectable-secondary-example-disabled-check"
              aria-labelledby="card-selectable-secondary-example-disabled"
            />
            <label
              class="pf-v6-c-check__label pf-m-disabled"
              for="card-selectable-secondary-example-disabled-check"
              id="card-selectable-secondary-example-disabled-check-label"
              name="card-selectable-secondary-example-disabled-check"
            ></label>
          </div>
        </div>
      </div>
      <div class="pf-v6-c-card__header-main">
        <div
          class="pf-v6-c-card__title"
          id="card-selectable-secondary-example-disabled-title"
        >
          <h2 class="pf-v6-c-card__title-text">Disabled card</h2>
        </div>
      </div>
    </div>
    <div class="pf-v6-c-card__body">Body</div>
    <div class="pf-v6-c-card__footer">Footer</div>
  </div>

  <div
    class="pf-v6-c-card pf-m-selectable pf-m-selected pf-m-disabled pf-m-secondary"
    id="card-selectable-secondary-example-selected-disabled"
  >
    <div class="pf-v6-c-card__header">
      <div class="pf-v6-c-card__actions pf-m-no-offset">
        <div class="pf-v6-c-card__selectable-actions">
          <div class="pf-v6-c-check">
            <input
              class="pf-v6-c-check__input"
              type="checkbox"
              checked
              disabled
              id="card-selectable-secondary-example-selected-disabled-check"
              name="card-selectable-secondary-example-selected-disabled-check"
              aria-labelledby="card-selectable-secondary-example-selected-disabled"
            />
            <label
              class="pf-v6-c-check__label pf-m-disabled"
              for="card-selectable-secondary-example-selected-disabled-check"
              id="card-selectable-secondary-example-selected-disabled-check-label"
              name="card-selectable-secondary-example-selected-disabled-check"
            ></label>
          </div>
        </div>
      </div>
      <div class="pf-v6-c-card__header-main">
        <div
          class="pf-v6-c-card__title"
          id="card-selectable-secondary-example-selected-disabled-title"
        >
          <h2 class="pf-v6-c-card__title-text">Selected but disabled card</h2>
        </div>
      </div>
    </div>
    <div class="pf-v6-c-card__body">Body</div>
    <div class="pf-v6-c-card__footer">Footer</div>
  </div>
</div>

```

### Single selectable

```html
<div class="pf-v6-l-gallery pf-m-gutter">
  <div class="pf-v6-c-card pf-m-selectable" id="card-single-selectable-example">
    <div class="pf-v6-c-card__header">
      <div class="pf-v6-c-card__actions pf-m-no-offset">
        <div class="pf-v6-c-card__selectable-actions">
          <div class="pf-v6-c-radio">
            <input
              class="pf-v6-c-radio__input"
              type="radio"
              id="card-single-selectable-example-radio"
              name="card-single-selectable-example-radio"
              aria-labelledby="card-single-selectable-example"
            />
            <label
              class="pf-v6-c-radio__label"
              for="card-single-selectable-example-radio"
              id="card-single-selectable-example-radio-label"
              name="card-single-selectable-example-radio"
            ></label>
          </div>
        </div>
      </div>
      <div class="pf-v6-c-card__header-main">
        <div
          class="pf-v6-c-card__title"
          id="card-single-selectable-example-title"
        >
          <h2 class="pf-v6-c-card__title-text">Title</h2>
        </div>
      </div>
    </div>
    <div class="pf-v6-c-card__body">Body</div>
    <div class="pf-v6-c-card__footer">Footer</div>
  </div>

  <div
    class="pf-v6-c-card pf-m-selectable pf-m-disabled"
    id="card-single-selectable-example-disabled"
  >
    <div class="pf-v6-c-card__header">
      <div class="pf-v6-c-card__actions pf-m-no-offset">
        <div class="pf-v6-c-card__selectable-actions">
          <div class="pf-v6-c-radio">
            <input
              class="pf-v6-c-radio__input"
              type="radio"
              id="card-single-selectable-example-disabled-radio"
              name="card-single-selectable-example-disabled-radio"
              aria-labelledby="card-single-selectable-example-disabled"
              disabled
            />
            <label
              class="pf-v6-c-radio__label pf-m-disabled"
              for="card-single-selectable-example-disabled-radio"
              id="card-single-selectable-example-disabled-radio-label"
              name="card-single-selectable-example-disabled-radio"
            ></label>
          </div>
        </div>
      </div>
      <div class="pf-v6-c-card__header-main">
        <div
          class="pf-v6-c-card__title"
          id="card-single-selectable-example-disabled-title"
        >
          <h2 class="pf-v6-c-card__title-text">Disabled card</h2>
        </div>
      </div>
    </div>
    <div class="pf-v6-c-card__body">Body</div>
    <div class="pf-v6-c-card__footer">Footer</div>
  </div>

  <div
    class="pf-v6-c-card pf-m-selectable pf-m-selected pf-m-disabled"
    id="card-single-selectable-example-selected-disabled"
  >
    <div class="pf-v6-c-card__header">
      <div class="pf-v6-c-card__actions pf-m-no-offset">
        <div class="pf-v6-c-card__selectable-actions">
          <div class="pf-v6-c-radio">
            <input
              class="pf-v6-c-radio__input"
              type="radio"
              id="card-single-selectable-example-selected-disabled-radio"
              name="card-single-selectable-example-selected-disabled-radio"
              aria-labelledby="card-single-selectable-example-selected-disabled"
              disabled
              checked
            />
            <label
              class="pf-v6-c-radio__label pf-m-disabled"
              for="card-single-selectable-example-selected-disabled-radio"
              id="card-single-selectable-example-selected-disabled-radio-label"
              name="card-single-selectable-example-selected-disabled-radio"
            ></label>
          </div>
        </div>
      </div>
      <div class="pf-v6-c-card__header-main">
        <div
          class="pf-v6-c-card__title"
          id="card-single-selectable-example-selected-disabled-title"
        >
          <h2 class="pf-v6-c-card__title-text">Selected but disabled card</h2>
        </div>
      </div>
    </div>
    <div class="pf-v6-c-card__body">Body</div>
    <div class="pf-v6-c-card__footer">Footer</div>
  </div>
</div>

```

### Actionable (button)

```html
<div class="pf-v6-l-gallery pf-m-gutter">
  <div class="pf-v6-c-card pf-m-clickable" id="card-actionable-button-example">
    <div class="pf-v6-c-card__header">
      <div class="pf-v6-c-card__actions pf-m-no-offset">
        <div class="pf-v6-c-card__selectable-actions">
          <button
            class="pf-v6-c-card__clickable-action"
            type="button"
            aria-labelledby="card-actionable-button-example"
          ></button>
        </div>
      </div>
      <div class="pf-v6-c-card__header-main">
        <div
          class="pf-v6-c-card__title"
          id="card-actionable-button-example-title"
        >
          <h2 class="pf-v6-c-card__title-text">Title</h2>
        </div>
      </div>
    </div>
    <div class="pf-v6-c-card__body">Body</div>
    <div class="pf-v6-c-card__footer">Footer</div>
  </div>

  <div
    class="pf-v6-c-card pf-m-clickable pf-m-current"
    id="card-actionable-button-example-clicked"
  >
    <div class="pf-v6-c-card__header">
      <div class="pf-v6-c-card__actions pf-m-no-offset">
        <div class="pf-v6-c-card__selectable-actions">
          <button
            class="pf-v6-c-card__clickable-action"
            type="button"
            aria-labelledby="card-actionable-button-example-clicked"
          ></button>
        </div>
      </div>
      <div class="pf-v6-c-card__header-main">
        <div
          class="pf-v6-c-card__title"
          id="card-actionable-button-example-clicked-title"
        >
          <h2 class="pf-v6-c-card__title-text">Title (clicked)</h2>
        </div>
      </div>
    </div>
    <div class="pf-v6-c-card__body">Body</div>
    <div class="pf-v6-c-card__footer">Footer</div>
  </div>

  <div
    class="pf-v6-c-card pf-m-clickable pf-m-disabled"
    id="card-actionable-button-example-disabled"
  >
    <div class="pf-v6-c-card__header">
      <div class="pf-v6-c-card__actions pf-m-no-offset">
        <div class="pf-v6-c-card__selectable-actions">
          <button
            class="pf-v6-c-card__clickable-action"
            type="button"
            aria-labelledby="card-actionable-button-example-disabled"
            disabled
          ></button>
        </div>
      </div>
      <div class="pf-v6-c-card__header-main">
        <div
          class="pf-v6-c-card__title"
          id="card-actionable-button-example-disabled-title"
        >
          <h2 class="pf-v6-c-card__title-text">Disabled card</h2>
        </div>
      </div>
    </div>
    <div class="pf-v6-c-card__body">Body</div>
    <div class="pf-v6-c-card__footer">Footer</div>
  </div>
</div>

```

### Actionable (link)

```html
<div class="pf-v6-l-gallery pf-m-gutter">
  <div class="pf-v6-c-card pf-m-clickable" id="card-actionable-link-example">
    <div class="pf-v6-c-card__header">
      <div class="pf-v6-c-card__actions pf-m-no-offset">
        <div class="pf-v6-c-card__selectable-actions">
          <a
            class="pf-v6-c-card__clickable-action"
            aria-labelledby="card-actionable-link-example"
            href="#"
          ></a>
        </div>
      </div>
      <div class="pf-v6-c-card__header-main">
        <div
          class="pf-v6-c-card__title"
          id="card-actionable-link-example-title"
        >
          <h2 class="pf-v6-c-card__title-text">Title</h2>
        </div>
      </div>
    </div>
    <div class="pf-v6-c-card__body">Body</div>
    <div class="pf-v6-c-card__footer">Footer</div>
  </div>

  <div
    class="pf-v6-c-card pf-m-clickable pf-m-disabled"
    id="card-actionable-link-example-disabled"
  >
    <div class="pf-v6-c-card__header">
      <div class="pf-v6-c-card__actions pf-m-no-offset">
        <div class="pf-v6-c-card__selectable-actions">
          <a
            class="pf-v6-c-card__clickable-action pf-m-disabled"
            tabindex="-1"
            aria-disabled="true"
            aria-labelledby="card-actionable-link-example-disabled"
            href="#"
          ></a>
        </div>
      </div>
      <div class="pf-v6-c-card__header-main">
        <div
          class="pf-v6-c-card__title"
          id="card-actionable-link-example-disabled-title"
        >
          <h2 class="pf-v6-c-card__title-text">Disabled card</h2>
        </div>
      </div>
    </div>
    <div class="pf-v6-c-card__body">Body</div>
    <div class="pf-v6-c-card__footer">Footer</div>
  </div>
</div>

```

### Actionable secondary style

```html
<div class="pf-v6-l-gallery pf-m-gutter">
  <div
    class="pf-v6-c-card pf-m-clickable pf-m-secondary"
    id="card-clickable-secondary-example"
  >
    <div class="pf-v6-c-card__header">
      <div class="pf-v6-c-card__actions pf-m-no-offset">
        <div class="pf-v6-c-card__selectable-actions">
          <div class="pf-v6-c-radio pf-m-standalone">
            <input
              class="pf-v6-c-radio__input pf-v6-screen-reader"
              type="radio"
              id="card-clickable-secondary-example-sr-only-radio"
              name="card-clickable-secondary-example-sr-only-radio"
              aria-labelledby="card-clickable-secondary-example"
            />

            <label
              class="pf-v6-c-radio__label"
              for="card-clickable-secondary-example-sr-only-radio"
              id="card-clickable-secondary-example-sr-only-radio-label"
              name="card-clickable-secondary-example-sr-only-radio"
            ></label>
          </div>
        </div>
      </div>
      <div class="pf-v6-c-card__header-main">
        <div
          class="pf-v6-c-card__title"
          id="card-clickable-secondary-example-title"
        >
          <h2 class="pf-v6-c-card__title-text">Title</h2>
        </div>
      </div>
    </div>
    <div class="pf-v6-c-card__body">Body</div>
    <div class="pf-v6-c-card__footer">Footer</div>
  </div>

  <div
    class="pf-v6-c-card pf-m-clickable pf-m-disabled pf-m-secondary"
    id="card-clickable-secondary-example-disabled"
  >
    <div class="pf-v6-c-card__header">
      <div class="pf-v6-c-card__actions pf-m-no-offset">
        <div class="pf-v6-c-card__selectable-actions">
          <div class="pf-v6-c-radio pf-m-standalone">
            <input
              class="pf-v6-c-radio__input pf-v6-screen-reader"
              type="radio"
              id="card-clickable-secondary-example-disabled-sr-only-radio"
              name="card-clickable-secondary-example-disabled-sr-only-radio"
              aria-labelledby="card-clickable-secondary-example-disabled"
              disabled
            />

            <label
              class="pf-v6-c-radio__label pf-m-disabled"
              for="card-clickable-secondary-example-disabled-sr-only-radio"
              id="card-clickable-secondary-example-disabled-sr-only-radio-label"
              name="card-clickable-secondary-example-disabled-sr-only-radio"
            ></label>
          </div>
        </div>
      </div>
      <div class="pf-v6-c-card__header-main">
        <div
          class="pf-v6-c-card__title"
          id="card-clickable-secondary-example-disabled-title"
        >
          <h2 class="pf-v6-c-card__title-text">Disabled card</h2>
        </div>
      </div>
    </div>
    <div class="pf-v6-c-card__body">Body</div>
    <div class="pf-v6-c-card__footer">Footer</div>
  </div>
</div>

```

### Actionable and selectable

```html
<div class="pf-v6-l-gallery pf-m-gutter">
  <div
    class="pf-v6-c-card pf-m-clickable pf-m-selectable"
    id="card-clickable-selectable-example"
  >
    <div class="pf-v6-c-card__header">
      <div class="pf-v6-c-card__actions pf-m-no-offset">
        <div class="pf-v6-c-card__selectable-actions">
          <div class="pf-v6-c-check">
            <input
              class="pf-v6-c-check__input"
              type="checkbox"
              id="card-clickable-selectable-example-check"
              name="card-clickable-selectable-example-check"
              aria-labelledby="card-clickable-selectable-example"
            />
            <label
              class="pf-v6-c-check__label"
              for="card-clickable-selectable-example-check"
              id="card-clickable-selectable-example-check-label"
              name="card-clickable-selectable-example-check"
            ></label>
          </div>
        </div>
      </div>
      <div class="pf-v6-c-card__header-main">
        <div
          class="pf-v6-c-card__title"
          id="card-clickable-selectable-example-title"
        >
          <h2 class="pf-v6-c-card__title-text">
            <button class="pf-v6-c-button pf-m-inline pf-m-link" type="button">
              <span class="pf-v6-c-button__text">Title</span>
            </button>
          </h2>
        </div>
      </div>
    </div>
    <div class="pf-v6-c-card__body">Body</div>
    <div class="pf-v6-c-card__footer">Footer</div>
  </div>

  <div
    class="pf-v6-c-card pf-m-clickable pf-m-selectable pf-m-current"
    id="card-clickable-selectable-current-example"
  >
    <div class="pf-v6-c-card__header">
      <div class="pf-v6-c-card__actions pf-m-no-offset">
        <div class="pf-v6-c-card__selectable-actions">
          <div class="pf-v6-c-check">
            <input
              class="pf-v6-c-check__input"
              type="checkbox"
              id="card-clickable-selectable-current-example-check"
              name="card-clickable-selectable-current-example-check"
              aria-labelledby="card-clickable-selectable-current-example"
            />
            <label
              class="pf-v6-c-check__label"
              for="card-clickable-selectable-current-example-check"
              id="card-clickable-selectable-current-example-check-label"
              name="card-clickable-selectable-current-example-check"
            ></label>
          </div>
        </div>
      </div>
      <div class="pf-v6-c-card__header-main">
        <div
          class="pf-v6-c-card__title"
          id="card-clickable-selectable-current-example-title"
        >
          <h2 class="pf-v6-c-card__title-text">
            <button class="pf-v6-c-button pf-m-inline pf-m-link" type="button">
              <span class="pf-v6-c-button__text">Current card (clicked)</span>
            </button>
          </h2>
        </div>
      </div>
    </div>
    <div class="pf-v6-c-card__body">Body</div>
    <div class="pf-v6-c-card__footer">Footer</div>
  </div>

  <div
    class="pf-v6-c-card pf-m-clickable pf-m-selectable pf-m-disabled"
    id="card-clickable-selectable-example-disabled"
  >
    <div class="pf-v6-c-card__header">
      <div class="pf-v6-c-card__actions pf-m-no-offset">
        <div class="pf-v6-c-card__selectable-actions">
          <div class="pf-v6-c-check">
            <input
              class="pf-v6-c-check__input"
              type="checkbox"
              disabled
              id="card-clickable-selectable-example-disabled-check"
              name="card-clickable-selectable-example-disabled-check"
              aria-labelledby="card-clickable-selectable-example-disabled"
            />
            <label
              class="pf-v6-c-check__label pf-m-disabled"
              for="card-clickable-selectable-example-disabled-check"
              id="card-clickable-selectable-example-disabled-check-label"
              name="card-clickable-selectable-example-disabled-check"
            ></label>
          </div>
        </div>
      </div>
      <div class="pf-v6-c-card__header-main">
        <div
          class="pf-v6-c-card__title"
          id="card-clickable-selectable-example-disabled-title"
        >
          <h2 class="pf-v6-c-card__title-text">
            <button
              class="pf-v6-c-button pf-m-inline pf-m-link"
              type="button"
              disabled
            >
              <span class="pf-v6-c-button__text">Disabled card</span>
            </button>
          </h2>
        </div>
      </div>
    </div>
    <div class="pf-v6-c-card__body">Body</div>
    <div class="pf-v6-c-card__footer">Footer</div>
  </div>

  <div
    class="pf-v6-c-card pf-m-clickable pf-m-selectable pf-m-selected pf-m-disabled"
    id="card-clickable-selectable-example-selected-disabled"
  >
    <div class="pf-v6-c-card__header">
      <div class="pf-v6-c-card__actions pf-m-no-offset">
        <div class="pf-v6-c-card__selectable-actions">
          <div class="pf-v6-c-check">
            <input
              class="pf-v6-c-check__input"
              type="checkbox"
              checked
              disabled
              id="card-clickable-selectable-example-selected-disabled-check"
              name="card-clickable-selectable-example-selected-disabled-check"
              aria-labelledby="card-clickable-selectable-example-selected-disabled"
            />
            <label
              class="pf-v6-c-check__label pf-m-disabled"
              for="card-clickable-selectable-example-selected-disabled-check"
              id="card-clickable-selectable-example-selected-disabled-check-label"
              name="card-clickable-selectable-example-selected-disabled-check"
            ></label>
          </div>
        </div>
      </div>
      <div class="pf-v6-c-card__header-main">
        <div
          class="pf-v6-c-card__title"
          id="card-clickable-selectable-example-selected-disabled-title"
        >
          <h2 class="pf-v6-c-card__title-text">
            <button
              class="pf-v6-c-button pf-m-inline pf-m-link"
              type="button"
              disabled
            >
              <span class="pf-v6-c-button__text">Selected but disabled card</span>
            </button>
          </h2>
        </div>
      </div>
    </div>
    <div class="pf-v6-c-card__body">Body</div>
    <div class="pf-v6-c-card__footer">Footer</div>
  </div>
</div>

```

### Actionable and selectable secondary style

```html
<div class="pf-v6-l-gallery pf-m-gutter">
  <div
    class="pf-v6-c-card pf-m-clickable pf-m-selectable pf-m-secondary"
    id="card-clickable-selectable-secondary-example"
  >
    <div class="pf-v6-c-card__header">
      <div class="pf-v6-c-card__actions pf-m-no-offset">
        <div class="pf-v6-c-card__selectable-actions">
          <div class="pf-v6-c-check">
            <input
              class="pf-v6-c-check__input"
              type="checkbox"
              id="card-clickable-selectable-secondary-example-check"
              name="card-clickable-selectable-secondary-example-check"
              aria-labelledby="card-clickable-selectable-secondary-example"
            />
            <label
              class="pf-v6-c-check__label"
              for="card-clickable-selectable-secondary-example-check"
              id="card-clickable-selectable-secondary-example-check-label"
              name="card-clickable-selectable-secondary-example-check"
            ></label>
          </div>
        </div>
      </div>
      <div class="pf-v6-c-card__header-main">
        <div
          class="pf-v6-c-card__title"
          id="card-clickable-selectable-secondary-example-title"
        >
          <h2 class="pf-v6-c-card__title-text">
            <button class="pf-v6-c-button pf-m-inline pf-m-link" type="button">
              <span class="pf-v6-c-button__text">Title</span>
            </button>
          </h2>
        </div>
      </div>
    </div>
    <div class="pf-v6-c-card__body">Body</div>
    <div class="pf-v6-c-card__footer">Footer</div>
  </div>

  <div
    class="pf-v6-c-card pf-m-clickable pf-m-selectable pf-m-current pf-m-secondary"
    id="card-clickable-selectable-secondary-current-example"
  >
    <div class="pf-v6-c-card__header">
      <div class="pf-v6-c-card__actions pf-m-no-offset">
        <div class="pf-v6-c-card__selectable-actions">
          <div class="pf-v6-c-check">
            <input
              class="pf-v6-c-check__input"
              type="checkbox"
              id="card-clickable-selectable-secondary-current-example-check"
              name="card-clickable-selectable-secondary-current-example-check"
              aria-labelledby="card-clickable-selectable-secondary-current-example"
            />
            <label
              class="pf-v6-c-check__label"
              for="card-clickable-selectable-secondary-current-example-check"
              id="card-clickable-selectable-secondary-current-example-check-label"
              name="card-clickable-selectable-secondary-current-example-check"
            ></label>
          </div>
        </div>
      </div>
      <div class="pf-v6-c-card__header-main">
        <div
          class="pf-v6-c-card__title"
          id="card-clickable-selectable-secondary-current-example-title"
        >
          <h2 class="pf-v6-c-card__title-text">
            <button class="pf-v6-c-button pf-m-inline pf-m-link" type="button">
              <span class="pf-v6-c-button__text">Current card (clicked)</span>
            </button>
          </h2>
        </div>
      </div>
    </div>
    <div class="pf-v6-c-card__body">Body</div>
    <div class="pf-v6-c-card__footer">Footer</div>
  </div>

  <div
    class="pf-v6-c-card pf-m-clickable pf-m-selectable pf-m-disabled pf-m-secondary"
    id="card-clickable-selectable-secondary-example-disabled"
  >
    <div class="pf-v6-c-card__header">
      <div class="pf-v6-c-card__actions pf-m-no-offset">
        <div class="pf-v6-c-card__selectable-actions">
          <div class="pf-v6-c-check">
            <input
              class="pf-v6-c-check__input"
              type="checkbox"
              disabled
              id="card-clickable-selectable-secondary-example-disabled-check"
              name="card-clickable-selectable-secondary-example-disabled-check"
              aria-labelledby="card-clickable-selectable-secondary-example-disabled"
            />
            <label
              class="pf-v6-c-check__label pf-m-disabled"
              for="card-clickable-selectable-secondary-example-disabled-check"
              id="card-clickable-selectable-secondary-example-disabled-check-label"
              name="card-clickable-selectable-secondary-example-disabled-check"
            ></label>
          </div>
        </div>
      </div>
      <div class="pf-v6-c-card__header-main">
        <div
          class="pf-v6-c-card__title"
          id="card-clickable-selectable-secondary-example-disabled-title"
        >
          <h2 class="pf-v6-c-card__title-text">
            <button
              class="pf-v6-c-button pf-m-inline pf-m-link"
              type="button"
              disabled
            >
              <span class="pf-v6-c-button__text">Disabled card</span>
            </button>
          </h2>
        </div>
      </div>
    </div>
    <div class="pf-v6-c-card__body">Body</div>
    <div class="pf-v6-c-card__footer">Footer</div>
  </div>

  <div
    class="pf-v6-c-card pf-m-clickable pf-m-selectable pf-m-selected pf-m-disabled pf-m-secondary"
    id="card-clickable-selectable-secondary-example-selected-disabled"
  >
    <div class="pf-v6-c-card__header">
      <div class="pf-v6-c-card__actions pf-m-no-offset">
        <div class="pf-v6-c-card__selectable-actions">
          <div class="pf-v6-c-check">
            <input
              class="pf-v6-c-check__input"
              type="checkbox"
              checked
              disabled
              id="card-clickable-selectable-secondary-example-selected-disabled-check"
              name="card-clickable-selectable-secondary-example-selected-disabled-check"
              aria-labelledby="card-clickable-selectable-secondary-example-selected-disabled"
            />
            <label
              class="pf-v6-c-check__label pf-m-disabled"
              for="card-clickable-selectable-secondary-example-selected-disabled-check"
              id="card-clickable-selectable-secondary-example-selected-disabled-check-label"
              name="card-clickable-selectable-secondary-example-selected-disabled-check"
            ></label>
          </div>
        </div>
      </div>
      <div class="pf-v6-c-card__header-main">
        <div
          class="pf-v6-c-card__title"
          id="card-clickable-selectable-secondary-example-selected-disabled-title"
        >
          <h2 class="pf-v6-c-card__title-text">
            <button
              class="pf-v6-c-button pf-m-inline pf-m-link"
              type="button"
              disabled
            >
              <span class="pf-v6-c-button__text">Selected but disabled card</span>
            </button>
          </h2>
        </div>
      </div>
    </div>
    <div class="pf-v6-c-card__body">Body</div>
    <div class="pf-v6-c-card__footer">Footer</div>
  </div>
</div>

```

### Secondary

```html
<div class="pf-v6-c-card pf-m-secondary" id="card-secondary-example">
  <div class="pf-v6-c-card__title">
    <h2 class="pf-v6-c-card__title-text">Title</h2>
  </div>
  <div class="pf-v6-c-card__body">Body</div>
  <div class="pf-v6-c-card__footer">Footer</div>
</div>

```

### Plain

```html
<div class="pf-v6-c-card pf-m-plain" id="card-plain-example">
  <div class="pf-v6-c-card__title">
    <h2 class="pf-v6-c-card__title-text">Title</h2>
  </div>
  <div class="pf-v6-c-card__body">Body</div>
  <div class="pf-v6-c-card__footer">Footer</div>
</div>

```

### Expandable

```html
<div class="pf-v6-c-card" id="card-expandable-example">
  <div class="pf-v6-c-card__header">
    <div class="pf-v6-c-card__header-toggle">
      <button
        class="pf-v6-c-button pf-m-plain"
        id="card-expandable-example-toggle"
        type="button"
        aria-labelledby="card-expandable-example-title card-expandable-example-toggle"
        aria-label="Details"
      >
        <span class="pf-v6-c-button__icon pf-m-start">
          <span class="pf-v6-c-card__header-toggle-icon">
            <i class="fas fa-angle-right" aria-hidden="true"></i>
          </span>
        </span>
      </button>
    </div>
    <div class="pf-v6-c-card__actions">
      <button
        class="pf-v6-c-menu-toggle pf-m-plain"
        type="button"
        aria-expanded="false"
        aria-label="Menu toggle"
        id="card-expandable-example-menu-toggle-kebab"
      >
        <span class="pf-v6-c-menu-toggle__icon">
          <i class="fas fa-ellipsis-v" aria-hidden="true"></i>
        </span>
      </button>
      <div class="pf-v6-c-check pf-m-standalone">
        <input
          class="pf-v6-c-check__input"
          type="checkbox"
          aria-label="Standalone check"
          id="card-expandable-example-check"
          name="card-expandable-example-check"
          aria-labelledby="card-expandable-example"
        />
      </div>
    </div>
    <div class="pf-v6-c-card__header-main">
      <div class="pf-v6-c-card__title">
        <h2
          class="pf-v6-c-card__title-text"
          id="card-expandable-example-title"
        >Title</h2>
      </div>
    </div>
  </div>
</div>

```

### Expandable with image

```html
<div class="pf-v6-c-card" id="card-expandable-image-example">
  <div class="pf-v6-c-card__header">
    <div class="pf-v6-c-card__header-toggle">
      <button
        class="pf-v6-c-button pf-m-plain"
        id="card-expandable-image-example-toggle"
        type="button"
        aria-labelledby="card-expandable-image-example-title card-expandable-image-example-toggle"
        aria-label="Details"
      >
        <span class="pf-v6-c-button__icon pf-m-start">
          <span class="pf-v6-c-card__header-toggle-icon">
            <i class="fas fa-angle-right" aria-hidden="true"></i>
          </span>
        </span>
      </button>
    </div>
    <div class="pf-v6-c-card__header-main">
      <img
        src="/assets/images/PF-IconLogo.svg"
        alt="PatternFly logo"
        width="27px"
      />
    </div>
    <div class="pf-v6-c-card__actions">
      <button
        class="pf-v6-c-menu-toggle pf-m-plain"
        type="button"
        aria-expanded="false"
        aria-label="Menu toggle"
        id="card-expandable-image-example-menu-toggle-kebab"
      >
        <span class="pf-v6-c-menu-toggle__icon">
          <i class="fas fa-ellipsis-v" aria-hidden="true"></i>
        </span>
      </button>
      <div class="pf-v6-c-check pf-m-standalone">
        <input
          class="pf-v6-c-check__input"
          type="checkbox"
          aria-label="Standalone check"
          id="card-expandable-image-example-check"
          name="card-expandable-image-example-check"
          aria-labelledby="card-expandable-image-example"
        />
      </div>
    </div>
  </div>
</div>

```

### Expanded

```html
<div class="pf-v6-c-card pf-m-expanded" id="card-expanded-example">
  <div class="pf-v6-c-card__header">
    <div class="pf-v6-c-card__header-toggle">
      <button
        class="pf-v6-c-button pf-m-plain"
        id="card-expanded-example-toggle"
        type="button"
        aria-labelledby="card-expanded-example-title card-expanded-example-toggle"
        aria-label="Details"
      >
        <span class="pf-v6-c-button__icon pf-m-start">
          <span class="pf-v6-c-card__header-toggle-icon">
            <i class="fas fa-angle-right" aria-hidden="true"></i>
          </span>
        </span>
      </button>
    </div>
    <div class="pf-v6-c-card__actions">
      <button
        class="pf-v6-c-menu-toggle pf-m-plain"
        type="button"
        aria-expanded="false"
        aria-label="Menu toggle"
        id="card-expanded-example-menu-toggle-kebab"
      >
        <span class="pf-v6-c-menu-toggle__icon">
          <i class="fas fa-ellipsis-v" aria-hidden="true"></i>
        </span>
      </button>
      <div class="pf-v6-c-check pf-m-standalone">
        <input
          class="pf-v6-c-check__input"
          type="checkbox"
          aria-label="Standalone check"
          id="card-expanded-example-check"
          name="card-expanded-example-check"
          aria-labelledby="card-expanded-example"
        />
      </div>
    </div>
    <div class="pf-v6-c-card__header-main">
      <h2
        class="pf-v6-c-card__title-text"
        id="card-expanded-example-title"
      >Title</h2>
    </div>
  </div>
  <div class="pf-v6-c-card__expandable-content">
    <div class="pf-v6-c-card__body">Body</div>
    <div class="pf-v6-c-card__footer">Footer</div>
  </div>
</div>

```

### Full height card

```html
<div class="pf-v6-c-card pf-m-full-height" id="card-full-height-example">
  <div class="pf-v6-c-card__header">
    <div class="pf-v6-c-card__actions">
      <button
        class="pf-v6-c-menu-toggle pf-m-plain"
        type="button"
        aria-expanded="false"
        aria-label="Menu toggle"
        id="card-full-height-example-menu-toggle-kebab"
      >
        <span class="pf-v6-c-menu-toggle__icon">
          <i class="fas fa-ellipsis-v" aria-hidden="true"></i>
        </span>
      </button>
      <div class="pf-v6-c-check pf-m-standalone">
        <input
          class="pf-v6-c-check__input"
          type="checkbox"
          aria-label="Standalone check"
          id="card-full-height-example-check"
          name="card-full-height-example-check"
          aria-labelledby="card-full-height-example"
        />
      </div>
    </div>
    <div class="pf-v6-c-card__header-main">
      <div class="pf-v6-c-card__title">
        <h2
          class="pf-v6-c-card__title-text"
          id="card-full-height-example-title&quot;"
        >Title</h2>
      </div>
    </div>
  </div>
  <div class="pf-v6-c-card__body">Body</div>
  <div class="pf-v6-c-card__footer">Footer</div>
</div>

```

### Expandable toggle on right

```html
<div class="pf-v6-c-card" id="card-toggle-on-right-example">
  <div class="pf-v6-c-card__header pf-m-toggle-right">
    <div class="pf-v6-c-card__actions">
      <button
        class="pf-v6-c-menu-toggle pf-m-plain"
        type="button"
        aria-expanded="false"
        aria-label="Menu toggle"
        id="card-toggle-on-right-example-menu-toggle-kebab"
      >
        <span class="pf-v6-c-menu-toggle__icon">
          <i class="fas fa-ellipsis-v" aria-hidden="true"></i>
        </span>
      </button>
      <div class="pf-v6-c-check pf-m-standalone">
        <input
          class="pf-v6-c-check__input"
          type="checkbox"
          aria-label="Standalone check"
          id="card-toggle-on-right-example-check"
          name="card-toggle-on-right-example-check"
          aria-labelledby="card-toggle-on-right-example"
        />
      </div>
    </div>
    <div class="pf-v6-c-card__header-main">
      <div class="pf-v6-c-card__title">
        <h2
          class="pf-v6-c-card__title-text"
          id="card-toggle-on-right-example-title"
        >Title</h2>
      </div>
    </div>
    <div class="pf-v6-c-card__header-toggle">
      <button
        class="pf-v6-c-button pf-m-plain"
        id="card-toggle-on-right-example-toggle"
        type="button"
        aria-labelledby="card-toggle-on-right-example-title card-toggle-on-right-example-toggle"
        aria-label="Details"
      >
        <span class="pf-v6-c-button__icon pf-m-start">
          <span class="pf-v6-c-card__header-toggle-icon">
            <i class="fas fa-angle-right" aria-hidden="true"></i>
          </span>
        </span>
      </button>
    </div>
  </div>
</div>

```

### Card with dividers between sections

```html
<div class="pf-v6-c-card">
  <div class="pf-v6-c-card__title">
    <h2 class="pf-v6-c-card__title-text">Title</h2>
  </div>
  <hr class="pf-v6-c-divider" />
  <div class="pf-v6-c-card__body">Body</div>
  <hr class="pf-v6-c-divider" />
  <div class="pf-v6-c-card__body">Body</div>
  <hr class="pf-v6-c-divider" />
  <div class="pf-v6-c-card__footer">Footer</div>
</div>

```

## Documentation

### Overview

A card is a generic rectangular container that can be used to build other components. Use a default card for regular page content and the compact variation for dashboard or small cards.

### Usage

| Class | Applied | Outcome |
| ---- | ---- | ---- |
| `.pf-v6-c-card` | `<div>` | Creates a card component.  **Required** |
| `.pf-v6-c-card__title` | `<div>` | Creates a card title container. |
| `.pf-v6-c-card__title-text` | `<h1>`, `<h2>`, `<h3>`, `<h4>`, `<h5>`, `<h6>`, `<div>` | Creates a card title text element. |
| `.pf-v6-c-card__body` | `<div>` | Creates the body of a card. By default, the body element fills the available space in the card. You can use multiple `.pf-v6-c-card__body` elements. |
| `.pf-v6-c-card__footer` | `<div>` | Creates the footer of a card. |
| `.pf-v6-c-card__header` | `<div>` | Creates the header of the card where images, actions, and/or the card title can go. |
| `.pf-v6-c-card__header-toggle` | `<div>` | Creates the expandable card toggle. |
| `.pf-v6-c-card__header-toggle-icon` | `<span>` | Creates the expandable card toggle icon. |
| `.pf-v6-c-card__actions` | `<div>` | Creates an actions element to be used in the card header. |
| `.pf-v6-c-card__selectable-actions` | `<div>` | Creates an element to hold a checkbox or radio and the related label used to make a card selectable or clickable. |
| `.pf-v6-c-card__header-main` | `<div>` | Creates a wrapper element to be used in the card header when using an image, logo, or text. **Required if `.pf-v6-c-card__header` has content outside of a card header toggle or card header actions** |
| `.pf-v6-c-card__expandable-content` | `<div>` | Creates the expandable card's expandable content. |
| `.pf-v6-c-card__sr-input` | `<input>` | Creates an input which, when focused, makes a following `.pf-v6-c-card` appear focused. |
| `.pf-m-compact` | `.pf-v6-c-card` | Creates a compact variation of the card component that involves smaller font sizes and spacing. This variation is for use on dashboards and where a smaller card is preferred. |
| `.pf-m-display-lg` | `.pf-v6-c-card` | Creates a large variation of the card component that involves larger font sizes and spacing. This variation is for marketing use cases. |
| `.pf-m-wrap` | `.pf-v6-c-card__header` | Modifies the card header to wrap its children. |
| `.pf-m-no-fill` | `.pf-v6-c-card__body` | Sets a `.pf-v6-c-card__body` not to fill the available space in `.pf-v6-c-card`. `.pf-m-no-fill` can be added to multiple card bodies. |
| `.pf-m-selectable` | `.pf-v6-c-card` | Modifies a card to be selectable.  |
| `.pf-m-clickable` | `.pf-v6-c-card` | Modifies a card to be clickable. |
| `.pf-m-selected` | `.pf-v6-c-card` | Modifies a selectable card for selected state styling. Can be used in addition to indicating selection via the `.pf-v6-c-card__input`. |
| `.pf-m-current` | `.pf-v6-c-card` | Modifies a card that is both clickable and selectable for clicked state styling. |
| `.pf-m-disabled` | `.pf-v6-c-card` | Modifies a card so it is not selectable or clickable.  |
| `.pf-m-secondary` | `.pf-v6-c-card` | Modifies the card to have secondary styling. |
| `.pf-m-flat` | `.pf-v6-c-card` | Modifies the card to have a border instead of a shadow. `.pf-m-flat` is for use in layouts where cards are against a white background. |
| `.pf-m-rounded` | `.pf-v6-c-card` | Modifies the card to have rounded corners. |
| `.pf-m-plain` | `.pf-v6-c-card` | Modifies the card to have no box shadow and no background color. |
| `.pf-m-expanded` | `.pf-v6-c-card` | Modifies the card for the expanded state. |
| `.pf-m-toggle-right` | `.pf-v6-c-card__header` | Modifies the expandable card header toggle to be positioned at flex-end. |
| `.pf-m-full-height` | `.pf-v6-c-card` | Modifies the card to full height of its parent. |
| `.pf-m-no-offset` | `.pf-v6-c-card__actions` | Removes the negative vertical margins on the actions element intended to align the action content with the card title. |
