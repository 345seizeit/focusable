Focusable
=============
An awesome and small library for perform spotlight in your DOM elements, setting an animated overlay to the rest of the page.

### Showcase

![](https://raw.github.com/zzarcon/focus-element-overlay/master/showcase/list.gif)

![](https://raw.github.com/zzarcon/focus-element-overlay/master/showcase/header.gif)

![](https://raw.github.com/zzarcon/focus-element-overlay/master/showcase/elements.gif)

### API
###### Set spotlight
```javascript
Focusable.setFocus($('#my-element'), options);
```
###### Hide spotlight
```javascript
Focusable.hide();
```
###### Options
```javascript
{
  fadeDuration: 700,
  hideOnClick: true,
  hideOnESC: true
}
```
### Dependencies
- jQuery
### TODO

- [ ] Close on ESC
- [ ] Add comments to code
- [ ] Add docs to readme
- [ ] Add gif's showing the functionality
- [ ] Remove jQuery dependency
- [ ] Support multiple elements at same time