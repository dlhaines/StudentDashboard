
# UMich Student Dashboard Repository

This code is kept in github and will be public for the whole world to see forever.

# Implementation

This server implements both a single page UI and a Rest API.  The Rest api can be used
independenly if that is appropriate.  It assumes that authentication has
already been done and the request object has a valid value for REMOTE_USER.

The server is implemented using Ruby Sinatra.

It is packaged into a war file along with
JRuby 1.7 (implementing Ruby 1.9.3).  It is expected to run within
Tomcat 7.

# Building the project

In the top level directory run to get dependencies:

	bundle install
	warble

This is easiest if you have rvm installed. It will great the war file.

#Organization

The UI and backend Server are kept in corresponding directories.  The
top level directory contains the configuration required to build the
war file.

---
This readme file is written with Markdown.
See this link for information on Markdown: https://help.github.com/articles/markdown-basics
