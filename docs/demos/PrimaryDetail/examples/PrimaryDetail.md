---
id: Primary-detail
section: patterns
wrapperTag: div
---## Demos

### Primary-detail expanded

```html isFullscreen
<div class="pf-v6-c-page" id="primary-detail-expanded-example">
  <div class="pf-v6-c-skip-to-content">
    <a
      class="pf-v6-c-button pf-m-primary"
      href="#main-content-primary-detail-expanded-example"
    >
      <span class="pf-v6-c-button__text">Skip to content</span>
    </a>
  </div>
  <header
    class="pf-v6-c-masthead pf-m-display-stack pf-m-display-inline-on-lg"
    id="primary-detail-expanded-example-masthead"
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
        id="primary-detail-expanded-example-masthead-toolbar"
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
        id="primary-detail-expanded-example-primary-nav"
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
      id="main-content-primary-detail-expanded-example"
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
          <!-- Drawer -->
          <div class="pf-v6-c-drawer pf-m-expanded pf-m-inline-on-2xl">
            <div class="pf-v6-c-drawer__main">
              <!-- Content -->
              <div class="pf-v6-c-drawer__content">
                <div class="pf-v6-c-drawer__body">
                  <div
                    class="pf-v6-c-toolbar"
                    id="primary-detail-expanded-example-drawer-toolbar"
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
                              aria-controls="primary-detail-expanded-example-drawer-toolbar-expandable-content"
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
                                  id="primary-detail-expanded-example-drawer-toolbar-search-filter-menu"
                                >
                                  <span class="pf-v6-c-menu-toggle__icon">
                                    <i class="fas fa-filter" aria-hidden="true"></i>
                                  </span>
                                  <span class="pf-v6-c-menu-toggle__text">Name</span>
                                  <span class="pf-v6-c-menu-toggle__controls">
                                    <span
                                      class="pf-v6-c-menu-toggle__toggle-icon"
                                    >
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
                                  <div
                                    class="pf-v6-c-text-input-group__main pf-m-icon"
                                  >
                                    <span
                                      class="pf-v6-c-text-input-group__text"
                                    >
                                      <span
                                        class="pf-v6-c-text-input-group__icon"
                                      >
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

                          <div
                            class="pf-v6-c-toolbar__group pf-m-show-on-xl pf-m-filter-group pf-m-toggle-group"
                          >
                            <div class="pf-v6-c-toolbar__item">
                              <button
                                class="pf-v6-c-menu-toggle"
                                type="button"
                                aria-expanded="false"
                                id="primary-detail-expanded-example-drawer-toolbar-select-checkbox-status"
                              >
                                <span class="pf-v6-c-menu-toggle__text">Status</span>
                                <span class="pf-v6-c-menu-toggle__controls">
                                  <span
                                    class="pf-v6-c-menu-toggle__toggle-icon"
                                  >
                                    <i
                                      class="fas fa-caret-down fa-fw"
                                      aria-hidden="true"
                                    ></i>
                                  </span>
                                </span>
                              </button>
                            </div>
                            <div class="pf-v6-c-toolbar__item">
                              <button
                                class="pf-v6-c-menu-toggle"
                                type="button"
                                aria-expanded="false"
                                id="primary-detail-expanded-example-drawer-toolbar-select-checkbox-risk"
                              >
                                <span class="pf-v6-c-menu-toggle__text">Risk</span>
                                <span class="pf-v6-c-menu-toggle__controls">
                                  <span
                                    class="pf-v6-c-menu-toggle__toggle-icon"
                                  >
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

                        <div class="pf-v6-c-toolbar__item">
                          <button
                            class="pf-v6-c-button pf-m-plain"
                            type="button"
                            aria-label="Sort"
                          >
                            <span class="pf-v6-c-button__icon">
                              <i
                                class="fas fa-sort-amount-down pf-v6-m-mirror-inline-rtl"
                                aria-hidden="true"
                              ></i>
                            </span>
                          </button>
                        </div>

                        <div
                          class="pf-v6-c-overflow-menu"
                          id="primary-detail-expanded-example-drawer-toolbar-overflow-menu"
                        >
                          <div
                            class="pf-v6-c-overflow-menu__content pf-v6-u-display-none pf-v6-u-display-flex-on-lg"
                          >
                            <div
                              class="pf-v6-c-overflow-menu__group pf-m-button-group"
                            >
                              <div class="pf-v6-c-overflow-menu__item">
                                <button
                                  class="pf-v6-c-button pf-m-primary"
                                  type="button"
                                >
                                  <span
                                    class="pf-v6-c-button__text"
                                  >Create instance</span>
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
                              id="primary-detail-expanded-example-drawer-toolbar-overflow-menu-toggle"
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
                                id="primary-detail-expanded-example-drawer-toolbar-top-pagination"
                              >
                                <span class="pf-v6-c-menu-toggle__text">
                                  <b>1 - 10</b>&nbsp;of&nbsp;
                                  <b>36</b>
                                </span>
                                <span class="pf-v6-c-menu-toggle__controls">
                                  <span
                                    class="pf-v6-c-menu-toggle__toggle-icon"
                                  >
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
                              <div
                                class="pf-v6-c-pagination__nav-control pf-m-prev"
                              >
                                <button
                                  class="pf-v6-c-button pf-m-plain"
                                  type="button"
                                  disabled
                                  aria-label="Go to previous page"
                                >
                                  <span class="pf-v6-c-button__icon">
                                    <i
                                      class="fas fa-angle-left"
                                      aria-hidden="true"
                                    ></i>
                                  </span>
                                </button>
                              </div>
                              <div
                                class="pf-v6-c-pagination__nav-control pf-m-next"
                              >
                                <button
                                  class="pf-v6-c-button pf-m-plain"
                                  type="button"
                                  aria-label="Go to next page"
                                >
                                  <span class="pf-v6-c-button__icon">
                                    <i
                                      class="fas fa-angle-right"
                                      aria-hidden="true"
                                    ></i>
                                  </span>
                                </button>
                              </div>
                            </nav>
                          </div>
                        </div>
                      </div>

                      <div
                        class="pf-v6-c-toolbar__expandable-content pf-m-hidden"
                        id="primary-detail-expanded-example-drawer-toolbar-expandable-content"
                        hidden
                      ></div>
                    </div>
                  </div>
                  <ul
                    class="pf-v6-c-data-list"
                    role="list"
                    aria-label="Simple data list example"
                    id="primary-detail-expanded-example-data-list"
                  >
                    <li
                      class="pf-v6-c-data-list__item"
                      aria-labelledby="primary-detail-expanded-example-data-list-item-1"
                    >
                      <div class="pf-v6-c-data-list__item-row">
                        <div class="pf-v6-c-data-list__item-content">
                          <div class="pf-v6-c-data-list__cell pf-m-align-left">
                            <div
                              class="pf-v6-l-flex pf-m-column pf-m-space-items-md"
                            >
                              <div
                                class="pf-v6-l-flex pf-m-column pf-m-space-items-none"
                              >
                                <div class="pf-v6-l-flex__item">
                                  <p
                                    id="primary-detail-expanded-example-data-list-item-1"
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
                                    <i
                                      class="fas fa-code-branch"
                                      aria-hidden="true"
                                    ></i>
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
                                <div
                                  class="pf-v6-l-flex__item"
                                >Updated 2 days ago</div>
                              </div>
                            </div>
                          </div>
                          <div
                            class="pf-v6-c-data-list__cell pf-m-align-right pf-m-no-fill"
                          >
                            <button
                              class="pf-v6-c-button pf-m-secondary"
                              type="button"
                            >
                              <span class="pf-v6-c-button__text">Action</span>
                            </button>
                            <button
                              class="pf-v6-c-button pf-m-link"
                              type="button"
                            >
                              <span class="pf-v6-c-button__text">Link</span>
                            </button>
                          </div>
                        </div>
                      </div>
                    </li>

                    <li
                      class="pf-v6-c-data-list__item"
                      aria-labelledby="primary-detail-expanded-example-data-list-item-2"
                    >
                      <div class="pf-v6-c-data-list__item-row">
                        <div class="pf-v6-c-data-list__item-content">
                          <div class="pf-v6-c-data-list__cell pf-m-align-left">
                            <div
                              class="pf-v6-l-flex pf-m-column pf-m-space-items-md"
                            >
                              <div
                                class="pf-v6-l-flex pf-m-column pf-m-space-items-none"
                              >
                                <div class="pf-v6-l-flex__item">
                                  <p
                                    id="primary-detail-expanded-example-data-list-item-2"
                                  >patternfly-elements</p>
                                </div>
                                <div class="pf-v6-l-flex__item">
                                  <small>PatternFly elements</small>
                                </div>
                              </div>
                              <div class="pf-v6-l-flex pf-m-wrap">
                                <div class="pf-v6-l-flex pf-m-space-items-xs">
                                  <div class="pf-v6-l-flex__item">
                                    <i
                                      class="fas fa-code-branch"
                                      aria-hidden="true"
                                    ></i>
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
                                    <i
                                      class="fas fa-check-circle"
                                      aria-hidden="true"
                                    ></i>
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
                                    <i
                                      class="fas fa-times-circle"
                                      aria-hidden="true"
                                    ></i>
                                  </div>
                                  <div class="pf-v6-l-flex__item">
                                    <span>1</span>
                                  </div>
                                </div>
                                <div
                                  class="pf-v6-l-flex__item"
                                >Updated 2 days ago</div>
                              </div>
                            </div>
                          </div>
                          <div
                            class="pf-v6-c-data-list__cell pf-m-align-right pf-m-no-fill"
                          >
                            <button
                              class="pf-v6-c-button pf-m-secondary"
                              type="button"
                            >
                              <span class="pf-v6-c-button__text">Action</span>
                            </button>
                            <button
                              class="pf-v6-c-button pf-m-link"
                              type="button"
                            >
                              <span class="pf-v6-c-button__text">Link</span>
                            </button>
                          </div>
                        </div>
                      </div>
                    </li>

                    <li
                      class="pf-v6-c-data-list__item"
                      aria-labelledby="primary-detail-expanded-example-data-list-item-3"
                    >
                      <div class="pf-v6-c-data-list__item-row">
                        <div class="pf-v6-c-data-list__item-content">
                          <div class="pf-v6-c-data-list__cell pf-m-align-left">
                            <p
                              id="primary-detail-expanded-example-data-list-item-3"
                            >patternfly-unified-design-kit</p>
                          </div>
                          <div
                            class="pf-v6-c-data-list__cell pf-m-align-right pf-m-no-fill"
                          >
                            <button
                              class="pf-v6-c-button pf-m-secondary"
                              type="button"
                            >
                              <span class="pf-v6-c-button__text">Action</span>
                            </button>
                            <button
                              class="pf-v6-c-button pf-m-link"
                              type="button"
                            >
                              <span class="pf-v6-c-button__text">Link</span>
                            </button>
                          </div>
                        </div>
                      </div>
                    </li>

                    <li
                      class="pf-v6-c-data-list__item"
                      aria-labelledby="primary-detail-expanded-example-data-list-item-4"
                    >
                      <div class="pf-v6-c-data-list__item-row">
                        <div class="pf-v6-c-data-list__item-content">
                          <div class="pf-v6-c-data-list__cell pf-m-align-left">
                            <div
                              class="pf-v6-l-flex pf-m-column pf-m-space-items-md"
                            >
                              <div
                                class="pf-v6-l-flex pf-m-column pf-m-space-items-none"
                              >
                                <div class="pf-v6-l-flex__item">
                                  <p
                                    id="primary-detail-expanded-example-data-list-item-4"
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
                                    <i
                                      class="fas fa-code-branch"
                                      aria-hidden="true"
                                    ></i>
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
                                <div
                                  class="pf-v6-l-flex__item"
                                >Updated 2 days ago</div>
                              </div>
                            </div>
                          </div>
                          <div
                            class="pf-v6-c-data-list__cell pf-m-align-right pf-m-no-fill"
                          >
                            <button
                              class="pf-v6-c-button pf-m-secondary"
                              type="button"
                            >
                              <span class="pf-v6-c-button__text">Action</span>
                            </button>
                            <button
                              class="pf-v6-c-button pf-m-link"
                              type="button"
                            >
                              <span class="pf-v6-c-button__text">Link</span>
                            </button>
                          </div>
                        </div>
                      </div>
                    </li>

                    <li
                      class="pf-v6-c-data-list__item"
                      aria-labelledby="primary-detail-expanded-example-data-list-item-5"
                    >
                      <div class="pf-v6-c-data-list__item-row">
                        <div class="pf-v6-c-data-list__item-content">
                          <div class="pf-v6-c-data-list__cell pf-m-align-left">
                            <div
                              class="pf-v6-l-flex pf-m-column pf-m-space-items-md"
                            >
                              <div
                                class="pf-v6-l-flex pf-m-column pf-m-space-items-none"
                              >
                                <div class="pf-v6-l-flex__item">
                                  <p
                                    id="primary-detail-expanded-example-data-list-item-5"
                                  >patternfly-elements</p>
                                </div>
                                <div class="pf-v6-l-flex__item">
                                  <small>PatternFly elements</small>
                                </div>
                              </div>
                              <div class="pf-v6-l-flex pf-m-wrap">
                                <div class="pf-v6-l-flex pf-m-space-items-xs">
                                  <div class="pf-v6-l-flex__item">
                                    <i
                                      class="fas fa-code-branch"
                                      aria-hidden="true"
                                    ></i>
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
                                    <i
                                      class="fas fa-check-circle"
                                      aria-hidden="true"
                                    ></i>
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
                                    <i
                                      class="fas fa-times-circle"
                                      aria-hidden="true"
                                    ></i>
                                  </div>
                                  <div class="pf-v6-l-flex__item">
                                    <span>1</span>
                                  </div>
                                </div>
                                <div
                                  class="pf-v6-l-flex__item"
                                >Updated 2 days ago</div>
                              </div>
                            </div>
                          </div>
                          <div
                            class="pf-v6-c-data-list__cell pf-m-align-right pf-m-no-fill"
                          >
                            <button
                              class="pf-v6-c-button pf-m-secondary"
                              type="button"
                            >
                              <span class="pf-v6-c-button__text">Action</span>
                            </button>
                            <button
                              class="pf-v6-c-button pf-m-link"
                              type="button"
                            >
                              <span class="pf-v6-c-button__text">Link</span>
                            </button>
                          </div>
                        </div>
                      </div>
                    </li>
                  </ul>
                </div>
              </div>

              <!-- Panel -->
              <div class="pf-v6-c-drawer__panel">
                <!-- Panel header -->
                <div class="pf-v6-c-drawer__body">
                  <div class="pf-v6-l-flex pf-m-column">
                    <div class="pf-v6-l-flex__item">
                      <div class="pf-v6-c-drawer__head">
                        <div class="pf-v6-c-drawer__actions">
                          <div class="pf-v6-c-drawer__close">
                            <button
                              class="pf-v6-c-button pf-m-plain"
                              type="button"
                              aria-label="Close drawer panel"
                            >
                              <span class="pf-v6-c-button__icon">
                                <i class="fas fa-times" aria-hidden="true"></i>
                              </span>
                            </button>
                          </div>
                        </div>
                        <h2
                          class="pf-v6-c-title pf-m-lg"
                          id="primary-detail-expanded-example-drawer-drawer-label"
                        >Node 2</h2>
                      </div>
                    </div>
                    <div class="pf-v6-l-flex__item">
                      <a href="#">siemur/test-space</a>
                    </div>
                  </div>
                </div>

                <!-- Tabs -->
                <div class="pf-v6-c-drawer__body pf-m-no-padding">
                  <div
                    class="pf-v6-c-tabs pf-m-box pf-m-fill"
                    role="region"
                    id="primary-detail-expanded-example-drawer-tabs"
                  >
                    <div class="pf-v6-c-tabs__scroll-button">
                      <button
                        class="pf-v6-c-button pf-m-plain"
                        type="button"
                        aria-label="Scroll left"
                      >
                        <span class="pf-v6-c-button__icon">
                          <i class="fas fa-angle-left" aria-hidden="true"></i>
                        </span>
                      </button>
                    </div>
                    <ul class="pf-v6-c-tabs__list" role="tablist">
                      <li
                        class="pf-v6-c-tabs__item pf-m-current"
                        role="presentation"
                      >
                        <button
                          type="button"
                          class="pf-v6-c-tabs__link"
                          role="tab"
                          aria-controls="primary-detail-expanded-example-drawer-tabs-tab1-panel"
                          id="primary-detail-expanded-example-drawer-tabs-tab1-link"
                        >
                          <span class="pf-v6-c-tabs__item-text">Overview</span>
                        </button>
                      </li>
                      <li class="pf-v6-c-tabs__item" role="presentation">
                        <button
                          type="button"
                          class="pf-v6-c-tabs__link"
                          role="tab"
                          aria-controls="primary-detail-expanded-example-drawer-tabs-tab2-panel"
                          id="primary-detail-expanded-example-drawer-tabs-tab2-link"
                        >
                          <span class="pf-v6-c-tabs__item-text">Activity</span>
                        </button>
                      </li>
                    </ul>
                    <div class="pf-v6-c-tabs__scroll-button">
                      <button
                        class="pf-v6-c-button pf-m-plain"
                        type="button"
                        aria-label="Scroll right"
                      >
                        <span class="pf-v6-c-button__icon">
                          <i class="fas fa-angle-right" aria-hidden="true"></i>
                        </span>
                      </button>
                    </div>
                  </div>
                </div>

                <!-- Tab content -->
                <div class="pf-v6-c-drawer__body">
                  <section
                    class="pf-v6-c-tab-content"
                    id="primary-detail-expanded-example-drawer-tabs-tab1-panel"
                    aria-labelledby="primary-detail-expanded-example-drawer-tabs-tab1-link"
                    role="tabpanel"
                    tabindex="0"
                  >
                    <div class="pf-v6-c-tab-content__body">
                      <div class="pf-v6-l-flex pf-m-column pf-m-space-items-lg">
                        <div class="pf-v6-l-flex__item">
                          <p>The content of the drawer really is up to you. It could have form fields, definition lists, text lists, labels, charts, progress bars, etc. Spacing recommendation is 24px margins. You can put tabs in here, and can also make the drawer scrollable.</p>
                        </div>
                        <div class="pf-v6-l-flex__item">
                          <div
                            class="pf-v6-c-progress pf-m-sm"
                            id="primary-detail-expanded-example-drawer-progress-example1"
                          >
                            <div
                              class="pf-v6-c-progress__description"
                              id="primary-detail-expanded-example-drawer-progress-example1-description"
                            >Capacity</div>
                            <div
                              class="pf-v6-c-progress__status"
                              aria-hidden="true"
                            >
                              <span class="pf-v6-c-progress__measure">33%</span>
                            </div>
                            <div
                              class="pf-v6-c-progress__bar"
                              role="progressbar"
                              aria-valuemin="0"
                              aria-valuemax="100"
                              aria-valuenow="33"
                              aria-labelledby="primary-detail-expanded-example-drawer-progress-example1-description"
                              aria-label="Progress 1"
                            >
                              <div
                                class="pf-v6-c-progress__indicator"
                                style="width:33%;"
                              ></div>
                            </div>
                          </div>
                        </div>
                        <div class="pf-v6-l-flex__item">
                          <div
                            class="pf-v6-c-progress pf-m-sm"
                            id="primary-detail-expanded-example-drawer-progress-example2"
                          >
                            <div
                              class="pf-v6-c-progress__description"
                              id="primary-detail-expanded-example-drawer-progress-example2-description"
                            >Modules</div>
                            <div
                              class="pf-v6-c-progress__status"
                              aria-hidden="true"
                            >
                              <span class="pf-v6-c-progress__measure">66%</span>
                            </div>
                            <div
                              class="pf-v6-c-progress__bar"
                              role="progressbar"
                              aria-valuemin="0"
                              aria-valuemax="100"
                              aria-valuenow="66"
                              aria-labelledby="primary-detail-expanded-example-drawer-progress-example2-description"
                              aria-label="Progress 2"
                            >
                              <div
                                class="pf-v6-c-progress__indicator"
                                style="width:66%;"
                              ></div>
                            </div>
                          </div>
                        </div>
                      </div>
                    </div>
                  </section>
                  <section
                    class="pf-v6-c-tab-content"
                    id="primary-detail-expanded-example-drawer-tabs-tab2-panel"
                    aria-labelledby="primary-detail-expanded-example-drawer-tabs-tab2-link"
                    role="tabpanel"
                    tabindex="0"
                    hidden
                  >
                    <div class="pf-v6-c-tab-content__body">Panel 2</div>
                  </section>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>
    </main>
  </div>
</div>

```

