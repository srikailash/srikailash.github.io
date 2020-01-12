---
layout: post
title: When am i ever gonna use this in real life
---

That favourite question of every computer science graduate.

I keep on asking this question a lot for things i learn and recently stumbled upon usage of
AVL tree as an indexer for DB instances in this super intersting article in

[HighScalability blog](http://highscalability.com/blog/2016/8/30/the-cat-and-mouse-story-of-implementing-anti-spam-for-mailru.html)

So, i ended up coding AVL tree for fun.

Something quick about indexes:

What is an index for:
- To optimize the performance of a database by minimizing number of disk accesses required.

Why AVL tree:
- Self balanced for insertions and deletions

When is this better than using a hashtable for indexing:
- sorted access
- range queries


{% gist 933459f3d3062edc3fe8981fcc36c342 %}