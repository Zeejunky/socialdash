<!-- markdownlint-disable MD032 MD033-->
<!-- Write your README.md file. Build something amazing! This README.md template can guide you to build your project documentation, but feel free to modify it as you wish 🥰 -->
# **Free Social Analytics Dashboard Template**
> Developer: Mikhail Konin, Designer: Yehor Haiduk

<div align="center">
  <!-- Change your logo -->
  <a href="https://github.com/KoninMikhail/social-analytics-dashboard-template">
    <img width="100%" src="https://raw.githubusercontent.com/KoninMikhail/social-analytics-dashboard-template/master/.repo/images/social-analytics-dashboard.jpg" alt="@koninmikhail/social-analytics-dashboard-template cover">
  </a>
  <br /><br />
  <a href="#">
      <img src="https://img.shields.io/badge/build-stable-blue?style=for-the-badge&color=succeess" alt="@koninmikhail/social-analytics-dashboard-template current release">
   </a>
  <a href="https://github.com/KoninMikhail/social-analytics-dashboard-template/issues">
    <img src="https://img.shields.io/github/issues/koninmikhail/social-analytics-dashboard-template?color=0088ff&style=for-the-badge&logo=github" alt="@koninmikhail/social analytics dashboard issues"/>
  </a>
  <a href="https://github.com/KoninMikhail/social-analytics-dashboard-template/pulls">
    <img src="https://img.shields.io/github/issues-pr/koninmikhail/social-analytics-dashboard-template?color=0088ff&style=for-the-badge&logo=github"  alt="@koninmikhail/social-analytics-dashboard-template/pulls analytics dashboard pull requests"/>
  </a>
  <a href="https://case.mikekonin.com/social-analytics-dashboard-template/">
       <img src="https://img.shields.io/badge/ -live demo-blue?style=for-the-badge&color=important" alt="@koninmikhail/social-analytics-dashboard-template link to live demo.">
  </a>
  <a href="https://github.com/KoninMikhail/social-analytics-dashboard-template/generate">
    <img src="https://img.shields.io/badge/use%20this-template-blue?logo=github-sponsors&style=for-the-badge&color=green" alt="@koninmikhail/social-analytics-dashboard-template link to create a new repository from the template">
  </a>

</div>

<br />

# **What is this template all about?**

