# Modern - Slide Show (S9) Template Pack

## What's Slide Show (S9)?
A Ruby gem that lets you create slide shows and author slides in plain text
using a wiki-style markup language that's easy-to-write and easy-to-read. More
Slide Show (S9) Project Site

## Intro
A clean, modern Slide Show (S9) template pack that lets you use wiki-style
markup languages like Markdown and Textile to generate an HTML slideshow.

To see a demo of the site, click
[here](http://jusjmkim.github.io/slideshow-modern/). The markdown and html
behind this site can be found in the [gh-pages
branch](https://github.com/jusjmkim/slideshow-modern/tree/gh-pages).

## Try It Yourself - How To Use The Modern Template Pack
If you want to try it yourself, install (fetch) the new template pack. Issue the
command:<br \>
`$ slideshow install modern`

Or as an alternative clone the template pack using git. Issue the commands:<br \>
`$ cd ~/.slideshow/templates`<br \>
`$ git clone git://github.com/slideshow-s9/slideshow-modern.git`

To check if the new template got installed, use the list command:
`$ slideshow list`

Listing something like:<br \>
`Installed templates include:`<br \>
`modern.txt (~/.slideshow/templates/modern/modern.txt)`

Now you're ready to use it using the -t/--template switch. Example:<br \>
`$ slideshow build tutorial -t modern`

That's it.

## Further Customizations
Even though h1's start new slides by default in slideshow, it is suggested to
use the --slide flag when building the slideshow, so only `!SLIDE` can generate
new slides. So, to build the slideshow, run <br \>
`$ slideshow build tutorial --slide -t modern`

This allows you to pass in HTML classes into each slide. This template pack
supports the `cover` and `large` classes. To see an example of this, go to the
[gh-pages branch](https://github.com/jusjmkim/slideshow-modern/tree/gh-pages) to
see the markdown for the demo site mentioned in the Intro section.

## Questions? Concerns?
Questions? Comments? Send them along to the [Free Web Slide Show Alternatives
(S5, S6, S9, Slidy And Friends) Forum/Mailing
List](https://groups.google.com/forum/#!forum/wwwmake). Thanks!

