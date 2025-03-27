---
id: 'Tabs'
section: components
---## Examples

### Open tabs

```html isFullscreen
<div class="pf-v6-c-page" id="tabs-tables-and-tabs-example">
  <div class="pf-v6-c-skip-to-content">
    <a
      class="pf-v6-c-button pf-m-primary"
      href="#main-content-tabs-tables-and-tabs-example"
    >
      <span class="pf-v6-c-button__text">Skip to content</span>
    </a>
  </div>
  <header class="pf-v6-c-masthead" id="tabs-tables-and-tabs-example-masthead">
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
        id="tabs-tables-and-tabs-example-masthead-toolbar"
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
        id="tabs-tables-and-tabs-example-primary-nav"
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
      id="main-content-tabs-tables-and-tabs-example"
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

      <section class="pf-v6-c-page__main-tabs pf-m-limit-width">
        <div class="pf-v6-c-page__main-body">
          <div
            class="pf-v6-c-tabs pf-m-page-insets"
            role="region"
            id="tabs-tables-and-tabs-example-tabs"
          >
            <ul class="pf-v6-c-tabs__list" role="tablist">
              <li class="pf-v6-c-tabs__item pf-m-current" role="presentation">
                <button
                  type="button"
                  class="pf-v6-c-tabs__link"
                  role="tab"
                  aria-controls="tabs-tables-and-tabs-example-tabs-details-panel"
                  id="tabs-tables-and-tabs-example-tabs-details-link"
                >
                  <span class="pf-v6-c-tabs__item-text">Details</span>
                </button>
              </li>
              <li class="pf-v6-c-tabs__item" role="presentation">
                <button
                  type="button"
                  class="pf-v6-c-tabs__link"
                  role="tab"
                  aria-controls="tabs-tables-and-tabs-example-tabs-yaml-panel"
                  id="tabs-tables-and-tabs-example-tabs-yaml-link"
                >
                  <span class="pf-v6-c-tabs__item-text">YAML</span>
                </button>
              </li>
              <li class="pf-v6-c-tabs__item" role="presentation">
                <button
                  type="button"
                  class="pf-v6-c-tabs__link"
                  role="tab"
                  aria-controls="tabs-tables-and-tabs-example-tabs-environment-panel"
                  id="tabs-tables-and-tabs-example-tabs-environment-link"
                >
                  <span class="pf-v6-c-tabs__item-text">Environment</span>
                </button>
              </li>
              <li class="pf-v6-c-tabs__item" role="presentation">
                <button
                  type="button"
                  class="pf-v6-c-tabs__link"
                  role="tab"
                  aria-controls="tabs-tables-and-tabs-example-tabs-logs-panel"
                  id="tabs-tables-and-tabs-example-tabs-logs-link"
                >
                  <span class="pf-v6-c-tabs__item-text">Logs</span>
                </button>
              </li>
              <li class="pf-v6-c-tabs__item" role="presentation">
                <button
                  type="button"
                  class="pf-v6-c-tabs__link"
                  role="tab"
                  aria-controls="tabs-tables-and-tabs-example-tabs-events-panel"
                  id="tabs-tables-and-tabs-example-tabs-events-link"
                >
                  <span class="pf-v6-c-tabs__item-text">Events</span>
                </button>
              </li>
              <li class="pf-v6-c-tabs__item" role="presentation">
                <button
                  type="button"
                  class="pf-v6-c-tabs__link"
                  role="tab"
                  aria-controls="tabs-tables-and-tabs-example-tabs-terminal-panel"
                  id="tabs-tables-and-tabs-example-tabs-terminal-link"
                >
                  <span class="pf-v6-c-tabs__item-text">Terminal</span>
                </button>
              </li>
            </ul>
          </div>
        </div>
      </section>

      <section class="pf-v6-c-page__main-section pf-m-limit-width">
        <div class="pf-v6-c-page__main-body">
          <section
            class="pf-v6-c-tab-content"
            aria-labelledby="tabs-tables-and-tabs-example-tabs-details-link"
            id="tabs-tables-and-tabs-example-tabs-details-panel"
            role="tabpanel"
            tabindex="0"
          >
            <div class="pf-v6-c-tab-content__body">
              <div class="pf-v6-l-flex pf-m-column">
                <div class="pf-v6-l-flex__item pf-m-spacer-lg">
                  <h2
                    class="pf-v6-c-title pf-m-lg pf-v6-u-mt-sm"
                    id="-details-title"
                  >Pod details</h2>
                </div>
                <div class="pf-v6-l-flex__item">
                  <dl
                    class="pf-v6-c-description-list pf-m-2-col-on-lg"
                    aria-labelledby="-details-title"
                  >
                    <div class="pf-v6-c-description-list__group">
                      <dt class="pf-v6-c-description-list__term">Name</dt>
                      <dd class="pf-v6-c-description-list__description">
                        <div
                          class="pf-v6-c-description-list__text"
                        >3scale-control-fccb6ddb9-phyqv9</div>
                      </dd>
                    </div>
                    <div class="pf-v6-c-description-list__group">
                      <dt class="pf-v6-c-description-list__term">Status</dt>
                      <dd class="pf-v6-c-description-list__description">
                        <div class="pf-v6-c-description-list__text">
                          <div class="pf-v6-l-flex pf-m-space-items-sm">
                            <div class="pf-v6-l-flex__item">
                              <i
                                class="fas fa-fw fa-check-circle"
                                aria-hidden="true"
                              ></i>
                            </div>
                            <div class="pf-v6-l-flex__item">Running</div>
                          </div>
                        </div>
                      </dd>
                    </div>
                    <div class="pf-v6-c-description-list__group">
                      <dt class="pf-v6-c-description-list__term">Namespace</dt>
                      <dd class="pf-v6-c-description-list__description">
                        <div class="pf-v6-c-description-list__text">
                          <div class="pf-v6-l-flex pf-m-space-items-sm">
                            <div class="pf-v6-l-flex__item">
                              <span class="pf-v6-c-label pf-m-teal">
                                <span class="pf-v6-c-label__content">
                                  <span class="pf-v6-c-label__text">NS</span>
                                </span>
                              </span>
                            </div>
                            <div class="pf-v6-l-flex__item">
                              <a href="#">knative-serving-ingress</a>
                            </div>
                          </div>
                        </div>
                      </dd>
                    </div>
                    <div class="pf-v6-c-description-list__group">
                      <dt class="pf-v6-c-description-list__term">Restart policy</dt>
                      <dd class="pf-v6-c-description-list__description">
                        <div
                          class="pf-v6-c-description-list__text"
                        >Always restart</div>
                      </dd>
                    </div>
                    <div class="pf-v6-c-description-list__group">
                      <dt class="pf-v6-c-description-list__term">Labels</dt>
                      <dd class="pf-v6-c-description-list__description">
                        <div class="pf-v6-c-description-list__text">
                          <div class="pf-v6-c-label-group">
                            <div class="pf-v6-c-label-group__main">
                              <ul
                                class="pf-v6-c-label-group__list"
                                role="list"
                                aria-label="Group of labels"
                              >
                                <li class="pf-v6-c-label-group__list-item">
                                  <span class="pf-v6-c-label pf-m-outline">
                                    <span class="pf-v6-c-label__content">
                                      <span
                                        class="pf-v6-c-label__text"
                                      >app=3scale-gateway</span>
                                    </span>
                                  </span>
                                </li>
                                <li class="pf-v6-c-label-group__list-item">
                                  <span class="pf-v6-c-label pf-m-outline">
                                    <span class="pf-v6-c-label__content">
                                      <span
                                        class="pf-v6-c-label__text"
                                      >pod-template-has=6747686899</span>
                                    </span>
                                  </span>
                                </li>
                              </ul>
                            </div>
                          </div>
                        </div>
                      </dd>
                    </div>
                    <div class="pf-v6-c-description-list__group">
                      <dt
                        class="pf-v6-c-description-list__term"
                      >Active deadline seconds</dt>
                      <dd class="pf-v6-c-description-list__description">
                        <div
                          class="pf-v6-c-description-list__text"
                        >Not configured</div>
                      </dd>
                    </div>
                    <div class="pf-v6-c-description-list__group">
                      <dt class="pf-v6-c-description-list__term">Tolerations</dt>
                      <dd class="pf-v6-c-description-list__description">
                        <div class="pf-v6-c-description-list__text">stuff</div>
                      </dd>
                    </div>
                    <div class="pf-v6-c-description-list__group">
                      <dt class="pf-v6-c-description-list__term">Pod IP</dt>
                      <dd class="pf-v6-c-description-list__description">
                        <div class="pf-v6-c-description-list__text">10.345.2.197</div>
                      </dd>
                    </div>
                    <div class="pf-v6-c-description-list__group">
                      <dt class="pf-v6-c-description-list__term">Annotations</dt>
                      <dd class="pf-v6-c-description-list__description">
                        <div class="pf-v6-c-description-list__text">stuff</div>
                      </dd>
                    </div>
                    <div class="pf-v6-c-description-list__group">
                      <dt class="pf-v6-c-description-list__term">Node</dt>
                      <dd class="pf-v6-c-description-list__description">
                        <div class="pf-v6-c-description-list__text">
                          <div class="pf-v6-l-flex pf-m-space-items-sm">
                            <div class="pf-v6-l-flex__item">
                              <span class="pf-v6-c-label pf-m-purple">
                                <span class="pf-v6-c-label__content">
                                  <span class="pf-v6-c-label__text">N</span>
                                </span>
                              </span>
                            </div>
                            <div
                              class="pf-v6-l-flex__item"
                            >ip-10-0-233-118.us-east-2.computer.external</div>
                          </div>
                        </div>
                      </dd>
                    </div>
                    <div class="pf-v6-c-description-list__group">
                      <dt class="pf-v6-c-description-list__term">Created at</dt>
                      <dd class="pf-v6-c-description-list__description">
                        <div class="pf-v6-c-description-list__text">
                          <time>Oct 15, 1:51 pm</time>
                        </div>
                      </dd>
                    </div>
                  </dl>
                </div>
              </div>
            </div>
          </section>
          <section
            class="pf-v6-c-tab-content"
            aria-labelledby="tabs-tables-and-tabs-example-tabs-yaml-link"
            id="tabs-tables-and-tabs-example-tabs-yaml-panel"
            role="tabpanel"
            tabindex="0"
            hidden
          >
            <div class="pf-v6-c-tab-content__body">YAML panel</div>
          </section>
          <section
            class="pf-v6-c-tab-content"
            aria-labelledby="tabs-tables-and-tabs-example-tabs-environment-link"
            id="tabs-tables-and-tabs-example-tabs-environment-panel"
            role="tabpanel"
            tabindex="0"
            hidden
          >
            <div class="pf-v6-c-tab-content__body">Environment panel</div>
          </section>
          <section
            class="pf-v6-c-tab-content"
            aria-labelledby="tabs-tables-and-tabs-example-tabs-logs-link"
            id="tabs-tables-and-tabs-example-tabs-logs-panel"
            role="tabpanel"
            tabindex="0"
            hidden
          >
            <div class="pf-v6-c-tab-content__body">Logs panel</div>
          </section>
          <section
            class="pf-v6-c-tab-content"
            aria-labelledby="tabs-tables-and-tabs-example-tabs-events-link"
            id="tabs-tables-and-tabs-example-tabs-events-panel"
            role="tabpanel"
            tabindex="0"
            hidden
          >
            <div class="pf-v6-c-tab-content__body">Events panel</div>
          </section>
          <section
            class="pf-v6-c-tab-content"
            aria-labelledby="tabs-tables-and-tabs-example-tabs-terminal-link"
            id="tabs-tables-and-tabs-example-tabs-terminal-panel"
            role="tabpanel"
            tabindex="0"
            hidden
          >
            <div class="pf-v6-c-tab-content__body">Terminal panel</div>
          </section>
        </div>
      </section>
    </main>
  </div>
</div>

```

