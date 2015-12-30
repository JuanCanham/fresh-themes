fresh-themes
============

Stylized templates for your résumé and/or CV, compatible with [FRESH][f] and
[JSON Resume][jrs] formats.

- [positive][t-positive]: A visually dense/compact theme.
- [modern][t-modern]: A middle of the road theme with a modern look 'n feel.
- [compact][t-compact]: A visually dense/compact theme.
- [awesome][t-awesome]: A technical resume theme based on [Awesome-CV][awe].
- [minimist][t-minimist]: An unstyled barebones theme.
- [hello-world][t-hello]: A simple-as-possible example theme.
- New themes weekly.

## Install

You don't need to install this repository to use the themes; just install
[FluentCV Desktop][1] or [Command Line][2]. Otherwise you can install the latest
official standalone version of the theme repository over NPM...

`[sudo] npm install fresh-themes --save`

...or fork and clone it as usual.

## Structure

FRESH themes are structured to allow for flexible generation of documents in
multiple formats. Each theme lives in a separate folder and consists of:

- A JSON description file.
- One or more template files in Handlebars or Underscore format.
- Any necessary support files (CSS, LaTeX partials, etc.).
- A dedicated README.

Within its containing folder, a theme can have an arbitrary structure provided
you either a) follow a standard naming convention or b) specify your theme files
in your theme's JSON file. If you can do `{{ r.name }}` in a template file you
can work with FRESH themes.

## Contribute

Contributions are welcome.

1. Fork, branch, and clone this repository.
2. Add or edit a theme or make other changes.
3. Submit a PR.

## License

MIT. See [LICENSE.md][1] for details.

[1]: http://fluentcv.com
[2]: https://github.com/fluentdesk/fluentcv
[3]: https://github.com/fluentdesk/fresh-themes/blob/master/LICENSE.md
[f]: https://github.com/fluentdesk/FRESCA
[jrs]: http://jsonresume.org
[awe]: https://github.com/posquit0/Awesome-CV
[t-awesome]: https://github.com/fluentdesk/fresh-themes/tree/master/themes/awesome
[t-minimist]: https://github.com/fluentdesk/fresh-themes/tree/master/themes/minimist
[t-modern]: https://github.com/fluentdesk/fresh-themes/tree/master/themes/modern
[t-hello]: https://github.com/fluentdesk/fresh-themes/tree/master/themes/hello-world
[t-compact]: https://github.com/fluentdesk/fresh-themes/tree/master/themes/compact
[t-positive]: https://github.com/fluentdesk/fresh-themes/tree/master/themes/positive
