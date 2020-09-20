---
title: Contact us
sections:
  - type: hero_section
    title: Contact us
    subtitle: Drop us a message if you have any questions about the app
    align: center
    padding_top: medium
    padding_bottom: medium
    background_color: none
  - form_position: right
    form_layout: inline
    padding_top: medium
    align_vert: top
    form_width: fifty
    enable_card: true
    submit_label: Send Message
    background_color: primary
    form_fields:
      - type: form_field
        input_type: text
        name: name
        label: Name
        default_value: Your name
        is_required: true
      - type: form_field
        input_type: email
        name: email
        label: Email
        default_value: Your email address
        is_required: true
      - type: form_field
        input_type: select
        name: subject
        label: Subject
        default_value: Please select
        options:
          - Error on the site
          - Sponsorship
          - Other
      - type: form_field
        input_type: textarea
        name: message
        label: Message
        default_value: Your message
      - type: form_field
        input_type: checkbox
        name: consent
        label: I understand that this form is storing my submitted information so I can
          be contacted.
        is_required: true
    form_id: contact-form
    content: >-
      ### For workers


      Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec nisl ligula, cursus id molestie vel, maximus aliquet risus. Vivamus in nibh fringilla, fringilla.


      ### For donors


      Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec nisl ligula, cursus id molestie vel, maximus aliquet risus. Vivamus in nibh fringilla, fringilla.
    padding_bottom: medium
    type: form_section
    content_align: left
template: advanced
---
