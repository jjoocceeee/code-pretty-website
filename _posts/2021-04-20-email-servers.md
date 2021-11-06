---
layout: post
title: "Why the Contact me button on your website is a mistake --- and how to fix it."
subtitle: "HTML email tag is NOT the way to go when adding a Contact button on your website. Instead write a custom email server."
date: 2021-01-31 10:45:13 -0400
background:
thumbnail:
publish: false
---

Do you have a website? Is there a contact form on your website? Does this contact form send you an email? Is it written like this
```html
<a href = "mailto: your_email@website.com">Send Email</a>
```

If that is the case, you are doing it wrong....
Okay, wrong may be a strong word, but you are definetly compromising your email address.

Don't you hate those junk emails you get sent where you think "What email list did I sign up for? Why did I get this email? I get so many junk emails!"

One reason you are asking yourself those questions is because you DO actually sign up for random email lists. Another reason though, is that your email address was scraped by a bot, and sold on an email list. 

Just think of how easy it would be to write a bot that just searches the HTML of websites and saves any email addresses it finds (Note to self - This sounds really fun to make!).

So what should you do instead? How do you allow people to contact you, while protecting your email, and not have to pay for a service of some kind....

A simple solution is to write your own Email Server.