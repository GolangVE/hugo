# Hugo Docs

Documentation site for [Hugo](https://github.com/gohugoio/hugo), the very fast and flexible static site generator built with love in GoLang.

## Contributing

We welcome contributions to Hugo of any kind including documentation, suggestions, bug reports, pull requests etc. Also check out our [contribution guide](https://gohugo.io/contribute/documentation/). We would love to hear from you. 

Note that this repository contains solely the documentation for Hugo. For contributions that aren't documentation-related please refer to the [hugo](https://github.com/gohugoio/hugo) repository. 

*Pull requests shall **only** contain changes to the actual documentation. However, changes on the code base of Hugo **and** the documentation shall be a single, atomic pull request in the [hugo](https://github.com/gohugoio/hugo) repository.*


## Build

To view the documentation site locally, you need to clone this repository with submodules:

```bash
git clone --recursive https://github.com/gohugoio/hugoDocs.git
```

Or if you already have a clone locally:

```bash
git submodule update --init
```
Also note that the documentation version for a given version of Hugo can also be found in the `/docs` sub-folder of the [Hugo source repository](https://github.com/gohugoio/hugo).

Then to view the docs in your browser, run Hugo and open up the link:

```bash
▶ hugo server

Started building sites ...
.
.
Serving pages from memory
Web Server is available at http://localhost:1313/ (bind address 127.0.0.1)
Press Ctrl+C to stop
```
