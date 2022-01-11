---
title: Contact
menu: Contact
forms:
    contact:
        keep_alive: true
        classes: reveal-content
        enabled: true # see https://github.com/getgrav/grav-plugin-form/issues/537

        fields:
            - name: email
              label: Email
              placeholder: Email
              autocomplete: email
              type: email
              outerclasses: form-group
              display_label: false
              classes: form-control
              attributes:
                aria-label: Email
              validate:
                required: true

            - name: subject
              label: Subject
              placeholder: Subject
              type: text
              outerclasses: form-group
              display_label: false
              classes: form-control
              attributes:
                aria-label: Subject
              validate:
                required: true

            - name: message
              label: Message
              placeholder: Enter your message
              type: textarea
              outerclasses: form-group
              display_label: false
              classes: form-control
              attributes:
                aria-label: Message
              rows: 3
              validate:
                required: true

        buttons:
            - type: submit
              classes: btn btn-primary btn-lg
              value: Send

        #process: # NB. there are no form actions because this is a demo and that's out of scope and not in the source theme
---
Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.<br />
Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
