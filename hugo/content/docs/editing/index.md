---
aliases:
- /docs/managing-content/managing-content/
title: Managing Content
weight: 1
publishdate: 2017-12-31 04:00:00 +0000
expirydate: 2030-01-01 04:00:00 +0000
date: 2017-12-31 00:00:00 -0400
menu:
  docs:
    parent: editing
    weight: 1
layout: single
---
Forestry allows editors to manage their website in a variety of different ways. All of these enable developers to build powerful, static sites while empowering editors to take full control over the content.

TK: image

## Pages
The most basic type of content in Forestry is a page. Pages are any ungrouped content in your static site, such as an about page or contact page.

{{% tip %}}
In **Hugo**, pages are any [content files](/docs/faqs/glossary/content-files/) stored inside of the root of the `content/` folder.
In **Jekyll**, these are any [content files](/docs/faqs/glossary/content-files/) that are not part of a [Jekyll collection](https://jekyllrb.com/docs/collections/).
{{% /tip %}}

## Collections
Collections are grouped content in your static site. These are feeds or hierarchies of content, such as blog posts or landing pages.

{{% tip %}}
In **Hugo**, these are any folders inside of the `content/` folder, called [sections](https://gohugo.io/content-management/sections/).
In **Jekyll**, these are [content files](/docs/faqs/glossary/content-files/) that are part of a [Jekyll collection](https://jekyllrb.com/docs/collections/).
{{% /tip %}}

## Data Files
[Data files](/docs/editing/data-files/) are special content files that aren't rendered as HTML pages in your built site. They are used for adding rich metadata site-wide, like authors or company information.

{{% tip %}}
Learn more about using data files with [Hugo](http://gohugo.io/templates/data-templates/) and [Jekyll](https://jekyllrb.com/docs/datafiles/) in their documentation sites.
{{% /tip %}}

## Searching Content
Pages, collections, and data files can all be searched by the `title` field and by filename.

TK: image of search

## Futher Reading

- [Hugo, Content Management Docs](https://gohugo.io/content-management/)
- [Jekyll, Creating Pages](https://jekyllrb.com/docs/pages/)
- [Jekyll, Collections Docs](https://jekyllrb.com/docs/collections/)