### Primary-detail collapsed

```html isFullscreen
<div class="pf-v6-c-page" id="primary-detail-collapsed-example">
  <div class="pf-v6-c-skip-to-content">
    <a
      class="pf-v6-c-button pf-m-primary"
      href="#main-content-primary-detail-collapsed-example"
    >
      <span class="pf-v6-c-button__text">Skip to content</span>
    </a>
  </div>
  <header
    class="pf-v6-c-masthead pf-m-display-stack pf-m-display-inline-on-lg"
    id="primary-detail-collapsed-example-masthead"
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
        id="primary-detail-collapsed-example-masthead-toolbar"
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
        id="primary-detail-collapsed-example-primary-nav"
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
      id="main-content-primary-detail-collapsed-example"
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
      <div class="pf-v6-c-divider" role="separator"></div>
      <section class="pf-v6-c-page__main-section">
        <div class="pf-v6-c-page__main-body">
          <!-- Drawer -->
          <div class="pf-v6-c-drawer pf-m-inline-on-2xl">
            <div class="pf-v6-c-drawer__main">
              <!-- Content -->
              <div class="pf-v6-c-drawer__content">
                <div class="pf-v6-c-drawer__body">
                  <div
                    class="pf-v6-c-toolbar"
                    id="primary-detail-collapsed-example-drawer-toolbar"
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
                              aria-controls="primary-detail-collapsed-example-drawer-toolbar-expandable-content"
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
                                  id="primary-detail-collapsed-example-drawer-toolbar-search-filter-menu"
                                >
                                  <span class="pf-v6-c-menu-toggle__icon">
                                    <i class="fas fa-filter" aria-hidden="true"></i>
                                  </span>
                                  <span class="pf-v6-c-menu-toggle__text">Name</span>
                                  <span class="pf-v6-c-menu-toggle__controls">
                                    <span
                                      class="pf-v6-c-menu-toggle__toggle-icon"
                                    >
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
                                  <div
                                    class="pf-v6-c-text-input-group__main pf-m-icon"
                                  >
                                    <span
                                      class="pf-v6-c-text-input-group__text"
                                    >
                                      <span
                                        class="pf-v6-c-text-input-group__icon"
                                      >
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

                          <div
                            class="pf-v6-c-toolbar__group pf-m-show-on-xl pf-m-filter-group pf-m-toggle-group"
                          >
                            <div class="pf-v6-c-toolbar__item">
                              <button
                                class="pf-v6-c-menu-toggle"
                                type="button"
                                aria-expanded="false"
                                id="primary-detail-collapsed-example-drawer-toolbar-select-checkbox-status"
                              >
                                <span class="pf-v6-c-menu-toggle__text">Status</span>
                                <span class="pf-v6-c-menu-toggle__controls">
                                  <span
                                    class="pf-v6-c-menu-toggle__toggle-icon"
                                  >
                                    <i
                                      class="fas fa-caret-down fa-fw"
                                      aria-hidden="true"
                                    ></i>
                                  </span>
                                </span>
                              </button>
                            </div>
                            <div class="pf-v6-c-toolbar__item">
                              <button
                                class="pf-v6-c-menu-toggle"
                                type="button"
                                aria-expanded="false"
                                id="primary-detail-collapsed-example-drawer-toolbar-select-checkbox-risk"
                              >
                                <span class="pf-v6-c-menu-toggle__text">Risk</span>
                                <span class="pf-v6-c-menu-toggle__controls">
                                  <span
                                    class="pf-v6-c-menu-toggle__toggle-icon"
                                  >
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

                        <div class="pf-v6-c-toolbar__item">
                          <button
                            class="pf-v6-c-button pf-m-plain"
                            type="button"
                            aria-label="Sort"
                          >
                            <span class="pf-v6-c-button__icon">
                              <i
                                class="fas fa-sort-amount-down pf-v6-m-mirror-inline-rtl"
                                aria-hidden="true"
                              ></i>
                            </span>
                          </button>
                        </div>

                        <div
                          class="pf-v6-c-overflow-menu"
                          id="primary-detail-collapsed-example-drawer-toolbar-overflow-menu"
                        >
                          <div
                            class="pf-v6-c-overflow-menu__content pf-v6-u-display-none pf-v6-u-display-flex-on-lg"
                          >
                            <div
                              class="pf-v6-c-overflow-menu__group pf-m-button-group"
                            >
                              <div class="pf-v6-c-overflow-menu__item">
                                <button
                                  class="pf-v6-c-button pf-m-primary"
                                  type="button"
                                >
                                  <span
                                    class="pf-v6-c-button__text"
                                  >Create instance</span>
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
                              id="primary-detail-collapsed-example-drawer-toolbar-overflow-menu-toggle"
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
                                id="primary-detail-collapsed-example-drawer-toolbar-top-pagination"
                              >
                                <span class="pf-v6-c-menu-toggle__text">
                                  <b>1 - 10</b>&nbsp;of&nbsp;
                                  <b>36</b>
                                </span>
                                <span class="pf-v6-c-menu-toggle__controls">
                                  <span
                                    class="pf-v6-c-menu-toggle__toggle-icon"
                                  >
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
                              <div
                                class="pf-v6-c-pagination__nav-control pf-m-prev"
                              >
                                <button
                                  class="pf-v6-c-button pf-m-plain"
                                  type="button"
                                  disabled
                                  aria-label="Go to previous page"
                                >
                                  <span class="pf-v6-c-button__icon">
                                    <i
                                      class="fas fa-angle-left"
                                      aria-hidden="true"
                                    ></i>
                                  </span>
                                </button>
                              </div>
                              <div
                                class="pf-v6-c-pagination__nav-control pf-m-next"
                              >
                                <button
                                  class="pf-v6-c-button pf-m-plain"
                                  type="button"
                                  aria-label="Go to next page"
                                >
                                  <span class="pf-v6-c-button__icon">
                                    <i
                                      class="fas fa-angle-right"
                                      aria-hidden="true"
                                    ></i>
                                  </span>
                                </button>
                              </div>
                            </nav>
                          </div>
                        </div>
                      </div>

                      <div
                        class="pf-v6-c-toolbar__expandable-content pf-m-hidden"
                        id="primary-detail-collapsed-example-drawer-toolbar-expandable-content"
                        hidden
                      ></div>
                    </div>
                  </div>
                  <ul
                    class="pf-v6-c-data-list"
                    role="list"
                    aria-label="Simple data list example"
                    id="primary-detail-collapsed-example-data-list"
                  >
                    <li
                      class="pf-v6-c-data-list__item"
                      aria-labelledby="primary-detail-collapsed-example-data-list-item-1"
                    >
                      <div class="pf-v6-c-data-list__item-row">
                        <div class="pf-v6-c-data-list__item-content">
                          <div class="pf-v6-c-data-list__cell pf-m-align-left">
                            <div
                              class="pf-v6-l-flex pf-m-column pf-m-space-items-md"
                            >
                              <div
                                class="pf-v6-l-flex pf-m-column pf-m-space-items-none"
                              >
                                <div class="pf-v6-l-flex__item">
                                  <p
                                    id="primary-detail-collapsed-example-data-list-item-1"
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
                                    <i
                                      class="fas fa-code-branch"
                                      aria-hidden="true"
                                    ></i>
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
                                <div
                                  class="pf-v6-l-flex__item"
                                >Updated 2 days ago</div>
                              </div>
                            </div>
                          </div>
                          <div
                            class="pf-v6-c-data-list__cell pf-m-align-right pf-m-no-fill"
                          >
                            <button
                              class="pf-v6-c-button pf-m-secondary"
                              type="button"
                            >
                              <span class="pf-v6-c-button__text">Action</span>
                            </button>
                            <button
                              class="pf-v6-c-button pf-m-link"
                              type="button"
                            >
                              <span class="pf-v6-c-button__text">Link</span>
                            </button>
                          </div>
                        </div>
                      </div>
                    </li>

                    <li
                      class="pf-v6-c-data-list__item"
                      aria-labelledby="primary-detail-collapsed-example-data-list-item-2"
                    >
                      <div class="pf-v6-c-data-list__item-row">
                        <div class="pf-v6-c-data-list__item-content">
                          <div class="pf-v6-c-data-list__cell pf-m-align-left">
                            <div
                              class="pf-v6-l-flex pf-m-column pf-m-space-items-md"
                            >
                              <div
                                class="pf-v6-l-flex pf-m-column pf-m-space-items-none"
                              >
                                <div class="pf-v6-l-flex__item">
                                  <p
                                    id="primary-detail-collapsed-example-data-list-item-2"
                                  >patternfly-elements</p>
                                </div>
                                <div class="pf-v6-l-flex__item">
                                  <small>PatternFly elements</small>
                                </div>
                              </div>
                              <div class="pf-v6-l-flex pf-m-wrap">
                                <div class="pf-v6-l-flex pf-m-space-items-xs">
                                  <div class="pf-v6-l-flex__item">
                                    <i
                                      class="fas fa-code-branch"
                                      aria-hidden="true"
                                    ></i>
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
                                    <i
                                      class="fas fa-check-circle"
                                      aria-hidden="true"
                                    ></i>
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
                                    <i
                                      class="fas fa-times-circle"
                                      aria-hidden="true"
                                    ></i>
                                  </div>
                                  <div class="pf-v6-l-flex__item">
                                    <span>1</span>
                                  </div>
                                </div>
                                <div
                                  class="pf-v6-l-flex__item"
                                >Updated 2 days ago</div>
                              </div>
                            </div>
                          </div>
                          <div
                            class="pf-v6-c-data-list__cell pf-m-align-right pf-m-no-fill"
                          >
                            <button
                              class="pf-v6-c-button pf-m-secondary"
                              type="button"
                            >
                              <span class="pf-v6-c-button__text">Action</span>
                            </button>
                            <button
                              class="pf-v6-c-button pf-m-link"
                              type="button"
                            >
                              <span class="pf-v6-c-button__text">Link</span>
                            </button>
                          </div>
                        </div>
                      </div>
                    </li>

                    <li
                      class="pf-v6-c-data-list__item"
                      aria-labelledby="primary-detail-collapsed-example-data-list-item-3"
                    >
                      <div class="pf-v6-c-data-list__item-row">
                        <div class="pf-v6-c-data-list__item-content">
                          <div class="pf-v6-c-data-list__cell pf-m-align-left">
                            <p
                              id="primary-detail-collapsed-example-data-list-item-3"
                            >patternfly-unified-design-kit</p>
                          </div>
                          <div
                            class="pf-v6-c-data-list__cell pf-m-align-right pf-m-no-fill"
                          >
                            <button
                              class="pf-v6-c-button pf-m-secondary"
                              type="button"
                            >
                              <span class="pf-v6-c-button__text">Action</span>
                            </button>
                            <button
                              class="pf-v6-c-button pf-m-link"
                              type="button"
                            >
                              <span class="pf-v6-c-button__text">Link</span>
                            </button>
                          </div>
                        </div>
                      </div>
                    </li>

                    <li
                      class="pf-v6-c-data-list__item"
                      aria-labelledby="primary-detail-collapsed-example-data-list-item-4"
                    >
                      <div class="pf-v6-c-data-list__item-row">
                        <div class="pf-v6-c-data-list__item-content">
                          <div class="pf-v6-c-data-list__cell pf-m-align-left">
                            <div
                              class="pf-v6-l-flex pf-m-column pf-m-space-items-md"
                            >
                              <div
                                class="pf-v6-l-flex pf-m-column pf-m-space-items-none"
                              >
                                <div class="pf-v6-l-flex__item">
                                  <p
                                    id="primary-detail-collapsed-example-data-list-item-4"
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
                                    <i
                                      class="fas fa-code-branch"
                                      aria-hidden="true"
                                    ></i>
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
                                <div
                                  class="pf-v6-l-flex__item"
                                >Updated 2 days ago</div>
                              </div>
                            </div>
                          </div>
                          <div
                            class="pf-v6-c-data-list__cell pf-m-align-right pf-m-no-fill"
                          >
                            <button
                              class="pf-v6-c-button pf-m-secondary"
                              type="button"
                            >
                              <span class="pf-v6-c-button__text">Action</span>
                            </button>
                            <button
                              class="pf-v6-c-button pf-m-link"
                              type="button"
                            >
                              <span class="pf-v6-c-button__text">Link</span>
                            </button>
                          </div>
                        </div>
                      </div>
                    </li>

                    <li
                      class="pf-v6-c-data-list__item"
                      aria-labelledby="primary-detail-collapsed-example-data-list-item-5"
                    >
                      <div class="pf-v6-c-data-list__item-row">
                        <div class="pf-v6-c-data-list__item-content">
                          <div class="pf-v6-c-data-list__cell pf-m-align-left">
                            <div
                              class="pf-v6-l-flex pf-m-column pf-m-space-items-md"
                            >
                              <div
                                class="pf-v6-l-flex pf-m-column pf-m-space-items-none"
                              >
                                <div class="pf-v6-l-flex__item">
                                  <p
                                    id="primary-detail-collapsed-example-data-list-item-5"
                                  >patternfly-elements</p>
                                </div>
                                <div class="pf-v6-l-flex__item">
                                  <small>PatternFly elements</small>
                                </div>
                              </div>
                              <div class="pf-v6-l-flex pf-m-wrap">
                                <div class="pf-v6-l-flex pf-m-space-items-xs">
                                  <div class="pf-v6-l-flex__item">
                                    <i
                                      class="fas fa-code-branch"
                                      aria-hidden="true"
                                    ></i>
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
                                    <i
                                      class="fas fa-check-circle"
                                      aria-hidden="true"
                                    ></i>
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
                                    <i
                                      class="fas fa-times-circle"
                                      aria-hidden="true"
                                    ></i>
                                  </div>
                                  <div class="pf-v6-l-flex__item">
                                    <span>1</span>
                                  </div>
                                </div>
                                <div
                                  class="pf-v6-l-flex__item"
                                >Updated 2 days ago</div>
                              </div>
                            </div>
                          </div>
                          <div
                            class="pf-v6-c-data-list__cell pf-m-align-right pf-m-no-fill"
                          >
                            <button
                              class="pf-v6-c-button pf-m-secondary"
                              type="button"
                            >
                              <span class="pf-v6-c-button__text">Action</span>
                            </button>
                            <button
                              class="pf-v6-c-button pf-m-link"
                              type="button"
                            >
                              <span class="pf-v6-c-button__text">Link</span>
                            </button>
                          </div>
                        </div>
                      </div>
                    </li>
                  </ul>
                </div>
              </div>

              <!-- Panel -->
              <div class="pf-v6-c-drawer__panel" hidden>
                <!-- Panel header -->
                <div class="pf-v6-c-drawer__body">
                  <div class="pf-v6-l-flex pf-m-column">
                    <div class="pf-v6-l-flex__item">
                      <div class="pf-v6-c-drawer__head">
                        <div class="pf-v6-c-drawer__actions">
                          <div class="pf-v6-c-drawer__close">
                            <button
                              class="pf-v6-c-button pf-m-plain"
                              type="button"
                              aria-label="Close drawer panel"
                            >
                              <span class="pf-v6-c-button__icon">
                                <i class="fas fa-times" aria-hidden="true"></i>
                              </span>
                            </button>
                          </div>
                        </div>
                        <h2
                          class="pf-v6-c-title pf-m-lg"
                          id="primary-detail-collapsed-example-drawer-drawer-label"
                        >Patternfly-elements</h2>
                      </div>
                    </div>
                    <div class="pf-v6-l-flex__item">PatternFly elements</div>
                  </div>
                </div>

                <!-- Tab content -->
                <div class="pf-v6-c-drawer__body">
                  <div class="pf-v6-l-flex pf-m-column pf-m-space-items-lg">
                    <div class="pf-v6-l-flex__item">
                      <p>The content of the drawer really is up to you. It could have form fields, definition lists, text lists, labels, charts, progress bars, etc. Spacing recommendation is 24px margins. You can put tabs in here, and can also make the drawer scrollable.</p>
                    </div>
                    <div class="pf-v6-l-flex__item">
                      <div
                        class="pf-v6-c-progress pf-m-sm"
                        id="primary-detail-collapsed-example-drawer-progress-example1"
                      >
                        <div
                          class="pf-v6-c-progress__description"
                          id="primary-detail-collapsed-example-drawer-progress-example1-description"
                        >Capacity</div>
                        <div
                          class="pf-v6-c-progress__status"
                          aria-hidden="true"
                        >
                          <span class="pf-v6-c-progress__measure">33%</span>
                        </div>
                        <div
                          class="pf-v6-c-progress__bar"
                          role="progressbar"
                          aria-valuemin="0"
                          aria-valuemax="100"
                          aria-valuenow="33"
                          aria-labelledby="primary-detail-collapsed-example-drawer-progress-example1-description"
                          aria-label="Progress 1"
                        >
                          <div
                            class="pf-v6-c-progress__indicator"
                            style="width:33%;"
                          ></div>
                        </div>
                      </div>
                    </div>
                    <div class="pf-v6-l-flex__item">
                      <div
                        class="pf-v6-c-progress pf-m-sm"
                        id="primary-detail-collapsed-example-drawer-progress-example2"
                      >
                        <div
                          class="pf-v6-c-progress__description"
                          id="primary-detail-collapsed-example-drawer-progress-example2-description"
                        >Modules</div>
                        <div
                          class="pf-v6-c-progress__status"
                          aria-hidden="true"
                        >
                          <span class="pf-v6-c-progress__measure">66%</span>
                        </div>
                        <div
                          class="pf-v6-c-progress__bar"
                          role="progressbar"
                          aria-valuemin="0"
                          aria-valuemax="100"
                          aria-valuenow="66"
                          aria-labelledby="primary-detail-collapsed-example-drawer-progress-example2-description"
                          aria-label="Progress 2"
                        >
                          <div
                            class="pf-v6-c-progress__indicator"
                            style="width:66%;"
                          ></div>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>
    </main>
  </div>
</div>

```

