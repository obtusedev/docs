# Documentation

## Purpose

This repo is a collection of what I think is the best and worst looking documentation. Decided to do this when I was looking at Crystal and the Ruby. The stark difference in the quality of documentation was eye opening. Crystal having really nice documentation made me want to start learning it over Ruby. With Crytal it was easy to find information while with Ruby it was like digging for gold. 


Good documentation can save you lots of time and frustration and can help generate interest in your tool. When I say good documentation I'm not just referring to how it looks but how easy it is to find what I'm looking for. There are good documentation that are simple in style, like [Request](https://docs.python-requests.org/en/master/index.html), and there are more stylish documentation like [FastAPI](https://fastapi.tiangolo.com/). 

Easy navigation > Good style/theme  
Function > Form

> Information here refers to but is not limited to tool setup (installation, updating, deleting), API ref (how to use a class, function/method, parameters), code examples, tutorial/quickstart (how to use your tool)

One important thing I recently learned is that sometimes even if a tool has good documentation, it can still be really hard to learn it.  

Something else I noticed is that the simpler the library, the better the docs are usually but not always.  
That might just be a result of less things to learn.  

Examples include:

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
    * Not only more resources but different types for people that learn different
      * Course
      * Interactive playground / Downloadable first project
      * Videos
        * Please make sure that some effort is put into production(audio, video, content, presenter) especially audio
        * Link to the code
      * Written
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
  * Easy to contribute to
  * Easy toggle between different versions
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
  * Supports multiple languages

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

### Kotlin: [Docs](https://kotlinlang.org/docs/home.html)

Kotlin documentations is another one of my favorites. The website has a main navigation on the left sidebar and on the right side more granular controls. For example on the left is Basic syntax and on right is Functions, Variables, Comments. Only thing missing is Dark mode.

  * Very good use of whitespace
  * Lots of examples
  * Easy navigation to
    * Tutorial
    * Standard Library
    * API Reference
    * Tools
  * Playground feature is amazing on par with TypeScript

### Go: [Docs](https://golang.org/doc/)

Seems odd that there is a dark theme for packages & Standard Library but not for language docs. Go code examples could really use syntax highlighting. 

  * Easy to Standard Library
  * Decent playground feature
    * No autocomplete
    * No syntax highlighting
  * Good tutorial
  * Lots of external resources for Go
### PHP: [Docs](https://www.php.net/docs.php)

PHP docs are pretty good. Some criticism would be to remove the comments section from the docs. There is little visual distinction to let you know you're in the comments if you're scrolling fast. Also some of the comments are from 20 years ago. Another improvement would be to have the right nav sticky so that when you scroll down you don't have empty space on the right and you can easily go to another section. The downloaded docs were bad since they would freeze my pc.

  * Multiple languages
  * Decent to navigate

### Node.js: [Docs](https://nodejs.org/en/docs/)

  * Dark mode by default
  * Easy navigation
  * Easy to choose different versions
  * Could use more examples

### Frameworks, Libraries, Platforms

### Angular: [Docs](https://angular.io/docs)

Angular has some of the nicest docs, reminds me of the typescript docs. An issue I have with the website is that when you switch pages there is a noticable lag as the page loads. The animation as it loads is annoying too. 

  * Dark mode!
  * Good learning resources
  * Easy navigation


[React](https://reactjs.org/)
[Node.js](https://nodejs.org/en/docs/)
[Request](https://docs.python-requests.org/en/master/index.html)
[Vue](https://vuejs.org/)

### Github: [Docs](https://docs.github.com/en)

Informative guides and tutorials for everything from setting up ssh keys to using git and everything inbetween.  
The only thing I dislike is that there's no link from Github home page directly to the docs.  
I mean if you have a link for everything else from pricing to Github features why not have a link directly to the docs?  
You should like Github docs in the Explore dropdown under the Learn and Contribute section.

  * Beginner friendly
  * Clear sections
    * Github takes this to a whole nother level
  * Detailed and informative

### GraphQL: [Docs](https://graphql.org/learn/)

Simple documentation with lots of code examples. Make good use of whitespace.  
Only issue is no dark mode as this website is hard to look at in the dark.

  * Good use of whitespace
  * Lots of examples
  * Simple one page navigation
    * Makes it easy to navigate

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

  The official docs are terrible. Use [rubyapi](https://rubyapi.org/) instead.  
  100x better than the official docs.

For a language that's elegant the documentation sure as hell don't reflect that. The documentations are ugly, hard to navigate, and find imformation. Needs a remake desperately

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

[Jekyll]()  
[Jekyll-Minimal-Mistakes](https://mmistakes.github.io/minimal-mistakes/)