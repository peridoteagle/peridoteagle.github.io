---
title: Teaching
summary: Courses and invited lectures
type: landing

cascade:
  - _target:
      kind: page
    params:
      show_breadcrumb: true

sections:
  - block: markdown
    content:
      title: Teaching
      subtitle: ""
      text: |-
        <div style="font-size: 0.95rem; line-height: 1.55;">
        <p>I teach practical, accessible material on data science and AI for students, educators, and community audiences.</p>
        <p>Below you'll find my university course and information about one-off classroom talks.</p>
        </div>
    design:
      columns: "1"
      spacing:
        padding: [0, 0, 1rem, 0]
  - block: collection
    id: teaching
    content:
      title: Courses and Talks
      filters:
        folders:
          - teaching
    design:
      view: article-grid
      columns: 2
      spacing:
        padding: [0, 0, 0, 0]
---