### Primary-detail content body padding

```html isFullscreen
<div class="pf-v6-c-page" id="primary-detail-content-body-padding-example">
  <div class="pf-v6-c-skip-to-content">
    <a
      class="pf-v6-c-button pf-m-primary"
      href="#main-content-primary-detail-content-body-padding-example"
    >
      <span class="pf-v6-c-button__text">Skip to content</span>
    </a>
  </div>
  <header
    class="pf-v6-c-masthead pf-m-display-stack pf-m-display-inline-on-lg"
    id="primary-detail-content-body-padding-example-masthead"
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
        id="primary-detail-content-body-padding-example-masthead-toolbar"
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
        id="primary-detail-content-body-padding-example-primary-nav"
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
      id="main-content-primary-detail-content-body-padding-example"
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
      <div class="pf-v6-c-divider" role="separator"></div>
      <section class="pf-v6-c-page__main-section pf-m-no-padding">
        <div class="pf-v6-c-page__main-body">
          <!-- Drawer -->
          <div class="pf-v6-c-drawer pf-m-expanded pf-m-inline-on-2xl">
            <div class="pf-v6-c-drawer__main">
              <!-- Content -->
              <div class="pf-v6-c-drawer__content pf-m-no-background">
                <div class="pf-v6-c-drawer__body pf-m-padding">
                  <div
                    class="pf-v6-c-toolbar"
                    id="primary-detail-content-body-padding-example-drawer-toolbar"
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
                              aria-controls="primary-detail-content-body-padding-example-drawer-toolbar-expandable-content"
                            >
                              <span class="pf-v6-c-menu-toggle__icon">
                                <i class="fas fa-filter" aria-hidden="true"></i>
                              </span>
                            </button>
                          </div>

                          <div
                            class="pf-v6-c-toolbar__group pf-m-show-on-xl pf-m-filter-group pf-m-toggle-group"
                          >
                            <div class="pf-v6-c-toolbar__item">
                              <button
                                class="pf-v6-c-menu-toggle"
                                type="button"
                                aria-expanded="false"
                                id="primary-detail-content-body-padding-example-drawer-toolbar-select-checkbox-status"
                              >
                                <span class="pf-v6-c-menu-toggle__text">Status</span>
                                <span class="pf-v6-c-menu-toggle__controls">
                                  <span
                                    class="pf-v6-c-menu-toggle__toggle-icon"
                                  >
                                    <i
                                      class="fas fa-caret-down fa-fw"
                                      aria-hidden="true"
                                    ></i>
                                  </span>
                                </span>
                              </button>
                            </div>
                            <div class="pf-v6-c-toolbar__item">
                              <button
                                class="pf-v6-c-menu-toggle"
                                type="button"
                                aria-expanded="false"
                                id="primary-detail-content-body-padding-example-drawer-toolbar-select-checkbox-risk"
                              >
                                <span class="pf-v6-c-menu-toggle__text">Risk</span>
                                <span class="pf-v6-c-menu-toggle__controls">
                                  <span
                                    class="pf-v6-c-menu-toggle__toggle-icon"
                                  >
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

                        <div class="pf-v6-c-toolbar__item">
                          <button
                            class="pf-v6-c-button pf-m-plain"
                            type="button"
                            aria-label="Sort"
                          >
                            <span class="pf-v6-c-button__icon">
                              <i
                                class="fas fa-sort-amount-down pf-v6-m-mirror-inline-rtl"
                                aria-hidden="true"
                              ></i>
                            </span>
                          </button>
                        </div>

                        <div
                          class="pf-v6-c-overflow-menu"
                          id="primary-detail-content-body-padding-example-drawer-toolbar-overflow-menu"
                        >
                          <div
                            class="pf-v6-c-overflow-menu__content pf-v6-u-display-none pf-v6-u-display-flex-on-lg"
                          >
                            <div
                              class="pf-v6-c-overflow-menu__group pf-m-button-group"
                            >
                              <div class="pf-v6-c-overflow-menu__item">
                                <button
                                  class="pf-v6-c-button pf-m-primary"
                                  type="button"
                                >
                                  <span
                                    class="pf-v6-c-button__text"
                                  >Create instance</span>
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
                              id="primary-detail-content-body-padding-example-drawer-toolbar-overflow-menu-toggle"
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
                                id="primary-detail-content-body-padding-example-drawer-toolbar-top-pagination"
                              >
                                <span class="pf-v6-c-menu-toggle__text">
                                  <b>1 - 10</b>&nbsp;of&nbsp;
                                  <b>36</b>
                                </span>
                                <span class="pf-v6-c-menu-toggle__controls">
                                  <span
                                    class="pf-v6-c-menu-toggle__toggle-icon"
                                  >
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
                              <div
                                class="pf-v6-c-pagination__nav-control pf-m-prev"
                              >
                                <button
                                  class="pf-v6-c-button pf-m-plain"
                                  type="button"
                                  disabled
                                  aria-label="Go to previous page"
                                >
                                  <span class="pf-v6-c-button__icon">
                                    <i
                                      class="fas fa-angle-left"
                                      aria-hidden="true"
                                    ></i>
                                  </span>
                                </button>
                              </div>
                              <div
                                class="pf-v6-c-pagination__nav-control pf-m-next"
                              >
                                <button
                                  class="pf-v6-c-button pf-m-plain"
                                  type="button"
                                  aria-label="Go to next page"
                                >
                                  <span class="pf-v6-c-button__icon">
                                    <i
                                      class="fas fa-angle-right"
                                      aria-hidden="true"
                                    ></i>
                                  </span>
                                </button>
                              </div>
                            </nav>
                          </div>
                        </div>
                      </div>

                      <div
                        class="pf-v6-c-toolbar__expandable-content pf-m-hidden"
                        id="primary-detail-content-body-padding-example-drawer-toolbar-expandable-content"
                        hidden
                      ></div>
                    </div>
                  </div>
                  <ul
                    class="pf-v6-c-data-list"
                    role="list"
                    aria-label="Simple data list example"
                    id="primary-detail-content-body-padding-example-data-list"
                  >
                    <li
                      class="pf-v6-c-data-list__item"
                      aria-labelledby="primary-detail-content-body-padding-example-data-list-item-1"
                    >
                      <div class="pf-v6-c-data-list__item-row">
                        <div class="pf-v6-c-data-list__item-content">
                          <div class="pf-v6-c-data-list__cell pf-m-align-left">
                            <div
                              class="pf-v6-l-flex pf-m-column pf-m-space-items-md"
                            >
                              <div
                                class="pf-v6-l-flex pf-m-column pf-m-space-items-none"
                              >
                                <div class="pf-v6-l-flex__item">
                                  <p
                                    id="primary-detail-content-body-padding-example-data-list-item-1"
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
                                    <i
                                      class="fas fa-code-branch"
                                      aria-hidden="true"
                                    ></i>
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
                                <div
                                  class="pf-v6-l-flex__item"
                                >Updated 2 days ago</div>
                              </div>
                            </div>
                          </div>
                          <div
                            class="pf-v6-c-data-list__cell pf-m-align-right pf-m-no-fill"
                          >
                            <button
                              class="pf-v6-c-button pf-m-secondary"
                              type="button"
                            >
                              <span class="pf-v6-c-button__text">Action</span>
                            </button>
                            <button
                              class="pf-v6-c-button pf-m-link"
                              type="button"
                            >
                              <span class="pf-v6-c-button__text">Link</span>
                            </button>
                          </div>
                        </div>
                      </div>
                    </li>

                    <li
                      class="pf-v6-c-data-list__item"
                      aria-labelledby="primary-detail-content-body-padding-example-data-list-item-2"
                    >
                      <div class="pf-v6-c-data-list__item-row">
                        <div class="pf-v6-c-data-list__item-content">
                          <div class="pf-v6-c-data-list__cell pf-m-align-left">
                            <div
                              class="pf-v6-l-flex pf-m-column pf-m-space-items-md"
                            >
                              <div
                                class="pf-v6-l-flex pf-m-column pf-m-space-items-none"
                              >
                                <div class="pf-v6-l-flex__item">
                                  <p
                                    id="primary-detail-content-body-padding-example-data-list-item-2"
                                  >patternfly-elements</p>
                                </div>
                                <div class="pf-v6-l-flex__item">
                                  <small>PatternFly elements</small>
                                </div>
                              </div>
                              <div class="pf-v6-l-flex pf-m-wrap">
                                <div class="pf-v6-l-flex pf-m-space-items-xs">
                                  <div class="pf-v6-l-flex__item">
                                    <i
                                      class="fas fa-code-branch"
                                      aria-hidden="true"
                                    ></i>
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
                                    <i
                                      class="fas fa-check-circle"
                                      aria-hidden="true"
                                    ></i>
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
                                    <i
                                      class="fas fa-times-circle"
                                      aria-hidden="true"
                                    ></i>
                                  </div>
                                  <div class="pf-v6-l-flex__item">
                                    <span>1</span>
                                  </div>
                                </div>
                                <div
                                  class="pf-v6-l-flex__item"
                                >Updated 2 days ago</div>
                              </div>
                            </div>
                          </div>
                          <div
                            class="pf-v6-c-data-list__cell pf-m-align-right pf-m-no-fill"
                          >
                            <button
                              class="pf-v6-c-button pf-m-secondary"
                              type="button"
                            >
                              <span class="pf-v6-c-button__text">Action</span>
                            </button>
                            <button
                              class="pf-v6-c-button pf-m-link"
                              type="button"
                            >
                              <span class="pf-v6-c-button__text">Link</span>
                            </button>
                          </div>
                        </div>
                      </div>
                    </li>

                    <li
                      class="pf-v6-c-data-list__item"
                      aria-labelledby="primary-detail-content-body-padding-example-data-list-item-3"
                    >
                      <div class="pf-v6-c-data-list__item-row">
                        <div class="pf-v6-c-data-list__item-content">
                          <div class="pf-v6-c-data-list__cell pf-m-align-left">
                            <p
                              id="primary-detail-content-body-padding-example-data-list-item-3"
                            >patternfly-unified-design-kit</p>
                          </div>
                          <div
                            class="pf-v6-c-data-list__cell pf-m-align-right pf-m-no-fill"
                          >
                            <button
                              class="pf-v6-c-button pf-m-secondary"
                              type="button"
                            >
                              <span class="pf-v6-c-button__text">Action</span>
                            </button>
                            <button
                              class="pf-v6-c-button pf-m-link"
                              type="button"
                            >
                              <span class="pf-v6-c-button__text">Link</span>
                            </button>
                          </div>
                        </div>
                      </div>
                    </li>

                    <li
                      class="pf-v6-c-data-list__item"
                      aria-labelledby="primary-detail-content-body-padding-example-data-list-item-4"
                    >
                      <div class="pf-v6-c-data-list__item-row">
                        <div class="pf-v6-c-data-list__item-content">
                          <div class="pf-v6-c-data-list__cell pf-m-align-left">
                            <div
                              class="pf-v6-l-flex pf-m-column pf-m-space-items-md"
                            >
                              <div
                                class="pf-v6-l-flex pf-m-column pf-m-space-items-none"
                              >
                                <div class="pf-v6-l-flex__item">
                                  <p
                                    id="primary-detail-content-body-padding-example-data-list-item-4"
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
                                    <i
                                      class="fas fa-code-branch"
                                      aria-hidden="true"
                                    ></i>
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
                                <div
                                  class="pf-v6-l-flex__item"
                                >Updated 2 days ago</div>
                              </div>
                            </div>
                          </div>
                          <div
                            class="pf-v6-c-data-list__cell pf-m-align-right pf-m-no-fill"
                          >
                            <button
                              class="pf-v6-c-button pf-m-secondary"
                              type="button"
                            >
                              <span class="pf-v6-c-button__text">Action</span>
                            </button>
                            <button
                              class="pf-v6-c-button pf-m-link"
                              type="button"
                            >
                              <span class="pf-v6-c-button__text">Link</span>
                            </button>
                          </div>
                        </div>
                      </div>
                    </li>

                    <li
                      class="pf-v6-c-data-list__item"
                      aria-labelledby="primary-detail-content-body-padding-example-data-list-item-5"
                    >
                      <div class="pf-v6-c-data-list__item-row">
                        <div class="pf-v6-c-data-list__item-content">
                          <div class="pf-v6-c-data-list__cell pf-m-align-left">
                            <div
                              class="pf-v6-l-flex pf-m-column pf-m-space-items-md"
                            >
                              <div
                                class="pf-v6-l-flex pf-m-column pf-m-space-items-none"
                              >
                                <div class="pf-v6-l-flex__item">
                                  <p
                                    id="primary-detail-content-body-padding-example-data-list-item-5"
                                  >patternfly-elements</p>
                                </div>
                                <div class="pf-v6-l-flex__item">
                                  <small>PatternFly elements</small>
                                </div>
                              </div>
                              <div class="pf-v6-l-flex pf-m-wrap">
                                <div class="pf-v6-l-flex pf-m-space-items-xs">
                                  <div class="pf-v6-l-flex__item">
                                    <i
                                      class="fas fa-code-branch"
                                      aria-hidden="true"
                                    ></i>
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
                                    <i
                                      class="fas fa-check-circle"
                                      aria-hidden="true"
                                    ></i>
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
                                    <i
                                      class="fas fa-times-circle"
                                      aria-hidden="true"
                                    ></i>
                                  </div>
                                  <div class="pf-v6-l-flex__item">
                                    <span>1</span>
                                  </div>
                                </div>
                                <div
                                  class="pf-v6-l-flex__item"
                                >Updated 2 days ago</div>
                              </div>
                            </div>
                          </div>
                          <div
                            class="pf-v6-c-data-list__cell pf-m-align-right pf-m-no-fill"
                          >
                            <button
                              class="pf-v6-c-button pf-m-secondary"
                              type="button"
                            >
                              <span class="pf-v6-c-button__text">Action</span>
                            </button>
                            <button
                              class="pf-v6-c-button pf-m-link"
                              type="button"
                            >
                              <span class="pf-v6-c-button__text">Link</span>
                            </button>
                          </div>
                        </div>
                      </div>
                    </li>
                  </ul>
                </div>
              </div>

              <!-- Panel -->
              <div class="pf-v6-c-drawer__panel">
                <!-- Panel header -->
                <div class="pf-v6-c-drawer__body">
                  <div class="pf-v6-l-flex pf-m-column">
                    <div class="pf-v6-l-flex__item">
                      <div class="pf-v6-c-drawer__head">
                        <div class="pf-v6-c-drawer__actions">
                          <div class="pf-v6-c-drawer__close">
                            <button
                              class="pf-v6-c-button pf-m-plain"
                              type="button"
                              aria-label="Close drawer panel"
                            >
                              <span class="pf-v6-c-button__icon">
                                <i class="fas fa-times" aria-hidden="true"></i>
                              </span>
                            </button>
                          </div>
                        </div>
                        <h2
                          class="pf-v6-c-title pf-m-lg"
                          id="primary-detail-content-body-padding-example-drawer-drawer-label"
                        >Patternfly-elements</h2>
                      </div>
                    </div>
                    <div class="pf-v6-l-flex__item">PatternFly elements</div>
                  </div>
                </div>

                <!-- Tab content -->
                <div class="pf-v6-c-drawer__body">
                  <div class="pf-v6-l-flex pf-m-column pf-m-space-items-lg">
                    <div class="pf-v6-l-flex__item">
                      <p>The content of the drawer really is up to you. It could have form fields, definition lists, text lists, labels, charts, progress bars, etc. Spacing recommendation is 24px margins. You can put tabs in here, and can also make the drawer scrollable.</p>
                    </div>
                    <div class="pf-v6-l-flex__item">
                      <div
                        class="pf-v6-c-progress pf-m-sm"
                        id="primary-detail-content-body-padding-example-drawer-progress-example1"
                      >
                        <div
                          class="pf-v6-c-progress__description"
                          id="primary-detail-content-body-padding-example-drawer-progress-example1-description"
                        >Capacity</div>
                        <div
                          class="pf-v6-c-progress__status"
                          aria-hidden="true"
                        >
                          <span class="pf-v6-c-progress__measure">33%</span>
                        </div>
                        <div
                          class="pf-v6-c-progress__bar"
                          role="progressbar"
                          aria-valuemin="0"
                          aria-valuemax="100"
                          aria-valuenow="33"
                          aria-labelledby="primary-detail-content-body-padding-example-drawer-progress-example1-description"
                          aria-label="Progress 1"
                        >
                          <div
                            class="pf-v6-c-progress__indicator"
                            style="width:33%;"
                          ></div>
                        </div>
                      </div>
                    </div>
                    <div class="pf-v6-l-flex__item">
                      <div
                        class="pf-v6-c-progress pf-m-sm"
                        id="primary-detail-content-body-padding-example-drawer-progress-example2"
                      >
                        <div
                          class="pf-v6-c-progress__description"
                          id="primary-detail-content-body-padding-example-drawer-progress-example2-description"
                        >Modules</div>
                        <div
                          class="pf-v6-c-progress__status"
                          aria-hidden="true"
                        >
                          <span class="pf-v6-c-progress__measure">66%</span>
                        </div>
                        <div
                          class="pf-v6-c-progress__bar"
                          role="progressbar"
                          aria-valuemin="0"
                          aria-valuemax="100"
                          aria-valuenow="66"
                          aria-labelledby="primary-detail-content-body-padding-example-drawer-progress-example2-description"
                          aria-label="Progress 2"
                        >
                          <div
                            class="pf-v6-c-progress__indicator"
                            style="width:66%;"
                          ></div>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>
    </main>
  </div>
</div>

```

