# jQuery ARIA

[![Code Climate](https://codeclimate.com/github/orgsync/jquery-aria.png)](https://codeclimate.com/github/orgsync/jquery-aria)

A jQuery plugin that adds support for [ARIA](http://www.w3.org/WAI/intro/aria) attributes.

jQuery methods:
  * `.aria`
  * `.removeAria`
  * `.hasAria`

jQuery object methods:
  * `.aria`
  * `.removeAria`
  * `.addRole`
  * `.removeRole`
  * `.toggleRole`
  * `.hasRole`
  * `.related`
  * `.addRelated`
  * `.removeRelated`
  
Planned methods (by nothrem)
  * `.atomic` (find closest parent with `aria-atomic=true` attribute, returning itself if none found or found one with `aria-atomic=false`)
  * `.hide`/`.show` (correctly change `aria-hidden` for hidden elements)
  * `.val` (read or set value from/to `aria-valuenow` on elements with `slider`, `spinbutton` and `progressbar` role)
  * `.button` (correctly change `aria-pressed` for JQUI buttons; if JQUI is installed)


This project uses [Semantic Versioning](http://semver.org/).

## Documentation

The [source code](https://github.com/orgsync/jquery-aria/blob/master/src/jquery.aria.js) is fully documented.

## License

This is licensed under the MIT license. The license itself can be found in the source.
