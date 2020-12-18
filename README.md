# Hugo Long Read

A simple open-source Hugo theme for lengthly single page websites.

Hugo Long Read is based on the design for the [Command Line Interface Guidelines](https://clig.dev/). Both websites are designed by [Mark Hurrell](https://mhurrell.co.uk/), with additional HTML templating and javascript from [Aanand Prasad](https://twitter.com/aanandprasad) and [Ben Firshman](https://twitter.com/bfirsh). The Command Line Interface Guidelines are a collaborative project written by [Aanand Prasad](https://twitter.com/aanandprasad), [Ben Firshman](https://twitter.com/bfirsh), [Carl Tashian](https://twitter.com/tashian) and [Eva Parish](https://twitter.com/evpari).

The main portion of this document uses an extract from [The Platinum Metals (1920)](https://www.gutenberg.org/files/64068/64068-h/64068-h.htm) by by A. D. Lumb, published by Project Gutenberg.

## Fonts

Hugo Long Read uses three typefaces; [IBM Plex Serif](https://github.com/IBM/plex/tree/master/IBM-Plex-Serif) for body text, [IBM Plex Mono](https://github.com/IBM/plex/tree/master/IBM-Plex-Mono) for code examples and [TeX Gyre Heros](https://ctan.org/pkg/tex-gyre-heros) for headings. All font files are provided by their creators under the [Open Font License](https://www.ctan.org/license/ofl) (OFL).

- IBM Plex is IBM’s corporate font family, and has been utilised as the building blocks for numerous other typefaces including Information Architects' [IA Writer font family](https://ia.net/writer/blog/a-typographic-christmas)
- TeX Gyre Heros is based on URW Nimbus Sans L, and was created by CTAN as an open-source be used as a substitute for Adobe Helvetica in documents

## Contributing

The content of the guide lives in a single Markdown file, [content/_index.md](content/_index.md).
The website is built using [Hugo](https://gohugo.io/).

To run Hugo locally to see your changes, run:

```
$ brew install hugo
$ cd <path>/<to>/cli-guidelines/
$ hugo server
```

To view the site on an external mobile device, run:

```
hugo server --bind 0.0.0.0 --baseURL http://$(hostname -f):1313
```

<!-- TODO: add contact info (how to reach the CLIG creators with questions) -->

## License

This work is licensed under a
[Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).
