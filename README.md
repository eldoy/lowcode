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

### Routes

Should be taken from page, or have them somewhere separate?

Default routes can be generated from page dir location (using _ technique)

```yml
hello_route:
  page: hello
  links:
    - lang: en
      route: /hello
    - lang: 'no'
      route: /no/hello
```

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
