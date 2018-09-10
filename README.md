# Uno Zen for Ghost

![Last version](https://img.shields.io/github/tag/Kikobeats/uno-zen.svg?style=flat-square)
[![Build Status](http://img.shields.io/travis/Kikobeats/uno-zen/master.svg?style=flat-square)](https://travis-ci.org/Kikobeats/uno-zen)
![Ghost version](https://img.shields.io/badge/Ghost-1.x-brightgreen.svg?style=flat-square)
![Node version](https://img.shields.io/node/v/uno-zen.svg?style=flat-square)

> Minimalist and Elegant theme for Ghost.

- [Uno Zen for Ghost](#uno-zen-for-ghost)
  * [Introduction](#introduction)
    + [Whats is new in 2.x](#whats-is-new-in-2x)
  * [Installation](#installation)
  * [Update](#update)
    + [Update your current version](#update-your-current-version)
    + [Receive a mail notification when a new version is available](#receive-a-mail-notification-when-a-new-version-is-available)
  * [Development and Customization](#development-and-customization)
  * [Showcase](#showcase)
  * [Related](#related)
  * [License](#license)

---

## Introduction

**Uno Zen** is a theme for Ghost inspired in [Uno](https://github.com/daleanthony/Uno) but providing a set of missing features in the original theme that are aligned with minimalist design style.

### Whats is new in 2.x

- Totally rewritten using HTML5 and CSS3.
- Improved development workflow with gulp + browersync.
- Improved responsive and mobile experience.
- Improved SEO Content with meta tags.

Things that already existed:

- A good [404 page error](http://kikobeats.com/404).
- Search support.
- Multiaccount support.
- Loading progress state for each page.
- Estimation about the time of reading.

You can see a [demo](http://kikobeats.com) in the owner's blog. Also you can check hi [styleguide](http://kikobeats.com/styleguide) to view how it looks.

## Installation

Please ensure that `git` and `curl` is installed on your machine.

Enter the theme folder (`content/themes`) of your Ghost installation and paste the following command:

```bash
$ curl -sSL http://git.io/vcIHr | sh
```

### Alternative installation (to enable deployment to remote server):

Run the above command inside a temporary folder.

Delete the `.git` folder inside the `uno-zen` folder.

Copy and paste the `uno-zen` folder into the theme folder (`content/themes`).

This will add a static copy of the theme to your blog's git repository and allow changes to be tracked by git.

## Setup

This theme needs a DOM selector library. The library is not provided by the theme. Instead, you need to paste one into the `Blog Footer` in the `Code injection` of your Ghost installation:

```html
<script type="text/javascript" src="https://code.jquery.com/jquery-1.11.3.min.js"></script>
```

You can use jQuery, but we recommend use [Zepto](https://github.com/madrobby/zepto), a lightweight jQuery alternative compatible with jQuery Plugins:

```html
<script type="text/javascript" src="https://cdnjs.cloudflare.com/ajax/libs/zepto/1.1.6/zepto.min.js"></script>
<script>jQuery = Zepto</script>
```

It should look like this:

![](http://i.imgur.com/xUXdFeH.png)

## Update

One objective of this project is to adopt an effective policy to have the latest version of the theme all the time. We have divided this process into two steps:

### Update your current version

Make sure you're in the uno-zen directory. Then run:

```bash
$ sh scripts/update.sh
```

That's all!

## Development and Customization

See in [Documentation](https://github.com/Kikobeats/uno-zen/blob/master/DOCUMENTATION.md).

## Related

* [Uno Urban](https://kikobeats.github.io/uno-urban) – Commercial version of Uno Zen.
* [Bloggy](https://github.com/Kikobeats/bloggy#bloggy-for-ghost) – Brand theme for Ghost.

## License

MIT © [Kiko Beats](kikobeats.com)
