---
marp: true
theme: gaia
class: invert
paginate: true
footer: "https://example.com"
transition: fade
---

<!-- Speaker Notes
Stellen Sie sich vor, Sie betreten einen Supermarkt, nehmen einen Energy Drink und einen Schokoriegel
und gehen einfach wieder hinaus - ohne zu bezahlen. Klingt wie Diebstahl, oder?
Nun, genau das habe ich gestern getan. Hier in München. (Karlstraße 36)

Aber zwei Minuten später erhielt ich eine
Benachrichtigung auf meinem Smartphone mit einer detaillierten Auflistung meiner
Einkäufe und dem abgebuchten Betrag. Willkommen in der Welt der Automatisierung,
wo selbst der Einkaufsprozess revolutioniert wird. 
-->

# The power of automation and how to control it.

March, 3rd 2025, at CS3 in Munich
Christoph Dyllick-Brenzinger

![bg right](https://picsum.photos/800/600)

<!-- _header: '' -->
<!-- _footer: '' -->

---

<!-- Speaker Notes -->

## Why do we need automation? (mittig ausgerichtet)

---

## Data-driven decisions

Feeling (intuition)

- Subject to interpretation
- Difficult to estimate and justify ROI
- Wasted resources (Budget + Time)

Data-Driven

- Logic-driven and objectivity
- Improved reporting + visibility on ROI
- Requires fewer resources (Human, Budget, Time)

---

## Automation: The key to being data-driven

Manual tasks

- Wasted time
- Human error
- High human resource requirements
- Low employee happiness and retention

Automation

- Predictability
- Better data availability
- Increased employee efficiency
- Focused efforts on higher-value taks
- Much higher ROI

---

## What is automation?

A predictable set of predetermined actions that transfers data from one point to another 

---

## Example:

Form submission -> What kind of company
> No company > Ignore
> Low-value > Add to email sequence
> High-value > Add to Google Sheet
> Give to account manager ASAP

---

## Core concepts of automation

---

## Trigger

A trigger is what starts an automation.
- Manual
- Scheduled
- Applications
  - Webhook
  - Property update
  - Form submission

-> Bild von einem n8n Form Trigger

---

## Filtering

Filtering is used to allow or block certain types of data from following a path based on certain conditions.

-> bild von einem filter in n8n

---

## Actions (Apps)

Actions allow you to interact with applications

Seafile:
- Upload file
- Get file
- Create folder

Slack:
- Get user
- Send message
- Get message

SeaTable
- Update rows
- Create new row

Salesforce
- Get contact
- Get Company
- Create lead

---

## Automation examples

Bilder von n8n workflows:

- https://n8n.io/workflows/2731-daily-birthday-reminders-from-google-contacts-to-slack/
- https://n8n.io/workflows/2843-automate-sports-betting-data-with-the-odds-api/
- https://n8n.io/workflows/2170-extract-data-from-resume-and-create-pdf-with-gotenberg/ (zu komplex)
- https://n8n.io/workflows/2561-send-matomo-analytics-data-to-ai-to-analyze-then-save-results-in-baserow/ (zu komplex)

- data transer: google analytics to seatable...
- detect errors: woocommerce trigger -> telegram
- backup n8n workflows to github
- send messages to ai for a summary

---

<!-- Speaker Notes:
visual interface to create workflow automations
"nodes" are predefined API connectors
-->

## What is n8n?

die zwei animated gifs von hier (leading visual editor, powerful debugging)
https://n8n.io/features/

plus video: wie man so einen workflow zusammenklickt. Gesamtes interface.

---

## Key Features

- Open Source / Fair Source
- visual interface
- flexibility: n8n supports simple and complex automation scenarios, 
      from sending notifications to building data pipelines and creating AI-powered workflows.
- self-hosting
- coder friendly: json format and custom code
- AI integration

---

## Who should use n8n?

Bild der Jetsons... oder einem menschen um den ganz viele roboter arbeiten...

<!--
Meine Damen und Herren,

Workflow-Automatisierung ist der Schlüssel zu einer effizienteren, präziseren und innovativeren Zukunft. Sie ermöglicht datengetriebene (data-driven) Entscheidungen, reduziert Fehler, spart Zeit und macht Prozesse reproduzierbar.

Stellen Sie sich eine Welt vor, in der wir uns auf das konzentrieren können, was wirklich zählt: Kreativität, Innovation und menschliche Interaktion.

Automatisierung befreit uns von der Monotonie und gibt uns die Freiheit, unser volles Potenzial zu entfalten. Sie ist nicht unser Gegner, sondern unser Verbündeter.

Sind Sie bereit, diese Zukunft zu gestalten? Lassen Sie uns gemeinsam eine Welt schaffen, in der Technologie uns befähigt. Vielleicht ja mit n8n.

Vielen Dank."
-->
