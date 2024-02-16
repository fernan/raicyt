---
title: 'Start'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: RAICyT
      text: Argentina's Network of Authorities of Science and Technology Institutions
      primary_action:
        text: Meet us
        url: about
        icon: rocket-launch
      secondary_action:
        text: Read our documents
        url: documents
      announcement:
        text: "Urgent Announcements."
        link:
          text: "Read"
          url: announcements
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "dark"
      background:
        image:
          # Add your image background to `assets/media/`.
          filename: bg-bandera-AR.svg
          filters:
            brightness: 0.8
  - block: stats
    content:
      items:
        - statistic: "340+"
          description: |
            Autoridades  
            de Institutos de Ciencia
        - statistic: "20k+"
          description: |
            Personas formadas en CyT  
            desde YYYY
        - statistic: "3k+"
          description: |
            Comunidad extendida 
            de Cientificos, Educadores,
            Estudiantes        
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
      # Reduce spacing
      spacing:
        padding: ["1rem", 0, "1rem", 0]
  - block: testimonials
    content:
      title: ""
      text: ""
      items:
        - name: "Bernardo Houssay"
          role: "Nobel Prize in Medicine, 1947"
          # Upload image to `assets/media/` and reference the filename here
          image: "testimonial-houssay.jpg"
          text: "Science is not expensive, expensive is ignorance."
        - name: "Luis Federico Leloir"
          role: "Nobel Prize in Chemistry, 1970"
          text: "A scientific mind is always curious, always questioning."
          image: "testimonial-leloir.jpg"
        - name: "Jorge Sahade"
          role: " Presidente de la Unión Astronómica Internacional, 1986."
          text: "Support for basic science, on which applied science and technology are based and nourished, is undoubtedly the only investment that will yield a modern, efficient, and decision-autonomous Argentina."
          image: "testimonial-sahade.png"
        - name: "Cesar Milstein"
          role: "Nobel Prize in Medicine, 1984"
          image: "testimonial-milstein.jpg"
          text: "Science will only fulfill its promises when the benefits are equally shared by the really poor of the world"
  # - block: collection
  #   id: posts
  #   content:
  #     title: Recent Posts
  #     subtitle: ''
  #     text: 🧱 Under construction 🧱
  #     # how many pages to display (0 = all pages)
  #     count: 3
  #     filters:
  #       # the folders to display content from
  #       folders:
  #         - en/post
  #       author: ""
  #       category: ""
  #       tag: ""
  #       publication_type: ""
  #       featured_only: false
  #       exclude_featured: false
  #       exclude_future: true
  #       exclude_past: false
  #     # how many pages we would like to offset by
  #     offset: 0
  #     # field to sort by, such as Date or Title
  #     sort_by: 'Date'
  #     sort_ascending: false
  #     design: 
  #       # choose a listing view
  #       view: card
  - block: cta-image-paragraph
    id: solutions
    content:
      items:
        - title: Social Networks
          text: Join our digital network activities - amplify and add your voice
          # Upload image to `assets/media/` and reference the filename here
          image: redes-raicyt.png
          feature_icon: bolt
          features: 
            - "[Read us in Facebook](https://www.facebook.com/RAICYT)"
            - "[Follow us in X / Twitter](https://twitter.com/RAICYT_Ar)"
            - "[Look at our Instagram](https://instagram.com/raicyt_argentina)"
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"  
---
