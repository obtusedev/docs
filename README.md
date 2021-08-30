# Documentation

## Purpose

This repo is a collection of what I think is the best and worst looking documentation.

Good documentation can save you lots of time and frustration and can help generate interest in your tool. When I say good documentation I'm not just referring to how it looks but how easy it is to find what I'm looking for. There are good documentation that are simple in style, like [Request](https://docs.python-requests.org/en/master/index.html), and there are more stylish documentation like [FastAPI](https://fastapi.tiangolo.com/). 

Easy to find information > Good style/theme
Function > Form

> Information here refers to but is not limited to tool setup (installation, updating, deleting), API ref (how to use a class, function/method, parameters), code examples, tutorial/quickstart (how to use your tool)

Something I've also noticed is that the simpler the library, the better the docs are usually but not always. Examples include 

### Good documentation:

  * Clear sections
  * Deprecation warning
    * Notify users on new version of documentation
  * Easy to navigate
  * Good for new and current users
  * Lots of examples
    * Best practices
    * Code examples for common usecases/problems
    * Code style recommendation
  * More resources for learning the tool beyond the official docs
  * Uniformity i.e standard code style(e.g JS code examples with and without ;)
    * There are tools that are more opinionated than others, think Django vs Flask, and there maybe many ways to do something. In that case it should show the multiple options with pros/cons and let the user decide.
  * Up to date


  Nice to have but not required:

  * Community forums e.g. Discord, Slack, Reddit
  * Community surveys & feedback
    * Engaged developers and maintainers
  * Course created by the developers
    * Preferably free but not required
  * DARK THEME
    * Really appreciated when coding late at night
  * Download offline with multiple formats (epub, pdf, html)
  * Easy to request an edit (for typos and suggestions) e.g. PR on Github for MDN docs
  * Good styling
    * Button to copy code snippet
    * Good use of whitespace i.e information not too jam packed [cppr](https://en.cppreference.com/w/)
    * Good size font where you don't have to squint [cppr](https://en.cppreference.com/w/)
    * Readable font meaning
      * avoid igatures
      * avoid italics especially on key words
      * distinction between characters that can be confused for one another.
        * upper, lowercase L, I [L, l, I, i, 1, |] and uppercase o and 0 i.e. O, 0
    * Syntax highlighting
  * Good SEO
    * Official documentation should be in the top search result over third party websites
    * Nothing worse than seeing W3, Geek4Geeks or other low quality websites ranking over MDN
  * Running code snippet on the site i.e. playground feature
  * Sample project to download and run for the first time
  * Search feature built in that actually works

Bad documentation on the other hand waste time for users when they go to Stackoverflow/Google rather than the official documentation. It can also prevent users from adopting your tool. I have decided against using a tool on the quality of the documentation.

### Bad Documentation:

  * Ambiguous and/or convoluted install instructions
  * Bad SEO
    * Where low quality third party resources rank above the official documentation
    * Sometimes you can't even find the official docs on search results first page
  * Difficult to find information *cough* ruby
  * No built in search feature
    * Disregard this if you have good navigation like sidebar with contents and clear sections
    * Having to resort to site:example.com
  * No/Few/Bad/Outdated code examples
  * No getting started guide
  * Lacking uniformity
    * Documentation with contradicting information as if it were written by different people with varying opinions and preferences that hated each other and didn't communicate at all
    * Code snippets with consistent styling

## Best

### Languages

### Rust: [Docs](https://www.rust-lang.org/)  

Really nice documentation especially when compared to something like C++.  
You can use [mdbook](https://github.com/rust-lang/book) to make your own documentation look as good as the [Rust docs](https://www.rust-lang.org/learn)

  * Appealing theme
  * Lots of examples
  * Easy to navigate and use 
  * Clear sections for std lib, book, course
  * [md-book](https://github.com/rust-lang/book)
  * Free book to learn rust
  * Free rust course
  * Good for first timers and professionals alike


### JavaScript: [MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript)  

One of the best documentation. Gold standard for web technologies.

  * Clean and concise
  * Easy to navigate and use
  * Clear sections for tutorial, language ref, APIs
  * Lots of examples
  * Plenty of documentation on tutorials, references, Web APIs, and tools
  * Good for first timers and professionals alike

### TypeScript: [Docs](https://www.typescriptlang.org/docs/)

Typescript documentation are some of the best I've seen. Props to the TS team.  
Unfortunately it seems the website is a static Gatsby [site](https://github.com/microsoft/TypeScript-Website) so no generating your docs in typescript style. You can use [typedoc](https://typedoc.org/) as an alternative. 

  * Clear sections
  * Very easy to navigate
  * Plenty of tutorials
    * Tutorials on coming from another language
  * Playground to run code
  * Excellent search feature
  * Dark theme!
    * You can chose light, dark, system theme
    * You can even change the font
### Frameworks, Libraries, Platforms
[React](https://reactjs.org/)
[Node.js](https://nodejs.org/en/docs/)
[Request](https://docs.python-requests.org/en/master/index.html)
[Vue](https://vuejs.org/)
### REST APIs



## Decent
### Languages
Python
### REST APIs
### Frameworks, Libraries, Platforms


## Worst
### Languages
### REST APIs
### Frameworks, Libraries, Platforms

[Ruby](https://www.ruby-lang.org/en/documentation/)


## Tools:

[Devdocs](https://devdocs.io/)

### Documentation Generators

[VuePress](https://github.com/vuepress)
  * Vue.js

[mdBook](https://github.com/rust-lang/mdBook)
  * Rust

[mkdocs]()

[mkdocs-material](https://github.com/squidfunk/mkdocs-material)
  * Crystal
  * FastAPI

[Sphinx](https://www.sphinx-doc.org/en/master/)

[Sphinx-Themes](https://sphinx-themes.org/)

[Sphinx-Alabaster](https://sphinx-themes.org/sample-sites/default-alabaster/)
  * Requests is using a modified version of Flask's theme called [krTheme](https://github.com/kennethreitz-archive/kr-sphinx-themes/blob/master/flask_theme_support.py) [[info]](https://github.com/psf/requests/tree/main/docs/_themes)
  * Flask is using a customize [version](https://github.com/pallets/pallets-sphinx-themes) of Sphinx Alabaster theme [[info]](https://www.sphinx-doc.org/en/master/examples.html)
