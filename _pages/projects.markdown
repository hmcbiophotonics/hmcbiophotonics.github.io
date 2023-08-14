---
title: Projects
layout: collection
permalink: /projects/
collection: projects
entries_layout: list
author_profile: false
show_excerpts: false
---

<section class="page__content cf">
  <div class="entries-{{ page.entries_layout }}">
    {% include documents-collection.html entries=site.projects sort_by=page.sort_by sort_order=page.sort_order type=page.entries_layout %}
  </div>
</section>

