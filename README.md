# Contact Form 7 Listener

Pushes a dataLayer event each time Contact Form 7 confirms a message was sent, with the form ID. Rejected or failed submissions are never counted, and your forms work exactly as before.

## Setup

Follow the [setup guide](https://converly.io/gtm-templates/contact-form-7).

Fire this tag on All Pages so it is listening on every page that has a Contact Form 7 form. Then trigger your conversion tags on the custom event contact_form_7_submitted.

## Event

The listener sends contact_form_7_submitted. Use CE - Contact Form 7 Submitted as the custom event trigger.

## Script

The template loads https://gtm-templates.converly.io/contact-form-7-listener.js.

## Notes

Sends one contact_form_7_submitted event each time Contact Form 7 confirms a message was sent, with the form ID. It reads none of the answers or other personal data and doesn't change how your forms work. Full setup guide at https://converly.io/gtm-templates/contact-form-7

## License

Apache License 2.0.
