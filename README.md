To view
-------
Visit [http://ardell.github.io/recipes/](http://ardell.github.io/recipes/)

To add a recipe
---------------

- Go to the `_posts` folder
- Click on the 'Create New File' button (top right)
- Name the file using the date and the name of the recipe (eg ``)
- Use an existing recipe as a template.
Must have the meta data at the top (layout, title, date, tags).
Use [markdown syntax](https://daringfireball.net/projects/markdown/syntax)
Example:
```
---
layout: post
title:  "Bluth Frozen Bananas"
date:   2015-10-24 13:22:21
tags: desserts
---

Ingredients
-----------
- Bananas (a little on the green side)
- 2 cups chocolate chips or chopped semi-sweet chocolate
- about 1/2 cup vegetable oil
- garnish (chopped toffee, chopped nuts, sprinkles, etc)

Instructions
------------

Peel bananas and carefully insert a popsicle stick in one end (I cut off about
the bottom third or fourth of the banana first to make this easier and create a
shape that was easier to work with). Place bananas on a cookie sheet lined with
parchment or waxed paper and freeze for at least 15 minutes, or until solid
enough to work with and not fall off the stick.

Combine chocolate chips and about 1/4 cup of the vegetable oil in a double
boiler or in the microwave and heat until melted (stop to stir it every 20-30
seconds to prevent burning).  Check the chocolate for thickness- a thick
chocolate will make a very thick coating. Add more oil as needed until not too
thick (mine was about the thickness of maple syrup). Dip one banana in the
chocolate until coated.

Working very quickly, roll in desired toppings, as the chocolate hardens very
quickly after hitting the cold banana. Place completed bananas back on the
parchment-lined cookie sheet and return to freezer. Can be made many days in
advance.


Source
------
[BakinBit.com](http://www.bakinbit.com/2013/05/17/bluth-frozen-bananas-and-ice-cream-sandwiches-with-homemade-chocolate-cookies-and-gelato/)
```
- Name the 'commit' (generally something like 'Add frozen bananas recipe') and click the green 'Commit changes' button.
- And you're done!

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

