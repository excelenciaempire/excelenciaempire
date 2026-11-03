# Related Riverz systems

These are distinct development workstreams around the products in the [full portfolio](../README.md), with shared foundations identified below.

## Riverz Dealers

**Work:** An automotive-sales adaptation of Riverz CRM. The application includes vehicle inventory, opportunities per buyer, visits and test drives, follow-up and sales context inside the inbox.

**My contribution:** Adapting the product model and conversation workflow to vehicles and salespeople, including a Spanish/English interface. It shares Riverz CRM's wacrm-derived foundation; it is not a new CRM engine written from scratch.

**Stack and status:** TypeScript, React and Next.js. Private domain-adaptation implementation; this page does not claim a measured sales outcome.

## Riverz Ventas

**Work:** A separate sales configuration for selling Riverz services, with qualification, nurturing, appointment setting and an internal operations handoff.

**My contribution:** Adapting the shared CRM workflow to software sales and separating sales records from fulfillment. A won deal starts an operations record rather than automatically activating a merchant account.

**Stack and status:** TypeScript and Next.js, using the Riverz CRM/wacrm foundation. An internal SaaS-sales adaptation, not an independent CRM platform.

## Radar catalog collection

**Work:** The data-collection side of Radar: catalog listings, product details, supplier information, observed stock and price history.

**My contribution:** Building the collection/update workflow, persistent observations and scheduled operation that supply Radar. The repository documents a daily VPS process; that source documentation is separate from a new uptime check.

**Stack and status:** Python and catalog data-processing tools. A supporting data system for [Radar](https://github.com/excelenciaempire/radar-showcase), not an additional consumer product. Stock changes remain observations rather than proven sales.

## Radar assistant connector

**Work:** Read-only access to the catalog for AI assistants through MCP, with reusable assistant workflows.

**My contribution:** Wrapping catalog queries and product/supplier context in a tool interface assistants can use, alongside the collection system and Radar's research interface.

**Stack and status:** Python and MCP. This case covers catalog access; it does not present planned full dropshipping operations as delivered functionality.

## Riverz AI UI workspace

**Work:** An isolated workspace for redesigning and reviewing Riverz AI's interface using fictional local data. It includes populated, empty, loading, approval and failure scenarios, with Spanish/English views.

**My contribution:** Separating the presentation layer and review fixtures from production integrations so design work can proceed without production accounts or customer data.

**Stack and status:** React, TypeScript and Next.js. A development/design replica of Riverz AI, not a second deployed product. Original interface code and assets remain related to that same product.

[Full portfolio](../README.md)