### Open tabs with secondary tabs

```html isFullscreen
<div class="pf-v6-c-page" id="tabs-tables-and-tabs-example">
  <div class="pf-v6-c-skip-to-content">
    <a
      class="pf-v6-c-button pf-m-primary"
      href="#main-content-tabs-tables-and-tabs-example"
    >
      <span class="pf-v6-c-button__text">Skip to content</span>
    </a>
  </div>
  <header class="pf-v6-c-masthead" id="tabs-tables-and-tabs-example-masthead">
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
        id="tabs-tables-and-tabs-example-masthead-toolbar"
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
        id="tabs-tables-and-tabs-example-primary-nav"
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
      id="main-content-tabs-tables-and-tabs-example"
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
      <section class="pf-v6-c-page__main-tabs pf-m-limit-width">
        <div class="pf-v6-c-page__main-body">
          <div
            class="pf-v6-c-tabs pf-m-page-insets"
            role="region"
            id="tabs-tables-and-tabs-example-tabs"
          >
            <ul class="pf-v6-c-tabs__list" role="tablist">
              <li class="pf-v6-c-tabs__item pf-m-current" role="presentation">
                <button
                  type="button"
                  class="pf-v6-c-tabs__link"
                  role="tab"
                  aria-controls="tabs-tables-and-tabs-example-tabs-details-panel"
                  id="tabs-tables-and-tabs-example-tabs-details-link"
                >
                  <span class="pf-v6-c-tabs__item-text">Details</span>
                </button>
              </li>
              <li class="pf-v6-c-tabs__item" role="presentation">
                <button
                  type="button"
                  class="pf-v6-c-tabs__link"
                  role="tab"
                  aria-controls="tabs-tables-and-tabs-example-tabs-yaml-panel"
                  id="tabs-tables-and-tabs-example-tabs-yaml-link"
                >
                  <span class="pf-v6-c-tabs__item-text">YAML</span>
                </button>
              </li>
              <li class="pf-v6-c-tabs__item" role="presentation">
                <button
                  type="button"
                  class="pf-v6-c-tabs__link"
                  role="tab"
                  aria-controls="tabs-tables-and-tabs-example-tabs-environment-panel"
                  id="tabs-tables-and-tabs-example-tabs-environment-link"
                >
                  <span class="pf-v6-c-tabs__item-text">Environment</span>
                </button>
              </li>
              <li class="pf-v6-c-tabs__item" role="presentation">
                <button
                  type="button"
                  class="pf-v6-c-tabs__link"
                  role="tab"
                  aria-controls="tabs-tables-and-tabs-example-tabs-logs-panel"
                  id="tabs-tables-and-tabs-example-tabs-logs-link"
                >
                  <span class="pf-v6-c-tabs__item-text">Logs</span>
                </button>
              </li>
              <li class="pf-v6-c-tabs__item" role="presentation">
                <button
                  type="button"
                  class="pf-v6-c-tabs__link"
                  role="tab"
                  aria-controls="tabs-tables-and-tabs-example-tabs-events-panel"
                  id="tabs-tables-and-tabs-example-tabs-events-link"
                >
                  <span class="pf-v6-c-tabs__item-text">Events</span>
                </button>
              </li>
              <li class="pf-v6-c-tabs__item" role="presentation">
                <button
                  type="button"
                  class="pf-v6-c-tabs__link"
                  role="tab"
                  aria-controls="tabs-tables-and-tabs-example-tabs-terminal-panel"
                  id="tabs-tables-and-tabs-example-tabs-terminal-link"
                >
                  <span class="pf-v6-c-tabs__item-text">Terminal</span>
                </button>
              </li>
            </ul>
          </div>
        </div>
      </section>
      <section class="pf-v6-c-page__main-section pf-m-limit-width">
        <div class="pf-v6-c-page__main-body">
          <div
            class="pf-v6-c-tabs pf-m-secondary pf-m-page-insets"
            role="region"
            id="tabs-tables-and-tabs-example-tabs-secondary"
          >
            <ul class="pf-v6-c-tabs__list" role="tablist">
              <li class="pf-v6-c-tabs__item pf-m-current" role="presentation">
                <button
                  type="button"
                  class="pf-v6-c-tabs__link"
                  role="tab"
                  aria-controls="tabs-tables-and-tabs-example-tabs-secondary-pod-info-panel"
                  id="tabs-tables-and-tabs-example-tabs-secondary-pod-info-link"
                >
                  <span class="pf-v6-c-tabs__item-text">Pod information</span>
                </button>
              </li>
              <li class="pf-v6-c-tabs__item" role="presentation">
                <button
                  type="button"
                  class="pf-v6-c-tabs__link"
                  role="tab"
                  aria-controls="tabs-tables-and-tabs-example-tabs-secondary-editable-aspects-panel"
                  id="tabs-tables-and-tabs-example-tabs-secondary-editable-aspects-link"
                >
                  <span class="pf-v6-c-tabs__item-text">Editable Aspects</span>
                </button>
              </li>
            </ul>
          </div>
          <section
            class="pf-v6-c-tab-content"
            aria-labelledby="tabs-tables-and-tabs-example-tabs-details-link"
            id="tabs-tables-and-tabs-example-tabs-details-panel"
            role="tabpanel"
            tabindex="0"
          >
            <div class="pf-v6-c-tab-content__body pf-m-padding">
              <section
                class="pf-v6-c-tab-content"
                aria-labelledby="tabs-tables-and-tabs-example-tabs-secondary-pod-info-link"
                id="tabs-tables-and-tabs-example-tabs-secondary-pod-info-panel"
                role="tabpanel"
                tabindex="0"
              >
                <div class="pf-v6-c-tab-content__body">
                  <div class="pf-v6-l-flex pf-m-column">
                    <div class="pf-v6-l-flex__item">
                      <dl
                        class="pf-v6-c-description-list pf-m-2-col-on-lg"
                        aria-label="Pod information list"
                      >
                        <div class="pf-v6-c-description-list__group">
                          <dt class="pf-v6-c-description-list__term">Name</dt>
                          <dd class="pf-v6-c-description-list__description">
                            <div
                              class="pf-v6-c-description-list__text"
                            >3scale-control-fccb6ddb9-phyqv9</div>
                          </dd>
                        </div>
                        <div class="pf-v6-c-description-list__group">
                          <dt class="pf-v6-c-description-list__term">Status</dt>
                          <dd class="pf-v6-c-description-list__description">
                            <div class="pf-v6-c-description-list__text">
                              <div class="pf-v6-l-flex pf-m-space-items-sm">
                                <div class="pf-v6-l-flex__item">
                                  <i
                                    class="fas fa-fw fa-check-circle"
                                    aria-hidden="true"
                                  ></i>
                                </div>
                                <div class="pf-v6-l-flex__item">Running</div>
                              </div>
                            </div>
                          </dd>
                        </div>
                        <div class="pf-v6-c-description-list__group">
                          <dt class="pf-v6-c-description-list__term">Namespace</dt>
                          <dd class="pf-v6-c-description-list__description">
                            <div class="pf-v6-c-description-list__text">
                              <div class="pf-v6-l-flex pf-m-space-items-sm">
                                <div class="pf-v6-l-flex__item">
                                  <span class="pf-v6-c-label pf-m-teal">
                                    <span class="pf-v6-c-label__content">
                                      <span class="pf-v6-c-label__text">NS</span>
                                    </span>
                                  </span>
                                </div>
                                <div class="pf-v6-l-flex__item">
                                  <a href="#">knative-serving-ingress</a>
                                </div>
                              </div>
                            </div>
                          </dd>
                        </div>
                        <div class="pf-v6-c-description-list__group">
                          <dt
                            class="pf-v6-c-description-list__term"
                          >Restart policy</dt>
                          <dd class="pf-v6-c-description-list__description">
                            <div
                              class="pf-v6-c-description-list__text"
                            >Always restart</div>
                          </dd>
                        </div>
                        <div class="pf-v6-c-description-list__group">
                          <dt class="pf-v6-c-description-list__term">Pod IP</dt>
                          <dd class="pf-v6-c-description-list__description">
                            <div
                              class="pf-v6-c-description-list__text"
                            >10.345.2.197</div>
                          </dd>
                        </div>
                        <div class="pf-v6-c-description-list__group">
                          <dt
                            class="pf-v6-c-description-list__term"
                          >Active deadline seconds</dt>
                          <dd class="pf-v6-c-description-list__description">
                            <div
                              class="pf-v6-c-description-list__text"
                            >Not configured</div>
                          </dd>
                        </div>
                        <div class="pf-v6-c-description-list__group">
                          <dt class="pf-v6-c-description-list__term">Created at</dt>
                          <dd class="pf-v6-c-description-list__description">
                            <div class="pf-v6-c-description-list__text">
                              <time>Oct 15, 1:51 pm</time>
                            </div>
                          </dd>
                        </div>
                        <div class="pf-v6-c-description-list__group">
                          <dt class="pf-v6-c-description-list__term">Node</dt>
                          <dd class="pf-v6-c-description-list__description">
                            <div class="pf-v6-c-description-list__text">
                              <div class="pf-v6-l-flex pf-m-space-items-sm">
                                <div class="pf-v6-l-flex__item">
                                  <span class="pf-v6-c-label pf-m-purple">
                                    <span class="pf-v6-c-label__content">
                                      <span class="pf-v6-c-label__text">N</span>
                                    </span>
                                  </span>
                                </div>
                                <div
                                  class="pf-v6-l-flex__item"
                                >ip-10-0-233-118.us-east-2.computer.external</div>
                              </div>
                            </div>
                          </dd>
                        </div>
                      </dl>
                    </div>
                  </div>
                </div>
              </section>
              <section
                class="pf-v6-c-tab-content"
                aria-labelledby="tabs-tables-and-tabs-example-tabs-secondary-editable-aspects-link"
                id="tabs-tables-and-tabs-example-tabs-secondary-editable-aspects-panel"
                role="tabpanel"
                tabindex="0"
                hidden
              >
                <div class="pf-v6-c-tab-content__body">Editable aspects panel</div>
              </section>
            </div>
          </section>
          <section
            class="pf-v6-c-tab-content"
            aria-labelledby="tabs-tables-and-tabs-example-tabs-yaml-link"
            id="tabs-tables-and-tabs-example-tabs-yaml-panel"
            role="tabpanel"
            tabindex="0"
            hidden
          >
            <div class="pf-v6-c-tab-content__body pf-m-padding">YAML panel</div>
          </section>
          <section
            class="pf-v6-c-tab-content"
            aria-labelledby="tabs-tables-and-tabs-example-tabs-environment-link"
            id="tabs-tables-and-tabs-example-tabs-environment-panel"
            role="tabpanel"
            tabindex="0"
            hidden
          >
            <div
              class="pf-v6-c-tab-content__body pf-m-padding"
            >Environment panel</div>
          </section>
          <section
            class="pf-v6-c-tab-content"
            aria-labelledby="tabs-tables-and-tabs-example-tabs-logs-link"
            id="tabs-tables-and-tabs-example-tabs-logs-panel"
            role="tabpanel"
            tabindex="0"
            hidden
          >
            <div class="pf-v6-c-tab-content__body pf-m-padding">Logs panel</div>
          </section>
          <section
            class="pf-v6-c-tab-content"
            aria-labelledby="tabs-tables-and-tabs-example-tabs-events-link"
            id="tabs-tables-and-tabs-example-tabs-events-panel"
            role="tabpanel"
            tabindex="0"
            hidden
          >
            <div class="pf-v6-c-tab-content__body pf-m-padding">Events panel</div>
          </section>
          <section
            class="pf-v6-c-tab-content"
            aria-labelledby="tabs-tables-and-tabs-example-tabs-terminal-link"
            id="tabs-tables-and-tabs-example-tabs-terminal-panel"
            role="tabpanel"
            tabindex="0"
            hidden
          >
            <div class="pf-v6-c-tab-content__body pf-m-padding">Terminal panel</div>
          </section>
        </div>
      </section>
    </main>
  </div>
</div>

```

