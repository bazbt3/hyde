---
layout: post
title: Developing
---

I may have mentioned my programming days are >30 years in the past?  Well they are.  It's not to say I haven't dabbled in the last few years.  Because I have.

My GitHub Pages site is a prime example; personal, trivial, offering not much mass-appeal; yet requiring a fair degree of time and patience to create.

And I've learned new skills too!

My pages are hosted at [GitHub.com](http://github.com); the design (the technical aspects, not necessarily how pretty it looks) is based on a forked version of the [poole/hyde](https://github.com/poole/hyde) repository (repo.)  **This is where the more in-depth instructions are located.**  Essentially it's a Web site in a box, free from the shackles of self-hosting and server security concerns.

Getting it personalised in the first instance was surprisingly easy.  Take a look at [http://github.com/bazbt3/bazbt3.github.io](http://github.com/bazbt3/bazbt3.github.io) for *my* site's files.

I'm assuming here that you want to create a new site and want to do it *the easy way*, as did I. There's a learning curve of course, but there's no compelling reason to step outside the GitHub.com site along the way.

The executive summary:

1. Login to your GitHub.com account.  You may need to create one for this step to work best!
2. Find and fork the 'poole/hyde' repo, calling your fork [your GitHub username].github.io - 
3. Remove the entry (all the text) in the `CNAME` file and save it back to your repo.  This forms one half of a redirect from a domain external to GitHub Pages.
4. Customise the fields within the `_config.yml` file and save it.  This effectively personalises the new site.
5. Edit the post within the `_data` folder.  This is to test whether the basics are working.
6. Browse to `[your GitHub username].github.io` - and you should see something superficially like poole/hyde and my sites, but with your content.
7. Fix anything that doesn't quite work.
94. Success!

If you don't see what you like, it's not a massive amount of work for anyone with any previous programming (at any level) or HTML background to work stuff out.  Knowing a bit of Markdown - to edit and format your posts - will help.

I've changed stuff and added a few things to the basic 'framework', such as:

* Changed the site name font (I know a tiny amount of CSS, not enough to break stuff, but I always do and have to revert.)
* An 'Archive' page, basically a copy and paste from the jekyllrb.com site, but formatted to add post excerpts.
* A 'Reading list' page, a simple loop reading data from a .csv file.
* Other stuff.

Once you get into this, the ideas flow quickly.

But, despite all this enthusiasm, faffing about…  my primary blog still resides at Jason Irwin's 10Centuries - [here.](http://bazbt3.re-app.net/)

Why?

Because there's more to blogging than fiddling with site nuts and bolts, SEO, testing, etc. - it's all about the *writing* for me.

Besides, [10Centuries v4] (http://10centuries.org/) is due soon (currently in invite-only beta) and that's an *entirely* different ballgame!

Despite my what it states in my App.net [bio](http://app.net/bazbt3) I am \#NotADeveloper.

But it helps to have a basic understanding of what it takes to *be* one.

A clear mind.
