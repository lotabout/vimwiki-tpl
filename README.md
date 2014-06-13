This template is a modified version of [frePerl's wiki notes](http://phpstone.com/wiki/index.html).

## Things added:
1. google code prettify.
2. disqus support.
3. mathjax support.

## How to use it.
1. clone this repository and put the files under `path_html` directory of your
   vimwiki settings(`~/vimwiki_html` by default).
    
    git clone https://github.com/lotabout/vimwiki-tpl

2. modify vimwiki options in your `.vimrc`(more on the options of vimwiki `:h vimwiki`)

        let wiki_1.path_html = '(The directory to output html files)'
        let wiki_1.template_path= wiki_1.path_html . '/template'
        let wiki_1.template_default = 'default'
        let wiki_1.template_ext = '.htm'

        let g:vimwiki_list = [wiki_1]

3. change the options of the template to your own.

    1. The `Blog` url in `default.htm->nav` tag.
    2. disqus_shortname in `default.htm->disqus_htread`.