### Nested tabs

```html isFullscreen
<div class="pf-v6-c-page" id="nested-tabs-example">
  <div class="pf-v6-c-skip-to-content">
    <a
      class="pf-v6-c-button pf-m-primary"
      href="#main-content-nested-tabs-example"
    >
      <span class="pf-v6-c-button__text">Skip to content</span>
    </a>
  </div>
  <header class="pf-v6-c-masthead" id="nested-tabs-example-masthead">
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
        id="nested-tabs-example-masthead-toolbar"
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
        id="nested-tabs-example-primary-nav"
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
      id="main-content-nested-tabs-example"
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
      <section class="pf-v6-c-page__main-tabs pf-m-limit-width">
        <div class="pf-v6-c-page__main-body">
          <div
            class="pf-v6-c-tabs pf-m-page-insets"
            role="region"
            id="nested-tabs-example-tabs-tabs"
          >
            <ul class="pf-v6-c-tabs__list" role="tablist">
              <li class="pf-v6-c-tabs__item pf-m-current" role="presentation">
                <button
                  type="button"
                  class="pf-v6-c-tabs__link"
                  role="tab"
                  aria-controls="nested-tabs-example-tabs-tabs-cluster-1-panel"
                  id="nested-tabs-example-tabs-tabs-cluster-1-link"
                >
                  <span class="pf-v6-c-tabs__item-text">Cluster 1</span>
                </button>
              </li>
              <li class="pf-v6-c-tabs__item" role="presentation">
                <button
                  type="button"
                  class="pf-v6-c-tabs__link"
                  role="tab"
                  aria-controls="nested-tabs-example-tabs-tabs-cluster-2-panel"
                  id="nested-tabs-example-tabs-tabs-cluster-2-link"
                >
                  <span class="pf-v6-c-tabs__item-text">Cluster 2</span>
                </button>
              </li>
            </ul>
          </div>
        </div>
      </section>
      <section class="pf-v6-c-page__main-section pf-m-limit-width">
        <div class="pf-v6-c-page__main-body">
          <section
            class="pf-v6-c-tab-content"
            aria-labelledby="nested-tabs-example-tabs-tabs-cluster-1-link"
            id="nested-tabs-example-tabs-tabs-cluster-1-panel"
            role="tabpanel"
            tabindex="0"
          >
            <div class="pf-v6-c-tab-content__body">
              <div class="pf-v6-l-grid pf-m-gutter">
                <div
                  class="pf-v6-l-grid__item pf-m-6-col-on-md pf-m-8-col-on-xl"
                >
                  <div class="pf-v6-c-card pf-m-full-height">
                    <div class="pf-v6-c-card__header">
                      <h2 class="pf-v6-c-title pf-m-lg">Status</h2>
                    </div>
                    <div class="pf-v6-c-card__body">
                      <div class="pf-v6-l-flex pf-m-column">
                        <div class="pf-v6-l-flex__item">
                          <div
                            class="pf-v6-c-tabs"
                            role="region"
                            id="nested-tabs-example-tabs-tabs-subtabs"
                          >
                            <ul class="pf-v6-c-tabs__list" role="tablist">
                              <li
                                class="pf-v6-c-tabs__item pf-m-current"
                                role="presentation"
                              >
                                <button
                                  type="button"
                                  class="pf-v6-c-tabs__link"
                                  role="tab"
                                  aria-controls="nested-tabs-example-tabs-tabs-subtabs-cluster-panel"
                                  id="nested-tabs-example-tabs-tabs-subtabs-cluster-link"
                                >
                                  <span class="pf-v6-c-tabs__item-text">Cluster</span>
                                </button>
                              </li>
                              <li
                                class="pf-v6-c-tabs__item"
                                role="presentation"
                              >
                                <button
                                  type="button"
                                  class="pf-v6-c-tabs__link"
                                  role="tab"
                                  aria-controls="nested-tabs-example-tabs-tabs-subtabs-control-plane-panel"
                                  id="nested-tabs-example-tabs-tabs-subtabs-control-plane-link"
                                >
                                  <span
                                    class="pf-v6-c-tabs__item-text"
                                  >Control plane</span>
                                </button>
                              </li>
                              <li
                                class="pf-v6-c-tabs__item"
                                role="presentation"
                              >
                                <button
                                  type="button"
                                  class="pf-v6-c-tabs__link"
                                  role="tab"
                                  aria-controls="nested-tabs-example-tabs-tabs-subtabs-operators-panel"
                                  id="nested-tabs-example-tabs-tabs-subtabs-operators-link"
                                >
                                  <span
                                    class="pf-v6-c-tabs__item-text"
                                  >Operators</span>
                                </button>
                              </li>
                              <li
                                class="pf-v6-c-tabs__item"
                                role="presentation"
                              >
                                <button
                                  type="button"
                                  class="pf-v6-c-tabs__link"
                                  role="tab"
                                  aria-controls="nested-tabs-example-tabs-tabs-subtabs-virtualization-panel"
                                  id="nested-tabs-example-tabs-tabs-subtabs-virtualization-link"
                                >
                                  <span
                                    class="pf-v6-c-tabs__item-text"
                                  >Virtualization</span>
                                </button>
                              </li>
                            </ul>
                          </div>
                        </div>
                        <div class="pf-v6-l-flex__item">
                          <section
                            class="pf-v6-c-tab-content"
                            aria-labelledby="nested-tabs-example-tabs-tabs-subtabs-cluster-link"
                            id="nested-tabs-example-tabs-tabs-subtabs-cluster-panel"
                            role="tabpanel"
                            tabindex="0"
                          >
                            <div class="pf-v6-c-tab-content__body">
                              <div class="pf-v6-c-content">
                                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Fusce in odio porttitor, feugiat risus in, feugiat arcu. Nullam euismod enim eget fringilla condimentum. Maecenas tincidunt et metus id aliquet. Integer et fermentum purus. Nulla tempor velit arcu, vitae semper purus iaculis at. Sed malesuada auctor luctus. Pellentesque et leo urna. Aliquam vitae felis congue lacus mattis fringilla. Nullam et ultricies erat, sed dignissim elit. Cras mattis pulvinar aliquam. In ac est nulla. Pellentesque fermentum nibh ac sapien porta, ut congue orci aliquam. Sed nisl est, tempor eu pharetra eget, ullamcorper ut augue. Vestibulum eleifend libero eu nulla cursus lacinia.</p>
                              </div>
                            </div>
                          </section>
                          <section
                            class="pf-v6-c-tab-content"
                            aria-labelledby="nested-tabs-example-tabs-tabs-subtabs-control-plane-link"
                            id="nested-tabs-example-tabs-tabs-subtabs-control-plane-panel"
                            role="tabpanel"
                            tabindex="0"
                            hidden
                          >
                            <div
                              class="pf-v6-c-tab-content__body"
                            >Control plane content</div>
                          </section>
                          <section
                            class="pf-v6-c-tab-content"
                            aria-labelledby="nested-tabs-example-tabs-tabs-subtabs-operators-link"
                            id="nested-tabs-example-tabs-tabs-subtabs-operators-panel"
                            role="tabpanel"
                            tabindex="0"
                            hidden
                          >
                            <div
                              class="pf-v6-c-tab-content__body"
                            >Operators content</div>
                          </section>
                          <section
                            class="pf-v6-c-tab-content"
                            aria-labelledby="nested-tabs-example-tabs-tabs-subtabs-virtualization-link"
                            id="nested-tabs-example-tabs-tabs-subtabs-virtualization-panel"
                            role="tabpanel"
                            tabindex="0"
                            hidden
                          >
                            <div
                              class="pf-v6-c-tab-content__body"
                            >Virtualization content</div>
                          </section>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
                <div
                  class="pf-v6-l-grid__item pf-m-6-col-on-md pf-m-4-col-on-xl"
                >
                  <div class="pf-v6-l-flex pf-m-column pf-v6-u-h-100">
                    <div class="pf-v6-l-flex__item pf-m-flex-1">
                      <div class="pf-v6-c-card pf-m-full-height">
                        <div class="pf-v6-c-card__header">
                          <h2 class="pf-v6-c-title pf-m-lg">Title of card</h2>
                        </div>
                      </div>
                    </div>
                    <div class="pf-v6-l-flex__item pf-m-flex-1">
                      <div class="pf-v6-c-card pf-m-full-height">
                        <div class="pf-v6-c-card__header">
                          <h2 class="pf-v6-c-title pf-m-lg">Title of card</h2>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </section>
          <section
            class="pf-v6-c-tab-content"
            aria-labelledby="nested-tabs-example-tabs-tabs-cluster-2-link"
            id="nested-tabs-example-tabs-tabs-cluster-2-panel"
            role="tabpanel"
            tabindex="0"
            hidden
          >
            <div class="pf-v6-c-tab-content__body">
              <div class="pf-v6-c-content">
                <p>Cluster 2 content</p>
              </div>
            </div>
          </section>
        </div>
      </section>
    </main>
  </div>
</div>

```

