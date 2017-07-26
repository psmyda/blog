---
layout:     post
title:      "How to fix WebEssentials in Visual Studio 2017"
subtitle:   ""
date:       2017-07-25 08:00:00
author:     "Piotr Smyda"
header-img: "img/posts/post2-bg.jpg"
comments: true
---

<p> WebEssentials is one of the most irreplaceable Visual Studio plugins. It's second on my list between 1) ReSharper and 3) ProductivityPowerTools and I really can't imagine front-end work without it.
Well I do but it will be painful.</p>

<p>After updating my Visual Studio to the latest '2017' version I've noticed issues with using WebEssentials - it literally prevent me from using the newest version of Microsoft's IDE.
There were problems with installation - it wouldn't event show up in Preferences (they fix it), and the browser toolbar went missing.
After a while I've decided to search for answers and here is my quick guide how to fix WebEssentials.</p>

<p>
According to this issue on GitHub: <a href="https://github.com/madskristensen/WebEssentials2017/issues/12">LINK</a> it won't work like in older Visual Studio versions. You need to do this:
<ol>
    <li>Install this Chrome extension: <a href="https://chrome.google.com/webstore/detail/web-essentials/mghdcdlpcdiodelbplncnodiiadljhhk">Chrome WebStore</a></li>
	<li>To get Inspect and Debug Mode install this additional extension in VisualStudio: <a href="https://marketplace.visualstudio.com/items?itemName=MadsKristensen.BrowserLinkInspector2017">VS Marketplace</a></li>
</ol>
</p>
