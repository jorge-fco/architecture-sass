# Architecture SCSS

📐 Architecture and Logic SCSS for projects.

📌 [View Documentation](https://nopal-horse-studio.github.io/architecture-sass/)

## 📚 SCSS

### 📁 Base
_fonts.scss <br/>
_icons.scss<br/>
_typhography.scss <br/>
_variables.scss <br/>
base.scss


### 📁 Components
_buttons.scss <br/>
_forms.scss <br/>
_modals.scss <br/>
_sliders.scss <br/>
_video.scss <br/>
components.scss


### 📁 Helpers
🗂 mixins<br/>
* _align.scss
* _calculate.scss
* _fonts.scss
* _row.scss
* _transition.scss

_mixins.scss <br/>
_modifiers.scss <br/>
_responsive.scss <br/>
helpers.scss

### 📁Layout
_aside.scss <br/>
_footer.scss <br/>
_header.scss <br/>
_loader.scss <br/>
layout.scss

### 📁 Pages
```css
_about.scss
_contact.scss
_error.scss
_home.scss
.
.
.
pages.scss
```

### 📁 Vendor
```css
_framework.scss <br/>
_carousel.scss <br/>
_animated.scss <br/>
. <br/>
. <br/>
. <br/>
vendors.scss
```
### 🔵 Core
```
main.scss
```

Archivo core en donde se realizan los @imports.
```scss

/*
	MAIN
	Core — v.03
	Year — 2018©
	✄ Not view code or copy ✄
	❤ CSS Core Design ❤
	www.jorge-frac.com
*/

@import "vendors/vendors";
@import "helpers/helpers";
@import "base/base";
@import "layout/layout";
@import "components/components";
@import "pages/pages";

```





