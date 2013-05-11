---
layout: post
title:  "Checking Out a Remote Branch with Git"
date:   2013-05-09 08:22:00
categories: git branch remote
references: 
---

After cloning a git repository, you may want to work on a branch from that clones repository. You cannot create a branch in the normal manner. Instead, you need to create a branch based on the remote branch that is set up to track the branch from the remote. It is simple to do, but easy to forget.

{% highlight bash %}
git checkout -b test origin/test
{% endhighlight %}

Reference:

[Stackoverflow: git checkout remote branch](http://stackoverflow.com/questions/1783405/git-checkout-remote-branch)