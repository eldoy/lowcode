# Low code

This is a low code concept for web app development that extends to full code if needed.

### Pages

Includes url so we can automatically generate sitemap. Can have a 'missing-function'-driven development experience, where we automatically create referenced elements.

```yml
title: 'Hello'
link: /hello
# or multiple
link:
  - /hello
  - /no/hello
layout: main
views:
  # If a view does not exist, we create it and the SCSS file for it too
  - top
  - middle
  - bottom
# Do this?
scripts:
  - handleClick
  - handleSayHello
```

### Views

Todo...

### Scripts

Todo...

### Assets

Todo...

### Sitemap

Todo...

### Build

Todo...

### Database

Todo...

### API

Todo...
