---
title: 'Inicio'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: RAICYT
      text: Red Argentina de Autoridades de Institutos de Ciencia y Tecnología 
      primary_action:
        text: Conocenos
        url: acerca
        icon: rocket-launch
      secondary_action:
        text: Lee nuestros documentos
        url: documentos
      announcement:
        text: "Anuncios."
        link:
          text: "Ver"
          url: anuncios
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "dark"
      background:
        image:
          # Add your image background to `assets/media/`.
          filename: bg-triangles-raicyt.svg
          filters:
            brightness: 0.8
  - block: stats
    content:
      items:
        - statistic: "340+"
          description: |
            Autoridades  
            de Institutos de Ciencia
        - statistic: "17k+"
          description: |
            Personas formadas en CyT  
            desde 2018
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
          role: "Premio Nobel de Medicina, 1947"
          # Upload image to `assets/media/` and reference the filename here
          image: "testimonial-houssay.jpg"
          text: "La ciencia no es cara, cara es la ignorancia."
        - name: "Luis Federico Leloir"
          role: "Premio Nobel de Química, 1970"
          text: "Una mente científica es siempre curiosa, siempre cuestiona."
          image: "testimonial-leloir.jpg"
        - name: "Jorge Sahade"
          role: " Presidente de la Unión Astronómica Internacional, 1986."
          text: "El apoyo a la ciencia básica en la cual se fundamentan y de la cual se nutren la ciencia aplicada y la tecnología es, sin lugar a dudas, la única inversión que redituará en una Argentina moderna, eficiente y autónoma en sus decisiones."
          image: "testimonial-sahade.png"
        - name: "Cesar Milstein"
          role: "Premio Nobel de Medicina, 1984"
          image: "testimonial-milstein.jpg"
          text: "La ciencia solo va a cumplir su prometido cuando los beneficios sean equitativamente compartidos por los verdaderamente pobres del mundo"
  # - block: collection
  #   id: anuncios
  #   content:
  #     title: Anuncios Recientes
  #     subtitle: ''
  #     text: 🧱 Under construction 🧱
  #     # how many pages to display (0 = all pages)
  #     count: 2
  #     filters:
  #       # the folders to display content from
  #       folders:
  #         - anuncios
  #       featured_only: false
  #       exclude_featured: false
  #       exclude_future: false
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
        - title: Redes Sociales
          text: Unite a nuestras actividades en redes - amplificá y hacé tu aporte
          # Upload image to `assets/media/` and reference the filename here
          image: redes-raicyt.png
          feature_icon: bolt
          features: 
            - "[Leenos en Facebook](https://www.facebook.com/RAICYT)"
            - "[Seguinos en X / Twitter](https://twitter.com/RAICYT_Ar)"
            - "[Mirá nuestro Instagram](https://instagram.com/raicyt_argentina)"
          button:
            text: Unite a nuestro grupo de Difusión
            url: comisiones/difusion
            icon: bolt
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"  
---
