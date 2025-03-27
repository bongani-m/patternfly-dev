---
id: Data list
section: components
wrapperTag: div
---## Demos

### Basic

```html isFullscreen
<div class="pf-v6-c-page" id="data-list-basic-example">
  <div class="pf-v6-c-skip-to-content">
    <a
      class="pf-v6-c-button pf-m-primary"
      href="#main-content-data-list-basic-example"
    >
      <span class="pf-v6-c-button__text">Skip to content</span>
    </a>
  </div>
  <header class="pf-v6-c-masthead" id="data-list-basic-example-masthead">
    <div class="pf-v6-c-masthead__main">
      <span class="pf-v6-c-masthead__toggle">
        <button
          class="pf-v6-c-button pf-m-plain"
          type="button"
          aria-label="Global navigation"
        >
          <span class="pf-v6-c-button__icon">
            <i class="fas fa-bars" aria-hidden="true"></i>
          </span>
        </button>
      </span>
      <div class="pf-v6-c-masthead__brand">
        <a class="pf-v6-c-masthead__logo" href="#">
          <svg
            height="37px"
            xmlns="http://www.w3.org/2000/svg"
            viewBox="0 0 40 40"
          >
            <path
              fill="var(--pf-t--global--text--color--regular)"
              fill-rule="evenodd"
              d="M37.03 25.32c.57 0 1.47.66 1.47 2.26 0 1.58-.65 3.38-.8 3.77C35.32 37.03 29.7 40.2 23 40c-6.24-.19-11.57-3.5-13.9-8.9a6.13 6.13 0 0 1-3.97-1.6 5.9 5.9 0 0 1-2.02-3.78 6.5 6.5 0 0 1 .37-2.99l-1.31-1.11C-3.83 16.52 14.92-4.42 20.9.84l2.04 2.01 1.12-.47c5.26-2.2 9.52-1.14 9.53 2.36 0 1.81-1.15 3.93-3 5.85.67.62 1.2 1.6 1.52 2.7.25.83.3 1.67.32 2.2l.07 2.5.74.2c1.42.4 2.42.93 2.91 1.45.5.52.73 1.02.82 1.6a3.1 3.1 0 0 1-.55 2.26s.16.35.32.85l.28.97zm-14.56 2.63zm14.63.16c.15-.95-.06-1.31-.35-1.49-.3-.19-.66-.12-.66-.12s-.17-1.13-.63-2.16a13.83 13.83 0 0 1-4.53 2.26c-1.56.45-3.68.8-6.04.65-1.31-.1-2.18-.49-2.5.58 2.99 1.1 6.16.63 6.16.63.06 0 .11.04.12.1 0 .05-.02.1-.07.12 0 0-2.43 1.13-6.3-.07.1.91.99 1.32 1.41 1.49.53.2 1.12.3 1.12.3 4.79.83 9.27-1.92 10.28-2.62.07-.05.12 0 .06.1l-.1.13c-1.23 1.6-4.55 3.46-8.87 3.46-1.88 0-3.76-.67-4.45-1.7-1.08-1.58-.06-3.9 1.73-3.66l.78.09a16.3 16.3 0 0 0 8.13-1.31c2.44-1.14 3.36-2.4 3.22-3.4a1.46 1.46 0 0 0-.42-.83 5.25 5.25 0 0 0-2.3-1.1c-.39-.1-.65-.18-.93-.27-.5-.17-.76-.3-.81-1.25l-.13-2.47c-.04-1.05-.17-2.48-1.05-3.07a1.48 1.48 0 0 0-.76-.25c-.26 0-.4.04-.45.05-.5.08-.8.35-1.18.67A4.04 4.04 0 0 1 24.51 14c-.62-.03-1.28-.13-2.03-.17l-.44-.03c-1.73-.08-3.6 1.42-3.9 3.56-.44 2.98 1.7 4.52 2.33 5.43.08.1.17.26.17.4 0 .17-.11.31-.22.43a7.66 7.66 0 0 0-1.36 8.03c1.57 3.68 6.43 5.4 11.18 3.84.63-.21 1.23-.47 1.8-.77 1.07-.52 2-1.24 2.76-2.07a8.27 8.27 0 0 0 2.3-4.54zm-7.9-9.2a3.23 3.23 0 0 1-.52-1.28c-.2-.96-.18-1.65.37-1.74.56-.09.82.49 1.02 1.44.14.64.11 1.23-.04 1.57a3.2 3.2 0 0 0-.82 0zm-4.74.75c-.4-.18-.91-.37-1.53-.34-.88.06-1.65.45-1.87.42-.09-.01-.13-.05-.14-.1-.04-.17.22-.44.48-.63.8-.58 1.84-.71 2.72-.33.42.18.82.5 1.02.83.1.15.11.27.05.33-.1.1-.34-.01-.73-.18zm-.8.45c.71-.08 1.23.25 1.35.45.05.08.03.14.02.16-.06.1-.18.08-.44.05a3.27 3.27 0 0 0-1.66.17s-.26.1-.38.1a.12.12 0 0 1-.12-.12c0-.1.1-.26.25-.4.18-.16.46-.33.98-.4zm3.94 1.68c-.35-.17-.53-.52-.4-.78.12-.26.5-.32.86-.15.35.17.53.52.4.78-.12.25-.5.32-.86.15zm2.25-1.98c.29 0 .51.33.5.72 0 .4-.23.7-.52.7-.28 0-.5-.32-.5-.72 0-.39.24-.7.52-.7zm-14.77-8.58c-.06.06.02.15.09.1A15.1 15.1 0 0 1 27.1 8.94c.07.02.12-.11.05-.15-1-.57-2.54-.95-3.63-.96-.06 0-.09-.06-.05-.1.19-.26.44-.51.68-.7.05-.04.02-.12-.05-.12-1.55.1-3.32.84-4.34 1.54-.05.04-.12 0-.1-.07.07-.38.32-.89.45-1.13.04-.05-.03-.11-.08-.08a17.67 17.67 0 0 0-4.95 4.06zm-7.72 8.2c1.71-4.61 4.57-8.87 8.35-11.8 2.81-2.35 5.84-4.04 5.84-4.04s-1.63-1.9-2.12-2.04C16.4.73 9.85 5.26 5.67 11.25c-1.69 2.43-4.1 6.73-2.95 8.94.14.27.95.97 1.38 1.34a5.15 5.15 0 0 1 3.26-2.1zm2.26 10.14c2.19-.37 2.76-2.76 2.4-5.1-.4-2.66-2.2-3.6-3.4-3.66-.34-.02-.65.01-.9.06-2.17.44-3.39 2.29-3.15 4.7.22 2.16 2.4 4 4.43 4.05.2 0 .41-.01.62-.05zm.83-2.72c.1-.03.22-.06.3.03.02.03.06.1.01.21-.08.19-.4.44-.85.43-.47-.04-1-.38-1.06-1.23-.04-.42.12-.94.22-1.2a1.12 1.12 0 0 0-1.3-1.52c-.3.07-.54.24-.7.5a2.64 2.64 0 0 0-.3.7c-.1.27-.25.35-.36.33-.05 0-.12-.04-.17-.16-.12-.34-.02-1.29.61-1.98a1.9 1.9 0 0 1 1.63-.6c.63.09 1.16.47 1.48 1.09.43.82.05 1.68-.18 2.2l-.06.15c-.15.34-.16.64-.03.84.1.15.28.24.49.24.1 0 .19-.02.27-.03z"
            />
          </svg>
        </a>
      </div>
    </div>
    <div class="pf-v6-c-masthead__content">
      <div
        class="pf-v6-c-toolbar pf-m-static"
        id="data-list-basic-example-masthead-toolbar"
      >
        <div class="pf-v6-c-toolbar__content">
          <div class="pf-v6-c-toolbar__content-section">
            <div
              class="pf-v6-c-toolbar__group pf-m-align-end pf-m-spacer-none pf-m-spacer-md-on-md pf-m-action-group-plain"
            >
              <div
                class="pf-v6-c-toolbar__group pf-m-hidden pf-m-visible-on-lg pf-m-action-group-plain"
              >
                <div class="pf-v6-c-toolbar__item">
                  <button
                    class="pf-v6-c-menu-toggle pf-m-plain"
                    type="button"
                    aria-expanded="false"
                    aria-label="Application launcher"
                  >
                    <span class="pf-v6-c-menu-toggle__icon">
                      <i class="fas fa-th" aria-hidden="true"></i>
                    </span>
                  </button>
                </div>
                <div class="pf-v6-c-toolbar__item">
                  <button
                    class="pf-v6-c-menu-toggle pf-m-plain"
                    type="button"
                    aria-expanded="false"
                    aria-label="Settings"
                  >
                    <span class="pf-v6-c-menu-toggle__icon">
                      <i class="fas fa-cog" aria-hidden="true"></i>
                    </span>
                  </button>
                </div>
                <div class="pf-v6-c-toolbar__item">
                  <button
                    class="pf-v6-c-menu-toggle pf-m-plain"
                    type="button"
                    aria-expanded="false"
                    aria-label="Help"
                  >
                    <span class="pf-v6-c-menu-toggle__icon">
                      <i class="fas fa-question-circle" aria-hidden="true"></i>
                    </span>
                  </button>
                </div>
              </div>

              <div class="pf-v6-c-toolbar__item pf-m-hidden-on-lg">
                <button
                  class="pf-v6-c-menu-toggle pf-m-plain"
                  type="button"
                  aria-expanded="false"
                  aria-label="Actions"
                >
                  <span class="pf-v6-c-menu-toggle__icon">
                    <i class="fas fa-ellipsis-v" aria-hidden="true"></i>
                  </span>
                </button>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </header>
  <div class="pf-v6-c-page__sidebar">
    <div class="pf-v6-c-page__sidebar-body">
      <nav
        class="pf-v6-c-nav"
        id="data-list-basic-example-primary-nav"
        aria-label="Global"
      >
        <ul class="pf-v6-c-nav__list" role="list">
          <li class="pf-v6-c-nav__item">
            <a href="#" class="pf-v6-c-nav__link">
              <span class="pf-v6-c-nav__link-text">System panel</span>
            </a>
          </li>
          <li class="pf-v6-c-nav__item">
            <a
              href="#"
              class="pf-v6-c-nav__link pf-m-current"
              aria-current="page"
            >
              <span class="pf-v6-c-nav__link-text">Policy</span>
            </a>
          </li>
          <li class="pf-v6-c-nav__item">
            <a href="#" class="pf-v6-c-nav__link">
              <span class="pf-v6-c-nav__link-text">Authentication</span>
            </a>
          </li>
          <li class="pf-v6-c-nav__item">
            <a href="#" class="pf-v6-c-nav__link">
              <span class="pf-v6-c-nav__link-text">Network services</span>
            </a>
          </li>
          <li class="pf-v6-c-nav__item">
            <a href="#" class="pf-v6-c-nav__link">
              <span class="pf-v6-c-nav__link-text">Server</span>
            </a>
          </li>
        </ul>
      </nav>
    </div>
  </div>
  <div class="pf-v6-c-page__main-container" tabindex="-1">
    <main
      class="pf-v6-c-page__main"
      tabindex="-1"
      id="main-content-data-list-basic-example"
    >
      <section class="pf-v6-c-page__main-breadcrumb pf-m-limit-width">
        <div class="pf-v6-c-page__main-body">
          <nav class="pf-v6-c-breadcrumb" aria-label="breadcrumb">
            <ol class="pf-v6-c-breadcrumb__list" role="list">
              <li class="pf-v6-c-breadcrumb__item">
                <a href="#" class="pf-v6-c-breadcrumb__link">Section home</a>
              </li>
              <li class="pf-v6-c-breadcrumb__item">
                <span class="pf-v6-c-breadcrumb__item-divider">
                  <i class="fas fa-angle-right" aria-hidden="true"></i>
                </span>

                <a href="#" class="pf-v6-c-breadcrumb__link">Section title</a>
              </li>
              <li class="pf-v6-c-breadcrumb__item">
                <span class="pf-v6-c-breadcrumb__item-divider">
                  <i class="fas fa-angle-right" aria-hidden="true"></i>
                </span>

                <a href="#" class="pf-v6-c-breadcrumb__link">Section title</a>
              </li>
              <li class="pf-v6-c-breadcrumb__item">
                <span class="pf-v6-c-breadcrumb__item-divider">
                  <i class="fas fa-angle-right" aria-hidden="true"></i>
                </span>

                <a
                  href="#"
                  class="pf-v6-c-breadcrumb__link pf-m-current"
                  aria-current="page"
                >Section landing</a>
              </li>
            </ol>
          </nav>
        </div>
      </section>
      <section class="pf-v6-c-page__main-section pf-m-limit-width">
        <div class="pf-v6-c-page__main-body">
          <h1 class="pf-v6-c-content--h1 pf-m-page-title">Main title</h1>
          <p class="pf-v6-c-content--p">This is a full page demo.</p>
        </div>
      </section>
      <section class="pf-v6-c-page__main-section">
        <div class="pf-v6-c-page__main-body">
          <div class="pf-v6-c-toolbar" id="data-list-basic-example-toolbar">
            <div class="pf-v6-c-toolbar__content">
              <div class="pf-v6-c-toolbar__content-section pf-m-nowrap">
                <div class="pf-v6-c-toolbar__item pf-m-bulk-select">
                  <div
                    class="pf-v6-c-menu-toggle pf-m-split-button"
                    id="data-list-basic-example-toolbar-check"
                  >
                    <label
                      class="pf-v6-c-check pf-m-standalone"
                      for="data-list-basic-example-toolbar-check-check-input"
                    >
                      <input
                        class="pf-v6-c-check__input"
                        type="checkbox"
                        id="data-list-basic-example-toolbar-check-check-input"
                        name="data-list-basic-example-toolbar-check-check-input"
                        aria-label="Standalone check"
                      />
                    </label>
                    <button
                      class="pf-v6-c-menu-toggle__button"
                      type="button"
                      aria-expanded="false"
                      id="data-list-basic-example-toolbar-menu-toggle-toggle-button"
                      aria-label="Menu toggle"
                    >
                      <span class="pf-v6-c-menu-toggle__controls">
                        <span class="pf-v6-c-menu-toggle__toggle-icon">
                          <i class="fas fa-caret-down fa-fw" aria-hidden="true"></i>
                        </span>
                      </span>
                    </button>
                  </div>
                </div>

                <div
                  class="pf-v6-c-overflow-menu"
                  id="data-list-basic-example-toolbar-overflow-menu"
                >
                  <div
                    class="pf-v6-c-overflow-menu__content pf-v6-u-display-none pf-v6-u-display-flex-on-lg"
                  >
                    <div class="pf-v6-c-overflow-menu__group pf-m-button-group">
                      <div class="pf-v6-c-overflow-menu__item">
                        <button
                          class="pf-v6-c-button pf-m-primary"
                          type="button"
                        >
                          <span class="pf-v6-c-button__text">Create instance</span>
                        </button>
                      </div>
                    </div>
                  </div>
                  <div class="pf-v6-c-overflow-menu__control">
                    <button
                      class="pf-v6-c-menu-toggle pf-m-plain"
                      type="button"
                      aria-expanded="false"
                      aria-label="Menu toggle"
                      id="data-list-basic-example-toolbar-overflow-menu-toggle"
                    >
                      <span class="pf-v6-c-menu-toggle__icon">
                        <i class="fas fa-ellipsis-v" aria-hidden="true"></i>
                      </span>
                    </button>
                  </div>
                </div>

                <div class="pf-v6-c-toolbar__item pf-m-pagination">
                  <div class="pf-v6-c-pagination pf-m-compact">
                    <div class="pf-v6-c-pagination__page-menu">
                      <button
                        class="pf-v6-c-menu-toggle pf-m-plain pf-m-text"
                        type="button"
                        aria-expanded="false"
                        aria-label="Menu toggle"
                        id="data-list-basic-example-toolbar-top-pagination"
                      >
                        <span class="pf-v6-c-menu-toggle__text">
                          <b>1 - 10</b>&nbsp;of&nbsp;
                          <b>36</b>
                        </span>
                        <span class="pf-v6-c-menu-toggle__controls">
                          <span class="pf-v6-c-menu-toggle__toggle-icon">
                            <i
                              class="fas fa-caret-down fa-fw"
                              aria-hidden="true"
                            ></i>
                          </span>
                        </span>
                      </button>
                    </div>
                    <nav
                      class="pf-v6-c-pagination__nav"
                      aria-label="Toolbar top pagination"
                    >
                      <div class="pf-v6-c-pagination__nav-control pf-m-prev">
                        <button
                          class="pf-v6-c-button pf-m-plain"
                          type="button"
                          disabled
                          aria-label="Go to previous page"
                        >
                          <span class="pf-v6-c-button__icon">
                            <i class="fas fa-angle-left" aria-hidden="true"></i>
                          </span>
                        </button>
                      </div>
                      <div class="pf-v6-c-pagination__nav-control pf-m-next">
                        <button
                          class="pf-v6-c-button pf-m-plain"
                          type="button"
                          aria-label="Go to next page"
                        >
                          <span class="pf-v6-c-button__icon">
                            <i class="fas fa-angle-right" aria-hidden="true"></i>
                          </span>
                        </button>
                      </div>
                    </nav>
                  </div>
                </div>
              </div>

              <div
                class="pf-v6-c-toolbar__expandable-content pf-m-hidden"
                id="data-list-basic-example-toolbar-expandable-content"
                hidden
              ></div>
            </div>
          </div>
          <ul
            class="pf-v6-c-data-list"
            role="list"
            aria-label="Simple data list example"
            id="data-list-basic-example-data-list"
          >
            <li
              class="pf-v6-c-data-list__item"
              aria-labelledby="data-list-basic-example-data-list-item-1"
            >
              <div class="pf-v6-c-data-list__item-row">
                <div class="pf-v6-c-data-list__item-content">
                  <div class="pf-v6-c-data-list__cell pf-m-align-left">
                    <div class="pf-v6-l-flex pf-m-column pf-m-space-items-md">
                      <div
                        class="pf-v6-l-flex pf-m-column pf-m-space-items-none"
                      >
                        <div class="pf-v6-l-flex__item">
                          <p
                            id="data-list-basic-example-data-list-item-1"
                          >patternfly</p>
                        </div>
                        <div class="pf-v6-l-flex__item">
                          <small>
                            Working repo for PatternFly 4
                            <a href>https://pf4.patternfly.org/</a>
                          </small>
                        </div>
                      </div>
                      <div class="pf-v6-l-flex pf-m-wrap">
                        <div class="pf-v6-l-flex pf-m-space-items-xs">
                          <div class="pf-v6-l-flex__item">
                            <i class="fas fa-code-branch" aria-hidden="true"></i>
                          </div>
                          <div class="pf-v6-l-flex__item">
                            <span>10</span>
                          </div>
                        </div>
                        <div class="pf-v6-l-flex pf-m-space-items-xs">
                          <div class="pf-v6-l-flex__item">
                            <i class="fas fa-code" aria-hidden="true"></i>
                          </div>
                          <div class="pf-v6-l-flex__item">
                            <span>4</span>
                          </div>
                        </div>
                        <div class="pf-v6-l-flex pf-m-space-items-xs">
                          <div class="pf-v6-l-flex__item">
                            <i class="fas fa-cube" aria-hidden="true"></i>
                          </div>
                          <div class="pf-v6-l-flex__item">
                            <span>5</span>
                          </div>
                        </div>
                        <div class="pf-v6-l-flex__item">Updated 2 days ago</div>
                      </div>
                    </div>
                  </div>
                  <div
                    class="pf-v6-c-data-list__cell pf-m-align-right pf-m-no-fill"
                  >
                    <button class="pf-v6-c-button pf-m-secondary" type="button">
                      <span class="pf-v6-c-button__text">Action</span>
                    </button>
                    <button class="pf-v6-c-button pf-m-link" type="button">
                      <span class="pf-v6-c-button__text">Link</span>
                    </button>
                  </div>
                </div>
              </div>
            </li>

            <li
              class="pf-v6-c-data-list__item"
              aria-labelledby="data-list-basic-example-data-list-item-2"
            >
              <div class="pf-v6-c-data-list__item-row">
                <div class="pf-v6-c-data-list__item-content">
                  <div class="pf-v6-c-data-list__cell pf-m-align-left">
                    <div class="pf-v6-l-flex pf-m-column pf-m-space-items-md">
                      <div
                        class="pf-v6-l-flex pf-m-column pf-m-space-items-none"
                      >
                        <div class="pf-v6-l-flex__item">
                          <p
                            id="data-list-basic-example-data-list-item-2"
                          >patternfly-elements</p>
                        </div>
                        <div class="pf-v6-l-flex__item">
                          <small>PatternFly elements</small>
                        </div>
                      </div>
                      <div class="pf-v6-l-flex pf-m-wrap">
                        <div class="pf-v6-l-flex pf-m-space-items-xs">
                          <div class="pf-v6-l-flex__item">
                            <i class="fas fa-code-branch" aria-hidden="true"></i>
                          </div>
                          <div class="pf-v6-l-flex__item">
                            <span>5</span>
                          </div>
                        </div>
                        <div class="pf-v6-l-flex pf-m-space-items-xs">
                          <div class="pf-v6-l-flex__item">
                            <i class="fas fa-code" aria-hidden="true"></i>
                          </div>
                          <div class="pf-v6-l-flex__item">
                            <span>9</span>
                          </div>
                        </div>
                        <div class="pf-v6-l-flex pf-m-space-items-xs">
                          <div class="pf-v6-l-flex__item">
                            <i class="fas fa-cube" aria-hidden="true"></i>
                          </div>
                          <div class="pf-v6-l-flex__item">
                            <span>2</span>
                          </div>
                        </div>
                        <div class="pf-v6-l-flex pf-m-space-items-xs">
                          <div class="pf-v6-l-flex__item">
                            <i class="fas fa-check-circle" aria-hidden="true"></i>
                          </div>
                          <div class="pf-v6-l-flex__item">
                            <span>11</span>
                          </div>
                        </div>
                        <div class="pf-v6-l-flex pf-m-space-items-xs">
                          <div class="pf-v6-l-flex__item">
                            <i
                              class="fas fa-exclamation-triangle"
                              aria-hidden="true"
                            ></i>
                          </div>
                          <div class="pf-v6-l-flex__item">
                            <span>4</span>
                          </div>
                        </div>
                        <div class="pf-v6-l-flex pf-m-space-items-xs">
                          <div class="pf-v6-l-flex__item">
                            <i class="fas fa-times-circle" aria-hidden="true"></i>
                          </div>
                          <div class="pf-v6-l-flex__item">
                            <span>1</span>
                          </div>
                        </div>
                        <div class="pf-v6-l-flex__item">Updated 2 days ago</div>
                      </div>
                    </div>
                  </div>
                  <div
                    class="pf-v6-c-data-list__cell pf-m-align-right pf-m-no-fill"
                  >
                    <button class="pf-v6-c-button pf-m-secondary" type="button">
                      <span class="pf-v6-c-button__text">Action</span>
                    </button>
                    <button class="pf-v6-c-button pf-m-link" type="button">
                      <span class="pf-v6-c-button__text">Link</span>
                    </button>
                  </div>
                </div>
              </div>
            </li>

            <li
              class="pf-v6-c-data-list__item"
              aria-labelledby="data-list-basic-example-data-list-item-3"
            >
              <div class="pf-v6-c-data-list__item-row">
                <div class="pf-v6-c-data-list__item-content">
                  <div class="pf-v6-c-data-list__cell pf-m-align-left">
                    <p
                      id="data-list-basic-example-data-list-item-3"
                    >patternfly-unified-design-kit</p>
                  </div>
                  <div
                    class="pf-v6-c-data-list__cell pf-m-align-right pf-m-no-fill"
                  >
                    <button class="pf-v6-c-button pf-m-secondary" type="button">
                      <span class="pf-v6-c-button__text">Action</span>
                    </button>
                    <button class="pf-v6-c-button pf-m-link" type="button">
                      <span class="pf-v6-c-button__text">Link</span>
                    </button>
                  </div>
                </div>
              </div>
            </li>

            <li
              class="pf-v6-c-data-list__item"
              aria-labelledby="data-list-basic-example-data-list-item-4"
            >
              <div class="pf-v6-c-data-list__item-row">
                <div class="pf-v6-c-data-list__item-content">
                  <div class="pf-v6-c-data-list__cell pf-m-align-left">
                    <div class="pf-v6-l-flex pf-m-column pf-m-space-items-md">
                      <div
                        class="pf-v6-l-flex pf-m-column pf-m-space-items-none"
                      >
                        <div class="pf-v6-l-flex__item">
                          <p
                            id="data-list-basic-example-data-list-item-4"
                          >patternfly</p>
                        </div>
                        <div class="pf-v6-l-flex__item">
                          <small>
                            Working repo for PatternFly 4
                            <a href>https://pf4.patternfly.org/</a>
                          </small>
                        </div>
                      </div>
                      <div class="pf-v6-l-flex pf-m-wrap">
                        <div class="pf-v6-l-flex pf-m-space-items-xs">
                          <div class="pf-v6-l-flex__item">
                            <i class="fas fa-code-branch" aria-hidden="true"></i>
                          </div>
                          <div class="pf-v6-l-flex__item">
                            <span>10</span>
                          </div>
                        </div>
                        <div class="pf-v6-l-flex pf-m-space-items-xs">
                          <div class="pf-v6-l-flex__item">
                            <i class="fas fa-code" aria-hidden="true"></i>
                          </div>
                          <div class="pf-v6-l-flex__item">
                            <span>4</span>
                          </div>
                        </div>
                        <div class="pf-v6-l-flex pf-m-space-items-xs">
                          <div class="pf-v6-l-flex__item">
                            <i class="fas fa-cube" aria-hidden="true"></i>
                          </div>
                          <div class="pf-v6-l-flex__item">
                            <span>5</span>
                          </div>
                        </div>
                        <div class="pf-v6-l-flex__item">Updated 2 days ago</div>
                      </div>
                    </div>
                  </div>
                  <div
                    class="pf-v6-c-data-list__cell pf-m-align-right pf-m-no-fill"
                  >
                    <button class="pf-v6-c-button pf-m-secondary" type="button">
                      <span class="pf-v6-c-button__text">Action</span>
                    </button>
                    <button class="pf-v6-c-button pf-m-link" type="button">
                      <span class="pf-v6-c-button__text">Link</span>
                    </button>
                  </div>
                </div>
              </div>
            </li>

            <li
              class="pf-v6-c-data-list__item"
              aria-labelledby="data-list-basic-example-data-list-item-5"
            >
              <div class="pf-v6-c-data-list__item-row">
                <div class="pf-v6-c-data-list__item-content">
                  <div class="pf-v6-c-data-list__cell pf-m-align-left">
                    <div class="pf-v6-l-flex pf-m-column pf-m-space-items-md">
                      <div
                        class="pf-v6-l-flex pf-m-column pf-m-space-items-none"
                      >
                        <div class="pf-v6-l-flex__item">
                          <p
                            id="data-list-basic-example-data-list-item-5"
                          >patternfly-elements</p>
                        </div>
                        <div class="pf-v6-l-flex__item">
                          <small>PatternFly elements</small>
                        </div>
                      </div>
                      <div class="pf-v6-l-flex pf-m-wrap">
                        <div class="pf-v6-l-flex pf-m-space-items-xs">
                          <div class="pf-v6-l-flex__item">
                            <i class="fas fa-code-branch" aria-hidden="true"></i>
                          </div>
                          <div class="pf-v6-l-flex__item">
                            <span>5</span>
                          </div>
                        </div>
                        <div class="pf-v6-l-flex pf-m-space-items-xs">
                          <div class="pf-v6-l-flex__item">
                            <i class="fas fa-code" aria-hidden="true"></i>
                          </div>
                          <div class="pf-v6-l-flex__item">
                            <span>9</span>
                          </div>
                        </div>
                        <div class="pf-v6-l-flex pf-m-space-items-xs">
                          <div class="pf-v6-l-flex__item">
                            <i class="fas fa-cube" aria-hidden="true"></i>
                          </div>
                          <div class="pf-v6-l-flex__item">
                            <span>2</span>
                          </div>
                        </div>
                        <div class="pf-v6-l-flex pf-m-space-items-xs">
                          <div class="pf-v6-l-flex__item">
                            <i class="fas fa-check-circle" aria-hidden="true"></i>
                          </div>
                          <div class="pf-v6-l-flex__item">
                            <span>11</span>
                          </div>
                        </div>
                        <div class="pf-v6-l-flex pf-m-space-items-xs">
                          <div class="pf-v6-l-flex__item">
                            <i
                              class="fas fa-exclamation-triangle"
                              aria-hidden="true"
                            ></i>
                          </div>
                          <div class="pf-v6-l-flex__item">
                            <span>4</span>
                          </div>
                        </div>
                        <div class="pf-v6-l-flex pf-m-space-items-xs">
                          <div class="pf-v6-l-flex__item">
                            <i class="fas fa-times-circle" aria-hidden="true"></i>
                          </div>
                          <div class="pf-v6-l-flex__item">
                            <span>1</span>
                          </div>
                        </div>
                        <div class="pf-v6-l-flex__item">Updated 2 days ago</div>
                      </div>
                    </div>
                  </div>
                  <div
                    class="pf-v6-c-data-list__cell pf-m-align-right pf-m-no-fill"
                  >
                    <button class="pf-v6-c-button pf-m-secondary" type="button">
                      <span class="pf-v6-c-button__text">Action</span>
                    </button>
                    <button class="pf-v6-c-button pf-m-link" type="button">
                      <span class="pf-v6-c-button__text">Link</span>
                    </button>
                  </div>
                </div>
              </div>
            </li>
          </ul>
          <div class="pf-v6-c-pagination pf-m-bottom">
            <div class="pf-v6-c-pagination__page-menu">
              <button
                class="pf-v6-c-menu-toggle pf-m-plain pf-m-text pf-m-top"
                type="button"
                aria-expanded="false"
                aria-label="Menu toggle"
                id="{{page--id}}-pagination-menu-toggle-bottom-example"
              >
                <span class="pf-v6-c-menu-toggle__text">
                  <b>1 - 10</b>&nbsp;of&nbsp;
                  <b>36</b>
                </span>
                <span class="pf-v6-c-menu-toggle__controls">
                  <span class="pf-v6-c-menu-toggle__toggle-icon">
                    <i class="fas fa-caret-down fa-fw" aria-hidden="true"></i>
                  </span>
                </span>
              </button>
            </div>
            <nav class="pf-v6-c-pagination__nav" aria-label="Pagination">
              <div class="pf-v6-c-pagination__nav-control pf-m-first">
                <button
                  class="pf-v6-c-button pf-m-plain"
                  type="button"
                  disabled
                  aria-label="Go to first page"
                >
                  <span class="pf-v6-c-button__icon">
                    <i class="fas fa-angle-double-left" aria-hidden="true"></i>
                  </span>
                </button>
              </div>
              <div class="pf-v6-c-pagination__nav-control pf-m-prev">
                <button
                  class="pf-v6-c-button pf-m-plain"
                  type="button"
                  disabled
                  aria-label="Go to previous page"
                >
                  <span class="pf-v6-c-button__icon">
                    <i class="fas fa-angle-left" aria-hidden="true"></i>
                  </span>
                </button>
              </div>
              <div class="pf-v6-c-pagination__nav-page-select">
                <span class="pf-v6-c-form-control">
                  <input
                    aria-label="Current page"
                    type="number"
                    min="1"
                    max="4"
                    value="1"
                  />
                </span>
                <span aria-hidden="true">of 4</span>
              </div>
              <div class="pf-v6-c-pagination__nav-control pf-m-next">
                <button
                  class="pf-v6-c-button pf-m-plain"
                  type="button"
                  aria-label="Go to next page"
                >
                  <span class="pf-v6-c-button__icon">
                    <i class="fas fa-angle-right" aria-hidden="true"></i>
                  </span>
                </button>
              </div>
              <div class="pf-v6-c-pagination__nav-control pf-m-last">
                <button
                  class="pf-v6-c-button pf-m-plain"
                  type="button"
                  disabled
                  aria-label="Go to last page"
                >
                  <span class="pf-v6-c-button__icon">
                    <i class="fas fa-angle-double-right" aria-hidden="true"></i>
                  </span>
                </button>
              </div>
            </nav>
          </div>
        </div>
      </section>
    </main>
  </div>
</div>

```

