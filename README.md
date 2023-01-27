# Hexo Demo Naive

This is a dummy Hexo site for theme unit test. You should test your theme before release.

This test doesn't contain the default theme. You have to install the theme you want to test before starting.

## Checklist

### Head Tag

- Use the proper [DOCTYPE](https://en.wikipedia.org/wiki/Document_Type_Declaration).
  If you don't know which doctype you should use, `<!DOCTYPE html>` is recommended.
- UTF8 charset

  ```html
  <meta charset="utf-8" />
  ```

- Proper titles for different pages
- Favicon support

  ```html
  <link rel="icon" href="path/of/favicon" />
  ```

### Index

- Only display excerpts. (Better with a "Read More" link)
- [Pagination](https://hexo.io/docs/configuration.html#Pagination)

### Post

- Display post categories and tags.
- Disqus comment support.
- Display the post date.
- Support `photo` and `link` layout.
- Posts without title should be accessible.
