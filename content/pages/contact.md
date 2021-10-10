---
title: Contacto
hide_title: false
sections:
  - section_id: contact-form
    type: section_form
    content: >-
      Hola gracias por estar interesado en contactar conmigo rellene el formulario e intentaré contestarle en la menor
      brevedad.
    form_id: contactForm
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: Nombre
        default_value: Tu nombre
        is_required: true
      - input_type: email
        name: email
        label: Email
        default_value: Tu dirección de email
        is_required: true
      - input_type: select
        name: subject
        label: Tipo de consulta
        default_value: Por favor seleccione una
        options:
          - Error en el sitio Web
          - Encargo
          - Otra
      - input_type: textarea
        name: message
        label: Mensaje
        default_value: Tu mensaje
      - input_type: checkbox
        name: consent
        label: >-
          Entiendo que este formulario guarda mi información de contacto para posteriormente ser contactado.
    submit_label: Enviar mensaje
seo:
  title: JCodeR Photography Contacto
  description: Página de contacto de JCodeR Photography
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Página de contacto de JCodeR Photography
      keyName: property
    - name: 'og:description'
      value: Página de contacto de JCodeR Photography
      keyName: property
    - name: 'twitter:card'
      value: summary
    - name: 'twitter:title'
      value: Página de contacto de JCodeR Photography
    - name: 'twitter:description'
      value: Página de contacto de JCodeR Photography
layout: advanced
---
