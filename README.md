# Shopify Dawn Skeleton Theme
A stripped down version of [Dawn](https://themes.shopify.com/themes/dawn/styles/default), Shopify's first source-available reference theme, with Online Store 2.0 features and performance built-in.

## Dawn
Dawn represents an HTML-first, JavaScript-only-as-needed approach to theme development. It's Shopify's first source-available theme with performance, flexibility, and [Online Store 2.0 features](https://www.shopify.com/partners/blog/shopify-online-store) built-in and acts as a reference for building Shopify themes.

* **Web-native in its purest form:** Themes run on the [evergreen web](https://www.w3.org/2001/tag/doc/evergreen-web/). We leverage the latest web browsers to their fullest, while maintaining support for the older ones through progressive enhancement—not polyfills.
* **Lean, fast, and reliable:** Functionality and design defaults to “no” until it meets this requirement. Code ships on quality. Themes must be built with purpose. They shouldn’t support each and every feature in Shopify.
* **Server-rendered:** HTML must be rendered by Shopify servers using Liquid. Business logic and platform primitives such as translations and money formatting don’t belong on the client. Async and on-demand rendering of parts of the page is OK, but we do it sparingly as a progressive enhancement.
* **Functional, not pixel-perfect:** The Web doesn’t require each page to be rendered pixel-perfect by each browser engine. Using semantic markup, progressive enhancement, and clever design, we ensure that themes remain functional regardless of the browser.

You can find more details through the [Dawn respository](https://github.com/Shopify/dawn/tree/main).

## To Do
- [x] Remove fluff from starter template json files
- [x] Delete any nonessential sections
- [x] Condense remaining sections
- [x] Make all schema readable (for now)
- [x] Add additional social media channels
- [ ] Condense asset svgs with snippets
- [ ] Delete any nonessential asset files
- [ ] Condense remaining asset files
- [ ] Strip all nonessential styling