### Actionable

```html isFullscreen
<div class="pf-v6-c-page" id="data-list-actionable-example">
  <div class="pf-v6-c-skip-to-content">
    <a
      class="pf-v6-c-button pf-m-primary"
      href="#main-content-data-list-actionable-example"
    >
      <span class="pf-v6-c-button__text">Skip to content</span>
    </a>
  </div>
  <header class="pf-v6-c-masthead" id="data-list-actionable-example-masthead">
    <div class="pf-v6-c-masthead__main">
      <span class="pf-v6-c-masthead__toggle">
        <button
          class="pf-v6-c-button pf-m-plain"
          type="button"
          aria-label="Global navigation"
        >
          <span class="pf-v6-c-button__icon">
            <i class="fas fa-bars" aria-hidden="true"></i>
          </span>
        </button>
      </span>
      <div class="pf-v6-c-masthead__brand">
        <a class="pf-v6-c-masthead__logo" href="#">
          <svg
            height="37px"
            xmlns="http://www.w3.org/2000/svg"
            viewBox="0 0 40 40"
          >
            <path
              fill="var(--pf-t--global--text--color--regular)"
              fill-rule="evenodd"
              d="M37.03 25.32c.57 0 1.47.66 1.47 2.26 0 1.58-.65 3.38-.8 3.77C35.32 37.03 29.7 40.2 23 40c-6.24-.19-11.57-3.5-13.9-8.9a6.13 6.13 0 0 1-3.97-1.6 5.9 5.9 0 0 1-2.02-3.78 6.5 6.5 0 0 1 .37-2.99l-1.31-1.11C-3.83 16.52 14.92-4.42 20.9.84l2.04 2.01 1.12-.47c5.26-2.2 9.52-1.14 9.53 2.36 0 1.81-1.15 3.93-3 5.85.67.62 1.2 1.6 1.52 2.7.25.83.3 1.67.32 2.2l.07 2.5.74.2c1.42.4 2.42.93 2.91 1.45.5.52.73 1.02.82 1.6a3.1 3.1 0 0 1-.55 2.26s.16.35.32.85l.28.97zm-14.56 2.63zm14.63.16c.15-.95-.06-1.31-.35-1.49-.3-.19-.66-.12-.66-.12s-.17-1.13-.63-2.16a13.83 13.83 0 0 1-4.53 2.26c-1.56.45-3.68.8-6.04.65-1.31-.1-2.18-.49-2.5.58 2.99 1.1 6.16.63 6.16.63.06 0 .11.04.12.1 0 .05-.02.1-.07.12 0 0-2.43 1.13-6.3-.07.1.91.99 1.32 1.41 1.49.53.2 1.12.3 1.12.3 4.79.83 9.27-1.92 10.28-2.62.07-.05.12 0 .06.1l-.1.13c-1.23 1.6-4.55 3.46-8.87 3.46-1.88 0-3.76-.67-4.45-1.7-1.08-1.58-.06-3.9 1.73-3.66l.78.09a16.3 16.3 0 0 0 8.13-1.31c2.44-1.14 3.36-2.4 3.22-3.4a1.46 1.46 0 0 0-.42-.83 5.25 5.25 0 0 0-2.3-1.1c-.39-.1-.65-.18-.93-.27-.5-.17-.76-.3-.81-1.25l-.13-2.47c-.04-1.05-.17-2.48-1.05-3.07a1.48 1.48 0 0 0-.76-.25c-.26 0-.4.04-.45.05-.5.08-.8.35-1.18.67A4.04 4.04 0 0 1 24.51 14c-.62-.03-1.28-.13-2.03-.17l-.44-.03c-1.73-.08-3.6 1.42-3.9 3.56-.44 2.98 1.7 4.52 2.33 5.43.08.1.17.26.17.4 0 .17-.11.31-.22.43a7.66 7.66 0 0 0-1.36 8.03c1.57 3.68 6.43 5.4 11.18 3.84.63-.21 1.23-.47 1.8-.77 1.07-.52 2-1.24 2.76-2.07a8.27 8.27 0 0 0 2.3-4.54zm-7.9-9.2a3.23 3.23 0 0 1-.52-1.28c-.2-.96-.18-1.65.37-1.74.56-.09.82.49 1.02 1.44.14.64.11 1.23-.04 1.57a3.2 3.2 0 0 0-.82 0zm-4.74.75c-.4-.18-.91-.37-1.53-.34-.88.06-1.65.45-1.87.42-.09-.01-.13-.05-.14-.1-.04-.17.22-.44.48-.63.8-.58 1.84-.71 2.72-.33.42.18.82.5 1.02.83.1.15.11.27.05.33-.1.1-.34-.01-.73-.18zm-.8.45c.71-.08 1.23.25 1.35.45.05.08.03.14.02.16-.06.1-.18.08-.44.05a3.27 3.27 0 0 0-1.66.17s-.26.1-.38.1a.12.12 0 0 1-.12-.12c0-.1.1-.26.25-.4.18-.16.46-.33.98-.4zm3.94 1.68c-.35-.17-.53-.52-.4-.78.12-.26.5-.32.86-.15.35.17.53.52.4.78-.12.25-.5.32-.86.15zm2.25-1.98c.29 0 .51.33.5.72 0 .4-.23.7-.52.7-.28 0-.5-.32-.5-.72 0-.39.24-.7.52-.7zm-14.77-8.58c-.06.06.02.15.09.1A15.1 15.1 0 0 1 27.1 8.94c.07.02.12-.11.05-.15-1-.57-2.54-.95-3.63-.96-.06 0-.09-.06-.05-.1.19-.26.44-.51.68-.7.05-.04.02-.12-.05-.12-1.55.1-3.32.84-4.34 1.54-.05.04-.12 0-.1-.07.07-.38.32-.89.45-1.13.04-.05-.03-.11-.08-.08a17.67 17.67 0 0 0-4.95 4.06zm-7.72 8.2c1.71-4.61 4.57-8.87 8.35-11.8 2.81-2.35 5.84-4.04 5.84-4.04s-1.63-1.9-2.12-2.04C16.4.73 9.85 5.26 5.67 11.25c-1.69 2.43-4.1 6.73-2.95 8.94.14.27.95.97 1.38 1.34a5.15 5.15 0 0 1 3.26-2.1zm2.26 10.14c2.19-.37 2.76-2.76 2.4-5.1-.4-2.66-2.2-3.6-3.4-3.66-.34-.02-.65.01-.9.06-2.17.44-3.39 2.29-3.15 4.7.22 2.16 2.4 4 4.43 4.05.2 0 .41-.01.62-.05zm.83-2.72c.1-.03.22-.06.3.03.02.03.06.1.01.21-.08.19-.4.44-.85.43-.47-.04-1-.38-1.06-1.23-.04-.42.12-.94.22-1.2a1.12 1.12 0 0 0-1.3-1.52c-.3.07-.54.24-.7.5a2.64 2.64 0 0 0-.3.7c-.1.27-.25.35-.36.33-.05 0-.12-.04-.17-.16-.12-.34-.02-1.29.61-1.98a1.9 1.9 0 0 1 1.63-.6c.63.09 1.16.47 1.48 1.09.43.82.05 1.68-.18 2.2l-.06.15c-.15.34-.16.64-.03.84.1.15.28.24.49.24.1 0 .19-.02.27-.03z"
            />
          </svg>
        </a>
      </div>
    </div>
    <div class="pf-v6-c-masthead__content">
      <div
        class="pf-v6-c-toolbar pf-m-static"
        id="data-list-actionable-example-masthead-toolbar"
      >
        <div class="pf-v6-c-toolbar__content">
          <div class="pf-v6-c-toolbar__content-section">
            <div
              class="pf-v6-c-toolbar__group pf-m-align-end pf-m-spacer-none pf-m-spacer-md-on-md pf-m-action-group-plain"
            >
              <div
                class="pf-v6-c-toolbar__group pf-m-hidden pf-m-visible-on-lg pf-m-action-group-plain"
              >
                <div class="pf-v6-c-toolbar__item">
                  <button
                    class="pf-v6-c-menu-toggle pf-m-plain"
                    type="button"
                    aria-expanded="false"
                    aria-label="Application launcher"
                  >
                    <span class="pf-v6-c-menu-toggle__icon">
                      <i class="fas fa-th" aria-hidden="true"></i>
                    </span>
                  </button>
                </div>
                <div class="pf-v6-c-toolbar__item">
                  <button
                    class="pf-v6-c-menu-toggle pf-m-plain"
                    type="button"
                    aria-expanded="false"
                    aria-label="Settings"
                  >
                    <span class="pf-v6-c-menu-toggle__icon">
                      <i class="fas fa-cog" aria-hidden="true"></i>
                    </span>
                  </button>
                </div>
                <div class="pf-v6-c-toolbar__item">
                  <button
                    class="pf-v6-c-menu-toggle pf-m-plain"
                    type="button"
                    aria-expanded="false"
                    aria-label="Help"
                  >
                    <span class="pf-v6-c-menu-toggle__icon">
                      <i class="fas fa-question-circle" aria-hidden="true"></i>
                    </span>
                  </button>
                </div>
              </div>

              <div class="pf-v6-c-toolbar__item pf-m-hidden-on-lg">
                <button
                  class="pf-v6-c-menu-toggle pf-m-plain"
                  type="button"
                  aria-expanded="false"
                  aria-label="Actions"
                >
                  <span class="pf-v6-c-menu-toggle__icon">
                    <i class="fas fa-ellipsis-v" aria-hidden="true"></i>
                  </span>
                </button>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </header>
  <div class="pf-v6-c-page__sidebar">
    <div class="pf-v6-c-page__sidebar-body">
      <nav
        class="pf-v6-c-nav"
        id="data-list-actionable-example-primary-nav"
        aria-label="Global"
      >
        <ul class="pf-v6-c-nav__list" role="list">
          <li class="pf-v6-c-nav__item">
            <a href="#" class="pf-v6-c-nav__link">
              <span class="pf-v6-c-nav__link-text">System panel</span>
            </a>
          </li>
          <li class="pf-v6-c-nav__item">
            <a
              href="#"
              class="pf-v6-c-nav__link pf-m-current"
              aria-current="page"
            >
              <span class="pf-v6-c-nav__link-text">Policy</span>
            </a>
          </li>
          <li class="pf-v6-c-nav__item">
            <a href="#" class="pf-v6-c-nav__link">
              <span class="pf-v6-c-nav__link-text">Authentication</span>
            </a>
          </li>
          <li class="pf-v6-c-nav__item">
            <a href="#" class="pf-v6-c-nav__link">
              <span class="pf-v6-c-nav__link-text">Network services</span>
            </a>
          </li>
          <li class="pf-v6-c-nav__item">
            <a href="#" class="pf-v6-c-nav__link">
              <span class="pf-v6-c-nav__link-text">Server</span>
            </a>
          </li>
        </ul>
      </nav>
    </div>
  </div>
  <div class="pf-v6-c-page__main-container" tabindex="-1">
    <main
      class="pf-v6-c-page__main"
      tabindex="-1"
      id="main-content-data-list-actionable-example"
    >
      <section class="pf-v6-c-page__main-breadcrumb pf-m-limit-width">
        <div class="pf-v6-c-page__main-body">
          <nav class="pf-v6-c-breadcrumb" aria-label="breadcrumb">
            <ol class="pf-v6-c-breadcrumb__list" role="list">
              <li class="pf-v6-c-breadcrumb__item">
                <a href="#" class="pf-v6-c-breadcrumb__link">Section home</a>
              </li>
              <li class="pf-v6-c-breadcrumb__item">
                <span class="pf-v6-c-breadcrumb__item-divider">
                  <i class="fas fa-angle-right" aria-hidden="true"></i>
                </span>

                <a href="#" class="pf-v6-c-breadcrumb__link">Section title</a>
              </li>
              <li class="pf-v6-c-breadcrumb__item">
                <span class="pf-v6-c-breadcrumb__item-divider">
                  <i class="fas fa-angle-right" aria-hidden="true"></i>
                </span>

                <a href="#" class="pf-v6-c-breadcrumb__link">Section title</a>
              </li>
              <li class="pf-v6-c-breadcrumb__item">
                <span class="pf-v6-c-breadcrumb__item-divider">
                  <i class="fas fa-angle-right" aria-hidden="true"></i>
                </span>

                <a
                  href="#"
                  class="pf-v6-c-breadcrumb__link pf-m-current"
                  aria-current="page"
                >Section landing</a>
              </li>
            </ol>
          </nav>
        </div>
      </section>
      <section class="pf-v6-c-page__main-section pf-m-limit-width">
        <div class="pf-v6-c-page__main-body">
          <h1 class="pf-v6-c-content--h1 pf-m-page-title">Main title</h1>
          <p class="pf-v6-c-content--p">This is a full page demo.</p>
        </div>
      </section>
      <section class="pf-v6-c-page__main-section">
        <div class="pf-v6-c-page__main-body">
          <div
            class="pf-v6-c-toolbar"
            id="data-list-actionable-example-toolbar"
          >
            <div class="pf-v6-c-toolbar__content">
              <div class="pf-v6-c-toolbar__content-section pf-m-nowrap">
                <div
                  class="pf-v6-c-toolbar__group pf-m-show-on-xl pf-m-toggle-group"
                >
                  <div class="pf-v6-c-toolbar__toggle">
                    <button
                      class="pf-v6-c-menu-toggle pf-m-plain"
                      type="button"
                      aria-expanded="false"
                      aria-label="Show filters"
                      aria-controls="data-list-actionable-example-toolbar-expandable-content"
                    >
                      <span class="pf-v6-c-menu-toggle__icon">
                        <i class="fas fa-filter" aria-hidden="true"></i>
                      </span>
                    </button>
                  </div>
                  <div class="pf-v6-c-toolbar__item pf-m-bulk-select">
                    <div
                      class="pf-v6-c-menu-toggle pf-m-split-button"
                      id="data-list-actionable-example-toolbar-check"
                    >
                      <label
                        class="pf-v6-c-check pf-m-standalone"
                        for="data-list-actionable-example-toolbar-check-check-input"
                      >
                        <input
                          class="pf-v6-c-check__input"
                          type="checkbox"
                          id="data-list-actionable-example-toolbar-check-check-input"
                          name="data-list-actionable-example-toolbar-check-check-input"
                          aria-label="Standalone check"
                        />
                      </label>
                      <button
                        class="pf-v6-c-menu-toggle__button"
                        type="button"
                        aria-expanded="false"
                        id="data-list-actionable-example-toolbar-menu-toggle-toggle-button"
                        aria-label="Menu toggle"
                      >
                        <span class="pf-v6-c-menu-toggle__controls">
                          <span class="pf-v6-c-menu-toggle__toggle-icon">
                            <i
                              class="fas fa-caret-down fa-fw"
                              aria-hidden="true"
                            ></i>
                          </span>
                        </span>
                      </button>
                    </div>
                  </div>
                </div>

                <div
                  class="pf-v6-c-overflow-menu"
                  id="data-list-actionable-example-toolbar-overflow-menu"
                >
                  <div
                    class="pf-v6-c-overflow-menu__content pf-v6-u-display-none pf-v6-u-display-flex-on-lg"
                  >
                    <div class="pf-v6-c-overflow-menu__group pf-m-button-group">
                      <div class="pf-v6-c-overflow-menu__item">
                        <button
                          class="pf-v6-c-button pf-m-primary"
                          type="button"
                        >
                          <span class="pf-v6-c-button__text">Create instance</span>
                        </button>
                      </div>

                      <div class="pf-v6-c-overflow-menu__item">
                        <button
                          class="pf-v6-c-button pf-m-secondary"
                          type="button"
                        >
                          <span class="pf-v6-c-button__text">Action</span>
                        </button>
                      </div>
                    </div>
                  </div>
                  <div class="pf-v6-c-overflow-menu__control">
                    <button
                      class="pf-v6-c-menu-toggle pf-m-plain"
                      type="button"
                      aria-expanded="false"
                      aria-label="Menu toggle"
                      id="data-list-actionable-example-toolbar-overflow-menu-toggle"
                    >
                      <span class="pf-v6-c-menu-toggle__icon">
                        <i class="fas fa-ellipsis-v" aria-hidden="true"></i>
                      </span>
                    </button>
                  </div>
                </div>

                <div class="pf-v6-c-toolbar__item pf-m-pagination">
                  <div class="pf-v6-c-pagination pf-m-compact">
                    <div class="pf-v6-c-pagination__page-menu">
                      <button
                        class="pf-v6-c-menu-toggle pf-m-plain pf-m-text"
                        type="button"
                        aria-expanded="false"
                        aria-label="Menu toggle"
                        id="data-list-actionable-example-toolbar-top-pagination"
                      >
                        <span class="pf-v6-c-menu-toggle__text">
                          <b>1 - 10</b>&nbsp;of&nbsp;
                          <b>36</b>
                        </span>
                        <span class="pf-v6-c-menu-toggle__controls">
                          <span class="pf-v6-c-menu-toggle__toggle-icon">
                            <i
                              class="fas fa-caret-down fa-fw"
                              aria-hidden="true"
                            ></i>
                          </span>
                        </span>
                      </button>
                    </div>
                    <nav
                      class="pf-v6-c-pagination__nav"
                      aria-label="Toolbar top pagination"
                    >
                      <div class="pf-v6-c-pagination__nav-control pf-m-prev">
                        <button
                          class="pf-v6-c-button pf-m-plain"
                          type="button"
                          disabled
                          aria-label="Go to previous page"
                        >
                          <span class="pf-v6-c-button__icon">
                            <i class="fas fa-angle-left" aria-hidden="true"></i>
                          </span>
                        </button>
                      </div>
                      <div class="pf-v6-c-pagination__nav-control pf-m-next">
                        <button
                          class="pf-v6-c-button pf-m-plain"
                          type="button"
                          aria-label="Go to next page"
                        >
                          <span class="pf-v6-c-button__icon">
                            <i class="fas fa-angle-right" aria-hidden="true"></i>
                          </span>
                        </button>
                      </div>
                    </nav>
                  </div>
                </div>
              </div>

              <div
                class="pf-v6-c-toolbar__expandable-content pf-m-hidden"
                id="data-list-actionable-example-toolbar-expandable-content"
                hidden
              ></div>
            </div>
          </div>
          <ul
            class="pf-v6-c-data-list"
            role="list"
            aria-label="Data list actionable demo"
            id="data-list-actionable-example-data-list"
          >
            <li
              class="pf-v6-c-data-list__item"
              aria-labelledby="data-list-actionable-example-data-list-item-1"
            >
              <div class="pf-v6-c-data-list__item-row">
                <div class="pf-v6-c-data-list__item-control">
                  <div class="pf-v6-c-data-list__check">
                    <label
                      class="pf-v6-c-check pf-m-standalone"
                      for="data-list-actionable-example-data-list-item-1&quot;type&#x3D;&quot;checkbox&quot; name&#x3D;&quot;check-action-check1&quot; aria-labelledby&#x3D;&quot;data-list-actionable-example-data-list-item-1&quot;-input"
                    >
                      <input
                        class="pf-v6-c-check__input"
                        type="checkbox"
                        id="data-list-actionable-example-data-list-item-1&quot;type&#x3D;&quot;checkbox&quot; name&#x3D;&quot;check-action-check1&quot; aria-labelledby&#x3D;&quot;data-list-actionable-example-data-list-item-1&quot;-input"
                        name="data-list-actionable-example-data-list-item-1&quot;type&#x3D;&quot;checkbox&quot; name&#x3D;&quot;check-action-check1&quot; aria-labelledby&#x3D;&quot;data-list-actionable-example-data-list-item-1&quot;-input"
                        aria-label="Standalone check"
                      />
                    </label>
                  </div>
                </div>
                <div class="pf-v6-c-data-list__item-content">
                  <div class="pf-v6-c-data-list__cell pf-m-align-left">
                    <div class="pf-v6-l-flex pf-m-column pf-m-space-items-md">
                      <div
                        class="pf-v6-l-flex pf-m-column pf-m-space-items-none"
                      >
                        <div class="pf-v6-l-flex__item">
                          <p
                            id="data-list-actionable-example-data-list-item-1"
                          >patternfly</p>
                        </div>
                        <div class="pf-v6-l-flex__item">
                          <small>
                            Working repo for PatternFly 4
                            <a href>https://pf4.patternfly.org/</a>
                          </small>
                        </div>
                      </div>
                      <div class="pf-v6-l-flex pf-m-wrap">
                        <div class="pf-v6-l-flex pf-m-space-items-xs">
                          <div class="pf-v6-l-flex__item">
                            <i class="fas fa-code-branch" aria-hidden="true"></i>
                          </div>
                          <div class="pf-v6-l-flex__item">
                            <span>10</span>
                          </div>
                        </div>
                        <div class="pf-v6-l-flex pf-m-space-items-xs">
                          <div class="pf-v6-l-flex__item">
                            <i class="fas fa-code" aria-hidden="true"></i>
                          </div>
                          <div class="pf-v6-l-flex__item">
                            <span>4</span>
                          </div>
                        </div>
                        <div class="pf-v6-l-flex pf-m-space-items-xs">
                          <div class="pf-v6-l-flex__item">
                            <i class="fas fa-cube" aria-hidden="true"></i>
                          </div>
                          <div class="pf-v6-l-flex__item">
                            <span>5</span>
                          </div>
                        </div>
                        <div class="pf-v6-l-flex__item">Updated 2 days ago</div>
                      </div>
                    </div>
                  </div>
                  <div
                    class="pf-v6-c-data-list__cell pf-m-align-right pf-m-no-fill"
                  >
                    <button class="pf-v6-c-button pf-m-secondary" type="button">
                      <span class="pf-v6-c-button__text">Action</span>
                    </button>
                    <button class="pf-v6-c-button pf-m-link" type="button">
                      <span class="pf-v6-c-button__text">Link</span>
                    </button>
                  </div>
                </div>
              </div>
            </li>

            <li
              class="pf-v6-c-data-list__item"
              aria-labelledby="data-list-actionable-example-data-list-item-2"
            >
              <div class="pf-v6-c-data-list__item-row">
                <div class="pf-v6-c-data-list__item-control">
                  <div class="pf-v6-c-data-list__check">
                    <label
                      class="pf-v6-c-check pf-m-standalone"
                      for="data-list-actionable-example-data-list-item-2&quot;type&#x3D;&quot;checkbox&quot; name&#x3D;&quot;check-action-check2&quot; aria-labelledby&#x3D;&quot;data-list-actionable-example-data-list-item-2&quot;-input"
                    >
                      <input
                        class="pf-v6-c-check__input"
                        type="checkbox"
                        id="data-list-actionable-example-data-list-item-2&quot;type&#x3D;&quot;checkbox&quot; name&#x3D;&quot;check-action-check2&quot; aria-labelledby&#x3D;&quot;data-list-actionable-example-data-list-item-2&quot;-input"
                        name="data-list-actionable-example-data-list-item-2&quot;type&#x3D;&quot;checkbox&quot; name&#x3D;&quot;check-action-check2&quot; aria-labelledby&#x3D;&quot;data-list-actionable-example-data-list-item-2&quot;-input"
                        aria-label="Standalone check"
                      />
                    </label>
                  </div>
                </div>
                <div class="pf-v6-c-data-list__item-content">
                  <div class="pf-v6-c-data-list__cell pf-m-align-left">
                    <div class="pf-v6-l-flex pf-m-column pf-m-space-items-md">
                      <div
                        class="pf-v6-l-flex pf-m-column pf-m-space-items-none"
                      >
                        <div class="pf-v6-l-flex__item">
                          <p
                            id="data-list-actionable-example-data-list-item-2"
                          >patternfly-elements</p>
                        </div>
                        <div class="pf-v6-l-flex__item">
                          <small>PatternFly elements</small>
                        </div>
                      </div>
                      <div class="pf-v6-l-flex pf-m-wrap">
                        <div class="pf-v6-l-flex pf-m-space-items-xs">
                          <div class="pf-v6-l-flex__item">
                            <i class="fas fa-code-branch" aria-hidden="true"></i>
                          </div>
                          <div class="pf-v6-l-flex__item">
                            <span>5</span>
                          </div>
                        </div>
                        <div class="pf-v6-l-flex pf-m-space-items-xs">
                          <div class="pf-v6-l-flex__item">
                            <i class="fas fa-code" aria-hidden="true"></i>
                          </div>
                          <div class="pf-v6-l-flex__item">
                            <span>9</span>
                          </div>
                        </div>
                        <div class="pf-v6-l-flex pf-m-space-items-xs">
                          <div class="pf-v6-l-flex__item">
                            <i class="fas fa-cube" aria-hidden="true"></i>
                          </div>
                          <div class="pf-v6-l-flex__item">
                            <span>2</span>
                          </div>
                        </div>
                        <div class="pf-v6-l-flex pf-m-space-items-xs">
                          <div class="pf-v6-l-flex__item">
                            <i class="fas fa-check-circle" aria-hidden="true"></i>
                          </div>
                          <div class="pf-v6-l-flex__item">
                            <span>11</span>
                          </div>
                        </div>
                        <div class="pf-v6-l-flex pf-m-space-items-xs">
                          <div class="pf-v6-l-flex__item">
                            <i
                              class="fas fa-exclamation-triangle"
                              aria-hidden="true"
                            ></i>
                          </div>
                          <div class="pf-v6-l-flex__item">
                            <span>4</span>
                          </div>
                        </div>
                        <div class="pf-v6-l-flex pf-m-space-items-xs">
                          <div class="pf-v6-l-flex__item">
                            <i class="fas fa-times-circle" aria-hidden="true"></i>
                          </div>
                          <div class="pf-v6-l-flex__item">
                            <span>1</span>
                          </div>
                        </div>
                        <div class="pf-v6-l-flex__item">Updated 2 days ago</div>
                      </div>
                    </div>
                  </div>
                  <div
                    class="pf-v6-c-data-list__cell pf-m-align-right pf-m-no-fill"
                  >
                    <button class="pf-v6-c-button pf-m-secondary" type="button">
                      <span class="pf-v6-c-button__text">Action</span>
                    </button>
                    <button class="pf-v6-c-button pf-m-link" type="button">
                      <span class="pf-v6-c-button__text">Link</span>
                    </button>
                  </div>
                </div>
              </div>
            </li>

            <li
              class="pf-v6-c-data-list__item"
              aria-labelledby="data-list-actionable-example-data-list-item-3"
            >
              <div class="pf-v6-c-data-list__item-row">
                <div class="pf-v6-c-data-list__item-control">
                  <div class="pf-v6-c-data-list__check">
                    <label
                      class="pf-v6-c-check pf-m-standalone"
                      for="data-list-actionable-example-data-list-item-3&quot;type&#x3D;&quot;checkbox&quot; name&#x3D;&quot;check-action-check3&quot; aria-labelledby&#x3D;&quot;data-list-actionable-example-data-list-item-3&quot;-input"
                    >
                      <input
                        class="pf-v6-c-check__input"
                        type="checkbox"
                        id="data-list-actionable-example-data-list-item-3&quot;type&#x3D;&quot;checkbox&quot; name&#x3D;&quot;check-action-check3&quot; aria-labelledby&#x3D;&quot;data-list-actionable-example-data-list-item-3&quot;-input"
                        name="data-list-actionable-example-data-list-item-3&quot;type&#x3D;&quot;checkbox&quot; name&#x3D;&quot;check-action-check3&quot; aria-labelledby&#x3D;&quot;data-list-actionable-example-data-list-item-3&quot;-input"
                        aria-label="Standalone check"
                      />
                    </label>
                  </div>
                </div>
                <div class="pf-v6-c-data-list__item-content">
                  <div
                    class="pf-v6-c-data-list__cell pf-m-align-left pf-m-flex-2"
                  >
                    <p
                      id="data-list-actionable-example-data-list-item-3"
                    >patternfly-unified-design-kit</p>
                  </div>
                  <div
                    class="pf-v6-c-data-list__cell pf-m-align-right pf-m-no-fill"
                  >
                    <button class="pf-v6-c-button pf-m-secondary" type="button">
                      <span class="pf-v6-c-button__text">Action</span>
                    </button>
                    <button class="pf-v6-c-button pf-m-link" type="button">
                      <span class="pf-v6-c-button__text">Link</span>
                    </button>
                  </div>
                </div>
              </div>
            </li>

            <li
              class="pf-v6-c-data-list__item"
              aria-labelledby="data-list-actionable-example-data-list-item-4"
            >
              <div class="pf-v6-c-data-list__item-row">
                <div class="pf-v6-c-data-list__item-control">
                  <div class="pf-v6-c-data-list__check">
                    <label
                      class="pf-v6-c-check pf-m-standalone"
                      for="data-list-actionable-example-data-list-item-4&quot;type&#x3D;&quot;checkbox&quot; name&#x3D;&quot;check-action-check4&quot; aria-labelledby&#x3D;&quot;data-list-actionable-example-data-list-item-4&quot;-input"
                    >
                      <input
                        class="pf-v6-c-check__input"
                        type="checkbox"
                        id="data-list-actionable-example-data-list-item-4&quot;type&#x3D;&quot;checkbox&quot; name&#x3D;&quot;check-action-check4&quot; aria-labelledby&#x3D;&quot;data-list-actionable-example-data-list-item-4&quot;-input"
                        name="data-list-actionable-example-data-list-item-4&quot;type&#x3D;&quot;checkbox&quot; name&#x3D;&quot;check-action-check4&quot; aria-labelledby&#x3D;&quot;data-list-actionable-example-data-list-item-4&quot;-input"
                        aria-label="Standalone check"
                      />
                    </label>
                  </div>
                </div>
                <div class="pf-v6-c-data-list__item-content">
                  <div
                    class="pf-v6-c-data-list__cell pf-m-align-left pf-m-flex-2"
                  >
                    <div class="pf-v6-l-flex pf-m-column pf-m-space-items-md">
                      <div
                        class="pf-v6-l-flex pf-m-column pf-m-space-items-none"
                      >
                        <div class="pf-v6-l-flex__item">
                          <p
                            id="data-list-actionable-example-data-list-item-4"
                          >patternfly</p>
                        </div>
                        <div class="pf-v6-l-flex__item">
                          <small>
                            Working repo for PatternFly 4
                            <a href>https://pf4.patternfly.org/</a>
                          </small>
                        </div>
                      </div>
                      <div class="pf-v6-l-flex pf-m-wrap">
                        <div class="pf-v6-l-flex pf-m-space-items-xs">
                          <div class="pf-v6-l-flex__item">
                            <i class="fas fa-code-branch" aria-hidden="true"></i>
                          </div>
                          <div class="pf-v6-l-flex__item">
                            <span>10</span>
                          </div>
                        </div>
                        <div class="pf-v6-l-flex pf-m-space-items-xs">
                          <div class="pf-v6-l-flex__item">
                            <i class="fas fa-code" aria-hidden="true"></i>
                          </div>
                          <div class="pf-v6-l-flex__item">
                            <span>4</span>
                          </div>
                        </div>
                        <div class="pf-v6-l-flex pf-m-space-items-xs">
                          <div class="pf-v6-l-flex__item">
                            <i class="fas fa-cube" aria-hidden="true"></i>
                          </div>
                          <div class="pf-v6-l-flex__item">
                            <span>5</span>
                          </div>
                        </div>
                        <div class="pf-v6-l-flex__item">Updated 2 days ago</div>
                      </div>
                    </div>
                  </div>
                  <div
                    class="pf-v6-c-data-list__cell pf-m-align-right pf-m-no-fill"
                  >
                    <button class="pf-v6-c-button pf-m-secondary" type="button">
                      <span class="pf-v6-c-button__text">Action</span>
                    </button>
                    <button class="pf-v6-c-button pf-m-link" type="button">
                      <span class="pf-v6-c-button__text">Link</span>
                    </button>
                  </div>
                </div>
              </div>
            </li>
          </ul>
          <div class="pf-v6-c-pagination pf-m-bottom">
            <div class="pf-v6-c-pagination__page-menu">
              <button
                class="pf-v6-c-menu-toggle pf-m-plain pf-m-text pf-m-top"
                type="button"
                aria-expanded="false"
                aria-label="Menu toggle"
                id="{{page--id}}-pagination-menu-toggle-bottom-example"
              >
                <span class="pf-v6-c-menu-toggle__text">
                  <b>1 - 10</b>&nbsp;of&nbsp;
                  <b>36</b>
                </span>
                <span class="pf-v6-c-menu-toggle__controls">
                  <span class="pf-v6-c-menu-toggle__toggle-icon">
                    <i class="fas fa-caret-down fa-fw" aria-hidden="true"></i>
                  </span>
                </span>
              </button>
            </div>
            <nav class="pf-v6-c-pagination__nav" aria-label="Pagination">
              <div class="pf-v6-c-pagination__nav-control pf-m-first">
                <button
                  class="pf-v6-c-button pf-m-plain"
                  type="button"
                  disabled
                  aria-label="Go to first page"
                >
                  <span class="pf-v6-c-button__icon">
                    <i class="fas fa-angle-double-left" aria-hidden="true"></i>
                  </span>
                </button>
              </div>
              <div class="pf-v6-c-pagination__nav-control pf-m-prev">
                <button
                  class="pf-v6-c-button pf-m-plain"
                  type="button"
                  disabled
                  aria-label="Go to previous page"
                >
                  <span class="pf-v6-c-button__icon">
                    <i class="fas fa-angle-left" aria-hidden="true"></i>
                  </span>
                </button>
              </div>
              <div class="pf-v6-c-pagination__nav-page-select">
                <span class="pf-v6-c-form-control">
                  <input
                    aria-label="Current page"
                    type="number"
                    min="1"
                    max="4"
                    value="1"
                  />
                </span>
                <span aria-hidden="true">of 4</span>
              </div>
              <div class="pf-v6-c-pagination__nav-control pf-m-next">
                <button
                  class="pf-v6-c-button pf-m-plain"
                  type="button"
                  aria-label="Go to next page"
                >
                  <span class="pf-v6-c-button__icon">
                    <i class="fas fa-angle-right" aria-hidden="true"></i>
                  </span>
                </button>
              </div>
              <div class="pf-v6-c-pagination__nav-control pf-m-last">
                <button
                  class="pf-v6-c-button pf-m-plain"
                  type="button"
                  disabled
                  aria-label="Go to last page"
                >
                  <span class="pf-v6-c-button__icon">
                    <i class="fas fa-angle-double-right" aria-hidden="true"></i>
                  </span>
                </button>
              </div>
            </nav>
          </div>
        </div>
      </section>
    </main>
  </div>
</div>

```

