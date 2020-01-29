---
title: Uploading and Deleting Using NodeJs fs
path: /uploading-and-deleting-using-fs
date: 2019-01-28
summary: Learn how to add and delete files to server using fs
tags: ['NodeJs']
---

![background](./images/blog_bg_1.jpg)


> Fs is a NodeJs library that handles all binary. It may seem hard at hard but its quite easy. It does its operations synronously.

### Getting Started
Open up an express server like so and add the following. You won't need to add anything else. The fs library comes packaged with NodeJs

```js
const express = require("express");
const app = express();
const fs = require("fs")

app.get("/", (req, res) => {
	res.send("Home")
})


app.listen(8080, () => {
	console.log("App running on port 8080")
})

```

After setting up, open up the browser and open up the localhost:8080 to ensure everything is working fine.