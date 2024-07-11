---
layout: layouts/right
title: Breadcrumb
tags: patterns
summary:

include: "{% include 'patterns/breadcrumb/breadcrumb.md' %}"
---

## Design
{% include 'patterns/breadcrumb/breadcrumb.md' %}

## Theme Settings
-  $theme-breadcrumb-background-color
-  $theme-breadcrumb-font-family 
-  $theme-breadcrumb-font-size 
-  $theme-breadcrumb-link-color
-  $theme-breadcrumb-min-width
-  $theme-breadcrumb-padding-bottom
-  $theme-breadcrumb-padding-top 
-  $theme-breadcrumb-padding-x 
-  $theme-breadcrumb-separator-color
  

### Variants
To wrap instead of truncating use `.usa-breadcrumb--wrap`

## Nex+ Library prototyping notes
The breadcrumb pattern was configured to pull in the breadcrumb parents based on the URL. You can use by including this code:

```markdown
{{ include }}
```