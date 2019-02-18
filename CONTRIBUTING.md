# Contributing

## Documented versions

Only major versions are documented (e.g. Contao 4 and later on Contao 5).

## General rules

* Only use ATX style headlines (e.g. # H1 or ### H3).
* See [learn.netlify.com/en/cont/markdown/](https://learn.netlify.com/en/cont/markdown/) and [learn.netlify.com/en/shortcodes/notice/](https://learn.netlify.com/en/shortcodes/) for available markdown and shortcode syntax.
* Always add two empty lines above each headline.
* Always add links at the bottom of the document.
* Add line breaks after 80 characters in paragraphs.

Example for link references:
```
Lorem ipsum dolor [sit amet][1] consectetuer adipiscing elitr. Aenean massa. 
Cum sociis [natoque][2] penatibus et magnis dis.

[1]: https://contao.org/
[2]: https://www.google.com/
```

## New features

Since we will not maintain different versions of the documentation for each minor Contao version, some features will be documented which are only available in newer Contao version. In such a case, document the _old_ way first (if applicable), then show the new way with a notice of the minimum Contao version required.

You can use the following short code to automatically add a note for features of a specific Contao version:

```
{{< version "4.7" >}}
```

### Example:

```markdown
# DCA callbacks

## PHP array configuration 

…

## Service tag

{{< version "4.7" >}}
```