---
id: 'Description list'
section: components
cssPrefix: pf-d-description-list
---## Examples

### Basic

```html isFullscreen
<div class="pf-v6-c-page" id="description-list-basic-example">
  <div class="pf-v6-c-skip-to-content">
    <a
      class="pf-v6-c-button pf-m-primary"
      href="#main-content-description-list-basic-example"
    >
      <span class="pf-v6-c-button__text">Skip to content</span>
    </a>
  </div>
  <header class="pf-v6-c-masthead" id="description-list-basic-example-masthead">
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
        id="description-list-basic-example-masthead-toolbar"
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
        id="description-list-basic-example-primary-nav"
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
      id="main-content-description-list-basic-example"
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
      <section class="pf-v6-c-page__main-section pf-m-limit-width">
        <div class="pf-v6-c-page__main-body">
          <div class="pf-v6-c-card">
            <div class="pf-v6-c-card__header">
              <h2 class="pf-v6-c-title pf-m-lg">Details</h2>
            </div>
            <hr class="pf-v6-c-divider" />
            <div class="pf-v6-c-card__body">
              <dl class="pf-v6-c-description-list pf-m-auto-fit">
                <div class="pf-v6-c-description-list__group">
                  <dt class="pf-v6-c-description-list__term">
                    <span class="pf-v6-c-description-list__text">Name</span>
                  </dt>
                  <dd class="pf-v6-c-description-list__description">
                    <div class="pf-v6-c-description-list__text">mary-test</div>
                  </dd>
                </div>
                <div class="pf-v6-c-description-list__group">
                  <dt class="pf-v6-c-description-list__term">
                    <span class="pf-v6-c-description-list__text">Status</span>
                  </dt>
                  <dd class="pf-v6-c-description-list__description">
                    <div class="pf-v6-c-description-list__text">
                      <div class="pf-v6-l-flex pf-m-space-items-sm">
                        <div class="pf-v6-l-flex__item">
                          <i
                            class="fas fa-check-circle pf-v6-u-success-color-100"
                            aria-hidden="true"
                          ></i>
                        </div>
                        <div class="pf-v6-l-flex__item">
                          <span>Active</span>
                        </div>
                      </div>
                    </div>
                  </dd>
                </div>
                <div class="pf-v6-c-description-list__group">
                  <dt class="pf-v6-c-description-list__term">
                    <span
                      class="pf-v6-c-description-list__text"
                    >Default pull secret</span>
                  </dt>
                  <dd class="pf-v6-c-description-list__description">
                    <div class="pf-v6-c-description-list__text">
                      <span class="pf-v6-u-color-300">Not configured</span>
                    </div>
                  </dd>
                </div>
                <div class="pf-v6-c-description-list__group">
                  <dt class="pf-v6-c-description-list__term">
                    <span class="pf-v6-c-description-list__text">Tolerations</span>
                  </dt>
                  <dd class="pf-v6-c-description-list__description">
                    <div class="pf-v6-c-description-list__text">6 Tolerations</div>
                  </dd>
                </div>
                <div class="pf-v6-c-description-list__group">
                  <dt class="pf-v6-c-description-list__term">
                    <span
                      class="pf-v6-c-description-list__text"
                    >Network Policies</span>
                  </dt>
                  <dd class="pf-v6-c-description-list__description">
                    <div class="pf-v6-c-description-list__text">
                      <a href="#">Network Policies</a>
                    </div>
                  </dd>
                </div>
                <div class="pf-v6-c-description-list__group">
                  <dt class="pf-v6-c-description-list__term">
                    <span class="pf-v6-c-description-list__text">Display name</span>
                  </dt>
                  <dd class="pf-v6-c-description-list__description">
                    <div class="pf-v6-c-description-list__text">mary</div>
                  </dd>
                </div>
                <div class="pf-v6-c-description-list__group">
                  <dt class="pf-v6-c-description-list__term">
                    <span class="pf-v6-c-description-list__text">Requester</span>
                  </dt>
                  <dd class="pf-v6-c-description-list__description">
                    <div class="pf-v6-c-description-list__text">kube:admin</div>
                  </dd>
                </div>
                <div class="pf-v6-c-description-list__group">
                  <dt class="pf-v6-c-description-list__term">
                    <span class="pf-v6-c-description-list__text">Created at:</span>
                  </dt>
                  <dd class="pf-v6-c-description-list__description">
                    <div class="pf-v6-c-description-list__text">3 minutes ago</div>
                  </dd>
                </div>
              </dl>
            </div>
          </div>
        </div>
      </section>
    </main>
  </div>
</div>

```

