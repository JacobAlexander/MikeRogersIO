---
layout: post
title: How to validate an email address with PHP
tags:
- PHP
status: publish
type: post
published: true
categories:
 – blog
meta:
  description: 'A method of validating emails in PHP without regex.'
  index: true
---
Validating an email address is a great way to reduce spam on your website, but there are several methods to do it. You could use a messy regex approach or alternatively you could also use PHP built in functions, it's really up to you. Here is the function I use:

{% gist 2941972 validate-email.php %}
