---
use:
    - settings
title: Pantheon Settings Tool
description: Learn how to change your site's settings on Pantheon Website Management Platform.
keywords: settings, add credit card, add a card, credit card, select a plan, plan, plan levels, php version, how to change php version, toggle php, php
---
The Settings page allows you to view and manage your site's configurations. This includes the site's service level, billing, add ons, and PHP version.
<div class="panel panel-default">
    <div class="panel-heading" role="tab" id="headingTwo">
      <h4 class="panel-title">
        <a class="collapsed" role="button" data-toggle="collapse"  href="#collapseTwo" aria-expanded="false" aria-controls="collapseTwo">
          All Settings Docs
        </a>
      </h4>
    </div>
    <div id="collapseTwo" class="panel-collapse collapse" role="tabpanel" aria-labelledby="headingTwo">
      <div class="panel-body">
        {% for article in data.settings %}
        <a href="{{ article.url }}">{{ article.title }}</a><br>
        {% endfor %}
       </div>
    </div>
</div>


## About Site
View general information on the site by selecting the **About Site** tab.
![](/source/docs/assets/images/interface-site-settings-about.png)
## Plans
Here you can [select the site's plan](/docs/articles/sites/settings/selecting-a-plan). For more detailed information on service levels, see [plan comparison](https://pantheon.io/pricing-comparison).
## Add Ons
The **Add Ons** tab provides the ability to enable additional features, such as [New Relic](/docs/articles/sites/newrelic/), [Apache Solr](/docs/articles/sites/apache-solr/), and [Redis](/docs/articles/sites/redis-as-a-caching-backend/).
## Delete Site
See [Deleting a Site on Pantheon](/docs/articles/sites/deleting-a-site/).
## PHP Version
See [Toggling Between PHP Versions](/docs/articles/sites/settings/toggling-between-php-versions).
