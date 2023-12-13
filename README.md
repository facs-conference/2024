# FACS2022

Website of the FACS2022 conference.

The documentation for the theme is at
https://github.com/DigitaleGesellschaft/jekyll-theme-conference

To add a new page type, add a template to the `_layouts/` subdirectory.  To
modify an existing page template, copy it from
https://github.com/DigitaleGesellschaft/jekyll-theme-conference/tree/main/_layouts
into `_layouts/`.

The documentation for the deployment process is at
https://www.moncefbelyamani.com/making-github-pages-work-with-latest-jekyll/

To run the website locally, see https://jekyllrb.com/docs/

    gem install jekyll bundler # run this one time
    bundle add webrick # ditto, for ruby 3.0 or higher
    bundle exec jekyll serve --livereload # to start jekyll
    
When jekyll is running, open http://localhost:4000 to see the website.

To serve for other IPs, use e.g.:

    bundle exec jekyll serve -H 100.111.101.124 --incremental
