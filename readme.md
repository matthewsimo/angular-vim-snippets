UltiSnip & Snipmate Snippets for AngularJS
==========================================

This repository contains snippets files for [AngularJS](http://angularjs.org/) including JavaScript, HTML, CoffeeScript and HAML.

## Contents

    snippets/*: snippets using snipmate format
    UltiSnips/*: snippets using UltiSnips format

## Installation

### UltiSnip
 - `git submodule add git@github.com:matthewsimo/angular-vim-snippets.git /path/you/want/it/`
 - add `./UltiSnip` to your list of `g:UltiSnipsSnippetDirectories` and you should be set

#### UltiSnip options

For ngdoc snippets in ultisnips, the module name can be overwritten in case
you're using a variable or js expression for your module name. Add this to your
modeline or set as needed.
```vim
let g:angular_module_name='FooBar' "Replace with your module name, of course.
```


### Snipmate

 - `git submodule add git@github.com:matthewsimo/angular-vim-snippets.git /path/you/want/it/`
 - add `./snippets` to your VIM *'runtimepath'* or *'rtp'*
   - e.g. `rtp/snippets/<filetype>/*.snippets`

### NeoSnippets

 - `git submodule add git@github.com:matthewsimo/angular-vim-snippets.git /path/you/want/it/`
 - add `./snippets` to `g:neosnippet#snippets_directory`

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
