---
title: Join our waitlist
sections:
  - media_position: top
    align: left
    padding_top: medium
    media_width: fifty
    background_image_repeat: no-repeat
    has_border: false
    background_color: secondary
    background_image_size: cover
    subtitle: ""
    title: Join our waitlist
    content: If you're a migrant worker and you're interested in using the app, fill
      in this form! We will let you know as soon as we open it up to more users.
    padding_bottom: medium
    type: hero_section
    background_image_position: center center
  - form_position: bottom
    form_layout: stacked
    padding_top: medium
    align_vert: top
    form_width: fifty
    enable_card: false
    submit_label: Submit
    background_image_repeat: no-repeat
    has_border: false
    background_color: none
    form_fields:
      - is_required: true
        type: form_field
        input_type: text
        name: name
        label: Your name
        default_value: e.g. Abdul
      - is_required: true
        type: form_field
        input_type: tel
        name: mobile
        label: Your mobile number
        default_value: "91234567"
      - is_required: true
        type: form_field
        input_type: select
        name: country
        label: Are you from Bangladesh?
        options:
          - Yes
          - No
        default_value: ""
      - is_required: true
        type: form_field
        input_type: number
        name: years
        label: How many years have you been in Singapore?
        default_value: ""
    background_image_size: cover
    form_id: waitlist
    padding_bottom: medium
    type: form_section
    title_align: left
    background_image_position: center center
    content_align: left
template: advanced
---
