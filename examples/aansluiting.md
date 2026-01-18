# Aansluiting — alignment case

## Anchor (NBNL)
- **NBNL concept URI:** https://begrippen.netbeheernederland.nl/id/gnhiy
- **Parent concept / domein:** (from NBNL page)
- **Source:** Nbility (as indicated on the NBNL page)

> This repo does not duplicate NBNL or Nbility content.  
> It captures how this concept is projected into technical models and data products across teams.

## Why projections
In a distributed data environment (data mesh / multiple teams and systems), the same business concept can legitimately appear in different **perspectives** (grid / market / enterprise) and different **layers** (asset / function).  
Without making those projections explicit, teams drift and interoperability degrades.

## Projections (the part we add)

### Projection A — Grid × Asset (physical grid reality)
- **Perspective:** Grid
- **Layer:** Asset
- **Typical usage context:** topology / operations / maintenance
- **CIM / profile targets:** TBD
- **Bounded context / owning team:** TBD
- **Data product references:** TBD
- **Notes:** This projection represents the physical connection reality as used in grid operations.
- **Non-goals:** Not a CRM view; not a settlement view.

### Projection B — Market × Function (rights, settlement, exchange)
- **Perspective:** Market
- **Layer:** Function
- **Typical usage context:** settlement / contracts / flexibility
- **CIM / profile targets:** TBD
- **Bounded context / owning team:** TBD
- **Data product references:** TBD
- **Notes:** This projection represents the functional/market interpretation that participates in exchange and rights.
- **Non-goals:** Not the physical asset composition.

### Projection C — Enterprise × Function (service delivery / administration)
- **Perspective:** Enterprise
- **Layer:** Function
- **Typical usage context:** CRM / service delivery / customer processes
- **CIM / profile targets:** TBD
- **Bounded context / owning team:** TBD
- **Data product references:** TBD
- **Notes:** This projection represents how the enterprise administers and services “aansluiting”.
- **Non-goals:** Not the grid topology representation.

## Data product metadata (how this becomes operational)
Minimum metadata you want every relevant data product to carry:

- **nbnl_concept_uri:** `https://begrippen.netbeheernederland.nl/id/gnhiy`
- **projection_id:** `grid_asset` | `market_function` | `enterprise_function`
- **cim_profile_target:** (one or more class links)
- **bounded_context:** (team/domain)
- **semantic_owner:** (role or group)

## Open questions
- Which exact CIM classes/profiles does Alliander/NBNL use for each projection in practice?
- Which data products are the primary “semantic surfaces” for this concept?

