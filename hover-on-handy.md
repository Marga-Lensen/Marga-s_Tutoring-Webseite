## Tips Mansour  -  do25jul24

### Marga's Tutoring Webseite has been designed for desktop;
- discussion mobile-first vs desktop-first
- transition w :hover doesn't work well on Handy

#### Links, Info
- [codepen](https://codepen.io/rishabhp/pen/NNNjNj); touch-action options

- [piclumen](https://www.piclumen.com/): example of wonderful (AI) website, which works horribly badly on Handy

- [ mobile first](https://kulturbanause.de/blog/responsive-webdesign-und-mobile-first/)
#
#### touch- in JavaScript...(?); problem: "freezing"; "sticky hover"

#### Addition to the CSS:

[slack](https://wd-tz-24-d01.slack.com/archives/D06Q131MEKU/p1721895965343799)

```css
.element {
  -webkit-transition: all 0.3s ease;
  -moz-transition: all 0.3s ease;
  -o-transition: all 0.3s ease;
  transition: all 0.3s ease;
}
```