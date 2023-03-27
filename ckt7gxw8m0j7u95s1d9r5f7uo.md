---
title: "What is Semantic HTML? 🤨"
datePublished: Sun Sep 05 2021 17:08:07 GMT+0000 (Coordinated Universal Time)
cuid: ckt7gxw8m0j7u95s1d9r5f7uo
slug: what-is-semantic-html
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1630796584054/StrJ0W5zQ.png
tags: frontend, web-development, webdev, html5, frontend-development

---

What's goooooood, coders! 😎 I've been crazy busy with homework for my Computer Science classes, but I wanted to talk about an important topic I've come across in my self-taught frontend journey: **semantic HTML!** 😍😍😍

<iframe src="https://giphy.com/embed/26BRL3pw98MWNOy0U" width="380" height="199" class="giphy-embed"></iframe>

### Table of Contents 🤩

* #### [`Wtf is 'Semantic HTML' 🤯`](#wtf)
    
* #### [`More Easily Readable Code 🤗`](#readability)
    
* #### [`Increasing Accessibility 😋`](#accessibility)
    
* #### [`Using Semantic HTML Tags Correctly 🕺`](#correctly)
    

---

### What exactly is 'Semantic HTML'? 🤯

Good question 😉 let me break it down for ya: **to write semantic HTML is to use elements in the *correct way*!**

A **semantic element** clearly describes its content *(between the tags)* to both the browser AND the developer. 🚫 Simply using div's for your header, navbar, footer, sections, etc. is not good practice! 🚫

<iframe src="https://giphy.com/embed/kEYsX3m6rzGP7d3WJe" width="380" height="200" class="giphy-embed"></iframe>

Let me elaborate further: when creating a *header* for your website/portfolio, some programmers might write them as: `<div class='header>` , `<div id='header'>`, `<div class='head'>` or simply `<div>`. (Or you can just use `<header>` 😉 ).

There are *so many ways* you could create a header element, and it *does* depend on the personal preference on the programmer...😜 **BUT** by creating a standard semantic element that's *consistent throughout your entire project*, it makes your code more readable and helps with debugging!

---

### More Easily Readable Code w/ Semantic HTML 😋

Take a look at the block of code below ⬇️

Notice all the `<div>`'s?

```plaintext
<div id="header"></div>
<div class="section">
	<div class="article">
		<div class="figure">
			<img>
			<div class="figcaption"></div>
		</div>
	</div>
</div>
<div id="footer"></div>
```

Now take a look at this block of code below ⬇️

```plaintext
<header></header>
<section>
	<article>
		<figure>
			<img>
			<figcaption></figcaption>
		</figure>
	</article>
</section>
<footer></footer>
```

Do you see how I replaced all the `<div>`'s from the first block of code to their corresponding semantic tag? 🧐

**Look how much easier the 2nd block of code is to read!** 😎 This is a super small example, but as a programmer you could be reading through hundreds/thousands lines of code... the easier it is to read and understand that code, the easier it makes your job!

➡️ *For example:* using the tag `<div>`, there are multiple ways to create a header element, versus just using `<header>` consistently every time! Semantic HTML elements === consistent code 😍

<iframe src="https://giphy.com/embed/Is1O1TWV0LEJi" width="380" height="170" class="giphy-embed"></iframe>

---

### Increase Accessibility with Semantic HTML Tags🤯

**More easily accessible webpage for your users AND search engines!** 😎

For *sighted users*, it’s easy to identify each part of a website. Form elements, headers, footers, and menus are all visually apparent.

*BUT*, for bots like Google’s spiders (before you make a Google search, these web crawlers gather information from hundreds of billions of webpages and organize it in the Search index), or a screen reader, these visual semantics aren’t as obvious.

By defining block-level elements with *semantic elements*, we can communicate to the search engines & screen readers what the elements are, so they can render them appropriately! 😛 Cool, right?

➡️ *Here's an example:* we don't declare italic elements with an `<i>` for *italics* anymore, (which is a purely visual change, without intrinsic meaning) but with an `<em>`, for *emphasize.*

On the screen, the browser will display text wrapped in an `<em>` in italics. But, on an audio device for the visually impaired, the text will be pronounced with a corresponding emphasis, just like a friend would say it. 😊❤️

<iframe src="https://giphy.com/embed/z1Ss4CmBlWbUcn9YRs" width="380" height="190" class="giphy-embed"></iframe>

---

### Using Semantic HTML Tags Correctly 🤩

So, now that you know the basics of Semantic HTML tags, I bet you're ready to see them in action 😎 Below is a cheatsheet I've created to compare an incorrect HTML layout design with the *semantically correct* layout design:

![htmllayout.jpeg](https://cdn.hashnode.com/res/hashnode/image/upload/v1630795051989/ljYyrmHUE.jpeg align="left")

Which one reminds you of your code? 😏

<iframe src="https://giphy.com/embed/B9KKBuOIp4zqI7Cll0" width="380" height="180" class="giphy-embed"></iframe>

Now, let's take a look at an example of a semantically correct webpage layout ⬇️

![semanticchart2.jpeg](https://cdn.hashnode.com/res/hashnode/image/upload/v1630794997889/oKnWz5zR4.jpeg align="left")

I bet you're thinking "But, Layla...how will I know when to use *which* semantic HTML tag to use *and when?*". Well, my friend, I have **THE GOLDEN FLOWCHART**! Check it out below ⬇️

![semanticchart.jpeg](https://cdn.hashnode.com/res/hashnode/image/upload/v1630794901467/u8q0JVXe_.jpeg align="left")

<iframe src="https://giphy.com/embed/26FLdmIp6wJr91JAI" width="380" height="170" class="giphy-embed"></iframe>

---

# YOU'RE DONE! 🥳🥳🥳

<iframe src="https://giphy.com/embed/U4DswrBiaz0p67ZweH" width="380" height="170" class="giphy-embed"></iframe>

I'll be creating more Hashnode blog posts about frontend development as I go through my self-taught frontend journey --if you enjoyed this post, follow me here on [Hashnode](https://hashnode.com/@laylacodes) and on [Twitter!](https://twitter.com/pilatesdev) ❤️❤️ also feel free to save these cheat sheets in this article! I've made them for anyone who needs them 🥰🥰

DM me on Twitter or leave a comment if you get confused about any of these! 😜