* **Fully CSS-Grid**
* **Fully responsive**
* **Fully separate to components**
* **No require dependencies**
* **No JQuery**
* All code based on BEM principles
* Sass
* Google Fonts
* Quick start from prepared workspace: 🗲🗲
    * [Husky](https://github.com/typicode/husky) - Pre-commit tests
    * [Commitlint](https://github.com/koninmikhail/social-analytics-dashboard-template/issues) - Conventional changelog commits linter
    * [Standard-version](https://github.com/conventional-changelog/standard-version) - Automatic Generate changelog from commits and create releases
    * Webpack and addons(Babel, Sass, loaders, minimizers, etc.)
* This template can be used as a base layer for any of your future projects

<br />

## Request features ⚡
>Use [issue](https://github.com/koninmikhail/social-analytics-dashboard-template/issues) and follow the rules :)

## Report bug 🤬
>The data from repository is provided an "As is", without any guarantees. All the data provided is used at your own risk.
**If you want report a bug** - use [issue](https://github.com/KoninMikhail/social-analytics-dashboard-template/issues)

<br />

![dashboard screenshot](https://raw.githubusercontent.com/KoninMikhail/social-analytics-dashboard-template/master/.repo/images/html-social-analytics-dashboard-template-bem.gif)
![dashboard screenshot mobile](https://raw.githubusercontent.com/KoninMikhail/social-analytics-dashboard-template/master/.repo/images/mobile-preview-min.png)

<br /><br />

<img align="left" src="https://raw.githubusercontent.com/KoninMikhail/social-analytics-dashboard-template/master/.repo/iconpack/menu.png" width="50px" />

## TABLE OF CONTENTS

- [General](#what-is-this-template-all-about)
    - [Request feature](#request-features-)
- [Quick start](#quick-start)
    - [Requirements](#requirements)
    - [Report a bug](#disclamer--%EF%B8%8F)
- [Workspace](#workspace)
    - [Toolbox with scripts](#separated-configurations)
    - [Separated configurations](#main)
    - [Semantic Versioning](#semantic-versioning)
- [Template](#template)
   - [Components](#components-)
   - [Customization](#customization-)
- [Scaffolding](#scaffolding)
- [Contributing](#contributors)
- [Buy Me A Coffee](#buy-me-a-coffee)
- [License and Changelog](#license-and-changelog)

<br /><br />

<img align="left" src="https://raw.githubusercontent.com/KoninMikhail/social-analytics-dashboard-template/master/.repo/iconpack/qs.png" width="50px" />

## Quick start
> If you need only compiled project:
1. Clone this repository:
2. Go to `Dist` folder.
3. Enjoy this!

> If you need full workspace:
1. Clone this repository
2. Check system requirements.
3. Console or bash command for install package.json<br>
   `` cd html-social-analytics-dashboard-template``<br>
   `` yarn install``
4. Enjoy this!

---------
if you do not have installed Yarn package manager:
``npm install -g yarn``, and repeat guide;

## Requirements:
>- **NodeJS:** 17.3 (My version at building time)
>- **Yarn:** 1.22

<br /><br />

<img align="left" src="https://raw.githubusercontent.com/KoninMikhail/social-analytics-dashboard-template/master/.repo/iconpack/features.png" width="50px" />

## Workspace

### Toolbox with scripts

> `package.json` contains shortcuts for most requirement operations

<img width="100%" src="https://raw.githubusercontent.com/KoninMikhail/social-analytics-dashboard-template/master/.repo/images/shortcuts.jpg" alt="@koninmikhail/social-analytics-dashboard project shortcuts">

---

### Separated configurations
> To simplify working environments and improve readability configuration - `webpack.config.js` will separate into 3 files, according building mode

New configs location: ``./configuration/webpack/``

| FileName ('.js')        |             Description             |
|-------------------------|:-----------------------------------:|
| ``environment``         | Configuration for environment paths |
| ``webpack.dev.config``  | Configuration for developer bundle  |
| ``webpack.prod.config`` | Configuration for production bundle |
---

### Semantic Versioning
> Project using commitlint for automatic generation of CHANGELOG.md from your commits.

Use template: `tag: run message` for commits.

**Allowed tags for commits:**
- build
- chore
- ci
- docs
- feat
- fix
- perf
- refactor
- revert
- style
- test

<br /><br />

<img align="left" src="https://raw.githubusercontent.com/KoninMikhail/social-analytics-dashboard-template/master/.repo/iconpack/template.png" width="50px" />

## Template
### Components 🔥

> All project separated to components by BEM. You can ``easy copy-paste any module into another project``. Don't forget to replace color variables.

| Name         |               Description                |      Type       |
|--------------|:----------------------------------------:|:---------------:|
| Select       |     Custom select dropdown list menu     | JS - Component  |
| Notifer      |       Small component for Notices        | JS - Component  |
| Toggle       |          Custom toggle switcher          | JS - Component  |
| Hamburger    | Use as button-switcher mobile menu state | JS - Component  |
| Counter Card |            Display statistic             |    HTML/CSS     |
| List         |    Use for list in another components    |    HTML/CSS     |
| Logo         |                   logo                   |    HTML/CSS     |
| Menu         |                   Menu                   |    HTML/CSS     |
| Messages     |        Messages item in user-bar         |    HTML/CSS     |
| More         |          More item in user-bar           |    HTML/CSS     |
| New Action   |    New Action button item in user-bar    |    HTML/CSS     |
| Profile      |     Profile picture item in user-bar     |    HTML/CSS     |
| Page Heading |                Page Title                |    HTML/CSS     |
| Pie Chart    |        Diagram and legend styles         |    HTML/CSS     |
| Search       |            Search box styles             |    HTML/CSS     |

### Customization ‍🎨
> Set colors, fonts, sizes as you like when needed.

For get all customize variables go to ``./src/config/``

| Filename                   |                    Description                    |
|----------------------------|:-------------------------------------------------:|
| ``colors.config.scss``     | Full library with all colors used on this project |
| ``typography.config.scss`` |                  All for fonts.                   |
| ``variables.config.scss``  |         Gaps, border radius, transition.          |

<br /><br />

<img align="left" src="https://raw.githubusercontent.com/KoninMikhail/social-analytics-dashboard-template/master/.repo/iconpack/tree.png" width="50px" />

## Scaffolding
```
.
├── .commitlintrc.json
├── .versionrc.json
├── babel.config.json
├── CHANGELOG.md
├── configuration
│   ├── husky
│   │   ├── commit-msg
│   │   ├── common.sh
│   │   └── pre-commit
│   └── webpack
│       ├── environment.js
│       ├── webpack.dev.config.js
│       └── webpack.prod.config.js
├── package.json
├── README.md
├── src
│   ├── assets
│   │   ├── css
│   │   │   └── main.scss
│   │   └── images
│   │       ├── branding
│   │       │   └── logo
│   │       │       ├── logo.png
│   │       │       ├── logo.svg
│   │       │       └── logo_stroked.svg
│   │       ├── favicon.ico
│   │       ├── icons
│   │       │   └── inbox.svg
│   │       └── thumbs
│   │           ├── posts
│   │           │   ├── loly.jpg
│   │           │   └── yory.jpg
│   │           └── users
│   │               ├── avatar.jpg
│   │               ├── mikhail.jpg
│   │               └── yehor.jpg
│   ├── components
│   │   ├── btn
│   │   │   └── btn.style.scss
│   │   ├── components.scss
│   │   ├── counter-card
│   │   │   ├── --darknes
│   │   │   │   └── counter-card--darkness.scss
│   │   │   ├── --primary
│   │   │   │   └── counter-card--primary.scss
│   │   │   ├── --rounded
│   │   │   │   └── counter-card--rounded.scss
│   │   │   ├── --secondary
│   │   │   │   └── counter-card--secondary.scss
│   │   │   ├── --tertiary
│   │   │   │   └── counter-card--tertiary.scss
│   │   │   ├── __count
│   │   │   │   ├── --balance
│   │   │   │   │   └── counter-card__count--balance.scss
│   │   │   │   ├── --has-label
│   │   │   │   │   └── counter-card__count--label.scss
│   │   │   │   ├── --size
│   │   │   │   │   └── counter-card__count--size.scss
│   │   │   │   └── counter-card__count.scss
│   │   │   ├── __footer
│   │   │   │   └── counter-card__footer.scss
│   │   │   ├── __head
│   │   │   │   └── counter-card__head.scss
│   │   │   ├── __icon
│   │   │   │   └── counter-card__icon.scss
│   │   │   ├── __link
│   │   │   │   └── counter-card__link.scss
│   │   │   ├── __list-item
│   │   │   │   ├── --icon
│   │   │   │   │   └── counter-card__list-item--icon.scss
│   │   │   │   └── counter-card__list-item.scss
│   │   │   ├── __list
│   │   │   │   ├── --horizontal
│   │   │   │   │   └── counter-card__list--horizontal.scss
│   │   │   │   └── counter-card__list.scss
│   │   │   ├── __logo
│   │   │   │   ├── --has-overlay
│   │   │   │   │   └── counter-card__logo--has-overlay.scss
│   │   │   │   └── counter-card__logo.scss
│   │   │   └── counter-card.style.scss
│   │   ├── hamburger
│   │   │   ├── --active
│   │   │   │   └── hamburger--active.scss
│   │   │   ├── __line
│   │   │   │   ├── --bottom
│   │   │   │   │   └── hamburger__line--bottom.scss
│   │   │   │   ├── --top
│   │   │   │   │   └── hamburger__line--top.scss
│   │   │   │   └── hamburger__line.scss
│   │   │   ├── __svg
│   │   │   │   └── hamburger__svg.scss
│   │   │   ├── hamburger.component.js
│   │   │   └── hamburger.style.scss
│   │   ├── list
│   │   │   ├── __brand-box
│   │   │   │   └── list__brand-box.scss
│   │   │   ├── __cell
│   │   │   │   ├── --wide
│   │   │   │   │   └── list__cell--wide.scss
│   │   │   │   └── list__cell.scss
│   │   │   ├── __counter
│   │   │   │   └── list__counter.scss
│   │   │   ├── __date
│   │   │   │   └── list__date.scss
│   │   │   ├── __item
│   │   │   │   └── list__item.scss
│   │   │   ├── __logo
│   │   │   │   └── list__logo.scss
│   │   │   ├── __picture
│   │   │   │   ├── --round
│   │   │   │   │   ├── list__picture--round.scss
│   │   │   │   │   └── list__picture--round_sm.scss
│   │   │   │   └── list__picture.scss
│   │   │   ├── __userlink
│   │   │   │   └── list__userlink.scss
│   │   │   └── list.styles.scss
│   │   ├── logo
│   │   │   ├── __picture
│   │   │   │   └── logo__picture.scss
│   │   │   └── logo.style.scss
│   │   ├── menu
│   │   │   ├── __icon
│   │   │   │   └── menu__icon.scss
│   │   │   ├── __item
│   │   │   │   └── menu__item.scss
│   │   │   ├── __link
│   │   │   │   ├── --active
│   │   │   │   │   └── menu--active.scss
│   │   │   │   └── menu__link.scss
│   │   │   ├── __name
│   │   │   │   └── menu__name.scss
│   │   │   ├── __svg
│   │   │   │   └── menu__svg.scss
│   │   │   └── menu.style.scss
│   │   ├── messages
│   │   │   ├── __icon
│   │   │   │   └── messages__icon.scss
│   │   │   ├── __ticker
│   │   │   │   └── messages__ticker.scss
│   │   │   └── messages.style.scss
│   │   ├── more
│   │   │   ├── __icon
│   │   │   │   └── more__icon.scss
│   │   │   └── more.style.scss
│   │   ├── new-action
│   │   │   ├── __icon
│   │   │   │   └── _new-action__icon.scss
│   │   │   ├── __wrapper
│   │   │   │   └── _new-action__wrapper.scss
│   │   │   └── new-action.style.scss
│   │   ├── notifer
│   │   │   ├── --active
│   │   │   │   └── notifier--active.scss
│   │   │   ├── __icon
│   │   │   │   └── _notifier__icon.scss
│   │   │   ├── __ticker
│   │   │   │   └── notifier__ticker.scss
│   │   │   ├── notifier.component.js
│   │   │   └── notifier.style.scss
│   │   ├── page-heading
│   │   │   ├── __title
│   │   │   │   └── page-heading__title.scss
│   │   │   └── page-heading.style.scss
│   │   ├── pie-chart
│   │   │   ├── __circle
│   │   │   │   ├── --negative
│   │   │   │   │   └── pie-chart__circle--negative.scss
│   │   │   │   └── pie-chart__circle.scss
│   │   │   ├── __legend-item-identifier
│   │   │   │   ├── --pure
│   │   │   │   │   └── pie-chart__legend-item-identifier--pure.scss
│   │   │   │   └── pie-chart__legend-item-identifier.scss
│   │   │   ├── __legend-item-name
│   │   │   │   └── pie-chart__legend-item-name.scss
│   │   │   ├── __legend-item-value
│   │   │   │   └── pie-chart__legend-item-value.scss
│   │   │   ├── __legend-item
│   │   │   │   └── pie-chart__legend-item.scss
│   │   │   ├── __legend
│   │   │   │   └── pie-chart__legend.scss
│   │   │   └── pie-chart.style.scss
│   │   ├── profile
│   │   │   └── _profile.style.scss
│   │   ├── search
│   │   │   ├── __icon-svg
│   │   │   │   └── search__icon-svg.scss
│   │   │   ├── __icon
│   │   │   │   └── search__icon.scss
│   │   │   ├── __input
│   │   │   │   └── search__input.scss
│   │   │   └── search.style..scss
│   │   ├── select
│   │   │   ├── --show
│   │   │   │   └── select--show.scss
│   │   │   ├── __dropdown
│   │   │   │   └── _select__dropdown.scss
│   │   │   ├── __option
│   │   │   │   └── _select__option.scss
│   │   │   ├── __options
│   │   │   │   └── _select__options.scss
│   │   │   ├── __toggle
│   │   │   │   └── select__toggle.scss
│   │   │   ├── select.component.js
│   │   │   └── select.style.scss
│   │   ├── toggle
│   │   │   ├── toggle.component.js
│   │   │   └── toggle.style.scss
│   │   └── widget
│   │       ├── --border
│   │       │   └── _border.scss
│   │       ├── --gap
│   │       │   └── _gap.scss
│   │       ├── --size
│   │       │   └── _size.scss
│   │       ├── __content
│   │       │   ├── --extra-col
│   │       │   │   └── _extra-col.scss
│   │       │   └── _content.scss
│   │       ├── __more-link
│   │       │   └── widget__more-link.scss
│   │       ├── __separator
│   │       │   └── _separator.scss
│   │       ├── __title
│   │       │   └── _title.scss
│   │       ├── __toolbar
│   │       │   └── _toolbar.scss
│   │       └── widget.style.scss
│   ├── config
│   │   ├── colors.config.scss
│   │   ├── mixins
│   │   │   ├── _animations.scss
│   │   │   ├── _border-styles.scss
│   │   │   ├── _box-shadows.scss
│   │   │   ├── _breakpoints.scss
│   │   │   ├── _gradient.scss
│   │   │   └── mixins.scss
│   │   ├── typography.config.scss
│   │   └── variables.config.scss
│   ├── entry-points.js
│   ├── helpers
│   │   └── mobileMenuSwitchState.js
│   ├── index.html
│   ├── index.js
│   ├── layouts
│   │   ├── app
│   │   │   └── app.scss
│   │   ├── container
│   │   │   ├── --gap
│   │   │   │   ├── --lg
│   │   │   │   │   └── container--gap--lg.scss
│   │   │   │   └── container--gap.scss
│   │   │   └── container.scss
│   │   ├── grid
│   │   │   ├── --main
│   │   │   │   └── grid--main.scss
│   │   │   ├── --toolbar
│   │   │   │   └── grid--toolbar.scss
│   │   │   ├── --widgets_area
│   │   │   │   └── grid--widgets-area.scss
│   │   │   ├── __col
│   │   │   │   └── grid__col.scss
│   │   │   └── grid.scss
│   │   ├── layouts.scss
│   │   ├── sidebar
│   │   │   ├── __footer-nav
│   │   │   │   └── sidebar__footer-nav.scss
│   │   │   ├── __hamburger
│   │   │   │   └── sidebar__hamburger.scss
│   │   │   ├── __item
│   │   │   │   └── sidebar__item.scss
│   │   │   ├── __logo
│   │   │   │   └── sidebar__logo.scss
│   │   │   ├── __main-nav
│   │   │   │   ├── menu
│   │   │   │   │   ├── __link
│   │   │   │   │   │   ├── --active
│   │   │   │   │   │   │   └── menu__link--active.scss
│   │   │   │   │   │   └── menu__link.scss
│   │   │   │   │   └── menu.scss
│   │   │   │   └── sidebar__main-nav.scss
│   │   │   └── sidebar.scss
│   │   ├── user-bar
│   │   │   ├── --mobile-float
│   │   │   │   ├── --center
│   │   │   │   │   └── user-bar--mobile-float--center.scss
│   │   │   │   ├── --left
│   │   │   │   │   └── user-bar--mobile-float--left.scss
│   │   │   │   ├── --right
│   │   │   │   │   └── user-bar--mobile-float--right.scss
│   │   │   │   └── user-bar--mobile-float.scss
│   │   │   ├── --pc-float
│   │   │   │   ├── --center
│   │   │   │   │   └── user-bar--pc-float--center.scss
│   │   │   │   ├── --left
│   │   │   │   │   └── user-bar--pc-float--left.scss
│   │   │   │   ├── --right
│   │   │   │   │   └── user-bar--pc-float--right.scss
│   │   │   │   └── user-bar--pc-float.scss
│   │   │   ├── __item
│   │   │   │   └── user-bar__item.scss
│   │   │   └── user-bar.scss
│   │   └── wrapper
│   │       └── wrapper.scss
│   └── theme
│       ├── theme-dark
│       │   └── _theme-dark.scss
│       ├── theme-light
│       │   └── _theme-light.scss
│       └── theme.scss
├── webpack.config.js

```
<br /><br />

<img align="left" src="https://raw.githubusercontent.com/KoninMikhail/social-analytics-dashboard-template/master/.repo/iconpack/contributors.png" width="50px" />

## Contributors
I am <3 contributions big or small. If you help my project --> 🍰**link to your profile will be here**🍰.

<a href="https://github.com/koninmikhail/social-analytics-dashboard-template/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=koninmikhail/social-analytics-dashboard-template" />
</a>

<br /><br />

<img align="left" src="https://raw.githubusercontent.com/KoninMikhail/social-analytics-dashboard-template/master/.repo/iconpack/coffee.png" width="50px" />

## Buy Me A Coffee
<a href="https://github.com/KoninMikhail/social-analytics-dashboard-template/generate">
  <img alt="@koninmikhail/Social Analytics Dashboard Template Author brand logo without text" align="right" src="https://raw.githubusercontent.com/KoninMikhail/social-analytics-dashboard-template/master/.repo/images/logo.png" width="25%" />
</a>

Currently I'm seeking for new sponsors to help maintain this project! ❤️

With every donation you make - you're helping with development of this project. *You will be also featured in project's README.md*, so everyone will see your contribution and visit your content⭐.

<a href="https://yoomoney.ru/to/410011749810070">
  <img src="https://raw.githubusercontent.com/KoninMikhail/social-analytics-dashboard-template/master/.repo/images/sponsor.svg">
</a>

#### OR CLICK BUTTON

[![GitHub followers](https://img.shields.io/github/followers/koninmikhail.svg?style=social)](https://github.com/koninmikhail)
[![GitHub stars](https://img.shields.io/github/stars/koninmikhail/social-analytics-dashboard-template.svg?style=social)](https://github.com/koninmikhail/social-analytics-dashboard-template/stargazers)
[![GitHub watchers](https://img.shields.io/github/watchers/koninmikhail/social-analytics-dashboard-template.svg?style=social)](https://github.com/koninmikhail/social-analytics-dashboard-template/watchers)
[![GitHub forks](https://img.shields.io/github/forks/koninmikhail/social-analytics-dashboard-template.svg?style=social)](https://github.com/koninmikhail/social-analytics-dashboard-template/network/members)

<br /><br />

<img align="left" src="https://raw.githubusercontent.com/KoninMikhail/social-analytics-dashboard-template/master/.repo/iconpack/law.png" width="50px" />

## **License and Changelog**

>Copyright (c) 2022, Mikahil Konin & Yehor Haiduk.
>This project under **[MIT](LICENSE)** license. See the changes in the **[CHANGELOG.md](CHANGELOG.md)** file.
