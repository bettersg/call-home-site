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
  - actions_width: sixty
    align: left
    padding_top: medium
    actions_position: right
    background_image_repeat: null
    has_border: false
    background_color: primary
    background_image_size: null
    title: " কর্মীদের জন্য For workers"
    content: সাহায্য দরকার? আমাদের ফেসবুকে পৌঁছে দিন। Need help? Reach us at Facebook.
    padding_bottom: medium
    type: cta_section
    actions:
      - style: primary
        has_icon: true
        icon_position: left
        new_window: true
        type: action
        label: যাও Facebook page
        url: https://www.facebook.com/
        icon: facebook
    background_image_position: null
  - form_position: right
    form_layout: inline
    padding_top: medium
    align_vert: top
    form_width: fifty
    enable_card: true
    submit_label: Send Message
    background_color: secondary
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
      ### For donors


      Questions about the app or the campaign? Interested in corporate sponsorships? Email us or fill in the form here.
    padding_bottom: medium
    type: form_section
    content_align: left
template: advanced
---
