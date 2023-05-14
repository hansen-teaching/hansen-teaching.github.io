---
layout: post
title: How I Built & Hosted a Website on My Domain for FREE (GitHub Pages + Jekyll Theme, NO CODING)
date: 2019-08-15 05:00:00 +0300
description: # Add post description (optional)
img: githubpages.jpg # Add image post (optional)
tags: [github, github pages, web development, website, web design] # add tag
---
I’ve owned my domain Rhiannon.io for a year now. When I got the renewal notice last week, I sighed, realizing I had yet to do anything with it.

Like so many of us, I tend to impulse buy domains that I never use, but I’ve wanted to get a personal site online since 2011 when I bought rhiannonpayne.com… but later let it expire without doing anything with it. When I purchased Rhiannon.io last year, I told myself it would be different this time, until it came to shelling out $150+ for web hosting, templates, etc.

Fast forward to yesterday, when I asked my boyfriend Justin how I could get a clean, simple personal website set up on my domain **without paying for anything.**

I thought this would be an impossible challenge. But Justin introduced me to GitHub Pages, and by the end of the day, I had a beautiful personal site online. And yes, it was *all free.*

*This post was originally published on [Medium](https://medium.com/@rhiannonpayne/how-i-built-hosted-a-website-on-my-domain-for-free-github-pages-jekyll-theme-no-coding-7211a24c2a32){:target="_blank"}--be sure to follow and clap!*

# **1. Buy Domain (Google Domains)**

My domain, Rhiannon.io, is the one thing I did pay for. I purchased my domain through Google Domains, which ended up being pretty easy for connecting it to the host later. It’s also great for setting up an email address through GSuite.

# **2. Create a GitHub Account**

GitHub is a ubiquitous tool that I’ve always known of but never had the opportunity to use until yesterday.

To get started with GitHub Pages, you need to first create a free [GitHub](https://github.com){:target="_blank"} account.

![](https://cdn-images-1.medium.com/max/2032/0*9PrPRGUM7EP-VraD)

# **3. Create a Repository**

Next, you will need to set up a repository for your site.

Per the instructions on [pages.github.com](https://pages.github.com/){:target="_blank"}, your repository name has to be *yourusername*.github.io. Because my GitHub username is rhiannon-io, my repository name is rhiannon-io.github.io. This is also the URL you will use to test your site before connecting it with your domain. The repository must be public to set it up with GitHub Pages.

You can find the rest of the instructions on pages.github.com. If you’re not a developer, you will probably be using the “GitHub Desktop” as your “client,” so be sure to select that option after step 1.

![](https://cdn-images-1.medium.com/max/2080/0*GplWcXC3m_xVY5F8)

# **4. Find a Free Jekyll Theme**

Similar to Wordpress and Squarespace, there are a lot of great themes out there that you can use for your GitHub Pages site. I used [jekyllthemes.io](https://jekyllthemes.io/){:target="_blank"} to find one that would fit my needs (namely: clean, blog, [free](https://jekyllthemes.io/free){:target="_blank"}).

The [Flexible Jekyll](https://jekyllthemes.io/theme/flexible-jekyll){:target="_blank"} theme was perfect for my little personal site. It also looks great on mobile!

![](https://cdn-images-1.medium.com/max/2278/0*OcV9RnWbovZxzHe1)

# **5. Fixing the Flexible Jekyll Theme**

Unfortunately, I encountered some issues with the Flexible Jekyll theme where GitHub wasn’t loading the dependencies properly.

Fortunately, my boyfriend is an incredible engineer, and I was able to enlist his help.

If you want to use Flexible Jekyll, you can simply [clone or fork my repo](http://github.com/rhiannon-io/rhiannon-io.github.io){:target="_blank"} and customize it for your own site.

![](https://cdn-images-1.medium.com/max/2028/0*_GyEm_DmYWV5Mllz)

By just forking the repo, you can save yourself from having to go through the more complex instructions on the Flexible Jekyll theme’s documentation. If you go this route, you will have to rename the repo fork to *yourusername*.github.io as discussed earlier — so if you already created a repo with that name in Step 3, you can delete that one and then rename your fork, *or* alternatively you can clone the repo and copy the files into your empty repo. Forking and renaming is the easiest way IMO.

If you have any issues, let me know in the comments!

And if you’re curious, this is [the commit](https://github.com/rhiannon-io/rhiannon-io.github.io/commit/f175b2416a101fa5d8466027d2ab25eb98e572d7){:target="_blank"} where Justin resolved the dependencies issue with the original theme.

If you select a different theme, I recommend following their documentation or just forking their repo and hopefully, you won’t encounter any issues.

# **6. Customize the Config File**

Now you’re ready to dive into site customizations! You’ll probably want to get started in the **_config.yml** file.

![](https://cdn-images-1.medium.com/max/2000/0*f0FWeqXdeJd9f0r0)

Click the pencil in the upper right corner to edit the file.

![](https://cdn-images-1.medium.com/max/2006/0*zAQNJs5jSBOm4a5z)

Now, it’s pretty easy to see the areas that you will need to configure with your own information — it’s like a game of fill in the blanks.

![](https://cdn-images-1.medium.com/max/2002/0*iOdOh7eBQAsXU_w9)

When you’re done, click the big green **“Commit changes”** button at the bottom of the page, then refresh your website (*yourusername*.github.io) to check it out!

# **7. Update Favicons**

You may notice that your site has a favicon (the little icon in the browser tab). To update it, find the favicon folder (on Flexible Jekyll it’s under **assets/img/favicon**) and replace the files by uploading new ones with the same image dimensions and same file names.

![](https://cdn-images-1.medium.com/max/2010/0*oR_IBrQxHH3sZmlE)

To create a .ico file you can use this [favicon generator tool](https://www.favicon-generator.org/){:target="_blank"}.

# **8. Customize Posts**

If you’re setting up a blog site like mine, you can do what I did and edit the filler/example posts with your own content.

Go to the **_posts **folder, click into an example post, and again go to edit.

![](https://cdn-images-1.medium.com/max/2000/0*71c7r7vaGxbIvjgC)

Now you’re once again filling in the blanks to make sure the post is formatted correctly.

![](https://cdn-images-1.medium.com/max/2016/0*WYsgBIG718LFAJPQ)

Once done, save your changes by hitting “Commit changes” at the bottom.

# **9. Add Images**

To add your own images in your posts, you will need to upload them to the correct folder in your repo. In Flexible Jekyll, that’s **/assets/img**.

![](https://cdn-images-1.medium.com/max/2000/0*ZuNz9oVq7YnIr7KU)

# **10. Understanding Markdown**

When editing your posts and pages in GitHub, you’ll need to understand the markdown language to format your posts. Markdown is what makes your text bold or italicized, allows you to add headers, add links, add images, etc.

It’s pretty straightforward — I use this handy [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet){:target="_blank"} and Google if there’s something I can’t figure out.

In my case, I wanted to post all my existing Medium blog posts on my site, but doing all the markdown manually was taking hours. So I found this [Medium to Markdown](https://medium.com/@macropus/export-your-medium-posts-to-markdown-b5ccc8cb0050){:target="_blank"} tool to help! The Google Chrome extensions are ridiculously easy.

# **11. Set Custom Domain**

Once your site is looking good on *yourusername*.github.io, you’re ready to connect it to your custom domain!

This is a very fast process, and you can find the GitHub pages instructions [here](https://help.github.com/en/articles/using-a-custom-domain-with-github-pages){:target="_blank"}.

If you purchased your domain with Google Domains as I did, you can read more specific instructions [here](https://medium.com/@Tnylnc/tnylnc-how-to-set-up-github-pages-with-google-domains-83bd5a4fbc5c){:target="_blank"}.

My site was live on my domain pretty much instantly after setting it up, and the SSL (which makes your site “secure”) gets set up within 24 hours.

# **In Conclusion**

I woke up yesterday wishing I could get a nice personal site up on my domain, and by the end of the day, I had exactly what I was hoping for without spending a dime! 

![](https://cdn-images-1.medium.com/max/2494/0*IGbKxWjKcMZEOtQm)

If you have any questions about setting up your GitHub Pages site or using the Flexible Jekyll theme, please leave me a comment! I typically respond within 24 hours and would be happy to help.

*This post was originally published on [Medium](https://medium.com/@rhiannonpayne/how-i-built-hosted-a-website-on-my-domain-for-free-github-pages-jekyll-theme-no-coding-7211a24c2a32){:target="_blank"}--be sure to follow and clap!*
