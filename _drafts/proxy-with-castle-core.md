---
layout: post
title: Proxy with Castle Core
---

Happy new Persian year! This year due to the covid-19 pandemic we should stay at home on the Noruz holidays and it gives me a lot of free time. So I decided to start writing again. I'm hoping to keep writing during this new year and make it a routine. 

A few weeks ago my colleague Arash had a great lecture about proxy patterns and dynamic proxies using Castle, and I want to share what I learned from him with you guys.

Let’s start with the proxy design pattern. Proxy is a structural design pattern that lets you provide a substitute or placeholder for another object. A proxy controls access to the original object, allowing you to perform something either before or after the request gets through to the original object.<br/>
Assume a simple back account manager business object that handles basic operations like deposit, withdrawal, ... :