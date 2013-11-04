jaggery-snippets
================

This is a **Jaggery.js** snippets collection for [Sublime Text (2|3)](http://www.sublimetext.com/). BTW, [Jaggery](http://jaggeryjs.org/) is a framework to write webapps and HTTP-focused web services for all aspects of the application: front-end, communication, Server-side logic and persistence in pure **Javascript**. Learn more from [jaggery API docs](http://jaggeryjs.org/documentation.jag)

## Install

To install through [Package Control](http://wbond.net/sublime_packages/package_control), in Sublime Text 2/3 press `⌘+shift+p` (or `ctrl+shift+p`), enter `Install Package`, and then search for **Jaggery Snippets**. If you still don't have Package Control in Sublime Text, [go get it](http://wbond.net/sublime_packages/package_control/installation).
It's pure awesomeness.

## Manual Setup

If you insist to not install [Package Control](http://wbond.net/sublime_packages/package_control), you can download the package and
put it manually inside your `Pacakages` directory. It should work but will not update automatically. See the instructions below.

### For Linux:

	git clone git@github.com:keheliya/jaggery-snippets.git \ 
	~/.config/sublime-text-2/Packages/jaggerySnippets

### For OSX

	$ cd ~/Library/Application\ Support/Sublime\ Text\ 2/Packages/
	$ git clone git://github.com/keheliya/jaggery-snippets.git jaggerySnippets

### For Windows

	$ cd %APPDATA%/Sublime Text 2/Packages/
	$ git clone git://github.com/keheliya/jaggery-snippets.git jaggerySnippets

## Available Snippets
* `new`: New jaggery snippet. Read more at [jaggery API docs](http://jaggeryjs.org/documentation.jag)
* `db`: Snippet for connecting to a relational database. Read more at [rdb.jag](http://jaggeryjs.org/apidocs/rdb.jag)
* `oauth`: Snippet for getting OAuth provider, authorization url. Read more at [oauth.jag](http://jaggeryjs.org/apidocs/oauth.jag)
* `oauthreq`: Snippet for accessing resources protected by OAuth. Read more at [oauth.jag](http://jaggeryjs.org/apidocs/oauth.jag)
* `config`: Creates new jaggery.conf file. Read more at [jagconf.jag](http://jaggeryjs.org/apidocs/jagconf.jag)
* `xhr`: XMLHttpRequest snippet for server side XML HTTP communication. Read more at [xhr.jag](http://jaggeryjs.org/apidocs/xhr.jag)