# Naringu


Naringu is dark jekyll theme that provide fully furnished jekyll setup, come with contact form, #6DD HTML color schema, and more features. It's based on [Poole](http://getpoole.com), the Jekyll butler.

![Naringu](images/screenshot-1.png)
![Naringu](images/screenshot-2.png)
![Naringu](images/screenshot-3.png)
![Naringu](images/screenshot-4.png)

## Contents

- [Usage](#usage)
 - [Sidebar menu](#sidebar-menu)
  - [Themes](#themes)
  - [Reverse layout](#reverse-layout)
  - [Contact Form](#contact-form)
  - [Comments](#comments)
- [Development](#development)
  - [Author](#author)
  - [Contributors](#contributors)
- [License](#license)


## Usage

Just download and start the Jekyll server or fork this repo.

### Sidebar menu

Create a list of nav links in the sidebar by assigning each Jekyll page the correct layout in the page's [front-matter](http://jekyllrb.com/docs/frontmatter/).

```
---
layout: page
title: About
---
```

**Why require a specific layout?** Jekyll will return *all* pages, including the `atom.xml`, and with an alphabetical sort order. To ensure the first link is *Home*, we exclude the `index.html` page from this list by specifying the `page` 


### Reverse layout

Reverse the page orientation with a single class.

```html
<body class="layout-reverse">
  ...
</body>
```
### Contact Form

Using formspree to enable contact form in static site.

Go a head `contact/index.html` just change the email in the code

```html
<form action="http://formspree.io/youremail@yourdomain.com" role="form" method="POST">
```

### Comments

Using [disqus](http://disqus.com/) to enable comments in static site.

Just edit variable `disqus` in `_config.yml` to your disqus link.

## Development

Naringu come with two branches :.

- `master` for active development. 
- `gh-pages` for preview of Naringu

### Author

**Rizky Ariestiyansyah**
- <https://github.com/ariestiyansyah>
- <https://twitter.com/ariestiyansyah>

### Contributors

**Gildásio Júnior** - *a.k.a. @gjuniioor*
- https://github.com/gjuniioor

## License

Open sourced under the [MIT license](LICENSE.md).
