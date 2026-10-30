# NEXORA AI Website

A responsive, bilingual (English/Hindi) landing page for NEXORA AI's website, chatbot, and business automation services.

## Run locally

From this folder, start a local server:

```sh
python3 -m http.server 8000
```

Open [http://localhost:8000](http://localhost:8000) in your browser.

## Included

- Responsive navigation, service overview, project process, starting-price cards, FAQs, and contact form.
- English/Hindi language toggle.
- Chatbot demo with predefined replies; it does not connect to a live AI service or send chat messages to a server.
- Enquiry form that opens a prefilled WhatsApp message. The visitor reviews and sends it from WhatsApp; the form does not submit data to this website.

## Before publishing

- Confirm the contact details and indicative prices in `index.html`.
- Update `WHATSAPP_NUMBER` in the page script if the enquiry number changes. Use the international country code without a `+` or spaces.
- Confirm project scope, pricing, and third-party costs with customers; domain, hosting, paid APIs, and subscriptions are not automatically included.