### Expandable demo

```html isFullscreen
<div class="pf-v6-c-page" id="data-list-expandable-example">
  <div class="pf-v6-c-skip-to-content">
    <a
      class="pf-v6-c-button pf-m-primary"
      href="#main-content-data-list-expandable-example"
    >
      <span class="pf-v6-c-button__text">Skip to content</span>
    </a>
  </div>
  <header class="pf-v6-c-masthead" id="data-list-expandable-example-masthead">
    <div class="pf-v6-c-masthead__main">
      <span class="pf-v6-c-masthead__toggle">
        <button
          class="pf-v6-c-button pf-m-plain"
          type="button"
          aria-label="Global navigation"
        >
          <span class="pf-v6-c-button__icon">
            <i class="fas fa-bars" aria-hidden="true"></i>
          </span>
        </button>
      </span>
      <div class="pf-v6-c-masthead__brand">
        <a class="pf-v6-c-masthead__logo" href="#">
          <svg
            height="37px"
            xmlns="http://www.w3.org/2000/svg"
            viewBox="0 0 40 40"
          >
            <path
              fill="var(--pf-t--global--text--color--regular)"
              fill-rule="evenodd"
              d="M37.03 25.32c.57 0 1.47.66 1.47 2.26 0 1.58-.65 3.38-.8 3.77C35.32 37.03 29.7 40.2 23 40c-6.24-.19-11.57-3.5-13.9-8.9a6.13 6.13 0 0 1-3.97-1.6 5.9 5.9 0 0 1-2.02-3.78 6.5 6.5 0 0 1 .37-2.99l-1.31-1.11C-3.83 16.52 14.92-4.42 20.9.84l2.04 2.01 1.12-.47c5.26-2.2 9.52-1.14 9.53 2.36 0 1.81-1.15 3.93-3 5.85.67.62 1.2 1.6 1.52 2.7.25.83.3 1.67.32 2.2l.07 2.5.74.2c1.42.4 2.42.93 2.91 1.45.5.52.73 1.02.82 1.6a3.1 3.1 0 0 1-.55 2.26s.16.35.32.85l.28.97zm-14.56 2.63zm14.63.16c.15-.95-.06-1.31-.35-1.49-.3-.19-.66-.12-.66-.12s-.17-1.13-.63-2.16a13.83 13.83 0 0 1-4.53 2.26c-1.56.45-3.68.8-6.04.65-1.31-.1-2.18-.49-2.5.58 2.99 1.1 6.16.63 6.16.63.06 0 .11.04.12.1 0 .05-.02.1-.07.12 0 0-2.43 1.13-6.3-.07.1.91.99 1.32 1.41 1.49.53.2 1.12.3 1.12.3 4.79.83 9.27-1.92 10.28-2.62.07-.05.12 0 .06.1l-.1.13c-1.23 1.6-4.55 3.46-8.87 3.46-1.88 0-3.76-.67-4.45-1.7-1.08-1.58-.06-3.9 1.73-3.66l.78.09a16.3 16.3 0 0 0 8.13-1.31c2.44-1.14 3.36-2.4 3.22-3.4a1.46 1.46 0 0 0-.42-.83 5.25 5.25 0 0 0-2.3-1.1c-.39-.1-.65-.18-.93-.27-.5-.17-.76-.3-.81-1.25l-.13-2.47c-.04-1.05-.17-2.48-1.05-3.07a1.48 1.48 0 0 0-.76-.25c-.26 0-.4.04-.45.05-.5.08-.8.35-1.18.67A4.04 4.04 0 0 1 24.51 14c-.62-.03-1.28-.13-2.03-.17l-.44-.03c-1.73-.08-3.6 1.42-3.9 3.56-.44 2.98 1.7 4.52 2.33 5.43.08.1.17.26.17.4 0 .17-.11.31-.22.43a7.66 7.66 0 0 0-1.36 8.03c1.57 3.68 6.43 5.4 11.18 3.84.63-.21 1.23-.47 1.8-.77 1.07-.52 2-1.24 2.76-2.07a8.27 8.27 0 0 0 2.3-4.54zm-7.9-9.2a3.23 3.23 0 0 1-.52-1.28c-.2-.96-.18-1.65.37-1.74.56-.09.82.49 1.02 1.44.14.64.11 1.23-.04 1.57a3.2 3.2 0 0 0-.82 0zm-4.74.75c-.4-.18-.91-.37-1.53-.34-.88.06-1.65.45-1.87.42-.09-.01-.13-.05-.14-.1-.04-.17.22-.44.48-.63.8-.58 1.84-.71 2.72-.33.42.18.82.5 1.02.83.1.15.11.27.05.33-.1.1-.34-.01-.73-.18zm-.8.45c.71-.08 1.23.25 1.35.45.05.08.03.14.02.16-.06.1-.18.08-.44.05a3.27 3.27 0 0 0-1.66.17s-.26.1-.38.1a.12.12 0 0 1-.12-.12c0-.1.1-.26.25-.4.18-.16.46-.33.98-.4zm3.94 1.68c-.35-.17-.53-.52-.4-.78.12-.26.5-.32.86-.15.35.17.53.52.4.78-.12.25-.5.32-.86.15zm2.25-1.98c.29 0 .51.33.5.72 0 .4-.23.7-.52.7-.28 0-.5-.32-.5-.72 0-.39.24-.7.52-.7zm-14.77-8.58c-.06.06.02.15.09.1A15.1 15.1 0 0 1 27.1 8.94c.07.02.12-.11.05-.15-1-.57-2.54-.95-3.63-.96-.06 0-.09-.06-.05-.1.19-.26.44-.51.68-.7.05-.04.02-.12-.05-.12-1.55.1-3.32.84-4.34 1.54-.05.04-.12 0-.1-.07.07-.38.32-.89.45-1.13.04-.05-.03-.11-.08-.08a17.67 17.67 0 0 0-4.95 4.06zm-7.72 8.2c1.71-4.61 4.57-8.87 8.35-11.8 2.81-2.35 5.84-4.04 5.84-4.04s-1.63-1.9-2.12-2.04C16.4.73 9.85 5.26 5.67 11.25c-1.69 2.43-4.1 6.73-2.95 8.94.14.27.95.97 1.38 1.34a5.15 5.15 0 0 1 3.26-2.1zm2.26 10.14c2.19-.37 2.76-2.76 2.4-5.1-.4-2.66-2.2-3.6-3.4-3.66-.34-.02-.65.01-.9.06-2.17.44-3.39 2.29-3.15 4.7.22 2.16 2.4 4 4.43 4.05.2 0 .41-.01.62-.05zm.83-2.72c.1-.03.22-.06.3.03.02.03.06.1.01.21-.08.19-.4.44-.85.43-.47-.04-1-.38-1.06-1.23-.04-.42.12-.94.22-1.2a1.12 1.12 0 0 0-1.3-1.52c-.3.07-.54.24-.7.5a2.64 2.64 0 0 0-.3.7c-.1.27-.25.35-.36.33-.05 0-.12-.04-.17-.16-.12-.34-.02-1.29.61-1.98a1.9 1.9 0 0 1 1.63-.6c.63.09 1.16.47 1.48 1.09.43.82.05 1.68-.18 2.2l-.06.15c-.15.34-.16.64-.03.84.1.15.28.24.49.24.1 0 .19-.02.27-.03z"
            />
          </svg>
        </a>
      </div>
    </div>
    <div class="pf-v6-c-masthead__content">
      <div
        class="pf-v6-c-toolbar pf-m-static"
        id="data-list-expandable-example-masthead-toolbar"
      >
        <div class="pf-v6-c-toolbar__content">
          <div class="pf-v6-c-toolbar__content-section">
            <div
              class="pf-v6-c-toolbar__group pf-m-align-end pf-m-spacer-none pf-m-spacer-md-on-md pf-m-action-group-plain"
            >
              <div
                class="pf-v6-c-toolbar__group pf-m-hidden pf-m-visible-on-lg pf-m-action-group-plain"
              >
                <div class="pf-v6-c-toolbar__item">
                  <button
                    class="pf-v6-c-menu-toggle pf-m-plain"
                    type="button"
                    aria-expanded="false"
                    aria-label="Application launcher"
                  >
                    <span class="pf-v6-c-menu-toggle__icon">
                      <i class="fas fa-th" aria-hidden="true"></i>
                    </span>
                  </button>
                </div>
                <div class="pf-v6-c-toolbar__item">
                  <button
                    class="pf-v6-c-menu-toggle pf-m-plain"
                    type="button"
                    aria-expanded="false"
                    aria-label="Settings"
                  >
                    <span class="pf-v6-c-menu-toggle__icon">
                      <i class="fas fa-cog" aria-hidden="true"></i>
                    </span>
                  </button>
                </div>
                <div class="pf-v6-c-toolbar__item">
                  <button
                    class="pf-v6-c-menu-toggle pf-m-plain"
                    type="button"
                    aria-expanded="false"
                    aria-label="Help"
                  >
                    <span class="pf-v6-c-menu-toggle__icon">
                      <i class="fas fa-question-circle" aria-hidden="true"></i>
                    </span>
                  </button>
                </div>
              </div>

              <div class="pf-v6-c-toolbar__item pf-m-hidden-on-lg">
                <button
                  class="pf-v6-c-menu-toggle pf-m-plain"
                  type="button"
                  aria-expanded="false"
                  aria-label="Actions"
                >
                  <span class="pf-v6-c-menu-toggle__icon">
                    <i class="fas fa-ellipsis-v" aria-hidden="true"></i>
                  </span>
                </button>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </header>
  <div class="pf-v6-c-page__sidebar">
    <div class="pf-v6-c-page__sidebar-body">
      <nav
        class="pf-v6-c-nav"
        id="data-list-expandable-example-primary-nav"
        aria-label="Global"
      >
        <ul class="pf-v6-c-nav__list" role="list">
          <li class="pf-v6-c-nav__item">
            <a href="#" class="pf-v6-c-nav__link">
              <span class="pf-v6-c-nav__link-text">System panel</span>
            </a>
          </li>
          <li class="pf-v6-c-nav__item">
            <a
              href="#"
              class="pf-v6-c-nav__link pf-m-current"
              aria-current="page"
            >
              <span class="pf-v6-c-nav__link-text">Policy</span>
            </a>
          </li>
          <li class="pf-v6-c-nav__item">
            <a href="#" class="pf-v6-c-nav__link">
              <span class="pf-v6-c-nav__link-text">Authentication</span>
            </a>
          </li>
          <li class="pf-v6-c-nav__item">
            <a href="#" class="pf-v6-c-nav__link">
              <span class="pf-v6-c-nav__link-text">Network services</span>
            </a>
          </li>
          <li class="pf-v6-c-nav__item">
            <a href="#" class="pf-v6-c-nav__link">
              <span class="pf-v6-c-nav__link-text">Server</span>
            </a>
          </li>
        </ul>
      </nav>
    </div>
  </div>
  <div class="pf-v6-c-page__main-container" tabindex="-1">
    <main
      class="pf-v6-c-page__main"
      tabindex="-1"
      id="main-content-data-list-expandable-example"
    >
      <section class="pf-v6-c-page__main-breadcrumb pf-m-limit-width">
        <div class="pf-v6-c-page__main-body">
          <nav class="pf-v6-c-breadcrumb" aria-label="breadcrumb">
            <ol class="pf-v6-c-breadcrumb__list" role="list">
              <li class="pf-v6-c-breadcrumb__item">
                <a href="#" class="pf-v6-c-breadcrumb__link">Section home</a>
              </li>
              <li class="pf-v6-c-breadcrumb__item">
                <span class="pf-v6-c-breadcrumb__item-divider">
                  <i class="fas fa-angle-right" aria-hidden="true"></i>
                </span>

                <a href="#" class="pf-v6-c-breadcrumb__link">Section title</a>
              </li>
              <li class="pf-v6-c-breadcrumb__item">
                <span class="pf-v6-c-breadcrumb__item-divider">
                  <i class="fas fa-angle-right" aria-hidden="true"></i>
                </span>

                <a href="#" class="pf-v6-c-breadcrumb__link">Section title</a>
              </li>
              <li class="pf-v6-c-breadcrumb__item">
                <span class="pf-v6-c-breadcrumb__item-divider">
                  <i class="fas fa-angle-right" aria-hidden="true"></i>
                </span>

                <a
                  href="#"
                  class="pf-v6-c-breadcrumb__link pf-m-current"
                  aria-current="page"
                >Section landing</a>
              </li>
            </ol>
          </nav>
        </div>
      </section>
      <section class="pf-v6-c-page__main-section pf-m-limit-width">
        <div class="pf-v6-c-page__main-body">
          <h1 class="pf-v6-c-content--h1 pf-m-page-title">Main title</h1>
          <p class="pf-v6-c-content--p">This is a full page demo.</p>
        </div>
      </section>
      <section class="pf-v6-c-page__main-section">
        <div class="pf-v6-c-page__main-body">
          <div
            class="pf-v6-c-toolbar"
            id="data-list-expandable-example-toolbar"
          >
            <div class="pf-v6-c-toolbar__content">
              <div class="pf-v6-c-toolbar__content-section pf-m-nowrap">
                <div class="pf-v6-c-toolbar__item pf-m-expand-all">
                  <button
                    class="pf-v6-c-button pf-m-plain"
                    type="button"
                    aria-label="Expand all rows"
                  >
                    <span class="pf-v6-c-button__icon">
                      <span class="pf-v6-c-icon">
                        <span
                          class="pf-v6-c-icon__content pf-v6-m-mirror-inline-rtl"
                        >
                          <span class="pf-v6-c-toolbar__expand-all-icon">
                            <i class="fas fa-angle-right" aria-hidden="true"></i>
                          </span>
                        </span>
                      </span>
                    </span>
                  </button>
                </div>

                <div
                  class="pf-v6-c-toolbar__group pf-m-show-on-xl pf-m-toggle-group"
                >
                  <div class="pf-v6-c-toolbar__toggle">
                    <button
                      class="pf-v6-c-menu-toggle pf-m-plain"
                      type="button"
                      aria-expanded="false"
                      aria-label="Show filters"
                      aria-controls="data-list-expandable-example-toolbar-expandable-content"
                    >
                      <span class="pf-v6-c-menu-toggle__icon">
                        <i class="fas fa-filter" aria-hidden="true"></i>
                      </span>
                    </button>
                  </div>
                  <div class="pf-v6-c-toolbar__item pf-m-bulk-select">
                    <div
                      class="pf-v6-c-menu-toggle pf-m-split-button"
                      id="data-list-expandable-example-toolbar-check"
                    >
                      <label
                        class="pf-v6-c-check pf-m-standalone"
                        for="data-list-expandable-example-toolbar-check-check-input"
                      >
                        <input
                          class="pf-v6-c-check__input"
                          type="checkbox"
                          id="data-list-expandable-example-toolbar-check-check-input"
                          name="data-list-expandable-example-toolbar-check-check-input"
                          aria-label="Standalone check"
                        />
                      </label>
                      <button
                        class="pf-v6-c-menu-toggle__button"
                        type="button"
                        aria-expanded="false"
                        id="data-list-expandable-example-toolbar-menu-toggle-toggle-button"
                        aria-label="Menu toggle"
                      >
                        <span class="pf-v6-c-menu-toggle__controls">
                          <span class="pf-v6-c-menu-toggle__toggle-icon">
                            <i
                              class="fas fa-caret-down fa-fw"
                              aria-hidden="true"
                            ></i>
                          </span>
                        </span>
                      </button>
                    </div>
                  </div>

                  <div class="pf-v6-c-toolbar__item pf-m-search-filter">
                    <div
                      class="pf-v6-c-input-group"
                      aria-label="search filter"
                      role="group"
                    >
                      <div class="pf-v6-c-input-group__item">
                        <button
                          class="pf-v6-c-menu-toggle"
                          type="button"
                          aria-expanded="false"
                          id="data-list-expandable-example-toolbar-search-filter-menu"
                        >
                          <span class="pf-v6-c-menu-toggle__icon">
                            <i class="fas fa-filter" aria-hidden="true"></i>
                          </span>
                          <span class="pf-v6-c-menu-toggle__text">Name</span>
                          <span class="pf-v6-c-menu-toggle__controls">
                            <span class="pf-v6-c-menu-toggle__toggle-icon">
                              <i
                                class="fas fa-caret-down fa-fw"
                                aria-hidden="true"
                              ></i>
                            </span>
                          </span>
                        </button>
                      </div>
                      <div class="pf-v6-c-input-group__item pf-m-fill">
                        <div class="pf-v6-c-text-input-group">
                          <div class="pf-v6-c-text-input-group__main pf-m-icon">
                            <span class="pf-v6-c-text-input-group__text">
                              <span class="pf-v6-c-text-input-group__icon">
                                <i class="fas fa-fw fa-search"></i>
                              </span>
                              <input
                                class="pf-v6-c-text-input-group__text-input"
                                type="text"
                                placeholder="Filter by name"
                                value
                                aria-label="Search input"
                              />
                            </span>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>

                <div
                  class="pf-v6-c-overflow-menu"
                  id="data-list-expandable-example-toolbar-overflow-menu"
                >
                  <div
                    class="pf-v6-c-overflow-menu__content pf-v6-u-display-none pf-v6-u-display-flex-on-lg"
                  >
                    <div class="pf-v6-c-overflow-menu__group pf-m-button-group">
                      <div class="pf-v6-c-overflow-menu__item">
                        <button
                          class="pf-v6-c-button pf-m-primary"
                          type="button"
                        >
                          <span class="pf-v6-c-button__text">Create instance</span>
                        </button>
                      </div>
                    </div>
                  </div>
                  <div class="pf-v6-c-overflow-menu__control">
                    <button
                      class="pf-v6-c-menu-toggle pf-m-plain"
                      type="button"
                      aria-expanded="false"
                      aria-label="Menu toggle"
                      id="data-list-expandable-example-toolbar-overflow-menu-toggle"
                    >
                      <span class="pf-v6-c-menu-toggle__icon">
                        <i class="fas fa-ellipsis-v" aria-hidden="true"></i>
                      </span>
                    </button>
                  </div>
                </div>

                <div class="pf-v6-c-toolbar__item pf-m-pagination">
                  <div class="pf-v6-c-pagination pf-m-compact">
                    <div class="pf-v6-c-pagination__page-menu">
                      <button
                        class="pf-v6-c-menu-toggle pf-m-plain pf-m-text"
                        type="button"
                        aria-expanded="false"
                        aria-label="Menu toggle"
                        id="data-list-expandable-example-toolbar-top-pagination"
                      >
                        <span class="pf-v6-c-menu-toggle__text">
                          <b>1 - 10</b>&nbsp;of&nbsp;
                          <b>36</b>
                        </span>
                        <span class="pf-v6-c-menu-toggle__controls">
                          <span class="pf-v6-c-menu-toggle__toggle-icon">
                            <i
                              class="fas fa-caret-down fa-fw"
                              aria-hidden="true"
                            ></i>
                          </span>
                        </span>
                      </button>
                    </div>
                    <nav
                      class="pf-v6-c-pagination__nav"
                      aria-label="Toolbar top pagination"
                    >
                      <div class="pf-v6-c-pagination__nav-control pf-m-prev">
                        <button
                          class="pf-v6-c-button pf-m-plain"
                          type="button"
                          disabled
                          aria-label="Go to previous page"
                        >
                          <span class="pf-v6-c-button__icon">
                            <i class="fas fa-angle-left" aria-hidden="true"></i>
                          </span>
                        </button>
                      </div>
                      <div class="pf-v6-c-pagination__nav-control pf-m-next">
                        <button
                          class="pf-v6-c-button pf-m-plain"
                          type="button"
                          aria-label="Go to next page"
                        >
                          <span class="pf-v6-c-button__icon">
                            <i class="fas fa-angle-right" aria-hidden="true"></i>
                          </span>
                        </button>
                      </div>
                    </nav>
                  </div>
                </div>
              </div>

              <div
                class="pf-v6-c-toolbar__expandable-content pf-m-hidden"
                id="data-list-expandable-example-toolbar-expandable-content"
                hidden
              ></div>
            </div>
          </div>
          <ul
            class="pf-v6-c-data-list"
            role="list"
            aria-label="Data list expandable demo"
            id="data-list-expandable-example-data-list"
          >
            <li
              class="pf-v6-c-data-list__item pf-m-expanded"
              aria-labelledby="data-list-expandable-example-data-list-item-1"
            >
              <div class="pf-v6-c-data-list__item-row">
                <div class="pf-v6-c-data-list__item-control">
                  <div class="pf-v6-c-data-list__toggle">
                    <button
                      class="pf-v6-c-button pf-m-plain"
                      type="button"
                      aria-labelledby="ex-toggle1 data-list-expandable-example-data-list-item1"
                      id="ex-toggle1"
                      aria-label="Toggle details for"
                      aria-expanded="false"
                      aria-controls="content-1"
                    >
                      <span class="pf-v6-c-button__icon pf-m-start">
                        <div class="pf-v6-c-data-list__toggle-icon">
                          <i class="fas fa-angle-right" aria-hidden="true"></i>
                        </div>
                      </span>
                    </button>
                  </div>

                  <div class="pf-v6-c-data-list__check">
                    <label
                      class="pf-v6-c-check pf-m-standalone"
                      for="data-list-expandable-example-data-list-item-1&quot;type&#x3D;&quot;checkbox&quot; name&#x3D;&quot;check-expandable-check1&quot; aria-labelledby&#x3D;&quot;data-list-expandable-example-data-list-item-1&quot;-input"
                    >
                      <input
                        class="pf-v6-c-check__input"
                        type="checkbox"
                        id="data-list-expandable-example-data-list-item-1&quot;type&#x3D;&quot;checkbox&quot; name&#x3D;&quot;check-expandable-check1&quot; aria-labelledby&#x3D;&quot;data-list-expandable-example-data-list-item-1&quot;-input"
                        name="data-list-expandable-example-data-list-item-1&quot;type&#x3D;&quot;checkbox&quot; name&#x3D;&quot;check-expandable-check1&quot; aria-labelledby&#x3D;&quot;data-list-expandable-example-data-list-item-1&quot;-input"
                        aria-label="Standalone check"
                      />
                    </label>
                  </div>
                </div>
                <div class="pf-v6-c-data-list__item-content">
                  <div class="pf-v6-c-data-list__cell pf-m-align-left">
                    <div class="pf-v6-l-flex pf-m-column pf-m-space-items-md">
                      <div
                        class="pf-v6-l-flex pf-m-column pf-m-space-items-none"
                      >
                        <div class="pf-v6-l-flex__item">
                          <p
                            id="data-list-expandable-example-data-list-item-1"
                          >patternfly</p>
                        </div>
                        <div class="pf-v6-l-flex__item">
                          <small>
                            Working repo for PatternFly 4
                            <a href>https://pf4.patternfly.org/</a>
                          </small>
                        </div>
                      </div>
                      <div class="pf-v6-l-flex pf-m-wrap">
                        <div class="pf-v6-l-flex pf-m-space-items-xs">
                          <div class="pf-v6-l-flex__item">
                            <i class="fas fa-code-branch" aria-hidden="true"></i>
                          </div>
                          <div class="pf-v6-l-flex__item">
                            <span>10</span>
                          </div>
                        </div>
                        <div class="pf-v6-l-flex pf-m-space-items-xs">
                          <div class="pf-v6-l-flex__item">
                            <i class="fas fa-code" aria-hidden="true"></i>
                          </div>
                          <div class="pf-v6-l-flex__item">
                            <span>4</span>
                          </div>
                        </div>
                        <div class="pf-v6-l-flex pf-m-space-items-xs">
                          <div class="pf-v6-l-flex__item">
                            <i class="fas fa-cube" aria-hidden="true"></i>
                          </div>
                          <div class="pf-v6-l-flex__item">
                            <span>5</span>
                          </div>
                        </div>
                        <div class="pf-v6-l-flex__item">Updated 2 days ago</div>
                      </div>
                    </div>
                  </div>
                  <div
                    class="pf-v6-c-data-list__cell pf-m-align-right pf-m-no-fill"
                  >
                    <button class="pf-v6-c-button pf-m-secondary" type="button">
                      <span class="pf-v6-c-button__text">Action</span>
                    </button>
                    <button class="pf-v6-c-button pf-m-link" type="button">
                      <span class="pf-v6-c-button__text">Link</span>
                    </button>
                  </div>
                </div>
              </div>
              <section
                class="pf-v6-c-data-list__expandable-content"
                id="content-1"
                aria-label="Content details"
              >
                <div
                  class="pf-v6-c-data-list__expandable-content-body pf-m-no-padding"
                >
                  <table
                    class="pf-v6-c-table pf-m-compact pf-m-grid-lg pf-m-no-border-rows"
                    role="grid"
                    aria-label="This is a compact table example"
                    id="compact-table-demo-data-list"
                  >
                    <thead class="pf-v6-c-table__thead">
                      <tr class="pf-v6-c-table__tr" role="row">
                        <th
                          class="pf-v6-c-table__th pf-v6-c-table__check"
                          aria-label="Row select"
                          role="columnheader"
                          scope="col"
                        >
                          <label
                            class="pf-v6-c-check pf-m-standalone"
                            for="compact-table-demo-data-list-checkrow-check-input"
                          >
                            <input
                              class="pf-v6-c-check__input"
                              type="checkbox"
                              id="compact-table-demo-data-list-checkrow-check-input"
                              name="compact-table-demo-data-list-checkrow-check-input"
                              aria-label="Select all rows"
                            />
                          </label>
                        </th>

                        <th
                          class="pf-v6-c-table__th"
                          role="columnheader"
                          scope="col"
                        >Contributor</th>

                        <th
                          class="pf-v6-c-table__th"
                          role="columnheader"
                          scope="col"
                        >Position</th>

                        <th
                          class="pf-v6-c-table__th"
                          role="columnheader"
                          scope="col"
                        >Location</th>

                        <th
                          class="pf-v6-c-table__th"
                          role="columnheader"
                          scope="col"
                        >Last seen</th>

                        <th
                          class="pf-v6-c-table__th"
                          role="columnheader"
                          scope="col"
                        >Numbers</th>

                        <th
                          class="pf-v6-c-table__th pf-v6-c-table__icon"
                          role="columnheader"
                          scope="col"
                        >Icons</th>

                        <th
                          class="pf-v6-c-table__th pf-v6-c-table__cell-empty"
                          role="columnheader"
                          scope="col"
                        >
                          <span class="pf-v6-screen-reader">Actions</span>
                        </th>

                        <th
                          class="pf-v6-c-table__th pf-v6-c-table__cell-empty"
                          role="columnheader"
                          scope="col"
                        >
                          <span class="pf-v6-screen-reader">Actions</span>
                        </th>
                      </tr>
                    </thead>

                    <tbody class="pf-v6-c-table__tbody" role="rowgroup">
                      <tr class="pf-v6-c-table__tr" role="row">
                        <td
                          class="pf-v6-c-table__td pf-v6-c-table__check"
                          aria-label="Check row"
                        >
                          <label
                            class="pf-v6-c-check pf-m-standalone"
                            for="compact-table-demo-data-list-checkrow-1-check-input"
                          >
                            <input
                              class="pf-v6-c-check__input"
                              type="checkbox"
                              id="compact-table-demo-data-list-checkrow-1-check-input"
                              name="compact-table-demo-data-list-checkrow-1-check-input"
                              aria-label="Select row"
                            />
                          </label>
                        </td>

                        <td
                          class="pf-v6-c-table__td"
                          role="cell"
                          data-label="Contributor"
                        >
                          <span
                            id="compact-table-demo-data-list-name1"
                          >Sam Jones</span>
                        </td>
                        <td
                          class="pf-v6-c-table__td"
                          role="cell"
                          data-label="Position"
                        >CSS guru</td>
                        <td
                          class="pf-v6-c-table__td"
                          role="cell"
                          data-label="Location"
                        >Not too sure</td>
                        <td
                          class="pf-v6-c-table__td"
                          role="cell"
                          data-label="Last seen"
                        >May 9, 2018</td>
                        <td
                          class="pf-v6-c-table__td"
                          role="cell"
                          data-label="Numbers"
                        >0556</td>
                        <td
                          class="pf-v6-c-table__td pf-v6-c-table__icon"
                          role="cell"
                          data-label="Icon"
                        >
                          <i class="fas fa-check"></i>
                        </td>
                        <td
                          class="pf-v6-c-table__td"
                          role="cell"
                          data-label="Action"
                        >
                          <a href="#">Action link</a>
                        </td>

                        <td class="pf-v6-c-table__td pf-v6-c-table__action">
                          <button
                            class="pf-v6-c-menu-toggle pf-m-plain"
                            type="button"
                            aria-expanded="false"
                            aria-label="Menu toggle"
                          >
                            <span class="pf-v6-c-menu-toggle__icon">
                              <i class="fas fa-ellipsis-v" aria-hidden="true"></i>
                            </span>
                          </button>
                        </td>
                      </tr>
                      <tr class="pf-v6-c-table__tr" role="row">
                        <td
                          class="pf-v6-c-table__td pf-v6-c-table__check"
                          aria-label="Check row"
                        >
                          <label
                            class="pf-v6-c-check pf-m-standalone"
                            for="compact-table-demo-data-list-checkrow-2-check-input"
                          >
                            <input
                              class="pf-v6-c-check__input"
                              type="checkbox"
                              id="compact-table-demo-data-list-checkrow-2-check-input"
                              name="compact-table-demo-data-list-checkrow-2-check-input"
                              aria-label="Select row"
                            />
                          </label>
                        </td>

                        <th
                          class="pf-v6-c-table__th"
                          role="columnheader"
                          data-label="Contributor"
                        >
                          <span
                            id="compact-table-demo-data-list-name2"
                          >Amy Miller</span>
                        </th>

                        <td
                          class="pf-v6-c-table__td"
                          role="cell"
                          data-label="Position"
                        >Visual design</td>
                        <td
                          class="pf-v6-c-table__td"
                          role="cell"
                          data-label="Location"
                        >Raleigh</td>
                        <td
                          class="pf-v6-c-table__td"
                          role="cell"
                          data-label="Last seen"
                        >May 9, 2018</td>
                        <td
                          class="pf-v6-c-table__td"
                          role="cell"
                          data-label="Numbers"
                        >9492</td>
                        <td
                          class="pf-v6-c-table__td pf-v6-c-table__icon"
                          role="cell"
                          data-label="Icon"
                        >
                          <i class="fas fa-check"></i>
                        </td>
                        <td
                          class="pf-v6-c-table__td"
                          role="cell"
                          data-label="Action"
                        >
                          <a href="#">Action link</a>
                        </td>

                        <td class="pf-v6-c-table__td pf-v6-c-table__action">
                          <button
                            class="pf-v6-c-menu-toggle pf-m-plain"
                            type="button"
                            aria-expanded="false"
                            aria-label="Menu toggle"
                          >
                            <span class="pf-v6-c-menu-toggle__icon">
                              <i class="fas fa-ellipsis-v" aria-hidden="true"></i>
                            </span>
                          </button>
                        </td>
                      </tr>
                      <tr class="pf-v6-c-table__tr" role="row">
                        <td
                          class="pf-v6-c-table__td pf-v6-c-table__check"
                          aria-label="Check row"
                        >
                          <label
                            class="pf-v6-c-check pf-m-standalone"
                            for="compact-table-demo-data-list-checkrow-3-check-input"
                          >
                            <input
                              class="pf-v6-c-check__input"
                              type="checkbox"
                              id="compact-table-demo-data-list-checkrow-3-check-input"
                              name="compact-table-demo-data-list-checkrow-3-check-input"
                              aria-label="Select row"
                            />
                          </label>
                        </td>

                        <th
                          class="pf-v6-c-table__th"
                          role="columnheader"
                          data-label="Contributor"
                        >
                          <span
                            id="compact-table-demo-data-list-name3"
                          >Steve Wilson</span>
                        </th>

                        <td
                          class="pf-v6-c-table__td"
                          role="cell"
                          data-label="Position"
                        >Visual design lead</td>
                        <td
                          class="pf-v6-c-table__td"
                          role="cell"
                          data-label="Location"
                        >Westford</td>
                        <td
                          class="pf-v6-c-table__td"
                          role="cell"
                          data-label="Last seen"
                        >May 9, 2018</td>
                        <td
                          class="pf-v6-c-table__td"
                          role="cell"
                          data-label="Numbers"
                        >9929</td>
                        <td
                          class="pf-v6-c-table__td pf-v6-c-table__icon"
                          role="cell"
                          data-label="Icon"
                        >
                          <i class="fas fa-check"></i>
                        </td>
                        <td
                          class="pf-v6-c-table__td"
                          role="cell"
                          data-label="Action"
                        >
                          <a href="#">Action link</a>
                        </td>

                        <td class="pf-v6-c-table__td pf-v6-c-table__action">
                          <button
                            class="pf-v6-c-menu-toggle pf-m-plain"
                            type="button"
                            aria-expanded="false"
                            aria-label="Menu toggle"
                          >
                            <span class="pf-v6-c-menu-toggle__icon">
                              <i class="fas fa-ellipsis-v" aria-hidden="true"></i>
                            </span>
                          </button>
                        </td>
                      </tr>
                      <tr class="pf-v6-c-table__tr" role="row">
                        <td
                          class="pf-v6-c-table__td pf-v6-c-table__check"
                          aria-label="Check row"
                        >
                          <label
                            class="pf-v6-c-check pf-m-standalone"
                            for="compact-table-demo-data-list-checkrow-4-check-input"
                          >
                            <input
                              class="pf-v6-c-check__input"
                              type="checkbox"
                              id="compact-table-demo-data-list-checkrow-4-check-input"
                              name="compact-table-demo-data-list-checkrow-4-check-input"
                              aria-label="Select row"
                            />
                          </label>
                        </td>

                        <td
                          class="pf-v6-c-table__td"
                          role="cell"
                          data-label="Contributor name"
                        >
                          <span
                            id="compact-table-demo-data-list-name4"
                          >Emma Jackson</span>
                        </td>
                        <td
                          class="pf-v6-c-table__td"
                          role="cell"
                          data-label="Position"
                        >Interaction design</td>
                        <td
                          class="pf-v6-c-table__td"
                          role="cell"
                          data-label="Location"
                        >Westford</td>
                        <td
                          class="pf-v6-c-table__td"
                          role="cell"
                          data-label="Workspaces"
                        >May 9, 2018</td>
                        <td
                          class="pf-v6-c-table__td"
                          role="cell"
                          data-label="Last commit"
                        >2217</td>
                        <td
                          class="pf-v6-c-table__td pf-v6-c-table__icon"
                          role="cell"
                          data-label="Icon"
                        >
                          <i class="fas fa-check"></i>
                        </td>
                        <td
                          class="pf-v6-c-table__td"
                          role="cell"
                          data-label="Action"
                        >
                          <a href="#">Action link</a>
                        </td>

                        <td class="pf-v6-c-table__td pf-v6-c-table__action">
                          <button
                            class="pf-v6-c-menu-toggle pf-m-plain"
                            type="button"
                            aria-expanded="false"
                            aria-label="Menu toggle"
                          >
                            <span class="pf-v6-c-menu-toggle__icon">
                              <i class="fas fa-ellipsis-v" aria-hidden="true"></i>
                            </span>
                          </button>
                        </td>
                      </tr>
                    </tbody>
                  </table>
                </div>
              </section>
            </li>

            <li
              class="pf-v6-c-data-list__item"
              aria-labelledby="data-list-expandable-example-data-list-item-2"
            >
              <div class="pf-v6-c-data-list__item-row">
                <div class="pf-v6-c-data-list__item-control">
                  <div class="pf-v6-c-data-list__toggle">
                    <button
                      class="pf-v6-c-button pf-m-plain"
                      type="button"
                      aria-labelledby="ex-toggle2 data-list-expandable-example-data-list-item2"
                      id="ex-toggle2"
                      aria-label="Toggle details for"
                      aria-expanded="false"
                      aria-controls="content-2"
                    >
                      <span class="pf-v6-c-button__icon pf-m-start">
                        <div class="pf-v6-c-data-list__toggle-icon">
                          <i class="fas fa-angle-right" aria-hidden="true"></i>
                        </div>
                      </span>
                    </button>
                  </div>

                  <div class="pf-v6-c-data-list__check">
                    <label
                      class="pf-v6-c-check pf-m-standalone"
                      for="data-list-expandable-example-data-list-item-2&quot;type&#x3D;&quot;checkbox&quot; name&#x3D;&quot;check-expandable-check2&quot; aria-labelledby&#x3D;&quot;data-list-expandable-example-data-list-item-2&quot;-input"
                    >
                      <input
                        class="pf-v6-c-check__input"
                        type="checkbox"
                        id="data-list-expandable-example-data-list-item-2&quot;type&#x3D;&quot;checkbox&quot; name&#x3D;&quot;check-expandable-check2&quot; aria-labelledby&#x3D;&quot;data-list-expandable-example-data-list-item-2&quot;-input"
                        name="data-list-expandable-example-data-list-item-2&quot;type&#x3D;&quot;checkbox&quot; name&#x3D;&quot;check-expandable-check2&quot; aria-labelledby&#x3D;&quot;data-list-expandable-example-data-list-item-2&quot;-input"
                        aria-label="Standalone check"
                      />
                    </label>
                  </div>
                </div>
                <div class="pf-v6-c-data-list__item-content">
                  <div class="pf-v6-c-data-list__cell pf-m-align-left">
                    <div class="pf-v6-l-flex pf-m-column pf-m-space-items-md">
                      <div
                        class="pf-v6-l-flex pf-m-column pf-m-space-items-none"
                      >
                        <div class="pf-v6-l-flex__item">
                          <p
                            id="data-list-expandable-example-data-list-item-2"
                          >patternfly-elements</p>
                        </div>
                        <div class="pf-v6-l-flex__item">
                          <small>PatternFly elements</small>
                        </div>
                      </div>
                      <div class="pf-v6-l-flex pf-m-wrap">
                        <div class="pf-v6-l-flex pf-m-space-items-xs">
                          <div class="pf-v6-l-flex__item">
                            <i class="fas fa-code-branch" aria-hidden="true"></i>
                          </div>
                          <div class="pf-v6-l-flex__item">
                            <span>5</span>
                          </div>
                        </div>
                        <div class="pf-v6-l-flex pf-m-space-items-xs">
                          <div class="pf-v6-l-flex__item">
                            <i class="fas fa-code" aria-hidden="true"></i>
                          </div>
                          <div class="pf-v6-l-flex__item">
                            <span>9</span>
                          </div>
                        </div>
                        <div class="pf-v6-l-flex pf-m-space-items-xs">
                          <div class="pf-v6-l-flex__item">
                            <i class="fas fa-cube" aria-hidden="true"></i>
                          </div>
                          <div class="pf-v6-l-flex__item">
                            <span>2</span>
                          </div>
                        </div>
                        <div class="pf-v6-l-flex pf-m-space-items-xs">
                          <div class="pf-v6-l-flex__item">
                            <i class="fas fa-check-circle" aria-hidden="true"></i>
                          </div>
                          <div class="pf-v6-l-flex__item">
                            <span>11</span>
                          </div>
                        </div>
                        <div class="pf-v6-l-flex pf-m-space-items-xs">
                          <div class="pf-v6-l-flex__item">
                            <i
                              class="fas fa-exclamation-triangle"
                              aria-hidden="true"
                            ></i>
                          </div>
                          <div class="pf-v6-l-flex__item">
                            <span>4</span>
                          </div>
                        </div>
                        <div class="pf-v6-l-flex pf-m-space-items-xs">
                          <div class="pf-v6-l-flex__item">
                            <i class="fas fa-times-circle" aria-hidden="true"></i>
                          </div>
                          <div class="pf-v6-l-flex__item">
                            <span>1</span>
                          </div>
                        </div>
                        <div class="pf-v6-l-flex__item">Updated 2 days ago</div>
                      </div>
                    </div>
                  </div>
                  <div
                    class="pf-v6-c-data-list__cell pf-m-align-right pf-m-no-fill"
                  >
                    <button class="pf-v6-c-button pf-m-secondary" type="button">
                      <span class="pf-v6-c-button__text">Action</span>
                    </button>
                    <button class="pf-v6-c-button pf-m-link" type="button">
                      <span class="pf-v6-c-button__text">Link</span>
                    </button>
                  </div>
                </div>
              </div>
              <section
                class="pf-v6-c-data-list__expandable-content"
                id="content-2"
                aria-label="Content details"
                hidden
              >
                <div
                  class="pf-v6-c-data-list__expandable-content-body pf-m-no-padding"
                ></div>
              </section>
            </li>

            <li
              class="pf-v6-c-data-list__item"
              aria-labelledby="data-list-expandable-example-data-list-item-3"
            >
              <div class="pf-v6-c-data-list__item-row">
                <div class="pf-v6-c-data-list__item-control">
                  <div class="pf-v6-c-data-list__toggle">
                    <button
                      class="pf-v6-c-button pf-m-plain"
                      type="button"
                      aria-labelledby="ex-toggle3 data-list-expandable-example-data-list-item3"
                      id="ex-toggle3"
                      aria-label="Toggle details for"
                      aria-expanded="false"
                      aria-controls="content-3"
                    >
                      <span class="pf-v6-c-button__icon pf-m-start">
                        <div class="pf-v6-c-data-list__toggle-icon">
                          <i class="fas fa-angle-right" aria-hidden="true"></i>
                        </div>
                      </span>
                    </button>
                  </div>

                  <div class="pf-v6-c-data-list__check">
                    <label
                      class="pf-v6-c-check pf-m-standalone"
                      for="data-list-expandable-example-data-list-item-3&quot;type&#x3D;&quot;checkbox&quot; name&#x3D;&quot;check-expandable-check3&quot; aria-labelledby&#x3D;&quot;data-list-expandable-example-data-list-item-3&quot;-input"
                    >
                      <input
                        class="pf-v6-c-check__input"
                        type="checkbox"
                        id="data-list-expandable-example-data-list-item-3&quot;type&#x3D;&quot;checkbox&quot; name&#x3D;&quot;check-expandable-check3&quot; aria-labelledby&#x3D;&quot;data-list-expandable-example-data-list-item-3&quot;-input"
                        name="data-list-expandable-example-data-list-item-3&quot;type&#x3D;&quot;checkbox&quot; name&#x3D;&quot;check-expandable-check3&quot; aria-labelledby&#x3D;&quot;data-list-expandable-example-data-list-item-3&quot;-input"
                        aria-label="Standalone check"
                      />
                    </label>
                  </div>
                </div>
                <div class="pf-v6-c-data-list__item-content">
                  <div class="pf-v6-c-data-list__cell pf-m-align-left">
                    <p
                      id="data-list-expandable-example-data-list-item-3"
                    >patternfly-unified-design-kit</p>
                  </div>
                </div>
              </div>
              <section
                class="pf-v6-c-data-list__expandable-content"
                id="content-3"
                aria-label="Content details"
                hidden
              >
                <div
                  class="pf-v6-c-data-list__expandable-content-body pf-m-no-padding"
                ></div>
              </section>
            </li>

            <li
              class="pf-v6-c-data-list__item"
              aria-labelledby="data-list-expandable-example-data-list-item-4"
            >
              <div class="pf-v6-c-data-list__item-row">
                <div class="pf-v6-c-data-list__item-control">
                  <div class="pf-v6-c-data-list__toggle">
                    <button
                      class="pf-v6-c-button pf-m-plain"
                      type="button"
                      aria-labelledby="ex-toggle4 data-list-expandable-example-data-list-item4"
                      id="ex-toggle4"
                      aria-label="Toggle details for"
                      aria-expanded="false"
                      aria-controls="content-4"
                    >
                      <span class="pf-v6-c-button__icon pf-m-start">
                        <div class="pf-v6-c-data-list__toggle-icon">
                          <i class="fas fa-angle-right" aria-hidden="true"></i>
                        </div>
                      </span>
                    </button>
                  </div>

                  <div class="pf-v6-c-data-list__check">
                    <label
                      class="pf-v6-c-check pf-m-standalone"
                      for="data-list-expandable-example-data-list-item-4&quot;type&#x3D;&quot;checkbox&quot; name&#x3D;&quot;check-expandable-check4&quot; aria-labelledby&#x3D;&quot;data-list-expandable-example-data-list-item-4&quot;-input"
                    >
                      <input
                        class="pf-v6-c-check__input"
                        type="checkbox"
                        id="data-list-expandable-example-data-list-item-4&quot;type&#x3D;&quot;checkbox&quot; name&#x3D;&quot;check-expandable-check4&quot; aria-labelledby&#x3D;&quot;data-list-expandable-example-data-list-item-4&quot;-input"
                        name="data-list-expandable-example-data-list-item-4&quot;type&#x3D;&quot;checkbox&quot; name&#x3D;&quot;check-expandable-check4&quot; aria-labelledby&#x3D;&quot;data-list-expandable-example-data-list-item-4&quot;-input"
                        aria-label="Standalone check"
                      />
                    </label>
                  </div>
                </div>
                <div class="pf-v6-c-data-list__item-content">
                  <div class="pf-v6-c-data-list__cell pf-m-align-left">
                    <div class="pf-v6-l-flex pf-m-column pf-m-space-items-md">
                      <div
                        class="pf-v6-l-flex pf-m-column pf-m-space-items-none"
                      >
                        <div class="pf-v6-l-flex__item">
                          <p
                            id="data-list-expandable-example-data-list-item-4"
                          >patternfly</p>
                        </div>
                        <div class="pf-v6-l-flex__item">
                          <small>
                            Working repo for PatternFly 4
                            <a href>https://pf4.patternfly.org/</a>
                          </small>
                        </div>
                      </div>
                      <div class="pf-v6-l-flex pf-m-wrap">
                        <div class="pf-v6-l-flex pf-m-space-items-xs">
                          <div class="pf-v6-l-flex__item">
                            <i class="fas fa-code-branch" aria-hidden="true"></i>
                          </div>
                          <div class="pf-v6-l-flex__item">
                            <span>10</span>
                          </div>
                        </div>
                        <div class="pf-v6-l-flex pf-m-space-items-xs">
                          <div class="pf-v6-l-flex__item">
                            <i class="fas fa-code" aria-hidden="true"></i>
                          </div>
                          <div class="pf-v6-l-flex__item">
                            <span>4</span>
                          </div>
                        </div>
                        <div class="pf-v6-l-flex pf-m-space-items-xs">
                          <div class="pf-v6-l-flex__item">
                            <i class="fas fa-cube" aria-hidden="true"></i>
                          </div>
                          <div class="pf-v6-l-flex__item">
                            <span>5</span>
                          </div>
                        </div>
                        <div class="pf-v6-l-flex__item">Updated 2 days ago</div>
                      </div>
                    </div>
                  </div>
                  <div
                    class="pf-v6-c-data-list__cell pf-m-align-right pf-m-no-fill"
                  >
                    <button class="pf-v6-c-button pf-m-secondary" type="button">
                      <span class="pf-v6-c-button__text">Action</span>
                    </button>
                    <button class="pf-v6-c-button pf-m-link" type="button">
                      <span class="pf-v6-c-button__text">Link</span>
                    </button>
                  </div>
                </div>
              </div>
              <section
                class="pf-v6-c-data-list__expandable-content"
                id="content-4"
                aria-label="Content details"
                hidden
              >
                <div
                  class="pf-v6-c-data-list__expandable-content-body pf-m-no-padding"
                ></div>
              </section>
            </li>

            <li
              class="pf-v6-c-data-list__item"
              aria-labelledby="data-list-expandable-example-data-list-item-5"
            >
              <div class="pf-v6-c-data-list__item-row">
                <div class="pf-v6-c-data-list__item-control">
                  <div class="pf-v6-c-data-list__toggle">
                    <button
                      class="pf-v6-c-button pf-m-plain"
                      type="button"
                      aria-labelledby="ex-toggle5 data-list-expandable-example-data-list-item5"
                      id="ex-toggle5"
                      aria-label="Toggle details for"
                      aria-expanded="false"
                      aria-controls="content-5"
                    >
                      <span class="pf-v6-c-button__icon pf-m-start">
                        <div class="pf-v6-c-data-list__toggle-icon">
                          <i class="fas fa-angle-right" aria-hidden="true"></i>
                        </div>
                      </span>
                    </button>
                  </div>

                  <div class="pf-v6-c-data-list__check">
                    <label
                      class="pf-v6-c-check pf-m-standalone"
                      for="data-list-expandable-example-data-list-item-5&quot;type&#x3D;&quot;checkbox&quot; name&#x3D;&quot;check-expandable-check5&quot; aria-labelledby&#x3D;&quot;data-list-expandable-example-data-list-item-5&quot;-input"
                    >
                      <input
                        class="pf-v6-c-check__input"
                        type="checkbox"
                        id="data-list-expandable-example-data-list-item-5&quot;type&#x3D;&quot;checkbox&quot; name&#x3D;&quot;check-expandable-check5&quot; aria-labelledby&#x3D;&quot;data-list-expandable-example-data-list-item-5&quot;-input"
                        name="data-list-expandable-example-data-list-item-5&quot;type&#x3D;&quot;checkbox&quot; name&#x3D;&quot;check-expandable-check5&quot; aria-labelledby&#x3D;&quot;data-list-expandable-example-data-list-item-5&quot;-input"
                        aria-label="Standalone check"
                      />
                    </label>
                  </div>
                </div>
                <div class="pf-v6-c-data-list__item-content">
                  <div class="pf-v6-c-data-list__cell pf-m-align-left">
                    <div class="pf-v6-l-flex pf-m-column pf-m-space-items-md">
                      <div
                        class="pf-v6-l-flex pf-m-column pf-m-space-items-none"
                      >
                        <div class="pf-v6-l-flex__item">
                          <p
                            id="data-list-expandable-example-data-list-item-5"
                          >patternfly-elements</p>
                        </div>
                        <div class="pf-v6-l-flex__item">
                          <small>PatternFly elements</small>
                        </div>
                      </div>
                      <div class="pf-v6-l-flex pf-m-wrap">
                        <div class="pf-v6-l-flex pf-m-space-items-xs">
                          <div class="pf-v6-l-flex__item">
                            <i class="fas fa-code-branch" aria-hidden="true"></i>
                          </div>
                          <div class="pf-v6-l-flex__item">
                            <span>5</span>
                          </div>
                        </div>
                        <div class="pf-v6-l-flex pf-m-space-items-xs">
                          <div class="pf-v6-l-flex__item">
                            <i class="fas fa-code" aria-hidden="true"></i>
                          </div>
                          <div class="pf-v6-l-flex__item">
                            <span>9</span>
                          </div>
                        </div>
                        <div class="pf-v6-l-flex pf-m-space-items-xs">
                          <div class="pf-v6-l-flex__item">
                            <i class="fas fa-cube" aria-hidden="true"></i>
                          </div>
                          <div class="pf-v6-l-flex__item">
                            <span>2</span>
                          </div>
                        </div>
                        <div class="pf-v6-l-flex pf-m-space-items-xs">
                          <div class="pf-v6-l-flex__item">
                            <i class="fas fa-check-circle" aria-hidden="true"></i>
                          </div>
                          <div class="pf-v6-l-flex__item">
                            <span>11</span>
                          </div>
                        </div>
                        <div class="pf-v6-l-flex pf-m-space-items-xs">
                          <div class="pf-v6-l-flex__item">
                            <i
                              class="fas fa-exclamation-triangle"
                              aria-hidden="true"
                            ></i>
                          </div>
                          <div class="pf-v6-l-flex__item">
                            <span>4</span>
                          </div>
                        </div>
                        <div class="pf-v6-l-flex pf-m-space-items-xs">
                          <div class="pf-v6-l-flex__item">
                            <i class="fas fa-times-circle" aria-hidden="true"></i>
                          </div>
                          <div class="pf-v6-l-flex__item">
                            <span>1</span>
                          </div>
                        </div>
                        <div class="pf-v6-l-flex__item">Updated 2 days ago</div>
                      </div>
                    </div>
                  </div>
                  <div
                    class="pf-v6-c-data-list__cell pf-m-align-right pf-m-no-fill"
                  >
                    <button class="pf-v6-c-button pf-m-secondary" type="button">
                      <span class="pf-v6-c-button__text">Action</span>
                    </button>
                    <button class="pf-v6-c-button pf-m-link" type="button">
                      <span class="pf-v6-c-button__text">Link</span>
                    </button>
                  </div>
                </div>
              </div>
              <section
                class="pf-v6-c-data-list__expandable-content"
                id="content-5"
                aria-label="Content details"
                hidden
              >
                <div
                  class="pf-v6-c-data-list__expandable-content-body pf-m-no-padding"
                ></div>
              </section>
            </li>
          </ul>
          <div class="pf-v6-c-pagination pf-m-bottom">
            <div class="pf-v6-c-pagination__page-menu">
              <button
                class="pf-v6-c-menu-toggle pf-m-plain pf-m-text pf-m-top"
                type="button"
                aria-expanded="false"
                aria-label="Menu toggle"
                id="{{page--id}}-pagination-menu-toggle-bottom-example"
              >
                <span class="pf-v6-c-menu-toggle__text">
                  <b>1 - 10</b>&nbsp;of&nbsp;
                  <b>36</b>
                </span>
                <span class="pf-v6-c-menu-toggle__controls">
                  <span class="pf-v6-c-menu-toggle__toggle-icon">
                    <i class="fas fa-caret-down fa-fw" aria-hidden="true"></i>
                  </span>
                </span>
              </button>
            </div>
            <nav class="pf-v6-c-pagination__nav" aria-label="Pagination">
              <div class="pf-v6-c-pagination__nav-control pf-m-first">
                <button
                  class="pf-v6-c-button pf-m-plain"
                  type="button"
                  disabled
                  aria-label="Go to first page"
                >
                  <span class="pf-v6-c-button__icon">
                    <i class="fas fa-angle-double-left" aria-hidden="true"></i>
                  </span>
                </button>
              </div>
              <div class="pf-v6-c-pagination__nav-control pf-m-prev">
                <button
                  class="pf-v6-c-button pf-m-plain"
                  type="button"
                  disabled
                  aria-label="Go to previous page"
                >
                  <span class="pf-v6-c-button__icon">
                    <i class="fas fa-angle-left" aria-hidden="true"></i>
                  </span>
                </button>
              </div>
              <div class="pf-v6-c-pagination__nav-page-select">
                <span class="pf-v6-c-form-control">
                  <input
                    aria-label="Current page"
                    type="number"
                    min="1"
                    max="4"
                    value="1"
                  />
                </span>
                <span aria-hidden="true">of 4</span>
              </div>
              <div class="pf-v6-c-pagination__nav-control pf-m-next">
                <button
                  class="pf-v6-c-button pf-m-plain"
                  type="button"
                  aria-label="Go to next page"
                >
                  <span class="pf-v6-c-button__icon">
                    <i class="fas fa-angle-right" aria-hidden="true"></i>
                  </span>
                </button>
              </div>
              <div class="pf-v6-c-pagination__nav-control pf-m-last">
                <button
                  class="pf-v6-c-button pf-m-plain"
                  type="button"
                  disabled
                  aria-label="Go to last page"
                >
                  <span class="pf-v6-c-button__icon">
                    <i class="fas fa-angle-double-right" aria-hidden="true"></i>
                  </span>
                </button>
              </div>
            </nav>
          </div>
        </div>
      </section>
    </main>
  </div>
</div>

```