### Primary-detail card view expanded

```html isFullscreen
<div class="pf-v6-c-page" id="primary-detail-card-view-expanded-example">
  <div class="pf-v6-c-skip-to-content">
    <a
      class="pf-v6-c-button pf-m-primary"
      href="#main-content-primary-detail-card-view-expanded-example"
    >
      <span class="pf-v6-c-button__text">Skip to content</span>
    </a>
  </div>
  <header
    class="pf-v6-c-masthead pf-m-display-stack pf-m-display-inline-on-lg"
    id="primary-detail-card-view-expanded-example-masthead"
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
        id="primary-detail-card-view-expanded-example-masthead-toolbar"
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
        id="primary-detail-card-view-expanded-example-primary-nav"
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
      id="main-content-primary-detail-card-view-expanded-example"
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
      <section class="pf-v6-c-page__main-section pf-m-no-padding">
        <div class="pf-v6-c-page__main-body">
          <!-- Drawer -->
          <div class="pf-v6-c-drawer pf-m-expanded pf-m-inline-on-2xl">
            <div class="pf-v6-c-drawer__section">
              <div
                class="pf-v6-c-toolbar"
                id="primary-detail-card-view-expanded-example-drawer-toolbar"
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
                          aria-controls="primary-detail-card-view-expanded-example-drawer-toolbar-expandable-content"
                        >
                          <span class="pf-v6-c-menu-toggle__icon">
                            <i class="fas fa-filter" aria-hidden="true"></i>
                          </span>
                        </button>
                      </div>
                      <div class="pf-v6-c-toolbar__item pf-m-bulk-select">
                        <div
                          class="pf-v6-c-menu-toggle pf-m-split-button"
                          id="primary-detail-card-view-expanded-example-drawer-toolbar-check"
                        >
                          <label
                            class="pf-v6-c-check pf-m-standalone"
                            for="primary-detail-card-view-expanded-example-drawer-toolbar-check-check-input"
                          >
                            <input
                              class="pf-v6-c-check__input"
                              type="checkbox"
                              id="primary-detail-card-view-expanded-example-drawer-toolbar-check-check-input"
                              name="primary-detail-card-view-expanded-example-drawer-toolbar-check-check-input"
                              aria-label="Standalone check"
                            />
                          </label>
                          <button
                            class="pf-v6-c-menu-toggle__button"
                            type="button"
                            aria-expanded="false"
                            id="primary-detail-card-view-expanded-example-drawer-toolbar-menu-toggle-toggle-button"
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
                              id="primary-detail-card-view-expanded-example-drawer-toolbar-search-filter-menu"
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
                              <div
                                class="pf-v6-c-text-input-group__main pf-m-icon"
                              >
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

                    <div class="pf-v6-c-toolbar__item">
                      <button
                        class="pf-v6-c-button pf-m-plain"
                        type="button"
                        aria-label="Sort"
                      >
                        <span class="pf-v6-c-button__icon">
                          <i
                            class="fas fa-sort-amount-down pf-v6-m-mirror-inline-rtl"
                            aria-hidden="true"
                          ></i>
                        </span>
                      </button>
                    </div>

                    <div
                      class="pf-v6-c-overflow-menu"
                      id="primary-detail-card-view-expanded-example-drawer-toolbar-overflow-menu"
                    >
                      <div
                        class="pf-v6-c-overflow-menu__content pf-v6-u-display-none pf-v6-u-display-flex-on-lg"
                      >
                        <div
                          class="pf-v6-c-overflow-menu__group pf-m-button-group"
                        >
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
                          id="primary-detail-card-view-expanded-example-drawer-toolbar-overflow-menu-toggle"
                        >
                          <span class="pf-v6-c-menu-toggle__icon">
                            <i class="fas fa-ellipsis-v" aria-hidden="true"></i>
                          </span>
                        </button>
                      </div>
                    </div>

                    <div
                      class="pf-v6-c-toolbar__group pf-m-align-end pf-m-action-group-plain"
                    >
                      <div class="pf-v6-c-toolbar__item">
                        <button
                          class="pf-v6-c-button pf-m-plain"
                          type="button"
                          aria-label="Grid view"
                        >
                          <span class="pf-v6-c-button__icon">
                            <i class="fas fa-th" aria-hidden="true"></i>
                          </span>
                        </button>
                      </div>
                      <div class="pf-v6-c-toolbar__item">
                        <button
                          class="pf-v6-c-button pf-m-plain"
                          type="button"
                          aria-label="List view"
                        >
                          <span class="pf-v6-c-button__icon">
                            <i class="fas fa-list-ul" aria-hidden="true"></i>
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
                            id="primary-detail-card-view-expanded-example-drawer-toolbar-top-pagination"
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
                          <div
                            class="pf-v6-c-pagination__nav-control pf-m-prev"
                          >
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
                          <div
                            class="pf-v6-c-pagination__nav-control pf-m-next"
                          >
                            <button
                              class="pf-v6-c-button pf-m-plain"
                              type="button"
                              aria-label="Go to next page"
                            >
                              <span class="pf-v6-c-button__icon">
                                <i
                                  class="fas fa-angle-right"
                                  aria-hidden="true"
                                ></i>
                              </span>
                            </button>
                          </div>
                        </nav>
                      </div>
                    </div>
                  </div>

                  <div
                    class="pf-v6-c-toolbar__expandable-content pf-m-hidden"
                    id="primary-detail-card-view-expanded-example-drawer-toolbar-expandable-content"
                    hidden
                  ></div>
                </div>
              </div>
              <div class="pf-v6-c-divider" role="separator"></div>
            </div>

            <div class="pf-v6-c-drawer__main">
              <!-- Content -->
              <div class="pf-v6-c-drawer__content pf-m-no-background">
                <div class="pf-v6-c-drawer__body pf-m-padding">
                  <div class="pf-v6-l-gallery pf-m-gutter">
                    <div
                      class="pf-v6-c-card pf-m-selectable-raised pf-m-selected-raised"
                      id="primary-detail-card-view-expanded-example-drawer-card-1"
                    >
                      <div class="pf-v6-c-card__header">
                        <img
                          src="/assets/images/PF-IconLogo.svg"
                          alt="PatternFly logo"
                        />
                        <div class="pf-v6-c-card__actions">
                          <button
                            class="pf-v6-c-menu-toggle pf-m-plain"
                            type="button"
                            aria-expanded="false"
                            aria-label="Menu toggle"
                            id="primary-detail-card-view-expanded-example-drawer-card-1-toggle"
                          >
                            <span class="pf-v6-c-menu-toggle__icon">
                              <i class="fas fa-ellipsis-v" aria-hidden="true"></i>
                            </span>
                          </button>
                          <div class="pf-v6-c-check pf-m-standalone">
                            <input
                              class="pf-v6-c-check__input"
                              type="checkbox"
                              id="primary-detail-card-view-expanded-example-drawer-card-1-check"
                              name="primary-detail-card-view-expanded-example-drawer-card-1-check"
                              aria-labelledby="primary-detail-card-view-expanded-example-drawer-card-1-check-label"
                            />
                          </div>
                        </div>
                      </div>
                      <div class="pf-v6-c-card__title">
                        <h2
                          class="pf-v6-c-card__title-text"
                          id="primary-detail-card-view-expanded-example-drawer-card-1-check-label"
                        >Patternfly</h2>
                        <div class="pf-v6-c-content">
                          <small>Provided by Red Hat</small>
                        </div>
                      </div>
                      <div
                        class="pf-v6-c-card__body"
                      >PatternFly is a community project that promotes design commonality and improves user experience.</div>
                    </div>
                    <div
                      class="pf-v6-c-card pf-m-selectable-raised"
                      id="primary-detail-card-view-expanded-example-drawer-card-2"
                    >
                      <div class="pf-v6-c-card__header">
                        <img
                          src="/assets/images/activemq-core_200x150.png"
                          width="60px"
                          alt="Logo"
                        />
                        <div class="pf-v6-c-card__actions">
                          <button
                            class="pf-v6-c-menu-toggle pf-m-plain"
                            type="button"
                            aria-expanded="false"
                            aria-label="Menu toggle"
                            id="primary-detail-card-view-expanded-example-drawer-card-2-toggle"
                          >
                            <span class="pf-v6-c-menu-toggle__icon">
                              <i class="fas fa-ellipsis-v" aria-hidden="true"></i>
                            </span>
                          </button>
                          <div class="pf-v6-c-check pf-m-standalone">
                            <input
                              class="pf-v6-c-check__input"
                              type="checkbox"
                              id="primary-detail-card-view-expanded-example-drawer-card-2-check"
                              name="primary-detail-card-view-expanded-example-drawer-card-2-check"
                              aria-labelledby="primary-detail-card-view-expanded-example-drawer-card-2-check-label"
                            />
                          </div>
                        </div>
                      </div>
                      <div class="pf-v6-c-card__title">
                        <h2
                          class="pf-v6-c-card__title-text"
                          id="primary-detail-card-view-expanded-example-drawer-card-2-check-label"
                        >ActiveQ</h2>
                        <div class="pf-v6-c-content">
                          <small>Provided by Red Hat</small>
                        </div>
                      </div>
                      <div
                        class="pf-v6-c-card__body"
                      >The ActiveMQ component allows messages to be sent to a JMS Queue or Topic; or messages to be consumed from a JMS Queue or Topic using Apache ActiveMQ.</div>
                    </div>
                    <div
                      class="pf-v6-c-card pf-m-selectable-raised"
                      id="primary-detail-card-view-expanded-example-drawer-card-3"
                    >
                      <div class="pf-v6-c-card__header">
                        <img
                          src="/assets/images/camel-spark_200x150.png"
                          width="60px"
                          alt="Logo"
                        />
                        <div class="pf-v6-c-card__actions">
                          <button
                            class="pf-v6-c-menu-toggle pf-m-plain"
                            type="button"
                            aria-expanded="false"
                            aria-label="Menu toggle"
                            id="primary-detail-card-view-expanded-example-drawer-card-3-toggle"
                          >
                            <span class="pf-v6-c-menu-toggle__icon">
                              <i class="fas fa-ellipsis-v" aria-hidden="true"></i>
                            </span>
                          </button>
                          <div class="pf-v6-c-check pf-m-standalone">
                            <input
                              class="pf-v6-c-check__input"
                              type="checkbox"
                              id="primary-detail-card-view-expanded-example-drawer-card-3-check"
                              name="primary-detail-card-view-expanded-example-drawer-card-3-check"
                              aria-labelledby="primary-detail-card-view-expanded-example-drawer-card-3-check-label"
                            />
                          </div>
                        </div>
                      </div>
                      <div class="pf-v6-c-card__title">
                        <h2
                          class="pf-v6-c-card__title-text"
                          id="primary-detail-card-view-expanded-example-drawer-card-3-check-label"
                        >Apache Spark</h2>
                        <div class="pf-v6-c-content">
                          <small>Provided by Red Hat</small>
                        </div>
                      </div>
                      <div
                        class="pf-v6-c-card__body"
                      >This documentation page covers the Apache Spark component for the Apache Camel.</div>
                    </div>
                    <div
                      class="pf-v6-c-card pf-m-selectable-raised"
                      id="primary-detail-card-view-expanded-example-drawer-card-4"
                    >
                      <div class="pf-v6-c-card__header">
                        <img
                          src="/assets/images/camel-avro_200x150.png"
                          width="60px"
                          alt="Logo"
                        />
                        <div class="pf-v6-c-card__actions">
                          <button
                            class="pf-v6-c-menu-toggle pf-m-plain"
                            type="button"
                            aria-expanded="false"
                            aria-label="Menu toggle"
                            id="primary-detail-card-view-expanded-example-drawer-card-4-toggle"
                          >
                            <span class="pf-v6-c-menu-toggle__icon">
                              <i class="fas fa-ellipsis-v" aria-hidden="true"></i>
                            </span>
                          </button>
                          <div class="pf-v6-c-check pf-m-standalone">
                            <input
                              class="pf-v6-c-check__input"
                              type="checkbox"
                              id="primary-detail-card-view-expanded-example-drawer-card-4-check"
                              name="primary-detail-card-view-expanded-example-drawer-card-4-check"
                              aria-labelledby="primary-detail-card-view-expanded-example-drawer-card-4-check-label"
                            />
                          </div>
                        </div>
                      </div>
                      <div class="pf-v6-c-card__title">
                        <h2
                          class="pf-v6-c-card__title-text"
                          id="primary-detail-card-view-expanded-example-drawer-card-4-check-label"
                        >Avro</h2>
                        <div class="pf-v6-c-content">
                          <small>Provided by Red Hat</small>
                        </div>
                      </div>
                      <div
                        class="pf-v6-c-card__body"
                      >This component provides a dataformat for avro, which allows serialization and deserialization of messages using Apache Avro’s binary dataformat. Moreover, it provides support for Apache Avro’s rpc, by providing producers and consumers endpoint for using avro over netty or http.</div>
                    </div>
                    <div
                      class="pf-v6-c-card pf-m-selectable-raised"
                      id="primary-detail-card-view-expanded-example-drawer-card-5"
                    >
                      <div class="pf-v6-c-card__header">
                        <img
                          src="/assets/images/FuseConnector_Icons_AzureServices.png"
                          width="60px"
                          alt="Logo"
                        />
                        <div class="pf-v6-c-card__actions">
                          <button
                            class="pf-v6-c-menu-toggle pf-m-plain"
                            type="button"
                            aria-expanded="false"
                            aria-label="Menu toggle"
                            id="primary-detail-card-view-expanded-example-drawer-card-5-toggle"
                          >
                            <span class="pf-v6-c-menu-toggle__icon">
                              <i class="fas fa-ellipsis-v" aria-hidden="true"></i>
                            </span>
                          </button>
                          <div class="pf-v6-c-check pf-m-standalone">
                            <input
                              class="pf-v6-c-check__input"
                              type="checkbox"
                              id="primary-detail-card-view-expanded-example-drawer-card-5-check"
                              name="primary-detail-card-view-expanded-example-drawer-card-5-check"
                              aria-labelledby="primary-detail-card-view-expanded-example-drawer-card-5-check-label"
                            />
                          </div>
                        </div>
                      </div>
                      <div class="pf-v6-c-card__title">
                        <h2
                          class="pf-v6-c-card__title-text"
                          id="primary-detail-card-view-expanded-example-drawer-card-5-check-label"
                        >Azure Services</h2>
                        <div class="pf-v6-c-content">
                          <small>Provided by Red Hat</small>
                        </div>
                      </div>
                      <div
                        class="pf-v6-c-card__body"
                      >The Camel Components for Windows Azure Services provide connectivity to Azure services from Camel.</div>
                    </div>
                    <div
                      class="pf-v6-c-card pf-m-selectable-raised"
                      id="primary-detail-card-view-expanded-example-drawer-card-6"
                    >
                      <div class="pf-v6-c-card__header">
                        <img
                          src="/assets/images/camel-saxon_200x150.png"
                          width="60px"
                          alt="Logo"
                        />
                        <div class="pf-v6-c-card__actions">
                          <button
                            class="pf-v6-c-menu-toggle pf-m-plain"
                            type="button"
                            aria-expanded="false"
                            aria-label="Menu toggle"
                            id="primary-detail-card-view-expanded-example-drawer-card-6-toggle"
                          >
                            <span class="pf-v6-c-menu-toggle__icon">
                              <i class="fas fa-ellipsis-v" aria-hidden="true"></i>
                            </span>
                          </button>
                          <div class="pf-v6-c-check pf-m-standalone">
                            <input
                              class="pf-v6-c-check__input"
                              type="checkbox"
                              id="primary-detail-card-view-expanded-example-drawer-card-6-check"
                              name="primary-detail-card-view-expanded-example-drawer-card-6-check"
                              aria-labelledby="primary-detail-card-view-expanded-example-drawer-card-6-check-label"
                            />
                          </div>
                        </div>
                      </div>
                      <div class="pf-v6-c-card__title">
                        <h2
                          class="pf-v6-c-card__title-text"
                          id="primary-detail-card-view-expanded-example-drawer-card-6-check-label"
                        >Crypto</h2>
                        <div class="pf-v6-c-content">
                          <small>Provided by Red Hat</small>
                        </div>
                      </div>
                      <div
                        class="pf-v6-c-card__body"
                      >For providing flexible endpoints to sign and verify exchanges using the Signature Service of the Java Cryptographic Extension.</div>
                    </div>
                    <div
                      class="pf-v6-c-card pf-m-selectable-raised"
                      id="primary-detail-card-view-expanded-example-drawer-card-7"
                    >
                      <div class="pf-v6-c-card__header">
                        <img
                          src="/assets/images/PF-IconLogo.svg"
                          alt="PatternFly logo"
                        />
                        <div class="pf-v6-c-card__actions">
                          <button
                            class="pf-v6-c-menu-toggle pf-m-plain"
                            type="button"
                            aria-expanded="false"
                            aria-label="Menu toggle"
                            id="primary-detail-card-view-expanded-example-drawer-card-7-toggle"
                          >
                            <span class="pf-v6-c-menu-toggle__icon">
                              <i class="fas fa-ellipsis-v" aria-hidden="true"></i>
                            </span>
                          </button>
                          <div class="pf-v6-c-check pf-m-standalone">
                            <input
                              class="pf-v6-c-check__input"
                              type="checkbox"
                              id="primary-detail-card-view-expanded-example-drawer-card-7-check"
                              name="primary-detail-card-view-expanded-example-drawer-card-7-check"
                              aria-labelledby="primary-detail-card-view-expanded-example-drawer-card-7-check-label"
                            />
                          </div>
                        </div>
                      </div>
                      <div class="pf-v6-c-card__title">
                        <h2
                          class="pf-v6-c-card__title-text"
                          id="primary-detail-card-view-expanded-example-drawer-card-7-check-label"
                        >Patternfly</h2>
                        <div class="pf-v6-c-content">
                          <small>Provided by Red Hat</small>
                        </div>
                      </div>
                      <div
                        class="pf-v6-c-card__body"
                      >PatternFly is a community project that promotes design commonality and improves user experience.</div>
                    </div>
                    <div
                      class="pf-v6-c-card pf-m-selectable-raised"
                      id="primary-detail-card-view-expanded-example-drawer-card-8"
                    >
                      <div class="pf-v6-c-card__header">
                        <img
                          src="/assets/images/PF-IconLogo.svg"
                          alt="PatternFly logo"
                        />
                        <div class="pf-v6-c-card__actions">
                          <button
                            class="pf-v6-c-menu-toggle pf-m-plain"
                            type="button"
                            aria-expanded="false"
                            aria-label="Menu toggle"
                            id="primary-detail-card-view-expanded-example-drawer-card-8-toggle"
                          >
                            <span class="pf-v6-c-menu-toggle__icon">
                              <i class="fas fa-ellipsis-v" aria-hidden="true"></i>
                            </span>
                          </button>
                          <div class="pf-v6-c-check pf-m-standalone">
                            <input
                              class="pf-v6-c-check__input"
                              type="checkbox"
                              id="primary-detail-card-view-expanded-example-drawer-card-8-check"
                              name="primary-detail-card-view-expanded-example-drawer-card-8-check"
                              aria-labelledby="primary-detail-card-view-expanded-example-drawer-card-8-check-label"
                            />
                          </div>
                        </div>
                      </div>
                      <div class="pf-v6-c-card__title">
                        <h2
                          class="pf-v6-c-card__title-text"
                          id="primary-detail-card-view-expanded-example-drawer-card-8-check-label"
                        >Patternfly</h2>
                        <div class="pf-v6-c-content">
                          <small>Provided by Red Hat</small>
                        </div>
                      </div>
                      <div
                        class="pf-v6-c-card__body"
                      >PatternFly is a community project that promotes design commonality and improves user experience.</div>
                    </div>
                    <div
                      class="pf-v6-c-card pf-m-selectable-raised"
                      id="primary-detail-card-view-expanded-example-drawer-card-9"
                    >
                      <div class="pf-v6-c-card__header">
                        <img
                          src="/assets/images/PF-IconLogo.svg"
                          alt="PatternFly logo"
                        />
                        <div class="pf-v6-c-card__actions">
                          <button
                            class="pf-v6-c-menu-toggle pf-m-plain"
                            type="button"
                            aria-expanded="false"
                            aria-label="Menu toggle"
                            id="primary-detail-card-view-expanded-example-drawer-card-9-toggle"
                          >
                            <span class="pf-v6-c-menu-toggle__icon">
                              <i class="fas fa-ellipsis-v" aria-hidden="true"></i>
                            </span>
                          </button>
                          <div class="pf-v6-c-check pf-m-standalone">
                            <input
                              class="pf-v6-c-check__input"
                              type="checkbox"
                              id="primary-detail-card-view-expanded-example-drawer-card-9-check"
                              name="primary-detail-card-view-expanded-example-drawer-card-9-check"
                              aria-labelledby="primary-detail-card-view-expanded-example-drawer-card-9-check-label"
                            />
                          </div>
                        </div>
                      </div>
                      <div class="pf-v6-c-card__title">
                        <h2
                          class="pf-v6-c-card__title-text"
                          id="primary-detail-card-view-expanded-example-drawer-card-9-check-label"
                        >Patternfly</h2>
                        <div class="pf-v6-c-content">
                          <small>Provided by Red Hat</small>
                        </div>
                      </div>
                      <div
                        class="pf-v6-c-card__body"
                      >PatternFly is a community project that promotes design commonality and improves user experience.</div>
                    </div>
                    <div
                      class="pf-v6-c-card pf-m-selectable-raised"
                      id="primary-detail-card-view-expanded-example-drawer-card-10"
                    >
                      <div class="pf-v6-c-card__header">
                        <img
                          src="/assets/images/PF-IconLogo.svg"
                          alt="PatternFly logo"
                        />
                        <div class="pf-v6-c-card__actions">
                          <button
                            class="pf-v6-c-menu-toggle pf-m-plain"
                            type="button"
                            aria-expanded="false"
                            aria-label="Menu toggle"
                            id="primary-detail-card-view-expanded-example-drawer-card-10-toggle"
                          >
                            <span class="pf-v6-c-menu-toggle__icon">
                              <i class="fas fa-ellipsis-v" aria-hidden="true"></i>
                            </span>
                          </button>
                          <div class="pf-v6-c-check pf-m-standalone">
                            <input
                              class="pf-v6-c-check__input"
                              type="checkbox"
                              id="primary-detail-card-view-expanded-example-drawer-card-10-check"
                              name="primary-detail-card-view-expanded-example-drawer-card-10-check"
                              aria-labelledby="primary-detail-card-view-expanded-example-drawer-card-10-check-label"
                            />
                          </div>
                        </div>
                      </div>
                      <div class="pf-v6-c-card__title">
                        <h2
                          class="pf-v6-c-card__title-text"
                          id="primary-detail-card-view-expanded-example-drawer-card-10-check-label"
                        >Patternfly</h2>
                        <div class="pf-v6-c-content">
                          <small>Provided by Red Hat</small>
                        </div>
                      </div>
                      <div
                        class="pf-v6-c-card__body"
                      >PatternFly is a community project that promotes design commonality and improves user experience.</div>
                    </div>
                  </div>
                </div>
              </div>

              <!-- Panel -->
              <div class="pf-v6-c-drawer__panel">
                <!-- Panel header -->
                <div class="pf-v6-c-drawer__body">
                  <div class="pf-v6-l-flex pf-m-column">
                    <div class="pf-v6-l-flex__item">
                      <div class="pf-v6-c-drawer__head">
                        <div class="pf-v6-c-drawer__actions">
                          <div class="pf-v6-c-drawer__close">
                            <button
                              class="pf-v6-c-button pf-m-plain"
                              type="button"
                              aria-label="Close drawer panel"
                            >
                              <span class="pf-v6-c-button__icon">
                                <i class="fas fa-times" aria-hidden="true"></i>
                              </span>
                            </button>
                          </div>
                        </div>
                        <h2
                          class="pf-v6-c-title pf-m-lg"
                          id="primary-detail-card-view-expanded-example-drawer-drawer-label"
                        >Patternfly</h2>
                      </div>
                    </div>
                    <div class="pf-v6-l-flex__item">PatternFly elements</div>
                  </div>
                </div>

                <div class="pf-v6-c-drawer__body">
                  <div class="pf-v6-l-flex pf-m-column pf-m-space-items-lg">
                    <div class="pf-v6-l-flex__item">
                      <p>The content of the drawer really is up to you. It could have form fields, definition lists, text lists, labels, charts, progress bars, etc. Spacing recommendation is 24px margins. You can put tabs in here, and can also make the drawer scrollable.</p>
                    </div>
                    <div class="pf-v6-l-flex__item">
                      <div
                        class="pf-v6-c-progress"
                        id="primary-detail-card-view-expanded-example-drawer-progress-example1"
                      >
                        <div
                          class="pf-v6-c-progress__description"
                          id="primary-detail-card-view-expanded-example-drawer-progress-example1-description"
                        >Capacity</div>
                        <div
                          class="pf-v6-c-progress__status"
                          aria-hidden="true"
                        >
                          <span class="pf-v6-c-progress__measure">33%</span>
                        </div>
                        <div
                          class="pf-v6-c-progress__bar"
                          role="progressbar"
                          aria-valuemin="0"
                          aria-valuemax="100"
                          aria-valuenow="33"
                          aria-labelledby="primary-detail-card-view-expanded-example-drawer-progress-example1-description"
                          aria-label="Progress 1"
                        >
                          <div
                            class="pf-v6-c-progress__indicator"
                            style="width:33%;"
                          ></div>
                        </div>
                      </div>
                    </div>
                    <div class="pf-v6-l-flex__item">
                      <div
                        class="pf-v6-c-progress"
                        id="primary-detail-card-view-expanded-example-drawer-progress-example2"
                      >
                        <div
                          class="pf-v6-c-progress__description"
                          id="primary-detail-card-view-expanded-example-drawer-progress-example2-description"
                        >Modules</div>
                        <div
                          class="pf-v6-c-progress__status"
                          aria-hidden="true"
                        >
                          <span class="pf-v6-c-progress__measure">66%</span>
                        </div>
                        <div
                          class="pf-v6-c-progress__bar"
                          role="progressbar"
                          aria-valuemin="0"
                          aria-valuemax="100"
                          aria-valuenow="66"
                          aria-labelledby="primary-detail-card-view-expanded-example-drawer-progress-example2-description"
                          aria-label="Progress 2"
                        >
                          <div
                            class="pf-v6-c-progress__indicator"
                            style="width:66%;"
                          ></div>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>
    </main>
  </div>
</div>

```

