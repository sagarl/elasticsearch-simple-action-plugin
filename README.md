elasticsearch-simple-action-plugin
==================================

A simple action plugin for Elasticsearch

The simple plugin is indeed very simple. It makes reuse of the standard search action:

- it defines a built-in query (a "match all" query)

- it creates a custom action for it

- the action is called from Java API

- the result of the action (the search response of the "match all" query) is logged

http://code972.com/blog/2014/05/72-the-ultimate-guide-for-elasticsearch-plugins-video-slides

Reference : https://groups.google.com/forum/?utm_medium=email&utm_source=footer#!topic/elasticsearch/VaiLBJkz-20
