+++
title = 'Sharpen an Axe for Longer'
date = 2024-04-02T23:05:17+02:00
draft = false
+++


The title is paraphrased from a quote that is [*incorrectly*](https://quoteinvestigator.com/2014/03/29/sharp-axe/) attributed to Abraham Lincoln: 
> To Cut Down a Tree in Five Minutes Spend Three Minutes Sharpening Your Axe

Anyway, what I think the quote is trying to say is, it's okay for things to take time. That is, if you're actively working on making the end result much better. 

Since I am a world renowned champion of doing things *the easy way™* but also *doing things good enough™*, I have found that the only reliable method for both those phrases to be true is if I take time to understand/study/figure out what the problem is [^1]. 

### Case study for this case to study <sup>*(working title)*</sup>

This site for instance. I want to document my writings/thoughts but do not want to spend too much time in fixing the content for each post. My initial solution involved writing in markdown first, converting this to html (via a converter) and then using templates to ensure the header and footer elements were standardised from page to page. This caused a certain amount of friction and meant I spent much less time writing and more time doing admin [^2].

I also wanted a landing page to act as a place to direct people to first that needed to have a different style from the posts page. Also since I had this need to keep everything as small as possible, I decided to write the HTML and CSS from scratch and use next to no JavaScript. his was okay, since I had a snappy page, but any time I made a change or decided to incorporate or test something new, something inevitably broke [^3]. 

### The fix

Just use a CSS framework for the landing site and a static site generator geared to blogs for the posts page. 

In my case this would be TailwindCSS and Hugo + Papermod. I could have saved a ton of headache earlier, by just spending some time with the really well written documentation online. I was being extra lazy and thought writing from scratch would be easier than learning something new [^4]. 


### The exception that proves the rule

If you are a serial procrastinator, perhaps avoid doing this. You might end up sharpening your axe for much longer than necessary.  &nbsp; 

<br> 
<br>

### Misc
For more information on how to get a hugo blog started up with a custom theme (specifically for cloudflare pages and github), [this article](https://www.andrewhoog.com/post/git-submodule-for-hugo-themes/) is super helpful&nbsp; 
<br> 
<br>


[^1]: This mostly rings true, but there are times when it is better to start doing and stop studying
[^2]: This is also known in certain circles as the devil's busywork [^5]
[^3]: Mostly since I would forget the duct tape code I had used to duct tape other code. 
[^4]: Don't write from scratch if you can avoid it guys. Avoid [NIH syndrome](https://en.wikipedia.org/wiki/Not_invented_here).  
[^5]: The circle I mention is currently one person as of the writing of this post, i.e. myself. 