### Tables and tabs

```html isFullscreen
<div class="pf-v6-c-page" id="table-tabs-example">
  <div class="pf-v6-c-skip-to-content">
    <a
      class="pf-v6-c-button pf-m-primary"
      href="#main-content-table-tabs-example"
    >
      <span class="pf-v6-c-button__text">Skip to content</span>
    </a>
  </div>
  <header class="pf-v6-c-masthead" id="table-tabs-example-masthead">
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
        id="table-tabs-example-masthead-toolbar"
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
        id="table-tabs-example-primary-nav"
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
      id="main-content-table-tabs-example"
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
          <div class="pf-v6-c-toolbar" id="table-tabs-example-tabs-toolbar">
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
                      aria-controls="table-tabs-example-tabs-toolbar-expandable-content"
                    >
                      <span class="pf-v6-c-menu-toggle__icon">
                        <i class="fas fa-filter" aria-hidden="true"></i>
                      </span>
                    </button>
                  </div>

                  <div class="pf-v6-c-toolbar__item">
                    <button
                      class="pf-v6-c-menu-toggle"
                      type="button"
                      aria-expanded="false"
                      id="table-tabs-example-tabs-toolbar-select-checkbox-status"
                    >
                      <span class="pf-v6-c-menu-toggle__text">Name</span>
                      <span class="pf-v6-c-menu-toggle__controls">
                        <span class="pf-v6-c-menu-toggle__toggle-icon">
                          <i class="fas fa-caret-down fa-fw" aria-hidden="true"></i>
                        </span>
                      </span>
                    </button>
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
                  id="table-tabs-example-tabs-toolbar-overflow-menu"
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
                          <span class="pf-v6-c-button__text">Generate</span>
                        </button>
                      </div>

                      <div class="pf-v6-c-overflow-menu__item">
                        <button
                          class="pf-v6-c-button pf-m-secondary"
                          type="button"
                        >
                          <span class="pf-v6-c-button__text">Deploy</span>
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
                      id="table-tabs-example-tabs-toolbar-overflow-menu-toggle"
                    >
                      <span class="pf-v6-c-menu-toggle__icon">
                        <i class="fas fa-ellipsis-v" aria-hidden="true"></i>
                      </span>
                    </button>
                  </div>
                </div>
              </div>

              <div
                class="pf-v6-c-toolbar__expandable-content pf-m-hidden"
                id="table-tabs-example-tabs-toolbar-expandable-content"
                hidden
              ></div>
            </div>
          </div>
          <hr class="pf-v6-c-divider" />
          <div class="pf-v6-c-drawer pf-m-expanded pf-m-inline">
            <div class="pf-v6-c-drawer__main">
              <!-- Content -->
              <div class="pf-v6-c-drawer__content">
                <div class="pf-v6-c-drawer__body">
                  <table
                    class="pf-v6-c-table pf-m-grid-md"
                    role="grid"
                    aria-label="This is a table with checkboxes"
                    id="table-tabs-example-table"
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
                            for="table-tabs-example-table-checkrow-check-input"
                          >
                            <input
                              class="pf-v6-c-check__input"
                              type="checkbox"
                              id="table-tabs-example-table-checkrow-check-input"
                              name="table-tabs-example-table-checkrow-check-input"
                              aria-label="Select all rows"
                            />
                          </label>
                        </th>

                        <th
                          class="pf-v6-c-table__th"
                          role="columnheader"
                          scope="col"
                        >Repositories</th>

                        <th
                          class="pf-v6-c-table__th"
                          role="columnheader"
                          scope="col"
                        >Branches</th>

                        <th
                          class="pf-v6-c-table__th"
                          role="columnheader"
                          scope="col"
                        >Pull requests</th>

                        <th
                          class="pf-v6-c-table__th"
                          role="columnheader"
                          scope="col"
                        >Workspaces</th>

                        <th
                          class="pf-v6-c-table__th"
                          role="columnheader"
                          scope="col"
                        >Last commit</th>

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
                            for="table-tabs-example-table-checkrow-1-check-input"
                          >
                            <input
                              class="pf-v6-c-check__input"
                              type="checkbox"
                              id="table-tabs-example-table-checkrow-1-check-input"
                              name="table-tabs-example-table-checkrow-1-check-input"
                              aria-label="Select row"
                            />
                          </label>
                        </td>

                        <th
                          class="pf-v6-c-table__th"
                          role="columnheader"
                          data-label="Repository name"
                        >
                          <div>
                            <div id="table-tabs-example-table-node1">Node 1</div>
                            <a href="#">siemur/test-space</a>
                          </div>
                        </th>

                        <td
                          class="pf-v6-c-table__td"
                          role="cell"
                          data-label="Branches"
                        >
                          <div
                            class="pf-v6-l-flex pf-m-space-items-sm pf-m-nowrap"
                          >
                            <div class="pf-v6-l-flex__item">10</div>
                            <div class="pf-v6-l-flex__item">
                              <i class="fas fa-code-branch"></i>
                            </div>
                          </div>
                        </td>
                        <td
                          class="pf-v6-c-table__td"
                          role="cell"
                          data-label="Pull requests"
                        >
                          <div
                            class="pf-v6-l-flex pf-m-space-items-sm pf-m-nowrap"
                          >
                            <div class="pf-v6-l-flex__item">25</div>
                            <div class="pf-v6-l-flex__item">
                              <i class="fas fa-code"></i>
                            </div>
                          </div>
                        </td>
                        <td
                          class="pf-v6-c-table__td"
                          role="cell"
                          data-label="Workspaces"
                        >
                          <div
                            class="pf-v6-l-flex pf-m-space-items-sm pf-m-nowrap"
                          >
                            <div class="pf-v6-l-flex__item">5</div>
                            <div class="pf-v6-l-flex__item">
                              <i class="fas fa-cube"></i>
                            </div>
                          </div>
                        </td>
                        <td
                          class="pf-v6-c-table__td"
                          role="cell"
                          data-label="Last commit"
                        >2 days ago</td>

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

                      <tr class="pf-v6-c-table__tr pf-m-selected" role="row">
                        <td
                          class="pf-v6-c-table__td pf-v6-c-table__check"
                          aria-label="Check row"
                        >
                          <label
                            class="pf-v6-c-check pf-m-standalone"
                            for="table-tabs-example-table-checkrow-2-check-input"
                          >
                            <input
                              class="pf-v6-c-check__input"
                              type="checkbox"
                              id="table-tabs-example-table-checkrow-2-check-input"
                              name="table-tabs-example-table-checkrow-2-check-input"
                              aria-label="Select row"
                            />
                          </label>
                        </td>

                        <th
                          class="pf-v6-c-table__th"
                          role="columnheader"
                          data-label="Repository name"
                        >
                          <div>
                            <div id="table-tabs-example-table-node2">Node 2</div>
                            <a href="#">siemur/test-space</a>
                          </div>
                        </th>

                        <td
                          class="pf-v6-c-table__td"
                          role="cell"
                          data-label="Branches"
                        >
                          <div
                            class="pf-v6-l-flex pf-m-space-items-sm pf-m-nowrap"
                          >
                            <div class="pf-v6-l-flex__item">8</div>
                            <div class="pf-v6-l-flex__item">
                              <i class="fas fa-code-branch"></i>
                            </div>
                          </div>
                        </td>
                        <td
                          class="pf-v6-c-table__td"
                          role="cell"
                          data-label="Pull requests"
                        >
                          <div
                            class="pf-v6-l-flex pf-m-space-items-sm pf-m-nowrap"
                          >
                            <div class="pf-v6-l-flex__item">30</div>
                            <div class="pf-v6-l-flex__item">
                              <i class="fas fa-code"></i>
                            </div>
                          </div>
                        </td>
                        <td
                          class="pf-v6-c-table__td"
                          role="cell"
                          data-label="Workspaces"
                        >
                          <div
                            class="pf-v6-l-flex pf-m-space-items-sm pf-m-nowrap"
                          >
                            <div class="pf-v6-l-flex__item">2</div>
                            <div class="pf-v6-l-flex__item">
                              <i class="fas fa-cube"></i>
                            </div>
                          </div>
                        </td>
                        <td
                          class="pf-v6-c-table__td"
                          role="cell"
                          data-label="Last commit"
                        >2 days ago</td>

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
                            for="table-tabs-example-table-checkrow-3-check-input"
                          >
                            <input
                              class="pf-v6-c-check__input"
                              type="checkbox"
                              id="table-tabs-example-table-checkrow-3-check-input"
                              name="table-tabs-example-table-checkrow-3-check-input"
                              aria-label="Select row"
                            />
                          </label>
                        </td>

                        <th
                          class="pf-v6-c-table__th"
                          role="columnheader"
                          data-label="Repository name"
                        >
                          <div>
                            <div id="table-tabs-example-table-node3">Node 3</div>
                            <a href="#">siemur/test-space</a>
                          </div>
                        </th>

                        <td
                          class="pf-v6-c-table__td"
                          role="cell"
                          data-label="Branches"
                        >
                          <div
                            class="pf-v6-l-flex pf-m-space-items-sm pf-m-nowrap"
                          >
                            <div class="pf-v6-l-flex__item">12</div>
                            <div class="pf-v6-l-flex__item">
                              <i class="fas fa-code-branch"></i>
                            </div>
                          </div>
                        </td>
                        <td
                          class="pf-v6-c-table__td"
                          role="cell"
                          data-label="Pull requests"
                        >
                          <div
                            class="pf-v6-l-flex pf-m-space-items-sm pf-m-nowrap"
                          >
                            <div class="pf-v6-l-flex__item">48</div>
                            <div class="pf-v6-l-flex__item">
                              <i class="fas fa-code"></i>
                            </div>
                          </div>
                        </td>
                        <td
                          class="pf-v6-c-table__td"
                          role="cell"
                          data-label="Workspaces"
                        >
                          <div
                            class="pf-v6-l-flex pf-m-space-items-sm pf-m-nowrap"
                          >
                            <div class="pf-v6-l-flex__item">13</div>
                            <div class="pf-v6-l-flex__item">
                              <i class="fas fa-cube"></i>
                            </div>
                          </div>
                        </td>
                        <td
                          class="pf-v6-c-table__td"
                          role="cell"
                          data-label="Last commit"
                        >30 days ago</td>

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
                            for="table-tabs-example-table-checkrow-4-check-input"
                          >
                            <input
                              class="pf-v6-c-check__input"
                              type="checkbox"
                              id="table-tabs-example-table-checkrow-4-check-input"
                              name="table-tabs-example-table-checkrow-4-check-input"
                              aria-label="Select row"
                            />
                          </label>
                        </td>

                        <th
                          class="pf-v6-c-table__th"
                          role="columnheader"
                          data-label="Repository name"
                        >
                          <div>
                            <div id="table-tabs-example-table-node4">Node 4</div>
                            <a href="#">siemur/test-space</a>
                          </div>
                        </th>

                        <td
                          class="pf-v6-c-table__td"
                          role="cell"
                          data-label="Branches"
                        >
                          <div
                            class="pf-v6-l-flex pf-m-space-items-sm pf-m-nowrap"
                          >
                            <div class="pf-v6-l-flex__item">3</div>
                            <div class="pf-v6-l-flex__item">
                              <i class="fas fa-code-branch"></i>
                            </div>
                          </div>
                        </td>
                        <td
                          class="pf-v6-c-table__td"
                          role="cell"
                          data-label="Pull requests"
                        >
                          <div
                            class="pf-v6-l-flex pf-m-space-items-sm pf-m-nowrap"
                          >
                            <div class="pf-v6-l-flex__item">8</div>
                            <div class="pf-v6-l-flex__item">
                              <i class="fas fa-code"></i>
                            </div>
                          </div>
                        </td>
                        <td
                          class="pf-v6-c-table__td"
                          role="cell"
                          data-label="Workspaces"
                        >
                          <div
                            class="pf-v6-l-flex pf-m-space-items-sm pf-m-nowrap"
                          >
                            <div class="pf-v6-l-flex__item">20</div>
                            <div class="pf-v6-l-flex__item">
                              <i class="fas fa-cube"></i>
                            </div>
                          </div>
                        </td>
                        <td
                          class="pf-v6-c-table__td"
                          role="cell"
                          data-label="Last commit"
                        >8 days ago</td>

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
                            for="table-tabs-example-table-checkrow-5-check-input"
                          >
                            <input
                              class="pf-v6-c-check__input"
                              type="checkbox"
                              id="table-tabs-example-table-checkrow-5-check-input"
                              name="table-tabs-example-table-checkrow-5-check-input"
                              aria-label="Select row"
                            />
                          </label>
                        </td>

                        <td
                          class="pf-v6-c-table__td"
                          role="cell"
                          data-label="Repository name"
                        >
                          <div>
                            <div id="table-tabs-example-table-node5">Node 5</div>
                            <a href="#">siemur/test-space</a>
                          </div>
                        </td>
                        <td
                          class="pf-v6-c-table__td"
                          role="cell"
                          data-label="Branches"
                        >
                          <div
                            class="pf-v6-l-flex pf-m-space-items-sm pf-m-nowrap"
                          >
                            <div class="pf-v6-l-flex__item">34</div>
                            <div class="pf-v6-l-flex__item">
                              <i class="fas fa-code-branch"></i>
                            </div>
                          </div>
                        </td>
                        <td
                          class="pf-v6-c-table__td"
                          role="cell"
                          data-label="Pull requests"
                        >
                          <div
                            class="pf-v6-l-flex pf-m-space-items-sm pf-m-nowrap"
                          >
                            <div class="pf-v6-l-flex__item">21</div>
                            <div class="pf-v6-l-flex__item">
                              <i class="fas fa-code"></i>
                            </div>
                          </div>
                        </td>
                        <td
                          class="pf-v6-c-table__td"
                          role="cell"
                          data-label="Workspaces"
                        >
                          <div
                            class="pf-v6-l-flex pf-m-space-items-sm pf-m-nowrap"
                          >
                            <div class="pf-v6-l-flex__item">26</div>
                            <div class="pf-v6-l-flex__item">
                              <i class="fas fa-cube"></i>
                            </div>
                          </div>
                        </td>
                        <td
                          class="pf-v6-c-table__td"
                          role="cell"
                          data-label="Last commit"
                        >2 days ago</td>

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
              </div>

              <!-- Panel -->
              <div
                class="pf-v6-c-drawer__panel pf-m-width-33 pf-m-width-33-on-xl"
              >
                <div class="pf-v6-c-drawer__body">
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
                    <div class="pf-v6-l-flex pf-m-column pf-m-space-items-sm">
                      <div class="pf-v6-l-flex__item">
                        <h2
                          class="pf-v6-c-title pf-m-lg"
                          id="-drawer-label"
                        >Node 2</h2>
                      </div>
                      <div class="pf-v6-l-flex__item">
                        <a href="#">siemur/test-space</a>
                      </div>
                    </div>
                  </div>
                </div>
                <div class="pf-v6-c-drawer__body pf-m-no-padding">
                  <div
                    class="pf-v6-c-tabs pf-m-box pf-m-fill"
                    role="region"
                    id="-tabs"
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
                          aria-controls="-tabs-tab1-panel"
                          id="-tabs-tab1-link"
                        >
                          <span class="pf-v6-c-tabs__item-text">Overview</span>
                        </button>
                      </li>
                      <li class="pf-v6-c-tabs__item" role="presentation">
                        <button
                          type="button"
                          class="pf-v6-c-tabs__link"
                          role="tab"
                          aria-controls="-tabs-tab2-panel"
                          id="-tabs-tab2-link"
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
                <div class="pf-v6-c-drawer__body">
                  <section
                    class="pf-v6-c-tab-content"
                    id="-tabs-tab1-panel"
                    aria-labelledby="-tabs-tab1-link"
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
                            id="-progress-example1"
                          >
                            <div
                              class="pf-v6-c-progress__description"
                              id="-progress-example1-description"
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
                              aria-labelledby="-progress-example1-description"
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
                            id="-progress-example2"
                          >
                            <div
                              class="pf-v6-c-progress__description"
                              id="-progress-example2-description"
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
                              aria-labelledby="-progress-example2-description"
                              aria-label="Progress 2"
                            >
                              <div
                                class="pf-v6-c-progress__indicator"
                                style="width:66%;"
                              ></div>
                            </div>
                          </div>
                        </div>
                        <div class="pf-v6-l-flex pf-m-column">
                          <div class="pf-v6-l-flex__item">
                            <h3 class="pf-v6-c-title" id="-title">Tags</h3>
                          </div>
                          <div class="pf-v6-l-flex__item">
                            <div class="pf-v6-c-label-group">
                              <div class="pf-v6-c-label-group__main">
                                <ul
                                  class="pf-v6-c-label-group__list"
                                  role="list"
                                  aria-label="Group of labels"
                                >
                                  <li class="pf-v6-c-label-group__list-item">
                                    <span class="pf-v6-c-label pf-m-outline">
                                      <span class="pf-v6-c-label__content">
                                        <span class="pf-v6-c-label__text">Tag 1</span>
                                      </span>
                                    </span>
                                  </li>
                                  <li class="pf-v6-c-label-group__list-item">
                                    <span class="pf-v6-c-label pf-m-outline">
                                      <span class="pf-v6-c-label__content">
                                        <span class="pf-v6-c-label__text">Tag 2</span>
                                      </span>
                                    </span>
                                  </li>
                                  <li class="pf-v6-c-label-group__list-item">
                                    <span class="pf-v6-c-label pf-m-outline">
                                      <span class="pf-v6-c-label__content">
                                        <span class="pf-v6-c-label__text">Tag 3</span>
                                      </span>
                                    </span>
                                  </li>
                                  <li class="pf-v6-c-label-group__list-item">
                                    <button
                                      class="pf-v6-c-label pf-m-overflow"
                                      type="button"
                                    >
                                      <span class="pf-v6-c-label__content">
                                        <span class="pf-v6-c-label__text">2 more</span>
                                      </span>
                                    </button>
                                  </li>
                                </ul>
                              </div>
                            </div>
                          </div>
                        </div>
                      </div>
                    </div>
                  </section>
                  <section
                    class="pf-v6-c-tab-content"
                    id="-tabs-tab2-panel"
                    aria-labelledby="-tabs-tab2-link"
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

### Modal tabs

```html isFullscreen
<div class="pf-v6-c-backdrop">
  <div class="pf-v6-l-bullseye">
    <div
      class="pf-v6-c-modal-box pf-m-sm"
      role="dialog"
      aria-modal="true"
      aria-labelledby="modal-tabs-example-modal-title"
      aria-describedby="modal-tabs-example-modal-description"
    >
      <div class="pf-v6-c-modal-box__close">
        <button
          class="pf-v6-c-button pf-m-plain"
          type="button"
          aria-label="Close"
        >
          <span class="pf-v6-c-button__icon">
            <i class="fas fa-times" aria-hidden="true"></i>
          </span>
        </button>
      </div>
      <header class="pf-v6-c-modal-box__header">
        <div class="pf-v6-c-modal-box__header-main">
          <h1
            class="pf-v6-c-modal-box__title"
            id="modal-tabs-example-modal-title"
          >PatternFly</h1>
        </div>
      </header>
      <div
        class="pf-v6-c-modal-box__body"
        id="modal-tabs-example-modal-description"
      >
        <div class="pf-v6-l-grid pf-m-gutter">
          <div class="pf-v6-l-grid__item">
            <div
              class="pf-v6-c-tabs pf-m-inset-none"
              role="region"
              id="modal-tabs-example-tabs"
            >
              <ul class="pf-v6-c-tabs__list" role="tablist">
                <li class="pf-v6-c-tabs__item pf-m-current" role="presentation">
                  <button
                    type="button"
                    class="pf-v6-c-tabs__link"
                    role="tab"
                    aria-controls="modal-tabs-example-tabs-details-panel"
                    id="modal-tabs-example-tabs-details-link"
                  >
                    <span class="pf-v6-c-tabs__item-text">Details</span>
                  </button>
                </li>
                <li class="pf-v6-c-tabs__item" role="presentation">
                  <button
                    type="button"
                    class="pf-v6-c-tabs__link"
                    role="tab"
                    aria-controls="modal-tabs-example-tabs-documentation-panel"
                    id="modal-tabs-example-tabs-documentation-link"
                  >
                    <span class="pf-v6-c-tabs__item-text">Documentation</span>
                  </button>
                </li>
              </ul>
            </div>
          </div>
          <div class="pf-v6-l-grid__item">
            <section
              class="pf-v6-c-tab-content"
              aria-labelledby="modal-tabs-example-tabs-details-link"
              id="modal-tabs-example-tabs-details-panel"
              role="tabpanel"
              tabindex="0"
            >
              <div class="pf-v6-c-tab-content__body">
                <p>PatternFly is a community project that promotes design commonality and improves user experience.</p>
              </div>
            </section>
            <section
              class="pf-v6-c-tab-content"
              aria-labelledby="modal-tabs-example-tabs-documentation-link"
              id="modal-tabs-example-tabs-documentation-panel"
              role="tabpanel"
              tabindex="0"
              hidden
            >
              <div class="pf-v6-c-tab-content__body">
                <ul class="pf-v6-c-list" role="list">
                  <li>
                    <a>Doc link 1</a>
                  </li>
                  <li>
                    <a>Doc link 2</a>
                  </li>
                  <li>
                    <a>Doc link 3</a>
                  </li>
                </ul>
              </div>
            </section>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>