### Primary-detail card simple list expanded on mobile

```html isFullscreen
<div
  class="pf-v6-c-page"
  id="primary-detail-card-simple-list-on-mobile-example"
>
  <div class="pf-v6-c-skip-to-content">
    <a
      class="pf-v6-c-button pf-m-primary"
      href="#main-content-primary-detail-card-simple-list-on-mobile-example"
    >
      <span class="pf-v6-c-button__text">Skip to content</span>
    </a>
  </div>
  <header
    class="pf-v6-c-masthead"
    id="primary-detail-card-simple-list-on-mobile-example-masthead"
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
        id="primary-detail-card-simple-list-on-mobile-example-masthead-toolbar"
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
        id="primary-detail-card-simple-list-on-mobile-example-primary-nav"
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
      id="main-content-primary-detail-card-simple-list-on-mobile-example"
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
      <div class="pf-v6-c-divider" role="separator"></div>
      <section class="pf-v6-c-page__main-section">
        <div class="pf-v6-c-page__main-body">
          <div class="pf-v6-c-card">
            <!-- Drawer -->
            <div class="pf-v6-c-drawer pf-m-expanded pf-m-static">
              <div class="pf-v6-c-drawer__main">
                <!-- Content -->
                <div class="pf-v6-c-drawer__content">
                  <div class="pf-v6-c-simple-list">
                    <section class="pf-v6-c-simple-list__section">
                      <h2 class="pf-v6-c-simple-list__title">Section title</h2>
                      <ul class="pf-v6-c-simple-list__list" role="list">
                        <li class="pf-v6-c-simple-list__item">
                          <button
                            class="pf-v6-c-simple-list__item-link pf-m-current"
                            type="button"
                          >List item 1</button>
                        </li>
                        <li class="pf-v6-c-simple-list__item">
                          <button
                            class="pf-v6-c-simple-list__item-link"
                            type="button"
                          >List item 2</button>
                        </li>
                        <li class="pf-v6-c-simple-list__item">
                          <button
                            class="pf-v6-c-simple-list__item-link"
                            type="button"
                          >List item 3</button>
                        </li>
                        <li class="pf-v6-c-simple-list__item">
                          <button
                            class="pf-v6-c-simple-list__item-link"
                            type="button"
                          >List item 4</button>
                        </li>
                      </ul>
                    </section>
                    <section class="pf-v6-c-simple-list__section">
                      <h2 class="pf-v6-c-simple-list__title">Section title</h2>
                      <ul class="pf-v6-c-simple-list__list" role="list">
                        <li class="pf-v6-c-simple-list__item">
                          <button
                            class="pf-v6-c-simple-list__item-link"
                            type="button"
                          >List item 5</button>
                        </li>
                        <li class="pf-v6-c-simple-list__item">
                          <button
                            class="pf-v6-c-simple-list__item-link"
                            type="button"
                          >List item 6</button>
                        </li>
                        <li class="pf-v6-c-simple-list__item">
                          <button
                            class="pf-v6-c-simple-list__item-link"
                            type="button"
                          >List item 7</button>
                        </li>
                        <li class="pf-v6-c-simple-list__item">
                          <button
                            class="pf-v6-c-simple-list__item-link"
                            type="button"
                          >List item 8</button>
                        </li>
                        <li class="pf-v6-c-simple-list__item">
                          <button
                            class="pf-v6-c-simple-list__item-link"
                            type="button"
                          >List item 9</button>
                        </li>
                        <li class="pf-v6-c-simple-list__item">
                          <button
                            class="pf-v6-c-simple-list__item-link"
                            type="button"
                          >List item 10</button>
                        </li>
                      </ul>
                    </section>
                  </div>
                </div>

                <!-- Panel -->
                <div
                  class="pf-v6-c-drawer__panel pf-m-width-75-on-xl"
                  id="primary-detail-card-simple-list-on-mobile-example-drawer-panel"
                  aria-label="Panel"
                >
                  <!-- Panel header -->
                  <div class="pf-v6-c-drawer__body">
                    <div class="pf-v6-l-flex pf-m-column">
                      <div class="pf-v6-l-flex__item">
                        <div class="pf-v6-c-drawer__head">
                          <div class="pf-v6-c-drawer__actions">
                            <div class="pf-v6-c-drawer__close">
                              <button
                                class="pf-v6-c-button pf-m-plain"
                                type="button"
                                aria-label="Close drawer panel"
                              >
                                <span class="pf-v6-c-button__icon">
                                  <i class="fas fa-times" aria-hidden="true"></i>
                                </span>
                              </button>
                            </div>
                          </div>
                          <h2
                            class="pf-v6-c-title pf-m-lg"
                            id="primary-detail-card-simple-list-on-mobile-example-drawer-drawer-label"
                          >Patternfly-elements</h2>
                        </div>
                      </div>
                    </div>
                  </div>

                  <div class="pf-v6-c-drawer__body">
                    <div class="pf-v6-l-flex pf-m-column pf-m-space-items-lg">
                      <div class="pf-v6-l-flex__item">
                        <p>The content of the drawer really is up to you. It could have form fields, definition lists, text lists, labels, charts, progress bars, etc. Spacing recommendation is 24px margins. You can put tabs in here, and can also make the drawer scrollable.</p>
                      </div>
                      <div class="pf-v6-l-flex__item">
                        <div
                          class="pf-v6-c-progress"
                          id="primary-detail-card-simple-list-on-mobile-example-drawer-progress-example1"
                        >
                          <div
                            class="pf-v6-c-progress__description"
                            id="primary-detail-card-simple-list-on-mobile-example-drawer-progress-example1-description"
                          >Capacity</div>
                          <div
                            class="pf-v6-c-progress__status"
                            aria-hidden="true"
                          >
                            <span class="pf-v6-c-progress__measure">33%</span>
                          </div>
                          <div
                            class="pf-v6-c-progress__bar"
                            role="progressbar"
                            aria-valuemin="0"
                            aria-valuemax="100"
                            aria-valuenow="33"
                            aria-labelledby="primary-detail-card-simple-list-on-mobile-example-drawer-progress-example1-description"
                            aria-label="Progress 1"
                          >
                            <div
                              class="pf-v6-c-progress__indicator"
                              style="width:33%;"
                            ></div>
                          </div>
                        </div>
                      </div>
                      <div class="pf-v6-l-flex__item">
                        <div
                          class="pf-v6-c-progress"
                          id="primary-detail-card-simple-list-on-mobile-example-drawer-progress-example2"
                        >
                          <div
                            class="pf-v6-c-progress__description"
                            id="primary-detail-card-simple-list-on-mobile-example-drawer-progress-example2-description"
                          >Modules</div>
                          <div
                            class="pf-v6-c-progress__status"
                            aria-hidden="true"
                          >
                            <span class="pf-v6-c-progress__measure">66%</span>
                          </div>
                          <div
                            class="pf-v6-c-progress__bar"
                            role="progressbar"
                            aria-valuemin="0"
                            aria-valuemax="100"
                            aria-valuenow="66"
                            aria-labelledby="primary-detail-card-simple-list-on-mobile-example-drawer-progress-example2-description"
                            aria-label="Progress 2"
                          >
                            <div
                              class="pf-v6-c-progress__indicator"
                              style="width:66%;"
                            ></div>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>
    </main>
  </div>
</div>

```

