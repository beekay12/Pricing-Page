AutoFlow Pricing Plans

A responsive pricing-plan interface for AutoFlow, built with plain
HTML, CSS, and JavaScript.

The page presents four subscription tiers and allows users to switch
between Cloud Hosted and Self-Hosted pricing.
fileciteturn0file0L263-L280

Features

Four pricing tiers:

Starter

AutoFlow Team

AutoFlow Business

AutoFlow Enterprise

Cloud Hosted / Self-Hosted pricing toggle

Responsive layout for desktop, tablet, and mobile screens

Featured Business plan with a limited-time free-month promotion

Plan-specific feature lists and calls to action

Dark, modern interface

Hover effects and animated UI transitions

Inline SVG icons for plan features

No external frameworks or dependencies

Pricing

Plan                            Cloud Hosted            Self-Hosted

Starter                             R0/month               R0/month
AutoFlow Team                      R49/month              R79/month
AutoFlow Business       R0/month for 1 month   R0/month for 1 month
AutoFlow Enterprise               R999/month           R1,499/month

The Business plan displays a crossed-out normal price of R249 for Cloud
Hosted and R349 for Self-Hosted during the promotion. After the
promotional month, the normal tier price applies.
fileciteturn0file0L347-L391

Plan Highlights

Starter

Designed for basic workflows and everyday automation.

100 active workflow executions

Standard app integration connectors

5-minute update trigger intervals

Single member workspace

Community forum support

AutoFlow Team

Designed for larger recurring business processes.

10,000 active workflow executions

Custom webhook endpoints

1-minute real-time triggers

Up to 5 team members

Standard email support

AutoFlow Business

Designed for advanced automation and complex integrations.

50,000 active workflow executions

AI-powered document and logic parsing

Shared team environments and credentials

Custom JavaScript/Python execution blocks

30-day detailed execution log history

Two-way CRM and ERP sync connectors

Priority ticket and live chat support

AutoFlow Enterprise

Designed for mission-critical automation and organizations requiring
additional security and scale.

Unlimited workflow execution volume

SOC2 Type II, HIPAA, and custom SSO/SAML

Dedicated worker nodes and infrastructure

99.99% uptime SLA with financial backing

Dedicated Technical Account Manager fileciteturn0file0L394-L428

Technologies

HTML5 --- page structure and content

CSS3 --- layout, responsive design, styling, animations, and
transitions

Vanilla JavaScript --- pricing-toggle functionality

Inline SVG --- feature icons

How It Works

The pricing toggle uses data-cloud and data-dedicated attributes on
the price elements. When a hosting option is selected, JavaScript
updates the displayed prices and switches the active toggle state.
fileciteturn0file0L433-L457

Responsive Design

The pricing grid adapts to different screen sizes:

Desktop: 4 pricing cards per row

Tablet: 2 cards per row

Mobile: 1 card per row fileciteturn0file0L248-L257

Getting Started

No build tools or installation are required.

Download or clone the project.

Open index(10).html in a modern web browser.

Use the Cloud Hosted and Self-Hosted toggle to compare
pricing.

Project Structure

.
└── index(10).html

Everything is contained in a single HTML file, including the CSS and
JavaScript.

Customization

To change pricing, edit the data-cloud and data-dedicated values on
the relevant price elements.

For example:

<span class="price" data-cloud="R49" data-dedicated="R79">R49</span>

To customize the interface, modify the CSS variables/properties and
component classes inside the <style> section.

Notes

The current buttons are visual UI elements and do not contain
checkout functionality.

Footer links currently use placeholder # destinations.

Pricing and promotional terms shown in the interface are demo
content and should be verified before production use.

License

This project does not currently specify an open-source license. If you
plan to distribute the code publicly, add a license appropriate to your
intended use.
