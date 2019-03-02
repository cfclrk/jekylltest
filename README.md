My ruby version

    $ ruby --version
    ruby 2.6.1p33 (2019-01-30 revision 66950) [x86_64-darwin18]

Download dependencies

    bundle install

Serve project locally

    jekyll serve

Regenerate syntax.css file

    rougify style base16.solarized > assets/syntax.css

Also add the following:

    .highlight {
      padding-left: 1em;
    }
