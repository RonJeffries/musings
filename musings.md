# Notes and musings as I try to grok 

## O500 15 Nov 2014

I initially built, I guess, a Github *project page* called `ronjeffries.github.io/ronjeffries`. Perhaps / probably, what I really want is a *user page*, which would be called `ronjeffries.github.io`.

Both, it appears, can contain a web site kind of thing, so perhaps(?) it doesn't matter. If it does matter, I'm not clear on just how it matters.

I build the `/ronjeffries` one with the "automatic page generator", where you pick a theme and a bunch of stuff, so it now has in it a gh-pages branch, where the web content is stored. that is all it has, apparently, i.e. it does not have a master branch.

A user page, on the contrary, would build itself from its master branch. There may be some arcane reason why this difference is there. 

It sounds as if the user page expects to find one's entire jekyll stuff in master? and will actually build the site, using jekyll, at github?

Does that mean that if i set up a `ronjeffries.github.io` repository and push the current contents of my rj-com folder (where our jekyll stuff is) to that repository, then http://ronjeffries.github.io will look like the rj-com stuff?

If so, before I tried that, I think I'd like to strip back out the 400 extra folders that are in there.

## 0545 15 Nov 2014

This repository: `https://github.com/mojombo/mojombo.github.io` generates this site: `http://tom.preston-werner.com` whose "real" address is `mojombo.github.io`.

The repository looks not unlike my rj-com folder. So possibly, if I were to create a repository ronjeffries.github.io and push rj-com to it, then `http:ronjeffries.github.io` would actually look like the local rj-com stuff.

Seems almost doable. Will have to learn how to push rj-com to other than its current origin?

## Strangely Confused

I feel like there are three things that I would need to understand before I understood enough of this to do it. As it stands right now, I feel like if I do the wrong thing I'll break the internet or something.

It has been a long time since I felt this way, if I ever have. Apparently I am outside my comfort zone with a programming kind of thing. Or I am coming down with Impostor Syndrome. Or becoming stupid. That would be bad.

## 1020 15 Nov 2014

Progress. I followed instructions at `https://help.github.com/articles/creating-project-pages-manually/` and created a minimal index.html and made a github *page* at `http://ronjeffries.github.io/musings/`. 

This entails, for a github *page*, making and pushing a branch whose name must be gh-pages. All it really needs to contain is an index.html, apparently

Then I added a link to index.html, pointing to info.html or something. Then I used kramdown to convert this markdown file to html. That turns out to require a template, which works if you make it refer to `body` in the place where you might think it'd say `yield`. There is essentially no information on the Internet about how to use kramdown on the command line. 

That turns out to be `kramdown --template musings.erb musings.md >>musings.html` in my case.

After some futzing with the file names, and I wish I hadn't named everything musings, I got this page, converted to HTML, linked to from the base page of the site. I have now added a link to a second html, `project`, where I was planning to write up what the xprogramming conversion project is, as an aid in a twitter um discussion I'm having with Woody and Neil.  I might defer that to learn more about this basic process, perhaps bridging my understanding gap between this much, and how to use jekyll in this process.

Right now, to regenerate this tiny site, I'll have to re-kramdown all the articles (all two of them if i do `'project`), then add them to git, commit, and push the branch. Basically jekyll is a giant batch file that does that, so it should not be TOO difficult to get it to do much of it.