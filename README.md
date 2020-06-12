# Edition

Product documentation template for Jekyll. Browse through a [live demo](https://long-pig.cloudvent.net/).
Start documenting your product, application, service or website with this configurable theme.

![Edition template screenshot](images/_screenshot.png)

Edition was made by [CloudCannon](http://cloudcannon.com/), the Cloud CMS for Jekyll.

Find more templates, themes and step-by-step Jekyll tutorials at [CloudCannon Academy](https://learn.cloudcannon.com/).

## Features

* Two column layout
* Full text search
* Pre-styled components
* Auto-generated navigation based on category
* Optimised for editing in [CloudCannon](http://cloudcannon.com/)
* Change log
* RSS/Atom feed
* SEO tags
* Google Analytics

两列布局
全文搜索
预先样式化的组件
根据类别自动生成的导航
针对CloudCannon中的编辑进行了优化
变更记录
RSS / Atom提要
SEO标签
谷歌分析


## Setup

1. Add your site and author details in `_config.yml`.
2. Get a workflow going to see your site's output (with [CloudCannon](https://app.cloudcannon.com/) or Jekyll locally).

1.在“ _config.yml”中添加您的站点和作者详细信息。
2.获得一个工作流，以查看您站点的输出（使用[CloudCannon]（https://app.cloudcannon.com/）或本地的Jekyll）。

## Develop

Edition was built with [Jekyll](http://jekyllrb.com/) version 3.3.1, but should support newer versions as well.

Install the dependencies with [Bundler](http://bundler.io/):

~~~bash
$ bundle install
~~~

Run `jekyll` commands through Bundler to ensure you're using the right versions:

~~~bash
$ bundle exec jekyll serve
~~~

## Editing

Edition is already optimised for adding, updating and removing documentation pages in CloudCannon.
该版本已经过优化，可以在CloudCannon中添加，更新和删除文档页面。

### Documentation pages

* Add, update or remove a documentation page in the *Documentation* collection.
* Change the category of a documentation page to move it to another section in the navigation.
* Documentation pages are organised in the navigation by category, with URLs based on the path inside the `_docs` folder.
*在* Documentation *集合中添加，更新或删除文档页面。
*更改文档页面的类别，以将其移至导航的另一部分。
*文档页面在导航中按类别进行组织，URL基于`_docs`文件夹中的路径。

### Change log

* Add, update or remove change log entries from your posts.
* Tag entries as minor or major in the front matter.

### Search

* Add `excluded_in_search: true` to any documentation page's front matter to exclude that page in the search results.

### Navigation

* Change `site.show_full_navigation` to control all or only the current navigation group being open.
