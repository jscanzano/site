---
title: Publications
type: landing

sections:
  - block: collection
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: card

  - block: collection
    content:
      title: All Publications
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      view: date-title-summary
---