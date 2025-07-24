---
title: Papers and Articles
type: page          # or "landing" if you're using blocks on a landing page
cms_exclude: true

sections:
  # 1. Research first
  - block: collection
    id: research
    content:
      title: Research Papers
      text: "Essays on the economics of directed medical innovation."
      filters:
        folders:
          - papers-research      # path under content/
        exclude_featured: false  # optional
      order: desc                 # newest first (optional)
      count: 0                    # 0 = show all (optional)
    design:
      view: citation

  # 2. Op-Eds second
  - block: collection
    id: opeds
    content:
      title: Op-Eds
      #text: ""                  # add intro text if you want
      filters:
        folders:
          - papers-op-ed         # path under content/
      order: desc
    design:
      view: citation

# Optional header image (relative to static/media/)
banner:
  caption: ''
  image: ''
---

