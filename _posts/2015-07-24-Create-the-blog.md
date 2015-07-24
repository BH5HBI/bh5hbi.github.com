---
layout: post
title:  "Create the blog by jekyll!"
date:   2015-07-24 16:51:56
categories: jekyll
---

#install ruby
1.Download ruby installer from http://rubyinstaller.org/downloads/.

2.Download ruby devkit from http://rubyinstaller.org/downloads/.

3.Install ruby to c:\ruby, especially notice that you should check the checkbox to add the path to system path,during the installation. 

4.Unzip ruby devkit to c:\rubydevkit.

5.execute the commands:

		cd c:\rubydevkit	
		ruby dk.rb init
		ruby dk.rb install

6.install jekyll

		gem install jekyll

7.create the blog and commit to github
		
		F:
		mkdir F:\github
		cd github
		jekyll new BH5HBI
		...			//change title ,change parameters....
		git init
		git add .
		git commit -m "initial"
		git remote set-url origin git@git.com/....
		git push origin master
