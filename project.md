# Project Description for the XProgramming Conversion

## XProgramming.com background

My site, XProgramming.com, is ten or more years old. It was initially a plain HTML site, which I administered with CoffeeCup or something. 

At some point, I got some experience with WordPress and thought that the site would be better off in WordPress, as it seemed to ease some of the writing and indexing. I read a book by some famous WordPress expert, and since they were in the business of making WP sites, engaged the expert to convert me to WP.

That went poorly: the expert soon passed the project off to an underling who had apparently had a very successful career in food services up until now.

I took the site back and engaged Laura, my present webmistress (not as interesting as it sounds) who got the site into its present shape. There are now more than 400 articles on the site. The complete site with all its articles, pages, pictures and attachments is over 400 megabytes and 7,000 items in WordPress. The WordPress XML dump, which does not include assets, is over 200 meg.

Laura is moving on to another phase of life. And the site is a bit fusty and needs to be responsive and to have an improved look and feel.

Something needs to be done.

## My current writing process

I currently write in Markdown. This gives me the ability to treat formatting and semantics separately, as one does, and gives me a confidence in archived copies of things as they are plain text and therefore, one assumes, not subject to loss if Word or Pages or whatever goes away.

I like to keep the article and all its assets in the same folder, with a unique folder for each article. The main alternative to that seems to be to keep articles in one folder (with sub-folders perhaps) and assets separately in an assets folder. This means that articles lose their integrity and cannot be moved around one at a time in any easy way.

Right now, when I publish to XProgramming, I copy the assets from my folder to WordPress's assets folder, then create the article, fill in WordPress's forms, and save it. With luck, it all links up. This process is tedious.

I would like to retain my writing process and simplify publication.

## XProgramming is an important historical archive

at least according to me. 

Therefore I want to preserve its entire contents in a web-readable form indefinitely.

## Personal control of the site

It's good to have help, and Laura has been a marvel. However, it is a pain relying on someone else to update WordPress and such. WordPress has many plug-ins and they tend to stop working on updates. Trust me, it's a pain.

And I do not desire to break in a new person to maintain the site, if I can do it myself.

So I want a simpler site that I can readily maintain.

## Two candidate structures

We considered a Ruby/Sinatra-based site for a while. I like Ruby and while I'm rusty at it, it comes back quickly. After consideration, though, I realized that maintaining a site that runs Ruby isn't all that much simpler than maintaining one that runs WordPress.