### Static bottom pagination

```html isFullscreen
<div class="pf-v6-c-page" id="data-list-static-bottom-example">
  <div class="pf-v6-c-skip-to-content">
    <a
      class="pf-v6-c-button pf-m-primary"
      href="#main-content-data-list-static-bottom-example"
    >
      <span class="pf-v6-c-button__text">Skip to content</span>
    </a>
  </div>
  <header
    class="pf-v6-c-masthead"
    id="data-list-static-bottom-example-masthead"
  >
    <div class="pf-v6-c-masthead__main">
      <span class="pf-v6-c-masthead__toggle">
        <button
          class="pf-v6-c-button pf-m-plain"
          type="button"
          aria-label="Global navigation"
        >
          <span class="pf-v6-c-button__icon">
            <i class="fas fa-bars" aria-hidden="true"></i>
          </span>
        </button>
      </span>
      <div class="pf-v6-c-masthead__brand">
        <a class="pf-v6-c-masthead__logo" href="#">
          <svg
            height="37px"
            xmlns="http://www.w3.org/2000/svg"
            viewBox="0 0 40 40"
          >
            <path
              fill="var(--pf-t--global--text--color--regular)"
              fill-rule="evenodd"
              d="M37.03 25.32c.57 0 1.47.66 1.47 2.26 0 1.58-.65 3.38-.8 3.77C35.32 37.03 29.7 40.2 23 40c-6.24-.19-11.57-3.5-13.9-8.9a6.13 6.13 0 0 1-3.97-1.6 5.9 5.9 0 0 1-2.02-3.78 6.5 6.5 0 0 1 .37-2.99l-1.31-1.11C-3.83 16.52 14.92-4.42 20.9.84l2.04 2.01 1.12-.47c5.26-2.2 9.52-1.14 9.53 2.36 0 1.81-1.15 3.93-3 5.85.67.62 1.2 1.6 1.52 2.7.25.83.3 1.67.32 2.2l.07 2.5.74.2c1.42.4 2.42.93 2.91 1.45.5.52.73 1.02.82 1.6a3.1 3.1 0 0 1-.55 2.26s.16.35.32.85l.28.97zm-14.56 2.63zm14.63.16c.15-.95-.06-1.31-.35-1.49-.3-.19-.66-.12-.66-.12s-.17-1.13-.63-2.16a13.83 13.83 0 0 1-4.53 2.26c-1.56.45-3.68.8-6.04.65-1.31-.1-2.18-.49-2.5.58 2.99 1.1 6.16.63 6.16.63.06 0 .11.04.12.1 0 .05-.02.1-.07.12 0 0-2.43 1.13-6.3-.07.1.91.99 1.32 1.41 1.49.53.2 1.12.3 1.12.3 4.79.83 9.27-1.92 10.28-2.62.07-.05.12 0 .06.1l-.1.13c-1.23 1.6-4.55 3.46-8.87 3.46-1.88 0-3.76-.67-4.45-1.7-1.08-1.58-.06-3.9 1.73-3.66l.78.09a16.3 16.3 0 0 0 8.13-1.31c2.44-1.14 3.36-2.4 3.22-3.4a1.46 1.46 0 0 0-.42-.83 5.25 5.25 0 0 0-2.3-1.1c-.39-.1-.65-.18-.93-.27-.5-.17-.76-.3-.81-1.25l-.13-2.47c-.04-1.05-.17-2.48-1.05-3.07a1.48 1.48 0 0 0-.76-.25c-.26 0-.4.04-.45.05-.5.08-.8.35-1.18.67A4.04 4.04 0 0 1 24.51 14c-.62-.03-1.28-.13-2.03-.17l-.44-.03c-1.73-.08-3.6 1.42-3.9 3.56-.44 2.98 1.7 4.52 2.33 5.43.08.1.17.26.17.4 0 .17-.11.31-.22.43a7.66 7.66 0 0 0-1.36 8.03c1.57 3.68 6.43 5.4 11.18 3.84.63-.21 1.23-.47 1.8-.77 1.07-.52 2-1.24 2.76-2.07a8.27 8.27 0 0 0 2.3-4.54zm-7.9-9.2a3.23 3.23 0 0 1-.52-1.28c-.2-.96-.18-1.65.37-1.74.56-.09.82.49 1.02 1.44.14.64.11 1.23-.04 1.57a3.2 3.2 0 0 0-.82 0zm-4.74.75c-.4-.18-.91-.37-1.53-.34-.88.06-1.65.45-1.87.42-.09-.01-.13-.05-.14-.1-.04-.17.22-.44.48-.63.8-.58 1.84-.71 2.72-.33.42.18.82.5 1.02.83.1.15.11.27.05.33-.1.1-.34-.01-.73-.18zm-.8.45c.71-.08 1.23.25 1.35.45.05.08.03.14.02.16-.06.1-.18.08-.44.05a3.27 3.27 0 0 0-1.66.17s-.26.1-.38.1a.12.12 0 0 1-.12-.12c0-.1.1-.26.25-.4.18-.16.46-.33.98-.4zm3.94 1.68c-.35-.17-.53-.52-.4-.78.12-.26.5-.32.86-.15.35.17.53.52.4.78-.12.25-.5.32-.86.15zm2.25-1.98c.29 0 .51.33.5.72 0 .4-.23.7-.52.7-.28 0-.5-.32-.5-.72 0-.39.24-.7.52-.7zm-14.77-8.58c-.06.06.02.15.09.1A15.1 15.1 0 0 1 27.1 8.94c.07.02.12-.11.05-.15-1-.57-2.54-.95-3.63-.96-.06 0-.09-.06-.05-.1.19-.26.44-.51.68-.7.05-.04.02-.12-.05-.12-1.55.1-3.32.84-4.34 1.54-.05.04-.12 0-.1-.07.07-.38.32-.89.45-1.13.04-.05-.03-.11-.08-.08a17.67 17.67 0 0 0-4.95 4.06zm-7.72 8.2c1.71-4.61 4.57-8.87 8.35-11.8 2.81-2.35 5.84-4.04 5.84-4.04s-1.63-1.9-2.12-2.04C16.4.73 9.85 5.26 5.67 11.25c-1.69 2.43-4.1 6.73-2.95 8.94.14.27.95.97 1.38 1.34a5.15 5.15 0 0 1 3.26-2.1zm2.26 10.14c2.19-.37 2.76-2.76 2.4-5.1-.4-2.66-2.2-3.6-3.4-3.66-.34-.02-.65.01-.9.06-2.17.44-3.39 2.29-3.15 4.7.22 2.16 2.4 4 4.43 4.05.2 0 .41-.01.62-.05zm.83-2.72c.1-.03.22-.06.3.03.02.03.06.1.01.21-.08.19-.4.44-.85.43-.47-.04-1-.38-1.06-1.23-.04-.42.12-.94.22-1.2a1.12 1.12 0 0 0-1.3-1.52c-.3.07-.54.24-.7.5a2.64 2.64 0 0 0-.3.7c-.1.27-.25.35-.36.33-.05 0-.12-.04-.17-.16-.12-.34-.02-1.29.61-1.98a1.9 1.9 0 0 1 1.63-.6c.63.09 1.16.47 1.48 1.09.43.82.05 1.68-.18 2.2l-.06.15c-.15.34-.16.64-.03.84.1.15.28.24.49.24.1 0 .19-.02.27-.03z"
            />
          </svg>
        </a>
      </div>
    </div>
    <div class="pf-v6-c-masthead__content">
      <div
        class="pf-v6-c-toolbar pf-m-static"
        id="data-list-static-bottom-example-masthead-toolbar"
      >
        <div class="pf-v6-c-toolbar__content">
          <div class="pf-v6-c-toolbar__content-section">
            <div
              class="pf-v6-c-toolbar__group pf-m-align-end pf-m-spacer-none pf-m-spacer-md-on-md pf-m-action-group-plain"
            >
              <div
                class="pf-v6-c-toolbar__group pf-m-hidden pf-m-visible-on-lg pf-m-action-group-plain"
              >
                <div class="pf-v6-c-toolbar__item">
                  <button
                    class="pf-v6-c-menu-toggle pf-m-plain"
                    type="button"
                    aria-expanded="false"
                    aria-label="Application launcher"
                  >
                    <span class="pf-v6-c-menu-toggle__icon">
                      <i class="fas fa-th" aria-hidden="true"></i>
                    </span>
                  </button>
                </div>
                <div class="pf-v6-c-toolbar__item">
                  <button
                    class="pf-v6-c-menu-toggle pf-m-plain"
                    type="button"
                    aria-expanded="false"
                    aria-label="Settings"
                  >
                    <span class="pf-v6-c-menu-toggle__icon">
                      <i class="fas fa-cog" aria-hidden="true"></i>
                    </span>
                  </button>
                </div>
                <div class="pf-v6-c-toolbar__item">
                  <button
                    class="pf-v6-c-menu-toggle pf-m-plain"
                    type="button"
                    aria-expanded="false"
                    aria-label="Help"
                  >
                    <span class="pf-v6-c-menu-toggle__icon">
                      <i class="fas fa-question-circle" aria-hidden="true"></i>
                    </span>
                  </button>
                </div>
              </div>

              <div class="pf-v6-c-toolbar__item pf-m-hidden-on-lg">
                <button
                  class="pf-v6-c-menu-toggle pf-m-plain"
                  type="button"
                  aria-expanded="false"
                  aria-label="Actions"
                >
                  <span class="pf-v6-c-menu-toggle__icon">
                    <i class="fas fa-ellipsis-v" aria-hidden="true"></i>
                  </span>
                </button>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </header>
  <div class="pf-v6-c-page__sidebar">
    <div class="pf-v6-c-page__sidebar-body">
      <nav
        class="pf-v6-c-nav"
        id="data-list-static-bottom-example-primary-nav"
        aria-label="Global"
      >
        <ul class="pf-v6-c-nav__list" role="list">
          <li class="pf-v6-c-nav__item">
            <a href="#" class="pf-v6-c-nav__link">
              <span class="pf-v6-c-nav__link-text">System panel</span>
            </a>
          </li>
          <li class="pf-v6-c-nav__item">
            <a
              href="#"
              class="pf-v6-c-nav__link pf-m-current"
              aria-current="page"
            >
              <span class="pf-v6-c-nav__link-text">Policy</span>
            </a>
          </li>
          <li class="pf-v6-c-nav__item">
            <a href="#" class="pf-v6-c-nav__link">
              <span class="pf-v6-c-nav__link-text">Authentication</span>
            </a>
          </li>
          <li class="pf-v6-c-nav__item">
            <a href="#" class="pf-v6-c-nav__link">
              <span class="pf-v6-c-nav__link-text">Network services</span>
            </a>
          </li>
          <li class="pf-v6-c-nav__item">
            <a href="#" class="pf-v6-c-nav__link">
              <span class="pf-v6-c-nav__link-text">Server</span>
            </a>
          </li>
        </ul>
      </nav>
    </div>
  </div>
  <div class="pf-v6-c-page__main-container" tabindex="-1">
    <main
      class="pf-v6-c-page__main"
      tabindex="-1"
      id="main-content-data-list-static-bottom-example"
    >
      <section class="pf-v6-c-page__main-breadcrumb pf-m-limit-width">
        <div class="pf-v6-c-page__main-body">
          <nav class="pf-v6-c-breadcrumb" aria-label="breadcrumb">
            <ol class="pf-v6-c-breadcrumb__list" role="list">
              <li class="pf-v6-c-breadcrumb__item">
                <a href="#" class="pf-v6-c-breadcrumb__link">Section home</a>
              </li>
              <li class="pf-v6-c-breadcrumb__item">
                <span class="pf-v6-c-breadcrumb__item-divider">
                  <i class="fas fa-angle-right" aria-hidden="true"></i>
                </span>

                <a href="#" class="pf-v6-c-breadcrumb__link">Section title</a>
              </li>
              <li class="pf-v6-c-breadcrumb__item">
                <span class="pf-v6-c-breadcrumb__item-divider">
                  <i class="fas fa-angle-right" aria-hidden="true"></i>
                </span>

                <a href="#" class="pf-v6-c-breadcrumb__link">Section title</a>
              </li>
              <li class="pf-v6-c-breadcrumb__item">
                <span class="pf-v6-c-breadcrumb__item-divider">
                  <i class="fas fa-angle-right" aria-hidden="true"></i>
                </span>

                <a
                  href="#"
                  class="pf-v6-c-breadcrumb__link pf-m-current"
                  aria-current="page"
                >Section landing</a>
              </li>
            </ol>
          </nav>
        </div>
      </section>
      <section class="pf-v6-c-page__main-section pf-m-limit-width">
        <div class="pf-v6-c-page__main-body">
          <h1 class="pf-v6-c-content--h1 pf-m-page-title">Main title</h1>
          <p class="pf-v6-c-content--p">This is a full page demo.</p>
        </div>
      </section>
      <section class="pf-v6-c-page__main-section">
        <div class="pf-v6-c-page__main-body">
          <div
            class="pf-v6-c-toolbar"
            id="data-list-static-bottom-example-toolbar"
          >
            <div class="pf-v6-c-toolbar__content">
              <div class="pf-v6-c-toolbar__content-section pf-m-nowrap">
                <div
                  class="pf-v6-c-toolbar__group pf-m-show-on-xl pf-m-toggle-group"
                >
                  <div class="pf-v6-c-toolbar__toggle">
                    <button
                      class="pf-v6-c-menu-toggle pf-m-plain"
                      type="button"
                      aria-expanded="false"
                      aria-label="Show filters"
                      aria-controls="data-list-static-bottom-example-toolbar-expandable-content"
                    >
                      <span class="pf-v6-c-menu-toggle__icon">
                        <i class="fas fa-filter" aria-hidden="true"></i>
                      </span>
                    </button>
                  </div>

                  <div class="pf-v6-c-toolbar__item pf-m-search-filter">
                    <div
                      class="pf-v6-c-input-group"
                      aria-label="search filter"
                      role="group"
                    >
                      <div class="pf-v6-c-input-group__item">
                        <button
                          class="pf-v6-c-menu-toggle"
                          type="button"
                          aria-expanded="false"
                          id="data-list-static-bottom-example-toolbar-search-filter-menu"
                        >
                          <span class="pf-v6-c-menu-toggle__icon">
                            <i class="fas fa-filter" aria-hidden="true"></i>
                          </span>
                          <span class="pf-v6-c-menu-toggle__text">Name</span>
                          <span class="pf-v6-c-menu-toggle__controls">
                            <span class="pf-v6-c-menu-toggle__toggle-icon">
                              <i
                                class="fas fa-caret-down fa-fw"
                                aria-hidden="true"
                              ></i>
                            </span>
                          </span>
                        </button>
                      </div>
                      <div class="pf-v6-c-input-group__item pf-m-fill">
                        <div class="pf-v6-c-text-input-group">
                          <div class="pf-v6-c-text-input-group__main pf-m-icon">
                            <span class="pf-v6-c-text-input-group__text">
                              <span class="pf-v6-c-text-input-group__icon">
                                <i class="fas fa-fw fa-search"></i>
                              </span>
                              <input
                                class="pf-v6-c-text-input-group__text-input"
                                type="text"
                                placeholder="Filter by name"
                                value
                                aria-label="Search input"
                              />
                            </span>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>

                <div
                  class="pf-v6-c-overflow-menu"
                  id="data-list-static-bottom-example-toolbar-overflow-menu"
                >
                  <div
                    class="pf-v6-c-overflow-menu__content pf-v6-u-display-none pf-v6-u-display-flex-on-lg"
                  >
                    <div class="pf-v6-c-overflow-menu__group pf-m-button-group">
                      <div class="pf-v6-c-overflow-menu__item">
                        <button
                          class="pf-v6-c-button pf-m-primary"
                          type="button"
                        >
                          <span class="pf-v6-c-button__text">Create instance</span>
                        </button>
                      </div>

                      <div class="pf-v6-c-overflow-menu__item">
                        <button
                          class="pf-v6-c-button pf-m-secondary"
                          type="button"
                        >
                          <span class="pf-v6-c-button__text">Action</span>
                        </button>
                      </div>
                    </div>
                  </div>
                  <div class="pf-v6-c-overflow-menu__control">
                    <button
                      class="pf-v6-c-menu-toggle pf-m-plain"
                      type="button"
                      aria-expanded="false"
                      aria-label="Menu toggle"
                      id="data-list-static-bottom-example-toolbar-overflow-menu-toggle"
                    >
                      <span class="pf-v6-c-menu-toggle__icon">
                        <i class="fas fa-ellipsis-v" aria-hidden="true"></i>
                      </span>
                    </button>
                  </div>
                </div>

                <div class="pf-v6-c-toolbar__item pf-m-pagination">
                  <div class="pf-v6-c-pagination pf-m-compact">
                    <div class="pf-v6-c-pagination__page-menu">
                      <button
                        class="pf-v6-c-menu-toggle pf-m-plain pf-m-text"
                        type="button"
                        aria-expanded="false"
                        aria-label="Menu toggle"
                        id="data-list-static-bottom-example-toolbar-top-pagination"
                      >
                        <span class="pf-v6-c-menu-toggle__text">
                          <b>1 - 10</b>&nbsp;of&nbsp;
                          <b>36</b>
                        </span>
                        <span class="pf-v6-c-menu-toggle__controls">
                          <span class="pf-v6-c-menu-toggle__toggle-icon">
                            <i
                              class="fas fa-caret-down fa-fw"
                              aria-hidden="true"
                            ></i>
                          </span>
                        </span>
                      </button>
                    </div>
                    <nav
                      class="pf-v6-c-pagination__nav"
                      aria-label="Toolbar top pagination"
                    >
                      <div class="pf-v6-c-pagination__nav-control pf-m-prev">
                        <button
                          class="pf-v6-c-button pf-m-plain"
                          type="button"
                          disabled
                          aria-label="Go to previous page"
                        >
                          <span class="pf-v6-c-button__icon">
                            <i class="fas fa-angle-left" aria-hidden="true"></i>
                          </span>
                        </button>
                      </div>
                      <div class="pf-v6-c-pagination__nav-control pf-m-next">
                        <button
                          class="pf-v6-c-button pf-m-plain"
                          type="button"
                          aria-label="Go to next page"
                        >
                          <span class="pf-v6-c-button__icon">
                            <i class="fas fa-angle-right" aria-hidden="true"></i>
                          </span>
                        </button>
                      </div>
                    </nav>
                  </div>
                </div>
              </div>

              <div
                class="pf-v6-c-toolbar__expandable-content pf-m-hidden"
                id="data-list-static-bottom-example-toolbar-expandable-content"
                hidden
              ></div>
            </div>
          </div>
          <ul
            class="pf-v6-c-data-list"
            role="list"
            aria-label="Simple data list example"
            id="data-list-static-bottom-example-data-list"
          >
            <li
              class="pf-v6-c-data-list__item"
              aria-labelledby="data-list-static-bottom-example-data-list-item-1"
            >
              <div class="pf-v6-c-data-list__item-row">
                <div class="pf-v6-c-data-list__item-content">
                  <div class="pf-v6-c-data-list__cell pf-m-align-left">
                    <div class="pf-v6-l-flex pf-m-column pf-m-space-items-md">
                      <div
                        class="pf-v6-l-flex pf-m-column pf-m-space-items-none"
                      >
                        <div class="pf-v6-l-flex__item">
                          <p
                            id="data-list-static-bottom-example-data-list-item-1"
                          >patternfly</p>
                        </div>
                        <div class="pf-v6-l-flex__item">
                          <small>
                            Working repo for PatternFly 4
                            <a href>https://pf4.patternfly.org/</a>
                          </small>
                        </div>
                      </div>
                      <div class="pf-v6-l-flex pf-m-wrap">
                        <div class="pf-v6-l-flex pf-m-space-items-xs">
                          <div class="pf-v6-l-flex__item">
                            <i class="fas fa-code-branch" aria-hidden="true"></i>
                          </div>
                          <div class="pf-v6-l-flex__item">
                            <span>10</span>
                          </div>
                        </div>
                        <div class="pf-v6-l-flex pf-m-space-items-xs">
                          <div class="pf-v6-l-flex__item">
                            <i class="fas fa-code" aria-hidden="true"></i>
                          </div>
                          <div class="pf-v6-l-flex__item">
                            <span>4</span>
                          </div>
                        </div>
                        <div class="pf-v6-l-flex pf-m-space-items-xs">
                          <div class="pf-v6-l-flex__item">
                            <i class="fas fa-cube" aria-hidden="true"></i>
                          </div>
                          <div class="pf-v6-l-flex__item">
                            <span>5</span>
                          </div>
                        </div>
                        <div class="pf-v6-l-flex__item">Updated 2 days ago</div>
                      </div>
                    </div>
                  </div>
                  <div
                    class="pf-v6-c-data-list__cell pf-m-align-right pf-m-no-fill"
                  >
                    <button class="pf-v6-c-button pf-m-secondary" type="button">
                      <span class="pf-v6-c-button__text">Action</span>
                    </button>
                    <button class="pf-v6-c-button pf-m-link" type="button">
                      <span class="pf-v6-c-button__text">Link</span>
                    </button>
                  </div>
                </div>
              </div>
            </li>

            <li
              class="pf-v6-c-data-list__item"
              aria-labelledby="data-list-static-bottom-example-data-list-item-2"
            >
              <div class="pf-v6-c-data-list__item-row">
                <div class="pf-v6-c-data-list__item-content">
                  <div class="pf-v6-c-data-list__cell pf-m-align-left">
                    <div class="pf-v6-l-flex pf-m-column pf-m-space-items-md">
                      <div
                        class="pf-v6-l-flex pf-m-column pf-m-space-items-none"
                      >
                        <div class="pf-v6-l-flex__item">
                          <p
                            id="data-list-static-bottom-example-data-list-item-2"
                          >patternfly-elements</p>
                        </div>
                        <div class="pf-v6-l-flex__item">
                          <small>PatternFly elements</small>
                        </div>
                      </div>
                      <div class="pf-v6-l-flex pf-m-wrap">
                        <div class="pf-v6-l-flex pf-m-space-items-xs">
                          <div class="pf-v6-l-flex__item">
                            <i class="fas fa-code-branch" aria-hidden="true"></i>
                          </div>
                          <div class="pf-v6-l-flex__item">
                            <span>5</span>
                          </div>
                        </div>
                        <div class="pf-v6-l-flex pf-m-space-items-xs">
                          <div class="pf-v6-l-flex__item">
                            <i class="fas fa-code" aria-hidden="true"></i>
                          </div>
                          <div class="pf-v6-l-flex__item">
                            <span>9</span>
                          </div>
                        </div>
                        <div class="pf-v6-l-flex pf-m-space-items-xs">
                          <div class="pf-v6-l-flex__item">
                            <i class="fas fa-cube" aria-hidden="true"></i>
                          </div>
                          <div class="pf-v6-l-flex__item">
                            <span>2</span>
                          </div>
                        </div>
                        <div class="pf-v6-l-flex pf-m-space-items-xs">
                          <div class="pf-v6-l-flex__item">
                            <i class="fas fa-check-circle" aria-hidden="true"></i>
                          </div>
                          <div class="pf-v6-l-flex__item">
                            <span>11</span>
                          </div>
                        </div>
                        <div class="pf-v6-l-flex pf-m-space-items-xs">
                          <div class="pf-v6-l-flex__item">
                            <i
                              class="fas fa-exclamation-triangle"
                              aria-hidden="true"
                            ></i>
                          </div>
                          <div class="pf-v6-l-flex__item">
                            <span>4</span>
                          </div>
                        </div>
                        <div class="pf-v6-l-flex pf-m-space-items-xs">
                          <div class="pf-v6-l-flex__item">
                            <i class="fas fa-times-circle" aria-hidden="true"></i>
                          </div>
                          <div class="pf-v6-l-flex__item">
                            <span>1</span>
                          </div>
                        </div>
                        <div class="pf-v6-l-flex__item">Updated 2 days ago</div>
                      </div>
                    </div>
                  </div>
                  <div
                    class="pf-v6-c-data-list__cell pf-m-align-right pf-m-no-fill"
                  >
                    <button class="pf-v6-c-button pf-m-secondary" type="button">
                      <span class="pf-v6-c-button__text">Action</span>
                    </button>
                    <button class="pf-v6-c-button pf-m-link" type="button">
                      <span class="pf-v6-c-button__text">Link</span>
                    </button>
                  </div>
                </div>
              </div>
            </li>

            <li
              class="pf-v6-c-data-list__item"
              aria-labelledby="data-list-static-bottom-example-data-list-item-3"
            >
              <div class="pf-v6-c-data-list__item-row">
                <div class="pf-v6-c-data-list__item-content">
                  <div class="pf-v6-c-data-list__cell pf-m-align-left">
                    <p
                      id="data-list-static-bottom-example-data-list-item-3"
                    >patternfly-unified-design-kit</p>
                  </div>
                  <div
                    class="pf-v6-c-data-list__cell pf-m-align-right pf-m-no-fill"
                  >
                    <button class="pf-v6-c-button pf-m-secondary" type="button">
                      <span class="pf-v6-c-button__text">Action</span>
                    </button>
                    <button class="pf-v6-c-button pf-m-link" type="button">
                      <span class="pf-v6-c-button__text">Link</span>
                    </button>
                  </div>
                </div>
              </div>
            </li>

            <li
              class="pf-v6-c-data-list__item"
              aria-labelledby="data-list-static-bottom-example-data-list-item-4"
            >
              <div class="pf-v6-c-data-list__item-row">
                <div class="pf-v6-c-data-list__item-content">
                  <div class="pf-v6-c-data-list__cell pf-m-align-left">
                    <div class="pf-v6-l-flex pf-m-column pf-m-space-items-md">
                      <div
                        class="pf-v6-l-flex pf-m-column pf-m-space-items-none"
                      >
                        <div class="pf-v6-l-flex__item">
                          <p
                            id="data-list-static-bottom-example-data-list-item-4"
                          >patternfly</p>
                        </div>
                        <div class="pf-v6-l-flex__item">
                          <small>
                            Working repo for PatternFly 4
                            <a href>https://pf4.patternfly.org/</a>
                          </small>
                        </div>
                      </div>
                      <div class="pf-v6-l-flex pf-m-wrap">
                        <div class="pf-v6-l-flex pf-m-space-items-xs">
                          <div class="pf-v6-l-flex__item">
                            <i class="fas fa-code-branch" aria-hidden="true"></i>
                          </div>
                          <div class="pf-v6-l-flex__item">
                            <span>10</span>
                          </div>
                        </div>
                        <div class="pf-v6-l-flex pf-m-space-items-xs">
                          <div class="pf-v6-l-flex__item">
                            <i class="fas fa-code" aria-hidden="true"></i>
                          </div>
                          <div class="pf-v6-l-flex__item">
                            <span>4</span>
                          </div>
                        </div>
                        <div class="pf-v6-l-flex pf-m-space-items-xs">
                          <div class="pf-v6-l-flex__item">
                            <i class="fas fa-cube" aria-hidden="true"></i>
                          </div>
                          <div class="pf-v6-l-flex__item">
                            <span>5</span>
                          </div>
                        </div>
                        <div class="pf-v6-l-flex__item">Updated 2 days ago</div>
                      </div>
                    </div>
                  </div>
                  <div
                    class="pf-v6-c-data-list__cell pf-m-align-right pf-m-no-fill"
                  >
                    <button class="pf-v6-c-button pf-m-secondary" type="button">
                      <span class="pf-v6-c-button__text">Action</span>
                    </button>
                    <button class="pf-v6-c-button pf-m-link" type="button">
                      <span class="pf-v6-c-button__text">Link</span>
                    </button>
                  </div>
                </div>
              </div>
            </li>

            <li
              class="pf-v6-c-data-list__item"
              aria-labelledby="data-list-static-bottom-example-data-list-item-5"
            >
              <div class="pf-v6-c-data-list__item-row">
                <div class="pf-v6-c-data-list__item-content">
                  <div class="pf-v6-c-data-list__cell pf-m-align-left">
                    <div class="pf-v6-l-flex pf-m-column pf-m-space-items-md">
                      <div
                        class="pf-v6-l-flex pf-m-column pf-m-space-items-none"
                      >
                        <div class="pf-v6-l-flex__item">
                          <p
                            id="data-list-static-bottom-example-data-list-item-5"
                          >patternfly-elements</p>
                        </div>
                        <div class="pf-v6-l-flex__item">
                          <small>PatternFly elements</small>
                        </div>
                      </div>
                      <div class="pf-v6-l-flex pf-m-wrap">
                        <div class="pf-v6-l-flex pf-m-space-items-xs">
                          <div class="pf-v6-l-flex__item">
                            <i class="fas fa-code-branch" aria-hidden="true"></i>
                          </div>
                          <div class="pf-v6-l-flex__item">
                            <span>5</span>
                          </div>
                        </div>
                        <div class="pf-v6-l-flex pf-m-space-items-xs">
                          <div class="pf-v6-l-flex__item">
                            <i class="fas fa-code" aria-hidden="true"></i>
                          </div>
                          <div class="pf-v6-l-flex__item">
                            <span>9</span>
                          </div>
                        </div>
                        <div class="pf-v6-l-flex pf-m-space-items-xs">
                          <div class="pf-v6-l-flex__item">
                            <i class="fas fa-cube" aria-hidden="true"></i>
                          </div>
                          <div class="pf-v6-l-flex__item">
                            <span>2</span>
                          </div>
                        </div>
                        <div class="pf-v6-l-flex pf-m-space-items-xs">
                          <div class="pf-v6-l-flex__item">
                            <i class="fas fa-check-circle" aria-hidden="true"></i>
                          </div>
                          <div class="pf-v6-l-flex__item">
                            <span>11</span>
                          </div>
                        </div>
                        <div class="pf-v6-l-flex pf-m-space-items-xs">
                          <div class="pf-v6-l-flex__item">
                            <i
                              class="fas fa-exclamation-triangle"
                              aria-hidden="true"
                            ></i>
                          </div>
                          <div class="pf-v6-l-flex__item">
                            <span>4</span>
                          </div>
                        </div>
                        <div class="pf-v6-l-flex pf-m-space-items-xs">
                          <div class="pf-v6-l-flex__item">
                            <i class="fas fa-times-circle" aria-hidden="true"></i>
                          </div>
                          <div class="pf-v6-l-flex__item">
                            <span>1</span>
                          </div>
                        </div>
                        <div class="pf-v6-l-flex__item">Updated 2 days ago</div>
                      </div>
                    </div>
                  </div>
                  <div
                    class="pf-v6-c-data-list__cell pf-m-align-right pf-m-no-fill"
                  >
                    <button class="pf-v6-c-button pf-m-secondary" type="button">
                      <span class="pf-v6-c-button__text">Action</span>
                    </button>
                    <button class="pf-v6-c-button pf-m-link" type="button">
                      <span class="pf-v6-c-button__text">Link</span>
                    </button>
                  </div>
                </div>
              </div>
            </li>
          </ul>
          <div class="pf-v6-c-pagination pf-m-bottom pf-m-static">
            <div class="pf-v6-c-pagination__page-menu">
              <button
                class="pf-v6-c-menu-toggle pf-m-plain pf-m-text pf-m-top"
                type="button"
                aria-expanded="false"
                aria-label="Menu toggle"
                id="{{page--id}}pagination-menu-toggle-bottom-example-static"
              >
                <span class="pf-v6-c-menu-toggle__text">
                  <b>1 - 10</b>&nbsp;of&nbsp;
                  <b>36</b>
                </span>
                <span class="pf-v6-c-menu-toggle__controls">
                  <span class="pf-v6-c-menu-toggle__toggle-icon">
                    <i class="fas fa-caret-down fa-fw" aria-hidden="true"></i>
                  </span>
                </span>
              </button>
            </div>
            <nav class="pf-v6-c-pagination__nav" aria-label="Pagination">
              <div class="pf-v6-c-pagination__nav-control pf-m-first">
                <button
                  class="pf-v6-c-button pf-m-plain"
                  type="button"
                  disabled
                  aria-label="Go to first page"
                >
                  <span class="pf-v6-c-button__icon">
                    <i class="fas fa-angle-double-left" aria-hidden="true"></i>
                  </span>
                </button>
              </div>
              <div class="pf-v6-c-pagination__nav-control pf-m-prev">
                <button
                  class="pf-v6-c-button pf-m-plain"
                  type="button"
                  disabled
                  aria-label="Go to previous page"
                >
                  <span class="pf-v6-c-button__icon">
                    <i class="fas fa-angle-left" aria-hidden="true"></i>
                  </span>
                </button>
              </div>
              <div class="pf-v6-c-pagination__nav-page-select">
                <span class="pf-v6-c-form-control">
                  <input
                    aria-label="Current page"
                    type="number"
                    min="1"
                    max="4"
                    value="1"
                  />
                </span>
                <span aria-hidden="true">of 4</span>
              </div>
              <div class="pf-v6-c-pagination__nav-control pf-m-next">
                <button
                  class="pf-v6-c-button pf-m-plain"
                  type="button"
                  aria-label="Go to next page"
                >
                  <span class="pf-v6-c-button__icon">
                    <i class="fas fa-angle-right" aria-hidden="true"></i>
                  </span>
                </button>
              </div>
              <div class="pf-v6-c-pagination__nav-control pf-m-last">
                <button
                  class="pf-v6-c-button pf-m-plain"
                  type="button"
                  disabled
                  aria-label="Go to last page"
                >
                  <span class="pf-v6-c-button__icon">
                    <i class="fas fa-angle-double-right" aria-hidden="true"></i>
                  </span>
                </button>
              </div>
            </nav>
          </div>
        </div>
      </section>
    </main>
  </div>
</div>

```
