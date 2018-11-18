---
layout: post
comments: true
title:  "CSS Pre-processors"
date:   2018-11-17 20:52:23 +0100
categories: blog posts
author: Sylvester Norrbjörk
---
Think pre-processing the CSS code helps keeps things tidy and organized.
With CSS you end up having to repeat lines of code again again, especially paths to elements. CSS pre-processors solve this by letting you nest elements. I used this technique to allow to set CSS properties at different levels without  having to create separate code blocks for each element. 

This can also become a slight disadvantage though; if you create complicated nested syntaxes it can become a little hard to understand exactle what is being affected by the CSS properties.

Another good thing about CSS pre-processors is possibility to use variables. This again helps keep things tidy and allows one to easily reuse variable throughout the file. I for example used variables for my colors, that makes it easier to set certain colors that were repeated, instead of having to write the RGB color codes again and again. 

Another advantage to CSS pre-processors is the ability to combine multiple stylesheets into one. The disadvantage to this is that it can be a little hard to troubleshoot the CSS code since the final generated CSS on the website isn't the actual physical CSS file so the actual code and line numbers would be different. There are workarounds for this though.

The are more advantages to using CSS pre-processors, but I will only mention one final advantage to not make this post too long; CSS pre-processing allows you to write less code and save time.
