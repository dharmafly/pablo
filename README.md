# Pablo

**For full documentation and interactive examples, see [pablojs.com][pablo-site].**


**[Pablo][pablo-site]** is a small, open-source JavaScript library for [SVG][svg], the web standard for vector graphics. It can be used for vector-based art, games, visualisations and interfaces.

Pablo focuses on simplicity and performance, targeting modern browsers for both desktop and mobile.

SVG has the potential to fulfil everything that Flash did for vector graphics on the web. However, SVG is severely behind Flash in terms of its developer tools. Pablo is a tiny offering to this cause.

Pablo is extendable via plugins and has no dependency on other JavaScript libraries.

* By [Premasagar Rose][prem] ([Dharmafly][df])
* Website: [pablojs.com][pablo-site]
* Repo: [github.com/premasagar/pablo][repo]
* Open source: [MIT license][mit]


## Download

For production, use [pablo.min.js][pablo.min.js].  
For development, use [pablo.js][pablo.js].


[A test suite][tests] and [changelog][changelog] are available.


=====


## How it works

Both SVG or HTML can be used in Pablo, although the main focus is on SVG.

Pablo acts as a thin wrapper around the contents of a web page, making it easier to work with dynamically-generated SVG and avoiding the verbose code required when using raw JavaScript.

Pablo provides methods like `circle()` and `line()` to create each kind of SVG element. It has methods for manipulating SVG and HTML, e.g. to change the appearance, size or position, and methods for filtering and sorting the elements.

It has a simple plugin system, allowing new functionality to be added.


## Which browsers are supported

Basic SVG is supported in all modern browsers, including Internet Explorer 9 and mobile web browsers ([browser support table][browsers]).

Except in a couple of instances, Pablo doesn't attempt to workaround the lack of support in older browsers, although does let you know if the browser [is supported][issupported].


## How it feels

Pablo's API is inspired by [jQuery][jquery], [Underscore][_], [Backbone][backbone] and [Raphaël][raphael], although knowledge of these libraries isn't required. Using Pablo is to use SVG, so a growing knowledge of SVG goes hand-in-hand with using the library. See the [Resources][resources] page for links and books on SVG.

[See Pablo's API Reference][api] for the details.


=====


## Contributing

Your feedback is welcome. For bug reports and requests, please use the GitHub ['Issues' page][issues] or contact [@premasagar][prem-twitter].

[Pull requests][pullrequests] are welcome.

To update the documentation on [pablojs.com][pablo-site], fork the [dharmafly/pablo-docs][pablo-docs] repo, edit the [Markdown][markdown-syntax] files in the [docs][docs-folder] folder on the master branch, and then send a [pull request][docs-pullrequests] with the changes.


[pablo-site]: http://pablojs.com
[prem]: http://premasagar.com
[prem-twitter]: https://twitter.com/premasagar
[df]: http://dharmafly.com
[mit]: http://opensource.org/licenses/mit-license.php
[repo]: https://github.com/premasagar/pablo
[pablo.js]: http://pablojs.com/downloads/pablo.js
[pablo.min.js]: http://pablojs.com/downloads/pablo.min.js
[tests]: http://pablojs.com/tests/
[changelog]: http://pablojs.com/details/#changelog
[jquery]: http://jquery.com
[_]: http://underscorejs.org
[backbone]: http://backbonejs.org
[raphael]: http://raphaeljs.com
[api]: http://pablojs.com/api/
[resources]: http://pablojs.com/api/
[issues]: https://github.com/premasagar/pablo/issues
[docs-folder]: https://github.com/premasagar/pablo-docs/tree/master/docs
[docs-pullrequests]: https://github.com/premasagar/pablo-docs/pulls
[markdown-syntax]: http://daringfireball.net/projects/markdown/syntax
