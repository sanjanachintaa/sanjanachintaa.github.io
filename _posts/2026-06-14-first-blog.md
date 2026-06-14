---
title: "First Blog"
date: 2026-06-14 00:00:00 +0000
categories: [Tech]
tags: [intro]
---

Here's the updated version with Step 1.5 added:

---

Hello!
This is my first blog post!
This post was originally about to be an introduction to me, Sanjana Chinta. Hii !! I am a cybersecurity student at FAMT, Ratnagiri expected to graduate in 2028. As im entering my 3rd year where the real magic about cybersecurity starts, i decided to document my journey in learning as much as i can about this domain as someone who is starting from ground zero. When i picked this course back in 2024 after my 12th, Cybersecurity seemed to be a fascinating and interesting domain. And i just hope it lives up to my expectations!
Earlier i said this was originally supposed to be my introductory post but this kind of wrote itself. sighs
Today i wrestled with multiple softwares like Ruby, Gem, Jekyll etc trying to configure my website for posting these blogs using github pages. I followed a particularly frustrating youtube video and well....? I fought tooth and nail for 5 hrs straight. I have a tendency to not get up from my seat if any computer related tasks aren't finished. Well this toxic trait of mine had been fruitful indeed.
Join me as i explain to you how ridiculously easy it is to set up your own website using github pages.

**Step 1:** Go to this link to use the jekyll chirpy theme:
https://github.com/cotes2020/chirpy-starter

Hit **"Use this template"** in the green box and create your own repo. Name it as:
`your-username.github.io`

Create the repo, then click **Actions** from the banner and wait a few seconds as your website is built and deployed.

**Step 1.5:**  Go to **Settings → Pages → Build and Deployment → Source** and select **"GitHub Actions"**. This tells GitHub to use the built in workflow to deploy your site instead of a branch.

**Problems I ran into:** This is where i strayed toward installing Jekyll and Ruby locally and cloning the repo locally and fighting with incompatible versions. However as it turns out, there was no need to do anything locally.

**Step 2:** Under the `_posts/` folder in the repo create a file in this exact format:
`YYYY-MM-DD-file-name.md`
example: `2024-01-02-setting-up-jekyll-chirpy-blog.md`

MAKE SURE it is directly inside `_posts/` only — no subfolders!

Now you are ready to start writing your first blog. Click on the `.md` you just made and hit the pencil option on the top right to edit it. Add your info like this:

```
---
title: "Hello World"
date: 2024-01-01 00:00:00 +0000
categories: [Tech]
tags: [intro]
---
start writing here
```
also ensure that the date in the file matches the date in the front matter.

**Step 3:** Once you are finished you can commit changes. Now you can either wait a couple minutes or go to the Actions tab again to stare at github "cooking" like you stare into the microwave while it finishes baking.

Refresh the website and if all goes well...HEY PRESTO!! there it is, your first blog for the world to see.

This has been fun. I hope to be back in a while to write another one.

toodles!
(...andddd commit changes!!)