### In drawer

```html isFullscreen
<div class="pf-v6-c-page" id="description-list-in-drawer-example">
  <div class="pf-v6-c-skip-to-content">
    <a
      class="pf-v6-c-button pf-m-primary"
      href="#main-content-description-list-in-drawer-example"
    >
      <span class="pf-v6-c-button__text">Skip to content</span>
    </a>
  </div>
  <header
    class="pf-v6-c-masthead"
    id="description-list-in-drawer-example-masthead"
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
        id="description-list-in-drawer-example-masthead-toolbar"
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
        id="description-list-in-drawer-example-primary-nav"
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
  <div class="pf-v6-c-page__drawer">
    <div class="pf-v6-c-drawer pf-m-expanded">
      <div class="pf-v6-c-drawer__main">
        <div class="pf-v6-c-drawer__content">
          <div class="pf-v6-c-drawer__body">
            <div class="pf-v6-c-page__main-container" tabindex="-1">
              <main
                class="pf-v6-c-page__main"
                tabindex="-1"
                id="main-content-description-list-in-drawer-example"
              >
                <section class="pf-v6-c-page__main-breadcrumb pf-m-limit-width">
                  <div class="pf-v6-c-page__main-body">
                    <nav class="pf-v6-c-breadcrumb" aria-label="breadcrumb">
                      <ol class="pf-v6-c-breadcrumb__list" role="list">
                        <li class="pf-v6-c-breadcrumb__item">
                          <a
                            href="#"
                            class="pf-v6-c-breadcrumb__link"
                          >Section home</a>
                        </li>
                        <li class="pf-v6-c-breadcrumb__item">
                          <span class="pf-v6-c-breadcrumb__item-divider">
                            <i class="fas fa-angle-right" aria-hidden="true"></i>
                          </span>

                          <a
                            href="#"
                            class="pf-v6-c-breadcrumb__link"
                          >Section title</a>
                        </li>
                        <li class="pf-v6-c-breadcrumb__item">
                          <span class="pf-v6-c-breadcrumb__item-divider">
                            <i class="fas fa-angle-right" aria-hidden="true"></i>
                          </span>

                          <a
                            href="#"
                            class="pf-v6-c-breadcrumb__link"
                          >Section title</a>
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
                <section class="pf-v6-c-page__main-section pf-m-limit-width">
                  <div class="pf-v6-c-page__main-body">
                    <div class="pf-v6-l-gallery pf-m-gutter">
                      <div class="pf-v6-c-card">
                        <div class="pf-v6-c-card__body">This is a card</div>
                      </div>
                      <div class="pf-v6-c-card">
                        <div class="pf-v6-c-card__body">This is a card</div>
                      </div>
                      <div class="pf-v6-c-card">
                        <div class="pf-v6-c-card__body">This is a card</div>
                      </div>
                      <div class="pf-v6-c-card">
                        <div class="pf-v6-c-card__body">This is a card</div>
                      </div>
                      <div class="pf-v6-c-card">
                        <div class="pf-v6-c-card__body">This is a card</div>
                      </div>
                      <div class="pf-v6-c-card">
                        <div class="pf-v6-c-card__body">This is a card</div>
                      </div>
                      <div class="pf-v6-c-card">
                        <div class="pf-v6-c-card__body">This is a card</div>
                      </div>
                      <div class="pf-v6-c-card">
                        <div class="pf-v6-c-card__body">This is a card</div>
                      </div>
                      <div class="pf-v6-c-card">
                        <div class="pf-v6-c-card__body">This is a card</div>
                      </div>
                      <div class="pf-v6-c-card">
                        <div class="pf-v6-c-card__body">This is a card</div>
                      </div>
                    </div>
                  </div>
                </section>
              </main>
            </div>
          </div>
        </div>
        <div class="pf-v6-c-drawer__panel pf-m-width-33-on-lg">
          <div class="pf-v6-c-drawer__body">
            <div class="pf-v6-c-drawer__head">
              <div class="pf-v6-c-drawer__actions">
                <button
                  class="pf-v6-c-menu-toggle pf-m-plain"
                  type="button"
                  aria-expanded="false"
                  aria-label="Menu toggle"
                  id="description-list-in-drawer-example-toggle"
                >
                  <span class="pf-v6-c-menu-toggle__icon">
                    <i class="fas fa-ellipsis-v" aria-hidden="true"></i>
                  </span>
                </button>
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
              <div class="pf-v6-l-flex pf-m-space-items-sm">
                <div class="pf-v6-l-flex__item">
                  <span class="pf-v6-c-label pf-m-compact pf-m-blue">
                    <span class="pf-v6-c-label__content">
                      <span class="pf-v6-c-label__text">DC</span>
                    </span>
                  </span>
                </div>
                <div class="pf-v6-l-flex__item">
                  <h2
                    class="pf-v6-c-title pf-m-xl"
                    id="description-list-in-drawer-example-drawer-label"
                  >mary-test</h2>
                </div>
              </div>
            </div>
          </div>
          <div class="pf-v6-c-drawer__body pf-m-no-padding">
            <div class="pf-v6-c-tabs pf-m-box pf-m-fill">
              <ul class="pf-v6-c-tabs__list" role="tablist">
                <li class="pf-v6-c-tabs__item pf-m-current" role="presentation">
                  <button
                    type="button"
                    class="pf-v6-c-tabs__link"
                    role="tab"
                    id="description-list-in-drawer-example-panel-tabs-tab1-link"
                  >
                    <span class="pf-v6-c-tabs__item-text">Overview</span>
                  </button>
                </li>
                <li class="pf-v6-c-tabs__item" role="presentation">
                  <button
                    type="button"
                    class="pf-v6-c-tabs__link"
                    role="tab"
                    id="description-list-in-drawer-example-panel-tabs-tab2-link"
                  >
                    <span class="pf-v6-c-tabs__item-text">Activity</span>
                  </button>
                </li>
              </ul>
            </div>
          </div>
          <div class="pf-v6-c-drawer__body">
            <section
              class="pf-v6-c-tab-content"
              id="description-list-in-drawer-example-panel-tabs-tab1-panel"
              aria-labelledby="description-list-in-drawer-example-panel-tabs-tab1-link"
              role="tabpanel"
              tabindex="0"
            >
              <div class="pf-v6-c-tab-content__body">
                <dl
                  class="pf-v6-c-description-list pf-m-fill-columns pf-m-2-col pf-m-compact"
                >
                  <div class="pf-v6-c-description-list__group">
                    <dt class="pf-v6-c-description-list__term">
                      <span class="pf-v6-c-description-list__text">Name</span>
                    </dt>
                    <dd class="pf-v6-c-description-list__description">
                      <div class="pf-v6-c-description-list__text">mary-test</div>
                    </dd>
                  </div>
                  <div class="pf-v6-c-description-list__group">
                    <dt class="pf-v6-c-description-list__term">
                      <span class="pf-v6-c-description-list__text">Namespace</span>
                    </dt>
                    <dd class="pf-v6-c-description-list__description">
                      <div class="pf-v6-c-description-list__text">
                        <div class="pf-v6-l-flex pf-m-space-items-sm">
                          <div class="pf-v6-l-flex__item">
                            <span class="pf-v6-c-label pf-m-green">
                              <span class="pf-v6-c-label__content">
                                <span class="pf-v6-c-label__text">NS</span>
                              </span>
                            </span>
                          </div>
                          <div class="pf-v6-l-flex__item">
                            <a href="#">mary-test</a>
                          </div>
                        </div>
                      </div>
                    </dd>
                  </div>
                  <div class="pf-v6-c-description-list__group">
                    <dt class="pf-v6-c-description-list__term">
                      <span class="pf-v6-c-description-list__text">Labels</span>
                    </dt>
                    <dd class="pf-v6-c-description-list__description">
                      <div class="pf-v6-c-description-list__text">
                        <span class="pf-v6-c-label pf-m-outline">
                          <span class="pf-v6-c-label__content">
                            <span class="pf-v6-c-label__content">
                              <span class="pf-v6-c-label__text">app=mary-test</span>
                            </span>
                          </span>
                        </span>
                      </div>
                    </dd>
                  </div>
                  <div class="pf-v6-c-description-list__group">
                    <dt class="pf-v6-c-description-list__term">
                      <span class="pf-v6-c-description-list__text">Node selector</span>
                    </dt>
                    <dd class="pf-v6-c-description-list__description">
                      <p
                        class="pf-v6-c-description-list__text pf-v6-u-text-color-subtle"
                      >Nod selector is not available at this time</p>
                    </dd>
                  </div>
                  <div class="pf-v6-c-description-list__group">
                    <dt class="pf-v6-c-description-list__term">
                      <span class="pf-v6-c-description-list__text">Tolerations</span>
                    </dt>
                    <dd class="pf-v6-c-description-list__description">
                      <div
                        class="pf-v6-c-description-list__text pf-v6-u-text-color-subtle"
                      >No tolerations</div>
                    </dd>
                  </div>
                  <div class="pf-v6-c-description-list__group">
                    <dt class="pf-v6-c-description-list__term">
                      <span class="pf-v6-c-description-list__text">Annotations</span>
                    </dt>
                    <dd class="pf-v6-c-description-list__description">
                      <div
                        class="pf-v6-c-description-list__text pf-v6-u-text-color-subtle"
                      >No annotations</div>
                    </dd>
                  </div>
                  <div class="pf-v6-c-description-list__group">
                    <dt class="pf-v6-c-description-list__term">
                      <span class="pf-v6-c-description-list__text">Status</span>
                    </dt>
                    <dd class="pf-v6-c-description-list__description">
                      <div class="pf-v6-c-description-list__text">Active</div>
                    </dd>
                  </div>
                  <div class="pf-v6-c-description-list__group">
                    <dt class="pf-v6-c-description-list__term">
                      <span class="pf-v6-c-description-list__text">Created at:</span>
                    </dt>
                    <dd class="pf-v6-c-description-list__description">
                      <div class="pf-v6-c-description-list__text">3 minutes ago</div>
                    </dd>
                  </div>
                  <div class="pf-v6-c-description-list__group">
                    <dt class="pf-v6-c-description-list__term">
                      <span class="pf-v6-c-description-list__text">Pod selector</span>
                    </dt>
                    <dd class="pf-v6-c-description-list__description">
                      <div class="pf-v6-c-description-list__text">
                        <a href="#">
                          <div class="pf-v6-l-flex pf-m-space-items-sm">
                            <div class="pf-v6-l-flex__item">
                              <i class="fas fa-search" aria-hidden="true"></i>
                            </div>
                            <div class="pf-v6-l-flex__item">
                              <span>app=MyApp</span>
                            </div>
                          </div>
                        </a>
                      </div>
                    </dd>
                  </div>
                  <div class="pf-v6-c-description-list__group">
                    <dt class="pf-v6-c-description-list__term">
                      <span class="pf-v6-c-description-list__text">Annotations</span>
                    </dt>
                    <dd class="pf-v6-c-description-list__description">
                      <div class="pf-v6-c-description-list__text">2 Annotations</div>
                    </dd>
                  </div>
                  <div class="pf-v6-c-description-list__group">
                    <dt class="pf-v6-c-description-list__term">
                      <span
                        class="pf-v6-c-description-list__text"
                      >Session affinity</span>
                    </dt>
                    <dd class="pf-v6-c-description-list__description">
                      <div
                        class="pf-v6-c-description-list__text pf-v6-u-text-color-subtle"
                      >None</div>
                    </dd>
                  </div>
                  <div class="pf-v6-c-description-list__group">
                    <dt class="pf-v6-c-description-list__term">
                      <span
                        class="pf-v6-c-description-list__text"
                      >Latest version</span>
                    </dt>
                    <dd class="pf-v6-c-description-list__description">
                      <div class="pf-v6-c-description-list__text">1.0</div>
                    </dd>
                  </div>
                  <div class="pf-v6-c-description-list__group">
                    <dt class="pf-v6-c-description-list__term">
                      <span
                        class="pf-v6-c-description-list__text"
                      >Update strategy</span>
                    </dt>
                    <dd class="pf-v6-c-description-list__description">
                      <div class="pf-v6-c-description-list__text">Rolling</div>
                    </dd>
                  </div>
                  <div class="pf-v6-c-description-list__group">
                    <dt class="pf-v6-c-description-list__term">
                      <span class="pf-v6-c-description-list__text">Timeout</span>
                    </dt>
                    <dd class="pf-v6-c-description-list__description">
                      <div class="pf-v6-c-description-list__text">600 seconds</div>
                    </dd>
                  </div>
                  <div class="pf-v6-c-description-list__group">
                    <dt class="pf-v6-c-description-list__term">
                      <span class="pf-v6-c-description-list__text">Update period</span>
                    </dt>
                    <dd class="pf-v6-c-description-list__description">
                      <div class="pf-v6-c-description-list__text">1 second</div>
                    </dd>
                  </div>
                  <div class="pf-v6-c-description-list__group">
                    <dt class="pf-v6-c-description-list__term">
                      <span class="pf-v6-c-description-list__text">Interval</span>
                    </dt>
                    <dd class="pf-v6-c-description-list__description">
                      <div class="pf-v6-c-description-list__text">1 second</div>
                    </dd>
                  </div>
                  <div class="pf-v6-c-description-list__group">
                    <dt class="pf-v6-c-description-list__term">
                      <span class="pf-v6-c-description-list__text">Max available</span>
                    </dt>
                    <dd class="pf-v6-c-description-list__description">
                      <div class="pf-v6-c-description-list__text">25% of 1 pod</div>
                    </dd>
                  </div>
                  <div class="pf-v6-c-description-list__group">
                    <dt class="pf-v6-c-description-list__term">
                      <span class="pf-v6-c-description-list__text">Max surge</span>
                    </dt>
                    <dd class="pf-v6-c-description-list__description">
                      <div
                        class="pf-v6-c-description-list__text"
                      >25% greater than 1 pod</div>
                    </dd>
                  </div>
                  <div class="pf-v6-c-description-list__group">
                    <dt class="pf-v6-c-description-list__term">
                      <span
                        class="pf-v6-c-description-list__text"
                      >Min ready seconds</span>
                    </dt>
                    <dd class="pf-v6-c-description-list__description">
                      <div
                        class="pf-v6-c-description-list__text pf-v6-u-text-color-subtle"
                      >Not configured</div>
                    </dd>
                  </div>
                  <div class="pf-v6-c-description-list__group">
                    <dt class="pf-v6-c-description-list__term">
                      <span class="pf-v6-c-description-list__text">Triggers</span>
                    </dt>
                    <dd class="pf-v6-c-description-list__description">
                      <div class="pf-v6-c-description-list__text">
                        ImageChange,
                        ConfigChange
                      </div>
                    </dd>
                  </div>
                </dl>
              </div>
            </section>
            <section
              class="pf-v6-c-tab-content"
              id="description-list-in-drawer-example-panel-tabs-tab2-panel"
              aria-labelledby="description-list-in-drawer-example-panel-tabs-tab2-link"
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
</div>

```

