---
title: Contact
hide_title: false
sections:
  - type: form_section
    section_id: contact-form
    content: >-
      Have a different question or want to contact us directly? Please feel free to let us know.


      ***


      ## Our Office


      ### Nairobi

      P. O. Box 0740128010<br>

      Nairobi, Kenya<br>

      +254-(0)-740-128-010
    form_id: contactForm
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: Name
        default_value: Your name
        is_required: true
      - input_type: email
        name: email
        label: Email
        default_value: Your email address
        is_required: true
      - input_type: select
        name: subject
        label: What services are you looking for?
        default_value: Please select
        options:
          - Brand Design
          - Experience Design
          - Social Media Management
      - input_type: textarea
        name: message
        label: Message
        default_value: Your message
      - input_type: checkbox
        name: consent
        label: >-
          I understand that this form stores my submitted information so I
          can be contacted.
    submit_label: Send Message
seo:
  title: Contact - Sawac Studio
  description: Get in touch with us for a custom design.
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Contact - Sawac Studio
      keyName: property
    - name: 'og:description'
      value: Get in touch with us for a custom design.
      keyName: property
    - name: 'twitter:card'
      value: summary
    - name: 'twitter:title'
      value: Contact - Sawac Studio
    - name: 'twitter:description'
      value: Get in touch with us for a custom design.
layout: advanced
---
