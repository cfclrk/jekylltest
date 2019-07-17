My ruby version:

    $ ruby --version
    ruby 2.6.1p33 (2019-01-30 revision 66950) [x86_64-darwin18]

Download dependencies. The `--path` flag is optional and installs dependencies
in a project-specific location. If used, it creates a file `./.bundle/config`
which future `bundle` commands use, so the `--path` option only needs to be used
once.

    bundle install --path vendor/bundle

Serve project locally

    bundle exec jekyll serve

To regenerate syntax.css file:

1. `rougify style base16.solarized > assets/syntax.css`
2. Also add the following to the generated `syntax.css`:

       .highlight {
         padding-left: 1em;
       }
