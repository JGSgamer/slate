---
title: JGSplayz Docs

toc_footers:

language_tabs: # must be one of https://git.io/vQNgJ

includes:

search: true
---

# Introduction

This guide will learn you how to install, update and manage your Minecraft server.

# Authentication

Start by visiting [GetBukkit](https://getbukkit.org/download/spigot) and downloading your desired version of Spigot.

Next,  create a folder and place the downloaded file in it.

After you did that, create a file named `start.bat` and paste in the following code:

```basic
java -Xms1G -Xmx1G -jar FileNameHere.jar
PAUSE
```

<aside class="notice">

* You must replace `FileNameHere.jar` with the name of the jar you downloaded from GetBukkit. 
* You can change `-Xms1G` and `-Xmx1G` to the amount of ram you'd like to allocate.

</aside>

After that, save the file and make sure it is `start.bat` and **not** `start.bar.txt`, if that's correct you have to double click the `start.bat`. A couple files will be generated in the server folder, one of them being `eula.txt`. Open that file and change `eula=false` to `eula=true`.

If you did that, you'll have to double click the `start.bat` file again and you should have a server up and running.

