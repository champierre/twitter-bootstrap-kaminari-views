# HAML Version with disabled arrow signs.

Based on HAML Version done by [konung](https://github.com/konung/twitter-bootstrap-kaminari-views) - Arrow signs for previous/next page navigation are disabled instead of being hidden, so that the whole length of pagination does not change.

![1](https://cloud.githubusercontent.com/assets/10215/26144025/39c3068e-3b22-11e7-91b9-b84408c27b59.png)

![2](https://cloud.githubusercontent.com/assets/10215/26144030/3b1878a2-3b22-11e7-9466-df041b91fdbb.png)

Original work done by [gabetax](https://github.com/gabetax/twitter-bootstrap-kaminari-views)

# Kaminari views for Twitter Bootstrap

[twitter bootstrap](https://github.com/twitter/bootstrap) is a toolkit from Twitter designed to kickstart development of webapps and sites, including styles for [pagination](http://twitter.github.com/bootstrap/#navigation).  If you're using [kaminari](https://github.com/amatsuda/kaminari) as your pagination library, the markup in its default views won't match the selectors used by bootstrap.  This repository contains modified copies of kaminari's views that you can drop in to your ruby application to work with bootstrap.

## Installation
1. Copy app/views/kaminari into your local Rails app/views folder.
2. Copy config/locales/*.yml into your local Rails config/locales folder.

## Compatibility
These views were tested with kaminari 0.14.1 and bootstrap v3.0.0.