### Primary-detail card data list expanded on mobile

```html isFullscreen
<div class="pf-v6-c-page" id="primary-detail-card-data-list-example">
  <div class="pf-v6-c-skip-to-content">
    <a
      class="pf-v6-c-button pf-m-primary"
      href="#main-content-primary-detail-card-data-list-example"
    >
      <span class="pf-v6-c-button__text">Skip to content</span>
    </a>
  </div>
  <header
    class="pf-v6-c-masthead"
    id="primary-detail-card-data-list-example-masthead"
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
        id="primary-detail-card-data-list-example-masthead-toolbar"
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
        id="primary-detail-card-data-list-example-primary-nav"
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
      id="main-content-primary-detail-card-data-list-example"
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
      <div class="pf-v6-c-divider" role="separator"></div>
      <section class="pf-v6-c-page__main-section">
        <div class="pf-v6-c-page__main-body">
          <div class="pf-v6-c-card">
            <!-- Drawer -->
            <div class="pf-v6-c-drawer pf-m-expanded pf-m-static">
              <div class="pf-v6-c-drawer__main">
                <!-- Content -->
                <div class="pf-v6-c-drawer__content">
                  <div class="pf-v6-c-drawer__body">
                    <div
                      class="pf-v6-c-toolbar"
                      id="primary-detail-card-data-list-example-drawer-toolbar-card-toolbar"
                    >
                      <div class="pf-v6-c-toolbar__content">
                        <div class="pf-v6-c-toolbar__content-section">
                          <div class="pf-v6-c-toolbar__item">
                            <button
                              class="pf-v6-c-menu-toggle"
                              type="button"
                              aria-expanded="false"
                              id="primary-detail-card-data-list-example-drawer-toolbar-card-toolbar-select-dropdown"
                              style="width: 150px"
                            >
                              <span class="pf-v6-c-menu-toggle__text">Dropdown</span>
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
                          <div class="pf-v6-c-toolbar__item pf-m-pagination">
                            <div class="pf-v6-c-pagination">
                              <div class="pf-v6-c-pagination__total-items">
                                <b>1 - 10</b> of
                                <b>37</b>
                              </div>
                              <div class="pf-v6-c-pagination__page-menu">
                                <button
                                  class="pf-v6-c-menu-toggle pf-m-plain pf-m-text"
                                  type="button"
                                  aria-expanded="false"
                                  aria-label="Menu toggle"
                                  id="primary-detail-card-data-list-example-drawer-toolbar-card-toolbar-pagination-menu-toggle"
                                >
                                  <span class="pf-v6-c-menu-toggle__text">
                                    <b>1 - 10</b>&nbsp;of&nbsp;
                                    <b>36</b>
                                  </span>
                                  <span class="pf-v6-c-menu-toggle__controls">
                                    <span
                                      class="pf-v6-c-menu-toggle__toggle-icon"
                                    >
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
                        </div>

                        <div
                          class="pf-v6-c-toolbar__expandable-content pf-m-hidden"
                          id="primary-detail-card-data-list-example-drawer-toolbar-card-toolbar-expandable-content"
                          hidden
                        ></div>
                      </div>
                    </div>
                    <ul
                      class="pf-v6-c-data-list"
                      role="list"
                      aria-label="Selectable rows data list example"
                      id="primary-detail-card-data-list-example-drawer-card-data-list"
                    >
                      <li
                        class="pf-v6-c-data-list__item"
                        aria-labelledby="primary-detail-card-data-list-example-drawer-card-data-list-item-1"
                      >
                        <div class="pf-v6-c-data-list__item-row">
                          <div class="pf-v6-c-data-list__item-content">
                            <div class="pf-v6-c-data-list__cell">
                              <div
                                id="primary-detail-card-data-list-example-drawer-card-data-list-item-1"
                              >Node 1</div>
                              <a href="#">siemur/test-space</a>
                            </div>
                          </div>
                        </div>
                      </li>

                      <li
                        class="pf-v6-c-data-list__item pf-m-selected"
                        aria-labelledby="primary-detail-card-data-list-example-drawer-card-data-list-item-2"
                      >
                        <div class="pf-v6-c-data-list__item-row">
                          <div class="pf-v6-c-data-list__item-content">
                            <div class="pf-v6-c-data-list__cell">
                              <div
                                id="primary-detail-card-data-list-example-drawer-card-data-list-item-2"
                              >Node 2</div>
                              <a href="#">siemur/test-space</a>
                            </div>
                          </div>
                        </div>
                      </li>

                      <li
                        class="pf-v6-c-data-list__item"
                        aria-labelledby="primary-detail-card-data-list-example-drawer-card-data-list-item-3"
                      >
                        <div class="pf-v6-c-data-list__item-row">
                          <div class="pf-v6-c-data-list__item-content">
                            <div class="pf-v6-c-data-list__cell">
                              <div
                                id="primary-detail-card-data-list-example-drawer-card-data-list-item-3"
                              >Node 3</div>
                              <a href="#">siemur/test-space</a>
                            </div>
                          </div>
                        </div>
                      </li>

                      <li
                        class="pf-v6-c-data-list__item"
                        aria-labelledby="primary-detail-card-data-list-example-drawer-card-data-list-item-4"
                      >
                        <div class="pf-v6-c-data-list__item-row">
                          <div class="pf-v6-c-data-list__item-content">
                            <div class="pf-v6-c-data-list__cell">
                              <div
                                id="primary-detail-card-data-list-example-drawer-card-data-list-item-4"
                              >Node 4</div>
                              <a href="#">siemur/test-space</a>
                            </div>
                          </div>
                        </div>
                      </li>

                      <li
                        class="pf-v6-c-data-list__item"
                        aria-labelledby="primary-detail-card-data-list-example-drawer-card-data-list-item-5"
                      >
                        <div class="pf-v6-c-data-list__item-row">
                          <div class="pf-v6-c-data-list__item-content">
                            <div class="pf-v6-c-data-list__cell">
                              <div
                                id="primary-detail-card-data-list-example-drawer-card-data-list-item-5"
                              >Node 5</div>
                              <a href="#">siemur/test-space</a>
                            </div>
                          </div>
                        </div>
                      </li>

                      <li
                        class="pf-v6-c-data-list__item"
                        aria-labelledby="primary-detail-card-data-list-example-drawer-card-data-list-item-6"
                      >
                        <div class="pf-v6-c-data-list__item-row">
                          <div class="pf-v6-c-data-list__item-content">
                            <div class="pf-v6-c-data-list__cell">
                              <div
                                id="primary-detail-card-data-list-example-drawer-card-data-list-item-6"
                              >Node 6</div>
                              <a href="#">siemur/test-space</a>
                            </div>
                          </div>
                        </div>
                      </li>

                      <li
                        class="pf-v6-c-data-list__item"
                        aria-labelledby="primary-detail-card-data-list-example-drawer-card-data-list-item-7"
                      >
                        <div class="pf-v6-c-data-list__item-row">
                          <div class="pf-v6-c-data-list__item-content">
                            <div class="pf-v6-c-data-list__cell">
                              <div
                                id="primary-detail-card-data-list-example-drawer-card-data-list-item-7"
                              >Node 7</div>
                              <a href="#">siemur/test-space</a>
                            </div>
                          </div>
                        </div>
                      </li>

                      <li
                        class="pf-v6-c-data-list__item"
                        aria-labelledby="primary-detail-card-data-list-example-drawer-card-data-list-item-8"
                      >
                        <div class="pf-v6-c-data-list__item-row">
                          <div class="pf-v6-c-data-list__item-content">
                            <div class="pf-v6-c-data-list__cell">
                              <div
                                id="primary-detail-card-data-list-example-drawer-card-data-list-item-8"
                              >Node 8</div>
                              <a href="#">siemur/test-space</a>
                            </div>
                          </div>
                        </div>
                      </li>

                      <li
                        class="pf-v6-c-data-list__item"
                        aria-labelledby="primary-detail-card-data-list-example-drawer-card-data-list-item-9"
                      >
                        <div class="pf-v6-c-data-list__item-row">
                          <div class="pf-v6-c-data-list__item-content">
                            <div class="pf-v6-c-data-list__cell">
                              <div
                                id="primary-detail-card-data-list-example-drawer-card-data-list-item-9"
                              >Node 9</div>
                              <a href="#">siemur/test-space</a>
                            </div>
                          </div>
                        </div>
                      </li>

                      <li
                        class="pf-v6-c-data-list__item"
                        aria-labelledby="primary-detail-card-data-list-example-drawer-card-data-list-item-10"
                      >
                        <div class="pf-v6-c-data-list__item-row">
                          <div class="pf-v6-c-data-list__item-content">
                            <div class="pf-v6-c-data-list__cell">
                              <div
                                id="primary-detail-card-data-list-example-drawer-card-data-list-item-10"
                              >Node 10</div>
                              <a href="#">siemur/test-space</a>
                            </div>
                          </div>
                        </div>
                      </li>
                    </ul>
                  </div>
                </div>

                <!-- Panel -->
                <div
                  class="pf-v6-c-drawer__panel pf-m-width-75-on-2xl"
                  id="primary-detail-card-data-list-example-drawer-panel"
                  aria-label="Panel"
                >
                  <!-- Panel header -->
                  <div class="pf-v6-c-drawer__body">
                    <div class="pf-v6-l-flex pf-m-column">
                      <div class="pf-v6-l-flex__item">
                        <div class="pf-v6-c-drawer__head">
                          <div class="pf-v6-c-drawer__actions">
                            <div class="pf-v6-c-drawer__close">
                              <button
                                class="pf-v6-c-button pf-m-plain"
                                type="button"
                                aria-label="Close drawer panel"
                              >
                                <span class="pf-v6-c-button__icon">
                                  <i class="fas fa-times" aria-hidden="true"></i>
                                </span>
                              </button>
                            </div>
                          </div>
                          <h2
                            class="pf-v6-c-title pf-m-lg"
                            id="primary-detail-card-data-list-example-drawer-drawer-label"
                          >Patternfly-elements</h2>
                        </div>
                      </div>
                    </div>
                  </div>
                  <div class="pf-v6-c-drawer__body">
                    <div class="pf-v6-l-flex pf-m-column pf-m-space-items-lg">
                      <div class="pf-v6-l-flex__item">
                        <p>The content of the drawer really is up to you. It could have form fields, definition lists, text lists, labels, charts, progress bars, etc. Spacing recommendation is 24px margins. You can put tabs in here, and can also make the drawer scrollable.</p>
                      </div>
                      <div class="pf-v6-l-flex__item">
                        <div
                          class="pf-v6-c-progress"
                          id="primary-detail-card-data-list-example-drawer-progress-example1"
                        >
                          <div
                            class="pf-v6-c-progress__description"
                            id="primary-detail-card-data-list-example-drawer-progress-example1-description"
                          >Capacity</div>
                          <div
                            class="pf-v6-c-progress__status"
                            aria-hidden="true"
                          >
                            <span class="pf-v6-c-progress__measure">33%</span>
                          </div>
                          <div
                            class="pf-v6-c-progress__bar"
                            role="progressbar"
                            aria-valuemin="0"
                            aria-valuemax="100"
                            aria-valuenow="33"
                            aria-labelledby="primary-detail-card-data-list-example-drawer-progress-example1-description"
                            aria-label="Progress 1"
                          >
                            <div
                              class="pf-v6-c-progress__indicator"
                              style="width:33%;"
                            ></div>
                          </div>
                        </div>
                      </div>
                      <div class="pf-v6-l-flex__item">
                        <div
                          class="pf-v6-c-progress"
                          id="primary-detail-card-data-list-example-drawer-progress-example2"
                        >
                          <div
                            class="pf-v6-c-progress__description"
                            id="primary-detail-card-data-list-example-drawer-progress-example2-description"
                          >Modules</div>
                          <div
                            class="pf-v6-c-progress__status"
                            aria-hidden="true"
                          >
                            <span class="pf-v6-c-progress__measure">66%</span>
                          </div>
                          <div
                            class="pf-v6-c-progress__bar"
                            role="progressbar"
                            aria-valuemin="0"
                            aria-valuemax="100"
                            aria-valuenow="66"
                            aria-labelledby="primary-detail-card-data-list-example-drawer-progress-example2-description"
                            aria-label="Progress 2"
                          >
                            <div
                              class="pf-v6-c-progress__indicator"
                              style="width:66%;"
                            ></div>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>
    </main>
  </div>
</div>

```

