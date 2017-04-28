---
layout: post
title:  "Branch open app"
date:   2017-04-28 11:58:30 -0600
categories: jekyll update
extra_head: |
    <script>
    branch.deepview(
    {
        channel: 'facebook',
        data: {
            mydata: 'content of my data',
            foo: 'bar',
            '$deeplink_path': 'item_id=12345'
        },
        feature: 'dashboard',
        stage: 'new user',
        tags: [ 'tag1', 'tag2' ],
    },
    {
        make_new_link: true,
        open_app: true
    },
    function(err) {
        console.log(err || 'no error');
    } 
    );
    </script>
---
To add new posts, simply add a file in the `_posts` directory that follows the convention `YYYY-MM-DD-name-of-post.ext` and includes the necessary front matter. Take a look at the source for this post to get an idea about how it works.

