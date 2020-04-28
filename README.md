# fcc-technical-documentation-page
Repo  for my technical documentation page for Free Code Camp

I based the hover effect of my links on this {tutorial}(https://css-tricks.com/having-fun-with-link-hover-effects/)

Here is the css code for those links :

```css
a {
  background: linear-gradient(to bottom, var(--Yellow) 0%, var(--Yellow) 100%);
  background-position: 0 110%;
  background-repeat: repeat-x;
  background-size: 4px 4px;
  transition: background-size 0.2s ease-in-out;
}

a:hover {
  background-size: 4px 50px;
}
```
