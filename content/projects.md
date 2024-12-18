---
title: 'Projects'
date: 2024-05-19
type: landing

design:
  # Section spacing
  spacing: '5rem'

# Page sections
sections:
  - block: collection
    content:
      title: Selected Projects
      text: I enjoy making things. Here are a selection of projects that I have worked on over the years.
      filters:
        folders:
          - project
    design:
      view: compact
      #fill_image: false
      #columns: 1
  - block: collection
    content:
      title: Featured Project
      text: This is a highlighted project demonstrating detailed traffic flow modeling.
      items:
        - title: Traffic Flow Modeling
          date: 2024-04-01
          external_link: https://github.com/pandas-dev/pandas
          tags:
            - Python
            - Mathematics
            - Simulation
          summary: |
            Developed and implemented traffic flow models, including cellular automata, car-following models, and PDEs to simulate realistic traffic dynamics. Optimized parameters to reduce congestion.
    design:
      view: compact
---
