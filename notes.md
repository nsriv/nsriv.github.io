#   Procedure
1. Create repo on github
2. Clone to desktop with GH Desktop app
3. Follow instructions from https://help.github.com/en/articles/setting-up-your-github-pages-site-locally-with-jekyll
4. But when bundle install fails in step 2.5, use:
   1. sudo gem install bundler -v '1.16.1'
5. When you get error bundler could not file compatible versions, follow suggestions and run
   1. bundle update
6. sudo gem install jekyll bundler
7. Edit Gemfile.lock to use Bundled With 2.0.1