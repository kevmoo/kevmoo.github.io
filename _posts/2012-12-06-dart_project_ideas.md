---
title: Dart project ideas
layout: post
tags: dart
---

# Tools
Things to help with Dart development.

## Live dartdoc
A way to live-edit code annotations and see the results immediately. Point a tool at a specific source file. Starts a local http server. File changes to the file auto-magically refresh the page.

* Plans for incremental build in dartdoc?

## Auto Changelog
Given two git commits in a Dart project, use mirror magic to see what's changed.
* New classes
* New members
* New optional arguments
* Deletions, renames, things marked obsolete -- flagged as BREAKING
One could then generate a detailed changelog with pointers to the right commits.

One could get really creative and support a commit syntax convention to pull helpful notes into the changelog.

# hop-related
Tools to plug into hop from the [Dart Bag-of-Tricks](https://github.com/kevmoo/bot.dart).

## Notes
Scan a project for specific code comments and print the result.

Usage: hop notes
Usage: hop notes:todo (Need to figure out subtask/namespace model for hop, first.)
* // NOTE:
* BUGBUG
* DARTBUG
* TODO

Inspired by [rake notes](http://siong1987.com/posts/powerful-and-hidden-rake-notes-in-rails/) from Rails.