---
layout:     post
title:      "Updating npm packages in project"
subtitle:   "Conquer this mess!!"
date:       2017-08-11 08:00:00
author:     "Piotr Smyda"
header-img: "img/posts/post3-bg.jpg"
comments: true
---

<p>Keeping up with JS projects packages is hard but not with <strong>npm</strong>.
<p>Every time I need to check if there are newer version for projects dependencies or have to update because of some important feature changes I do this:
<br>
1st let's check what packages versions we have in a project:
<br><br>
<code>npm outdated</code>
<br><br>
This will generate a list of all packages that are currently installed, their current and latest versions. From that list we can go to updating.
<br>
There are few ways we can take to complete update.
<br>
To update all dependencies in a project at once we can just run
<br><br>
<code>npm update --save</code>
<br><br>
<i>There was a bug that duplicated devDependencies - I believe it is fixed but If you have problems with this simple command you can use </i>
<br><br>
<code>npm update -D && npm update -S</code>
<br><br>
Second option is to just update packages one by one using:
<br><br>
<code>npm i <i> {package-name}</i> --save</code>
<br><br>
Remember to add <code>--save</code> parameter to persist changes in package.json file.<br>
Also you can always specify package version you want to install by placing its number after "@" sign like this:
<br><br>
<code>npm i <i> express@3.0.0</i> --save</code>
<br><br>

