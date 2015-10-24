To view
-------
Visit [http://ardell.github.io/recipes/](http://ardell.github.io/recipes/)

To run locally
--------------
- clone this repository
- `cd recipes`
- `git checkout -b gh-pages origin/gh-pages`
- `echo 2.2.3 > .ruby-version`
- `echo recipes > .ruby-gemset`
- `cd .. && cd recipes`
- `gem install bundler && bundle install`
- `jekyll serve`
- navigate to [http://localhost:4000/recipes](http://localhost:4000/recipes)

