---
title: Git Powered Blog Drafts
date: '2011-11-10'
---

Ok, I don't personally care how you build/host/hump your blog, although in
general, it is probably, wait...for it [wrong][wordpress]. Now that we got that
out of the way, here is a nifty idea to think about:

Use the simplistic yet elegant power behind [Git][git-scm] to keep a robust and
burgeoning amount of blog posts and drafts. Why? Well Git is able to track
changes across a system fairly well..shit it's actually the only thing it does.
Being able to track diffrent blog posts, when they were completed and being
able to rewind to them, seems like something a powerful blogger might like to
have at his or her fingertips. To get going you need 2 things:

1. [Git][git-scm], the powerful (some would say the best…and or the "bomb")
	 <s>source</s> version control management system.
2. A static generated site. This means, that all of your files are flat in
	 nature and rely on no database to produce the overall content. Not only does
	 this solve a nasty [injection][wikipedia] [problem][youtube], but it can
	 withstand high amounts of traffic. Here are a [few
	 options][mathematism](mostly Python and Ruby variants) if you are completely
	 lost to this concept. Don't worry about choosing one that is "wrong". Most
	 of the posts can be moved from one system to another.

Navigate to the root folder of your newly built static site blog and invoke:

<script src="https://gist.github.com/2710866.js?file=git init"></script>

This will create a brand spanking new git repo, surrounding your code in a
wonderous pillow of fluffy safety. From here it is really simple:

<script src="https://gist.github.com/2710866.js?file=git branch"></script>

<script src="https://gist.github.com/2710866.js?file=git checkout"></script>

Now you are free to modify your new post to your hearts content. By using
"post" at the beginning of the branch name, it is easy to see what branches are
posts and what are other, structural changes. This concept is ridiculously easy
however, it works well for one reason: nil == friction. One of Git's most
amazing features is its ability to handle branches and merging said branches
with ease. This "freedom" cuts down on the constant anxiety of "lost work". If
you aren't worried about losing work, causing problems, or breaking something
you are free to use 100% of your creative juices to…well create!

Elegant solutions will always trample their off-the-shelf, boxed, rural cousins.

[git-scm]: http://git-scm.com/
[mathematism]: #
[wikipedia]: http://en.wikipedia.org/wiki/SQL_injection
[wordpress]: http://wordpress.com/
[youtube]: http://www.youtube.com/watch?v=-JFfN5pKzFU

