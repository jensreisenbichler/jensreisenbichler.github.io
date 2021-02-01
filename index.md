---
title: Overview 
layout: doc
info: Welcome to the Jekyll Style Guide.
nav: false
---

<h1>👋 Hi! </h1>

My name's [Matthew](https://matthewelsom.com), and I built this [Jekyll-based](http://jekyllrb.com/) tool that you can use to generate and document product or system user interface (UI) patterns in a simple [Style Guide](https://jekyllstyleguide.com).


## Why?

There are a lot of really great style guide methods, tools and [examples](http://styleguides.io) out there... but, I struggled to find one that was:

- easy and quick to use,
- simple to maintain,
- a match for my current workflow,
- flexible enough to use on a wide variety of projects.

## Requirements

I decided that the following requirements would meet my needs: 

- Use only [Jekyll](https://jekyll.rb) as a pre-requisit
- Use HMTL/CSS/JS to build a web component, template, etc. (I called these 'patterns')
- Track the 'maturity' of a pattern - i.e. is it ready to use, or not?
- Automatically add all patterns into a 'Roadmap'
- Enable simple documentation for developers, designers and product owners to use
- Provide a style guide container or 'shell' that is unobtrusive and easy to visually customize


## Help

To get started using this tool check out these useful pages: 

- Read the [design principles]({{ site.baseurl }}/docs/about/02-design-principle.html)
- Setup and [installation]({{ site.baseurl }}/docs/about/01-getting-started.html) info
- Learn how to [add patterns]({{ site.baseurl }}/docs/about/01-getting-started.html#adding-patterns), and [documentation]({{ site.baseurl }}/docs/about/01-getting-started.html#adding-documentation)
- Understand the pattern [maturity]({{ site.baseurl }}/docs/about/03-maturity.html) scale
- View all patterns in the [Roadmap]({{ site.baseurl }}/docs/about/04-roadmap.html)


___


**This tool was originally published in the public domain as 'Living Styleguide' on 12 September 2016 by [{{ site.sg_author }}](https://matthewelsom.com)**

It's name was changed to 'Jekyll Style Guide' in 2018, and it's license was updated.

It was last updated on {{ site.time | date: "%b %-d, %Y"  }} by {{ site.sg_author }}. 

Copyright © 2016 - 2018 & Beyond. All Rights Reserved. 

><i class="icon red" data-icon="warning"></i>This tool has been tested for Google Chrome (Mac) v67+ and iOS Safari. Use with Caution.


# License 

This tool is free for everyone to use, and modify, but don't try and sell it.
Available under [Apache license version 2.0](https://www.apache.org/licenses/LICENSE-2.0.html).


It was built using [Jekyll](https://jekyll.rb), it's [design principle]({{ site.baseurl }}/docs/about/02-design-principle.html) is based on the [US Design Standards](https://designsystem.digital.gov/design-principles/), and the css architecture is based on the [Simple SCSS Playbook](https://matthewelsom.com/blog/simple-scss-playbook.html).

[View License File](https://github.com/matthewelsom/jekyll-style-guide/blob/master/LICENSE)

--- 

A few parts of this project are not in the public domain:

- [Material Icons](https://material.io/tools/icons/) font files included in the `styleguide/fonts` directory were extracted from [Github](https://github.com/google/material-design-icons).
- [HK Grotesk](https://hanken.co/product/hk-grotesk/) font files included in the `styleguide/fonts` directory were extracted from [Hanken](https://hanken.co/product/hk-grotesk/), copyright Alfredo Marco Pradil and Stefan Peev.
- jQuery `[jquery-2.1.4.min.js]` was extracted from [jQuery](https://jquery.com/), copyright The jQuery Foundation.
- Roboto font files in `fonts/roboto` were extracted from [Google Fonts](https://fonts.google.com/), copyright Christian Robertson.
- Normalize `[_normalize.scss]` was extrcted from [Normalize.css](https://github.com/necolas/normalize.css), copyright Nicolas Gallagher and Jonathan Neal.

**Please check with the respective rights holders for license details.**