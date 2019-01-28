# Architecture SCSS

📐 Architecture and Logic SCSS for projects.

📌 [View Documentation](https://jorgefrac.github.io/architecture-sass/)

## 📚 SCSS

### 📁 Base
```css
	_fonts.scss
	_icons.scs
	_typhography.scss
	_variables.scss
	.
	.
	.
	[]base.scss
```

### 📁 Components
```css
	_buttons.scss
	_forms.scss
	_modals.scss
	_sliders.scss
	_video.scss
	.
	.
	.
	[]components.scss
```

### 📁 Helpers
```css
	🗂 mixin
	└── _align.scss
	└── _calculate.scss
	└── _fonts.scss
	└── _row.scss
	└── _transition.scss
	_mixins.scss
	_modifiers.scss
	_responsive.scss
	.
	.
	.
	[]helpers.scss
```

### 📁Layout
```css
	_aside.scss
	_footer.scss
	_header.scss
	_loader.scss
	.
	.
	.
	[]layout.scss
```

### 📁 Pages
```css
	_about.scss
	_contact.scss
	_error.scss
	_home.scss
	.
	.
	.
	[]pages.scss
```

### 📁 Vendor
```css
	_framework.scss
	_carousel.scss
	_animated.scss
	.
	.
	.
	[]vendors.scss
```

### 🔵 Core
```css
main.scss
```

Archivo core en donde se realizan los @imports.
```css

/*
	MAIN
	Core — v.05
	Year — 2019©
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