<div class="pf-v6-c-page" id="modal-tabs-example">
  <div class="pf-v6-c-skip-to-content">
    <a
      class="pf-v6-c-button pf-m-primary"
      href="#main-content-modal-tabs-example"
    >
      <span class="pf-v6-c-button__text">Skip to content</span>
    </a>
  </div>
  <header class="pf-v6-c-masthead" id="modal-tabs-example-masthead">
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
        id="modal-tabs-example-masthead-toolbar"
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
        id="modal-tabs-example-primary-nav"
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
      id="main-content-modal-tabs-example"
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
          <div class="pf-v6-l-gallery pf-m-gutter">
            <div
              class="pf-v6-c-card pf-m-selectable-raised pf-m-compact"
              id="modal-tabs-example-card-1"
            >
              <div class="pf-v6-c-card__title">
                <h2 class="pf-v6-c-card__title-text">PatternFly</h2>
              </div>
              <div
                class="pf-v6-c-card__body"
              >PatternFly is a community project that promotes design commonality and improves user experience.</div>
            </div>
            <div
              class="pf-v6-c-card pf-m-selectable-raised pf-m-compact"
              id="modal-tabs-example-card-2"
            >
              <div class="pf-v6-c-card__title">
                <h2 class="pf-v6-c-card__title-text">ActiveMQ</h2>
              </div>
              <div
                class="pf-v6-c-card__body"
              >The ActiveMQ component allows messages to be sent to a JMS Queue or Topic; or messages to be consumed from a JMS Queue or Topic using Apache ActiveMQ.</div>
            </div>
            <div
              class="pf-v6-c-card pf-m-selectable-raised pf-m-compact"
              id="modal-tabs-example-card-3"
            >
              <div class="pf-v6-c-card__title">
                <h2 class="pf-v6-c-card__title-text">Apache Spark</h2>
              </div>
              <div
                class="pf-v6-c-card__body"
              >This documentation page covers the Apache Spark component for the Apache Camel.</div>
            </div>
          </div>
        </div>
      </section>
    </main>
  </div>
