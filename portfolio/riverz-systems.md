# Product internals and adaptations

These are implementation areas within the product families below.

## Riverz CRM

<a id="riverz-dealers"></a>
<a id="riverz-ventas"></a>

Dealers and Ventas adapt Riverz CRM to automotive sales and internal SaaS sales. Their contributions and shared wacrm foundation are documented in the [CRM variants case](https://github.com/excelenciaempire/riverz-crm-showcase/blob/main/VARIANTS.md).

## Radar

<a id="radar-catalog-collection"></a>
<a id="radar-assistant-connector"></a>

Catalog collection, the research workspace and read-only assistant access belong to one Radar product. Their implementation is documented in the [Radar system map](https://github.com/excelenciaempire/radar-showcase/blob/main/SYSTEM.md).

## Riverz AI

### Riverz AI UI workspace

**Work:** An isolated workspace for redesigning and reviewing Riverz AI's interface using fictional local data. It includes populated, empty, loading, approval and failure scenarios, with Spanish/English views.

**My contribution:** Separating the presentation layer and review fixtures from production integrations so design work can proceed without production accounts or customer data.

**Stack and status:** React, TypeScript and Next.js. A development/design replica of Riverz AI, not a second deployed product. Original interface code and assets remain related to that same product.

[Work catalog](README.md) · [Selected work](../README.md)
