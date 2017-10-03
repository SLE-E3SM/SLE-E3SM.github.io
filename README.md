# Overview

This is the official DOE ProSPect website, hosted on GitHub.  It's web address is [https://doe-prospect.github.io/](https://doe-prospect.github.io/).

# Usage

ProSPect members should feel free to directly modify the master branch as they see fit.  One easy way to do this is via [web-based editing and committing](https://help.github.com/articles/editing-files-in-your-repository/).  If error-free, your edits will be automatically incorporated into the website, generally within a few seconds.

# Layout

The site is based on [Jekyll](https://github.com/jekyll/jekyll), which is a Github-supported static site generator.  Main pages are written in [Markdown](https://guides.github.com/features/mastering-markdown/) (.md).  You can use Markdown or HTML/CSS in these files, they're pretty flexible. 

```\_config.yml.```

The landing page is index.md.

Additional pages are added as follows:

1) Create and commit a new .md file (online or via local clone/create/commit/push).
2) Add YAML header to top of file (see existing .md files), including a permalink ID for the page.
3) If you want your page appearing on the top banner, in \_layouts/default.html, being careful about upper/lower cases, add: 
```<a href="{{ site.baseurl }}/[YOURPAGENAME]">[YOURPAGENAME]</a>.```