So the idea arose of making the site almost completely static. (We'll probably need a little JavaScript and maybe I should worry about that.)

So the goal, so far:

Convert XProgramming.com to a static site, preserving all its existing content, and allowing me to work in my preferred Markdown style.

## Basic Stories

We have a whole bunch of story cards. I'll not reiterate them here but here are some of the main ones.

Note that you might have different priorities. These are mine. It's my time, my money, my project. This will be important when we come to the estimation topic below.

### Do it myself, with partners

**MUST:** To keep my hand in, for fun, and so that I can maintain the site going forward, I want to build the site myself. I clearly need people to pair with, advise, and help. But I want to understand every line of code, and ideally to have typed it in myself.

### Build this in "Agile style"

**MUSt:** The project must proceed incrementally and iteratively, with visible results at all times. 

### One site rules them all

**MUST:** I might change the address of the site, but I do not want to have two sites. 

### Contains all XProgramming content

**MUST:** All existing articles must be present in no worse shape than they are now (some are damaged, we've discovered)

**VERY HIGH WANT:** Content is in the new format.

### Responsive

**MUST:** The new site needs to be responsive. I'd like a more modern simpler look and feel. 

### Indexing

**MUST:** The site now contains a number of categories. Some of them are important enough to require index pages. There will be more categories, more indexes. 

**HIGH WANT:** Indexes will be long. Index pages probably need to have PREV/NEXT capability so as to load quickly. 

### Existing article links should work

**WANT:** People may have saved links to existing articles. In WP, these will typically be "article slugs". It would be nice if these continued to work but this is a lower priority.

### Edit old articles in new style

**VERY HIGH WANT:** Existing articles in separate folders with their associated assets, preferably converted to Markdown as well as possible. (Markdown passes through HTML but for editing convenience, let's do better.)

### Easy push

**MUST:** Pushing articles needs to be a one-button process when all is said and done.

**WANT:** Ideally push only new and changed material, not all 200+ megs. That would not work well from a hotel or bookstore.

### Use my existing ISP

**HIGH WANT:** He has been a good and faithful ISP, helpful to me over the years, and is a friend if not a close one. I'd like to continue to have him host the site. There are issues with this in that for personal reason he's not able to be doing things right now.

**ACCEPTABLE:** Host temporarily elsewhere.

**POSSIBLE BUT UNDESIRABLE:** Host elsewhere permanently.

## Summing up

I want a new site, not running on WordPress, preferably running as close to zero infrastructure as possible (i.e. no Ruby etc on the server).

The site must contain all XProgramming's content.

The site must have a new look and feel, to include all the existing content, not just the new.

The site must support Markdown and the article and assets in the same folder.

## Estimation

### Agile Estimation

Perhaps you did not recognize my name. I am an author of the Agile Manifesto and have been doing, coaching, and teaching Agile methods since 1996. So I fully get the idea of doing experiments to find out what works and what does not, and as we'll talk about below, that's what's happening.

Even at this level, however, I really wanted an estimate of the time and money needed to do this. My time is worth something (according to me), and there are many things I'd like to pay attention to. And some of the people helping deserve to be paid.

My starting intuitive feeling was that if this could be done for $5,000 or less, I'd happily do it. If it was going to cost $10,000 or more, I probably would not. Between $5,000 and $10,000, I would become increasingly unhappy.

I have an existing staff: me, my pals, people on the Internet who might ask questions. Possibly could hire a consultant if need be, but that quickly gets costly. 

Therefore, even if there is someone in the world who could do this project and knows how much it would cost, he is no use to me, because he's not going to do it. My team is going to do it.

And my team do not know how to estimate it. And even as an Agilista, I really would like not to undertake the project if it'll come to nothing.

Let me repeat that. If I spend a few thousand dollars only to discover that this is a bad idea, I'm not going to be happy about it. Frankly if it was a bad idea, I'd not like to spend even $1,000 to find out. Certainly not more.

### Conventional Business Estimation

Imagine a non-Agile company, with non-Agile staff, who need this done and want to do it with their existing staff. They, too, want to know if it can be done under $10,000 (or whatever max). And they're not interested in "going Agile" to find out. 

Joe Programmer, in such an organization, is not in a position to answer "well, let's just get started and see what happens".

We probably all agree that there's no good way for Joe (or for me) to figure out how much it'll cost to do this. 

I have the advantage that I can start spending and stop if it looks bad, and even then I won't be happy. 

Joe is less able to do that. He is in a situation where not accomplishing the task will be seen as "failure", even if he comes back after only a few thousand bucks.

Now, sure, Joe should learn how to negotiate with management, learn how to educate them, and so on. It would be great if he'd do that. But by God I've been there and without knowing a lot of the things I know now, I really was not equipped to undertake that kind of an approach. 

So I'd like to know ways to help Joe, and the ones I do know, I do. I write articles and books on development, including advice on estimation. I teach programmers how to work incrementally, so that at least they'll be better equipped to find out costs early. (See below on our own actual experience.)

When I can, I write for, or talk to, Joe's managers, to help them see that there may be better ways. I'm working as hard and smart as I can to get the alternatives out there. This is part of that.

I'm trying to help everyone, including Joe. Right now, I don't have much help for him beyond reporting what I know, showing what I do, and all that stuff that I do. I can't help wishing for more.

## More Later ...