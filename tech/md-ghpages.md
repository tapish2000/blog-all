## How to use github pages and markdown to make websites
---
> [Home](../index.md) > [Posts](../posts.md) > [Tech Stuff](tposts.md) > `Markdown-githubpages`

---

<br>

<div style="text-align: right">📅 06-04-2021 11:48</div>

I tried to find ways 👷‍♂️ to make a website containing multiple pages. All the searches show that the possibility of doing this is by using *jekyll*. For that, it says to clone a repo which is already built by someone with a good theme and some HTML and CSS. If you want to check them out, these are with the name *Jekyll's Free Themes* 👉 [click here](http://jekyllthemes.org/)   
I didn't wanna do that, so I figured out a way of **making links using markdown only** 😎. I was completely focused to use `.md` to make the website, atleast for now 😏. So, now to get this if you go to [my repo](https://github.com/tapish2000/blog-all) and then open `index.md` which is the first page of this website, it contains `Content` and links to other `.md` files. And similarly all other pages are linked to others.    

So that's how I changed my repo to give the website a multi-page view. I hope it's easy to understand and also, if you also want, you can easily try it out.

**If you like thw work, I request you to give the repo a star ⭐.**

---

<br>


<div style="text-align: right">📅 03-04-2021 14:37</div>

Anyone who wants to learn how to make a website like this (using only markdown files), can see my [repo](https://github.com/tapish2000/blog-all) 😏. It is as simple as you can think of 🆒. 
1. Create a repo of your desired name 😃.
2. Go to 👉 Settings > Options > Github Pages and enable that.
3. Choose some root, I read [here](https://github.com/mkdocs/mkdocs/issues/608#issuecomment-109799721) later 😅 that it's better to choose docs/README.md but I chose the root one.
4. Select a theme if you want ✨.
5. A `_config.yml` will be created. I have added some plugins and all in my `_config.yml` file which helps in creating links between pages although I don't need that for now.
6. Whatever you write in your README.md converts into HTML in your selected theme 🚀. I didn't want my posts' markdown file to be called README.md so I changed it to `index.md` as index is also a default name for the homepage on github pages.

---
