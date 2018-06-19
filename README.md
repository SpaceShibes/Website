# Website
Repo to track updates to my personal website, nathandsouza.ca
My goals are to learn html, css and javascript in order to build a website I am content with. My current plan of attack is to learn the languages in the order I stated via online lectures such as lynda and linkedin learning. 

Updates and Issues:
- When I first started playing around with my website I found that all the changes I made were via the cpanel. Although this was very convenient the issue with this was that I wanted to track my changes and progress on this repository. I did ssome research and what I learned was that I could push from my local to a remote repo on my site, which would then update the html on the site. This was the perfect solution as I could just as easily push to my github instead of having to copy and paste html files. Setting this post-receive hook up was quite the challenge as many of the guides were outdated. Nevertheless, I now currently have a post-receive hook setup so I can just as easily update this repo as my live site.

- My next issue was designing the site itself. With html/css/javascript I found many resources to learn it and found that this wouldn't be a huge problem for me. Rather what I struggled with was designing the site itself. The code I could learn but I had no clue how to make the site actually look nice and finding resources for that proved to be a bit tougher. What I ended up doing is that I went through countless sites, looking at features I liked and disliked. This in turn gave my a better idea of what I would want my site to look like. 

- Post-Receive Hook Notes: Just as a reminder to yourself on how your hook works, there are two branches you will mainly use, dev and production. Do work on dev, when satisfied merge it into production (note you have to be on the prod branch when doing this) and then push to the deploy_server remote repo (git push deploy_server production). Also remember to push the prod branch to this repo as well to track progress.

- First draft of the website is finished! I'll be adding new features every now and then, but for the time being I'm finished and will be moving onto other projects.

Things I would still like to do:
- Make more responsive 
- Add some more fun javascript features (like sections loading as you scroll)
- Change up colours, maybe redesign to make it more vibrant?
- Personalize, add more sections for hobbies and photography