</div>

```

### Nested, unindented tabs

```html isFullscreen
<div class="pf-v6-c-page" id="gray-tabs-example">
  <div class="pf-v6-c-skip-to-content">
    <a
      class="pf-v6-c-button pf-m-primary"
      href="#main-content-gray-tabs-example"
    >
      <span class="pf-v6-c-button__text">Skip to content</span>
    </a>
  </div>
  <header class="pf-v6-c-masthead" id="gray-tabs-example-masthead">
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
        id="gray-tabs-example-masthead-toolbar"
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
        id="gray-tabs-example-primary-nav"
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
      id="main-content-gray-tabs-example"
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
      <section class="pf-v6-c-page__main-tabs pf-m-limit-width">
        <div class="pf-v6-c-page__main-body">
          <div
            class="pf-v6-c-tabs pf-m-page-insets"
            role="region"
            id="gray-tabs-example-tabs-tabs"
          >
            <ul class="pf-v6-c-tabs__list" role="tablist">
              <li class="pf-v6-c-tabs__item" role="presentation">
                <button
                  type="button"
                  class="pf-v6-c-tabs__link"
                  role="tab"
                  aria-controls="gray-tabs-example-tabs-tabs-new-panel"
                  id="gray-tabs-example-tabs-tabs-new-link"
                >
                  <span class="pf-v6-c-tabs__item-text">What's new</span>
                </button>
              </li>
              <li class="pf-v6-c-tabs__item pf-m-current" role="presentation">
                <button
                  type="button"
                  class="pf-v6-c-tabs__link"
                  role="tab"
                  aria-controls="gray-tabs-example-tabs-tabs-get-started-panel"
                  id="gray-tabs-example-tabs-tabs-get-started-link"
                >
                  <span class="pf-v6-c-tabs__item-text">Get started</span>
                </button>
              </li>
              <li class="pf-v6-c-tabs__item" role="presentation">
                <button
                  type="button"
                  class="pf-v6-c-tabs__link"
                  role="tab"
                  aria-controls="gray-tabs-example-tabs-tabs-knowledge-panel"
                  id="gray-tabs-example-tabs-tabs-knowledge-link"
                >
                  <span class="pf-v6-c-tabs__item-text">Knowledge</span>
                </button>
              </li>
              <li class="pf-v6-c-tabs__item" role="presentation">
                <button
                  type="button"
                  class="pf-v6-c-tabs__link"
                  role="tab"
                  aria-controls="gray-tabs-example-tabs-tabs-support-panel"
                  id="gray-tabs-example-tabs-tabs-support-link"
                >
                  <span class="pf-v6-c-tabs__item-text">Support</span>
                </button>
              </li>
            </ul>
          </div>
        </div>
      </section>
      <section class="pf-v6-c-page__main-section pf-m-limit-width">
        <div class="pf-v6-c-page__main-body">
          <section
            class="pf-v6-c-tab-content"
            aria-labelledby="gray-tabs-example-tabs-tabs-new-link"
            id="gray-tabs-example-tabs-tabs-new-panel"
            role="tabpanel"
            tabindex="0"
            hidden
          >
            <div class="pf-v6-c-tab-content__body">What's new content</div>
          </section>
          <section
            class="pf-v6-c-tab-content"
            aria-labelledby="gray-tabs-example-tabs-tabs-get-started-link"
            id="gray-tabs-example-tabs-tabs-get-started-panel"
            role="tabpanel"
            tabindex="0"
          >
            <div class="pf-v6-c-tab-content__body">
              <div class="pf-v6-l-grid pf-m-gutter">
                <div class="pf-v6-l-grid__item">
                  <h1
                    class="pf-v6-c-title pf-m-lg"
                  >Get started with Red Hat Enterprise Linux</h1>
                </div>
                <div class="pf-v6-l-grid__item">
                  <div
                    class="pf-v6-c-tabs pf-m-inset-none"
                    role="region"
                    id="gray-tabs-example-tabs-subtabs"
                  >
                    <ul class="pf-v6-c-tabs__list" role="tablist">
                      <li
                        class="pf-v6-c-tabs__item pf-m-current"
                        role="presentation"
                      >
                        <button
                          type="button"
                          class="pf-v6-c-tabs__link"
                          role="tab"
                          aria-controls="gray-tabs-example-tabs-subtabs-x86-panel"
                          id="gray-tabs-example-tabs-subtabs-x86-link"
                        >
                          <span class="pf-v6-c-tabs__item-text">x86 architecture</span>
                        </button>
                      </li>
                      <li class="pf-v6-c-tabs__item" role="presentation">
                        <button
                          type="button"
                          class="pf-v6-c-tabs__link"
                          role="tab"
                          aria-controls="gray-tabs-example-tabs-subtabs-additional-architectures-panel"
                          id="gray-tabs-example-tabs-subtabs-additional-architectures-link"
                        >
                          <span
                            class="pf-v6-c-tabs__item-text"
                          >Additional Architectures</span>
                        </button>
                      </li>
                    </ul>
                  </div>
                </div>
                <div class="pf-v6-l-grid__item">
                  <section
                    class="pf-v6-c-tab-content"
                    aria-labelledby="gray-tabs-example-tabs-subtabs-x86-link"
                    id="gray-tabs-example-tabs-subtabs-x86-panel"
                    role="tabpanel"
                    tabindex="0"
                  >
                    <div class="pf-v6-c-tab-content__body">
                      <div class="pf-v6-l-grid pf-m-gutter">
                        <div class="pf-v6-l-grid__item">
                          <div class="pf-v6-c-content">
                            <p>To perform a standard x86_64 installation using the GUI, you'll need to:</p>
                          </div>
                        </div>
                        <div
                          class="pf-v6-l-grid pf-m-all-6-col-on-md pf-m-all-3-col-on-2xl pf-m-gutter"
                        >
                          <div class="pf-v6-c-card pf-m-flat">
                            <div class="pf-v6-c-card__title">
                              <h2
                                class="pf-v6-c-card__title-text"
                              >Check system requirements</h2>
                            </div>
                            <div class="pf-v6-c-card__body">
                              <p>
                                Your physical or virtual machine should meet the
                                <a href="#">system requirement</a>.
                              </p>
                            </div>
                          </div>
                          <div class="pf-v6-c-card pf-m-flat">
                            <div class="pf-v6-c-card__title">
                              <h2
                                class="pf-v6-c-card__title-text"
                              >Download an installation ISO image</h2>
                            </div>
                            <div class="pf-v6-c-card__body">
                              <p>
                                <a href="#">Download</a>&nbsp;the binary DVD ISO.
                              </p>
                            </div>
                          </div>
                          <div class="pf-v6-c-card pf-m-flat">
                            <div class="pf-v6-c-card__title">
                              <h2
                                class="pf-v6-c-card__title-text"
                              >Create a bootable installation media</h2>
                            </div>
                            <div class="pf-v6-c-card__body">
                              <p>
                                <a href="#">Create</a>&nbsp;a bootable installation media, for example a USB flash drive.
                              </p>
                            </div>
                          </div>
                        </div>
                      </div>
                    </div>
                  </section>
                  <section
                    class="pf-v6-c-tab-content"
                    aria-labelledby="gray-tabs-example-tabs-subtabs-additional-architectures-link"
                    id="gray-tabs-example-tabs-subtabs-additional-architectures-panel"
                    role="tabpanel"
                    tabindex="0"
                    hidden
                  >
                    <div class="pf-v6-c-tab-content__body">
                      <p>Additional architectural content</p>
                    </div>
                  </section>
                </div>
              </div>
            </div>
          </section>
          <section
            class="pf-v6-c-tab-content"
            aria-labelledby="gray-tabs-example-tabs-tabs-knowledge-link"
            id="gray-tabs-example-tabs-tabs-knowledge-panel"
            role="tabpanel"
            tabindex="0"
            hidden
          >
            <div class="pf-v6-c-tab-content__body">
              <div class="pf-v6-c-content">
                <p>Knowledge content</p>
              </div>
            </div>
          </section>
          <section
            class="pf-v6-c-tab-content"
            aria-labelledby="gray-tabs-example-tabs-tabs-support-link"
            id="gray-tabs-example-tabs-tabs-support-panel"
            role="tabpanel"
            tabindex="0"
            hidden
          >
            <div class="pf-v6-c-tab-content__body">
              <div class="pf-v6-c-content">
                <p>Support content</p>
              </div>
            </div>
          </section>
        </div>
      </section>
    </main>
  </div>
</div>

```