### Inline modifier

```html isFullscreen
<div class="pf-v6-c-page" id="primary-detail-inline-modifier-example">
  <div class="pf-v6-c-skip-to-content">
    <a
      class="pf-v6-c-button pf-m-primary"
      href="#main-content-primary-detail-inline-modifier-example"
    >
      <span class="pf-v6-c-button__text">Skip to content</span>
    </a>
  </div>
  <header
    class="pf-v6-c-masthead"
    id="primary-detail-inline-modifier-example-masthead"
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
        id="primary-detail-inline-modifier-example-masthead-toolbar"
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
        id="primary-detail-inline-modifier-example-primary-nav"
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
      id="main-content-primary-detail-inline-modifier-example"
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
      <div class="pf-v6-c-divider" role="separator"></div>
      <div class="pf-v6-c-drawer pf-m-expanded pf-m-inline-on-2xl">
        <div class="pf-v6-c-drawer__main">
          <!-- Content -->
          <div class="pf-v6-c-drawer__content">
            <div class="pf-v6-c-drawer__body">
              <div
                class="pf-v6-c-toolbar"
                id="primary-detail-inline-modifier-example-drawer-toolbar"
              >
                <div class="pf-v6-c-toolbar__content">
                  <div class="pf-v6-c-toolbar__content-section pf-m-nowrap">
                    <div class="pf-v6-c-toolbar__item">
                      <button
                        class="pf-v6-c-menu-toggle"
                        type="button"
                        aria-expanded="false"
                        id="primary-detail-inline-modifier-example-drawer-toolbar-select-status"
                        style="width: 150px"
                      >
                        <span class="pf-v6-c-menu-toggle__icon">
                          <i class="fas fa-bookmark" aria-hidden="true"></i>
                        </span>
                        <span class="pf-v6-c-menu-toggle__text">Status</span>
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

                    <div
                      class="pf-v6-c-overflow-menu"
                      id="primary-detail-inline-modifier-example-drawer-toolbar-overflow-menu"
                    >
                      <div
                        class="pf-v6-c-overflow-menu__content pf-v6-u-display-none pf-v6-u-display-flex-on-lg"
                      >
                        <div
                          class="pf-v6-c-overflow-menu__group pf-m-button-group"
                        >
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
                          id="primary-detail-inline-modifier-example-drawer-toolbar-overflow-menu-toggle"
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
                            id="primary-detail-inline-modifier-example-drawer-toolbar-top-pagination"
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
                          <div
                            class="pf-v6-c-pagination__nav-control pf-m-prev"
                          >
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
                          <div
                            class="pf-v6-c-pagination__nav-control pf-m-next"
                          >
                            <button
                              class="pf-v6-c-button pf-m-plain"
                              type="button"
                              aria-label="Go to next page"
                            >
                              <span class="pf-v6-c-button__icon">
                                <i
                                  class="fas fa-angle-right"
                                  aria-hidden="true"
                                ></i>
                              </span>
                            </button>
                          </div>
                        </nav>
                      </div>
                    </div>
                  </div>

                  <div
                    class="pf-v6-c-toolbar__expandable-content pf-m-hidden"
                    id="primary-detail-inline-modifier-example-drawer-toolbar-expandable-content"
                    hidden
                  ></div>
                </div>
              </div>
              <ul
                class="pf-v6-c-data-list"
                role="list"
                aria-label="Simple data list example"
                id="primary-detail-inline-modifier-example-data-list"
              >
                <li
                  class="pf-v6-c-data-list__item"
                  aria-labelledby="primary-detail-inline-modifier-example-data-list-item-1"
                >
                  <div class="pf-v6-c-data-list__item-row">
                    <div class="pf-v6-c-data-list__item-content">
                      <div class="pf-v6-c-data-list__cell pf-m-align-left">
                        <div
                          class="pf-v6-l-flex pf-m-column pf-m-space-items-md"
                        >
                          <div
                            class="pf-v6-l-flex pf-m-column pf-m-space-items-none"
                          >
                            <div class="pf-v6-l-flex__item">
                              <p
                                id="primary-detail-inline-modifier-example-data-list-item-1"
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
                                <i
                                  class="fas fa-code-branch"
                                  aria-hidden="true"
                                ></i>
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
                        <button
                          class="pf-v6-c-button pf-m-secondary"
                          type="button"
                        >
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
                  aria-labelledby="primary-detail-inline-modifier-example-data-list-item-2"
                >
                  <div class="pf-v6-c-data-list__item-row">
                    <div class="pf-v6-c-data-list__item-content">
                      <div class="pf-v6-c-data-list__cell pf-m-align-left">
                        <div
                          class="pf-v6-l-flex pf-m-column pf-m-space-items-md"
                        >
                          <div
                            class="pf-v6-l-flex pf-m-column pf-m-space-items-none"
                          >
                            <div class="pf-v6-l-flex__item">
                              <p
                                id="primary-detail-inline-modifier-example-data-list-item-2"
                              >patternfly-elements</p>
                            </div>
                            <div class="pf-v6-l-flex__item">
                              <small>PatternFly elements</small>
                            </div>
                          </div>
                          <div class="pf-v6-l-flex pf-m-wrap">
                            <div class="pf-v6-l-flex pf-m-space-items-xs">
                              <div class="pf-v6-l-flex__item">
                                <i
                                  class="fas fa-code-branch"
                                  aria-hidden="true"
                                ></i>
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
                                <i
                                  class="fas fa-check-circle"
                                  aria-hidden="true"
                                ></i>
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
                                <i
                                  class="fas fa-times-circle"
                                  aria-hidden="true"
                                ></i>
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
                        <button
                          class="pf-v6-c-button pf-m-secondary"
                          type="button"
                        >
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
                  aria-labelledby="primary-detail-inline-modifier-example-data-list-item-3"
                >
                  <div class="pf-v6-c-data-list__item-row">
                    <div class="pf-v6-c-data-list__item-content">
                      <div class="pf-v6-c-data-list__cell pf-m-align-left">
                        <p
                          id="primary-detail-inline-modifier-example-data-list-item-3"
                        >patternfly-unified-design-kit</p>
                      </div>
                      <div
                        class="pf-v6-c-data-list__cell pf-m-align-right pf-m-no-fill"
                      >
                        <button
                          class="pf-v6-c-button pf-m-secondary"
                          type="button"
                        >
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
                  aria-labelledby="primary-detail-inline-modifier-example-data-list-item-4"
                >
                  <div class="pf-v6-c-data-list__item-row">
                    <div class="pf-v6-c-data-list__item-content">
                      <div class="pf-v6-c-data-list__cell pf-m-align-left">
                        <div
                          class="pf-v6-l-flex pf-m-column pf-m-space-items-md"
                        >
                          <div
                            class="pf-v6-l-flex pf-m-column pf-m-space-items-none"
                          >
                            <div class="pf-v6-l-flex__item">
                              <p
                                id="primary-detail-inline-modifier-example-data-list-item-4"
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
                                <i
                                  class="fas fa-code-branch"
                                  aria-hidden="true"
                                ></i>
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
                        <button
                          class="pf-v6-c-button pf-m-secondary"
                          type="button"
                        >
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
                  aria-labelledby="primary-detail-inline-modifier-example-data-list-item-5"
                >
                  <div class="pf-v6-c-data-list__item-row">
                    <div class="pf-v6-c-data-list__item-content">
                      <div class="pf-v6-c-data-list__cell pf-m-align-left">
                        <div
                          class="pf-v6-l-flex pf-m-column pf-m-space-items-md"
                        >
                          <div
                            class="pf-v6-l-flex pf-m-column pf-m-space-items-none"
                          >
                            <div class="pf-v6-l-flex__item">
                              <p
                                id="primary-detail-inline-modifier-example-data-list-item-5"
                              >patternfly-elements</p>
                            </div>
                            <div class="pf-v6-l-flex__item">
                              <small>PatternFly elements</small>
                            </div>
                          </div>
                          <div class="pf-v6-l-flex pf-m-wrap">
                            <div class="pf-v6-l-flex pf-m-space-items-xs">
                              <div class="pf-v6-l-flex__item">
                                <i
                                  class="fas fa-code-branch"
                                  aria-hidden="true"
                                ></i>
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
                                <i
                                  class="fas fa-check-circle"
                                  aria-hidden="true"
                                ></i>
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
                                <i
                                  class="fas fa-times-circle"
                                  aria-hidden="true"
                                ></i>
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
                        <button
                          class="pf-v6-c-button pf-m-secondary"
                          type="button"
                        >
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
            </div>
          </div>

          <!-- Panel -->
          <div class="pf-v6-c-drawer__panel">
            <!-- Panel header -->
            <div class="pf-v6-c-drawer__body">
              <div class="pf-v6-l-flex pf-m-column">
                <div class="pf-v6-l-flex__item">
                  <div class="pf-v6-c-drawer__head">
                    <div class="pf-v6-c-drawer__actions">
                      <div class="pf-v6-c-drawer__close">
                        <button
                          class="pf-v6-c-button pf-m-plain"
                          type="button"
                          aria-label="Close drawer panel"
                        >
                          <span class="pf-v6-c-button__icon">
                            <i class="fas fa-times" aria-hidden="true"></i>
                          </span>
                        </button>
                      </div>
                    </div>
                    <h2
                      class="pf-v6-c-title pf-m-lg"
                      id="primary-detail-inline-modifier-example-drawer-drawer-label"
                    >Node 2</h2>
                  </div>
                </div>
                <div class="pf-v6-l-flex__item">
                  <a href="#">siemur/test-space</a>
                </div>
              </div>
            </div>

            <!-- Tabs -->
            <div class="pf-v6-c-drawer__body pf-m-no-padding">
              <div
                class="pf-v6-c-tabs pf-m-box pf-m-fill"
                role="region"
                id="primary-detail-inline-modifier-example-drawer-tabs"
              >
                <div class="pf-v6-c-tabs__scroll-button">
                  <button
                    class="pf-v6-c-button pf-m-plain"
                    type="button"
                    aria-label="Scroll left"
                  >
                    <span class="pf-v6-c-button__icon">
                      <i class="fas fa-angle-left" aria-hidden="true"></i>
                    </span>
                  </button>
                </div>
                <ul class="pf-v6-c-tabs__list" role="tablist">
                  <li
                    class="pf-v6-c-tabs__item pf-m-current"
                    role="presentation"
                  >
                    <button
                      type="button"
                      class="pf-v6-c-tabs__link"
                      role="tab"
                      aria-controls="primary-detail-inline-modifier-example-drawer-tabs-tab1-panel"
                      id="primary-detail-inline-modifier-example-drawer-tabs-tab1-link"
                    >
                      <span class="pf-v6-c-tabs__item-text">Overview</span>
                    </button>
                  </li>
                  <li class="pf-v6-c-tabs__item" role="presentation">
                    <button
                      type="button"
                      class="pf-v6-c-tabs__link"
                      role="tab"
                      aria-controls="primary-detail-inline-modifier-example-drawer-tabs-tab2-panel"
                      id="primary-detail-inline-modifier-example-drawer-tabs-tab2-link"
                    >
                      <span class="pf-v6-c-tabs__item-text">Activity</span>
                    </button>
                  </li>
                </ul>
                <div class="pf-v6-c-tabs__scroll-button">
                  <button
                    class="pf-v6-c-button pf-m-plain"
                    type="button"
                    aria-label="Scroll right"
                  >
                    <span class="pf-v6-c-button__icon">
                      <i class="fas fa-angle-right" aria-hidden="true"></i>
                    </span>
                  </button>
                </div>
              </div>
            </div>

            <!-- Tab content -->
            <div class="pf-v6-c-drawer__body">
              <section
                class="pf-v6-c-tab-content"
                id="primary-detail-inline-modifier-example-drawer-tabs-tab1-panel"
                aria-labelledby="primary-detail-inline-modifier-example-drawer-tabs-tab1-link"
                role="tabpanel"
                tabindex="0"
              >
                <div class="pf-v6-c-tab-content__body">
                  <div class="pf-v6-l-flex pf-m-column pf-m-space-items-lg">
                    <div class="pf-v6-l-flex__item">
                      <p>The content of the drawer really is up to you. It could have form fields, definition lists, text lists, labels, charts, progress bars, etc. Spacing recommendation is 24px margins. You can put tabs in here, and can also make the drawer scrollable.</p>
                    </div>
                    <div class="pf-v6-l-flex__item">
                      <div
                        class="pf-v6-c-progress pf-m-sm"
                        id="primary-detail-inline-modifier-example-drawer-progress-example1"
                      >
                        <div
                          class="pf-v6-c-progress__description"
                          id="primary-detail-inline-modifier-example-drawer-progress-example1-description"
                        >Capacity</div>
                        <div
                          class="pf-v6-c-progress__status"
                          aria-hidden="true"
                        >
                          <span class="pf-v6-c-progress__measure">33%</span>
                        </div>
                        <div
                          class="pf-v6-c-progress__bar"
                          role="progressbar"
                          aria-valuemin="0"
                          aria-valuemax="100"
                          aria-valuenow="33"
                          aria-labelledby="primary-detail-inline-modifier-example-drawer-progress-example1-description"
                          aria-label="Progress 1"
                        >
                          <div
                            class="pf-v6-c-progress__indicator"
                            style="width:33%;"
                          ></div>
                        </div>
                      </div>
                    </div>
                    <div class="pf-v6-l-flex__item">
                      <div
                        class="pf-v6-c-progress pf-m-sm"
                        id="primary-detail-inline-modifier-example-drawer-progress-example2"
                      >
                        <div
                          class="pf-v6-c-progress__description"
                          id="primary-detail-inline-modifier-example-drawer-progress-example2-description"
                        >Modules</div>
                        <div
                          class="pf-v6-c-progress__status"
                          aria-hidden="true"
                        >
                          <span class="pf-v6-c-progress__measure">66%</span>
                        </div>
                        <div
                          class="pf-v6-c-progress__bar"
                          role="progressbar"
                          aria-valuemin="0"
                          aria-valuemax="100"
                          aria-valuenow="66"
                          aria-labelledby="primary-detail-inline-modifier-example-drawer-progress-example2-description"
                          aria-label="Progress 2"
                        >
                          <div
                            class="pf-v6-c-progress__indicator"
                            style="width:66%;"
                          ></div>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </section>
              <section
                class="pf-v6-c-tab-content"
                id="primary-detail-inline-modifier-example-drawer-tabs-tab2-panel"
                aria-labelledby="primary-detail-inline-modifier-example-drawer-tabs-tab2-link"
                role="tabpanel"
                tabindex="0"
                hidden
              >
                <div class="pf-v6-c-tab-content__body">Panel 2</div>
              </section>
            </div>
          </div>
        </div>
      </div>
    </main>
  </div>
</div>

```

## Documentation

This demo implements the drawer in context of the page component.
