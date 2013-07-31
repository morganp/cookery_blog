## What is Octopress?

Octopress is [Jekyll](https://github.com/mojombo/jekyll) blogging at its finest.

New Post
==

    rake new_post["title"]

New Page
==

    rake new_page[super-awesome]

# creates /source/super-awesome/index.markdown

    rake new_page[super-awesome/page.html]

# creates /source/super-awesome/page.html


View/Generate
==

    rake generate   # Generates posts and pages into the public directory
    rake watch      # Watches source/ and sass/ for changes and regenerates
    rake preview 