### Complex content

```html isFullscreen
<div class="pf-v6-c-page" id="description-list-complex-content-example">
  <div class="pf-v6-c-skip-to-content">
    <a
      class="pf-v6-c-button pf-m-primary"
      href="#main-content-description-list-complex-content-example"
    >
      <span class="pf-v6-c-button__text">Skip to content</span>
    </a>
  </div>
  <header
    class="pf-v6-c-masthead"
    id="description-list-complex-content-example-masthead"
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
        id="description-list-complex-content-example-masthead-toolbar"
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
        id="description-list-complex-content-example-primary-nav"
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
      id="main-content-description-list-complex-content-example"
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
      <hr class="pf-v6-c-divider" />
      <section class="pf-v6-c-page__main-section pf-m-limit-width">
        <div class="pf-v6-c-page__main-body">
          <div class="pf-v6-l-grid pf-m-gutter">
            <div class="pf-v6-l-grid__item pf-m-5-col-on-lg pf-m-4-col-on-xl">
              <div class="pf-v6-l-grid pf-m-gutter">
                <div class="pf-v6-l-grid__item">
                  <h2 class="pf-v6-c-title pf-m-lg">Service overview</h2>
                </div>
                <div class="pf-v6-l-grid__item">
                  <dl class="pf-v6-c-description-list pf-m-2-col-on-xl">
                    <div class="pf-v6-c-description-list__group">
                      <dt class="pf-v6-c-description-list__term">
                        <span class="pf-v6-c-description-list__text">Name</span>
                      </dt>
                      <dd class="pf-v6-c-description-list__description">
                        <div class="pf-v6-c-description-list__text">mary-test</div>
                      </dd>
                    </div>
                    <div class="pf-v6-c-description-list__group">
                      <dt class="pf-v6-c-description-list__term">
                        <span class="pf-v6-c-description-list__text">Namespace</span>
                      </dt>
                      <dd class="pf-v6-c-description-list__description">
                        <div class="pf-v6-c-description-list__text">
                          <div class="pf-v6-l-flex pf-m-space-items-sm">
                            <div class="pf-v6-l-flex__item">
                              <span class="pf-v6-c-label pf-m-green">
                                <span class="pf-v6-c-label__content">
                                  <span class="pf-v6-c-label__text">NS</span>
                                </span>
                              </span>
                            </div>
                            <div class="pf-v6-l-flex__item">
                              <a href="#">mary-test</a>
                            </div>
                          </div>
                        </div>
                      </dd>
                    </div>
                    <div class="pf-v6-c-description-list__group">
                      <dt class="pf-v6-c-description-list__term">
                        <span class="pf-v6-c-description-list__text">Labels</span>
                      </dt>
                      <dd class="pf-v6-c-description-list__description">
                        <div class="pf-v6-c-description-list__text">No labels</div>
                      </dd>
                    </div>
                    <div class="pf-v6-c-description-list__group">
                      <dt class="pf-v6-c-description-list__term">
                        <span
                          class="pf-v6-c-description-list__text"
                        >Pod selector</span>
                      </dt>
                      <dd class="pf-v6-c-description-list__description">
                        <div class="pf-v6-c-description-list__text">
                          <a href="#">
                            <div class="pf-v6-l-flex pf-m-space-items-sm">
                              <div class="pf-v6-l-flex__item">
                                <i class="fas fa-search" aria-hidden="true"></i>
                              </div>
                              <div class="pf-v6-l-flex__item">
                                <span>app=MyApp</span>
                              </div>
                            </div>
                          </a>
                        </div>
                      </dd>
                    </div>
                    <div class="pf-v6-c-description-list__group">
                      <dt class="pf-v6-c-description-list__term">
                        <span class="pf-v6-c-description-list__text">Annotations</span>
                      </dt>
                      <dd class="pf-v6-c-description-list__description">
                        <div
                          class="pf-v6-c-description-list__text"
                        >2 Annotations</div>
                      </dd>
                    </div>
                    <div class="pf-v6-c-description-list__group">
                      <dt class="pf-v6-c-description-list__term">
                        <span
                          class="pf-v6-c-description-list__text"
                        >Session affinity</span>
                      </dt>
                      <dd class="pf-v6-c-description-list__description">
                        <div class="pf-v6-c-description-list__text">None</div>
                      </dd>
                    </div>
                    <div class="pf-v6-c-description-list__group">
                      <dt class="pf-v6-c-description-list__term">
                        <span class="pf-v6-c-description-list__text">Created at:</span>
                      </dt>
                      <dd class="pf-v6-c-description-list__description">
                        <div
                          class="pf-v6-c-description-list__text"
                        >3 minutes ago</div>
                      </dd>
                    </div>
                  </dl>
                </div>
              </div>
            </div>
            <div class="pf-v6-l-grid__item pf-m-6-col-on-lg pf-m-4-col-on-xl">
              <div class="pf-v6-l-grid pf-m-gutter">
                <div class="pf-v6-l-grid__item">
                  <h2 class="pf-v6-c-title pf-m-lg">Service routing</h2>
                </div>
                <div class="pf-v6-l-grid__item">
                  <dl class="pf-v6-c-description-list">
                    <div class="pf-v6-c-description-list__group">
                      <dt class="pf-v6-c-description-list__term">
                        <span
                          class="pf-v6-c-description-list__text"
                        >Service address</span>
                      </dt>
                      <dd class="pf-v6-c-description-list__description">
                        <div class="pf-v6-c-description-list__text">
                          <table
                            class="pf-v6-c-table pf-m-grid-md pf-m-compact"
                            role="grid"
                            aria-label="Service address"
                            id="service-address"
                          >
                            <thead class="pf-v6-c-table__thead">
                              <tr class="pf-v6-c-table__tr" role="row">
                                <th
                                  class="pf-v6-c-table__th"
                                  role="columnheader"
                                  scope="col"
                                >Type</th>

                                <th
                                  class="pf-v6-c-table__th"
                                  role="columnheader"
                                  scope="col"
                                >Location</th>
                              </tr>
                            </thead>

                            <tbody class="pf-v6-c-table__tbody" role="rowgroup">
                              <tr class="pf-v6-c-table__tr" role="row">
                                <td
                                  class="pf-v6-c-table__td"
                                  role="cell"
                                  data-label="Type"
                                >Cluster IP</td>
                                <td
                                  class="pf-v6-c-table__td"
                                  role="cell"
                                  data-label="Location"
                                >172.30.126.106</td>
                              </tr>
                              <tr class="pf-v6-c-table__tr" role="row">
                                <td
                                  class="pf-v6-c-table__td"
                                  role="cell"
                                  data-label="Type"
                                >Accessible within the cluster only</td>
                                <td
                                  class="pf-v6-c-table__td"
                                  role="cell"
                                  data-label="Location"
                                >n/a</td>
                              </tr>
                            </tbody>
                          </table>
                        </div>
                      </dd>
                    </div>
                    <div class="pf-v6-c-description-list__group">
                      <dt class="pf-v6-c-description-list__term">
                        <span
                          class="pf-v6-c-description-list__text"
                        >Service port mapping</span>
                      </dt>
                      <dd class="pf-v6-c-description-list__description">
                        <div class="pf-v6-c-description-list__text">
                          <table
                            class="pf-v6-c-table pf-m-grid-md pf-m-compact"
                            role="grid"
                            aria-label="Service address"
                            id="service-port"
                          >
                            <thead class="pf-v6-c-table__thead">
                              <tr class="pf-v6-c-table__tr" role="row">
                                <th
                                  class="pf-v6-c-table__th"
                                  role="columnheader"
                                  scope="col"
                                >Name</th>

                                <th
                                  class="pf-v6-c-table__th"
                                  role="columnheader"
                                  scope="col"
                                >Port</th>

                                <th
                                  class="pf-v6-c-table__th"
                                  role="columnheader"
                                  scope="col"
                                >Protocol</th>

                                <th
                                  class="pf-v6-c-table__th"
                                  role="columnheader"
                                  scope="col"
                                >Pod port or name</th>
                              </tr>
                            </thead>

                            <tbody class="pf-v6-c-table__tbody" role="rowgroup">
                              <tr class="pf-v6-c-table__tr" role="row">
                                <td
                                  class="pf-v6-c-table__td"
                                  role="cell"
                                  data-label="Name"
                                >--</td>
                                <td
                                  class="pf-v6-c-table__td"
                                  role="cell"
                                  data-label="Port"
                                >
                                  <div class="pf-v6-l-flex pf-m-space-items-sm">
                                    <div class="pf-v6-l-flex__item">
                                      <span
                                        class="pf-v6-c-label pf-m-compact pf-m-green"
                                      >
                                        <span class="pf-v6-c-label__content">
                                          <span class="pf-v6-c-label__text">S</span>
                                        </span>
                                      </span>
                                    </div>
                                    <div class="pf-v6-l-flex__item">80</div>
                                  </div>
                                </td>
                                <td
                                  class="pf-v6-c-table__td"
                                  role="cell"
                                  data-label="Protocol"
                                >TCP</td>
                                <td
                                  class="pf-v6-c-table__td"
                                  role="cell"
                                  data-label="Pod port or name"
                                >
                                  <div class="pf-v6-l-flex pf-m-space-items-sm">
                                    <div class="pf-v6-l-flex__item">
                                      <span
                                        class="pf-v6-c-label pf-m-compact pf-m-teal"
                                      >
                                        <span class="pf-v6-c-label__content">
                                          <span class="pf-v6-c-label__text">P</span>
                                        </span>
                                      </span>
                                    </div>
                                    <div class="pf-v6-l-flex__item">80</div>
                                  </div>
                                </td>
                              </tr>
                            </tbody>
                          </table>
                        </div>
                      </dd>
                    </div>
                  </dl>
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
