---
title: SGID Policies
author:
  display_name: UGRC Office
  email: ugrc@utah.gov
tags:
  - policy
  - sgid
categories: []
date: 2020-01-14 17:00
---

The policies on this page govern the way we interact with data in the [SGID]({% link sgid/index.html %}). Many of these policies also apply to external data being submitted to the SGID.

- TOC list
{:toc}

A Brief Word on Language
{: style="
    margin-bottom: .3em;
    font-size: 1.4em;
    text-align: left;
    font-weight: 300;
    color: #323232;
    padding-top: .5em;
    margin: 0 0 1em;
    "}

We use the following terms intentionally on this page:

- **Must**: This is as close to a hard and fast rule as we get (short of the legislative "thou shalt" language in our establishing [laws]({% link about/code/index.html %})).
- **Should**: We generally follow this rule, but we allow for exceptions at our discretion.
- **May**: We can apply this rule, but our policies don't necessarily require or encourage us to act.
- **Will**: We will take the prescribed action if the specified conditions occur.

---

## SGID Dataset Qualifications

Datasets added to the SGID must meet the following criteria. We may remove any existing datasets that do not meet these criteria.  All additions to the SGID should follow the appropriate [sharing process]({% link sharing/index.md %}) and be tracked through [Porter](https://github.com/agrc/porter).

### General Qualifications
{: .text-left}

These criteria apply to all datasets added to the SGID, regardless of which part of the SGID they belong to.

- Datasets must cover a **state-wide** geographic extent, be part of a state-wide project or initiative (such as roads, address points, and parcels), or be relevant to broader projects or mandates that have a state-wide interest (e.g. geologic hazard mapping or endangered species mapping).
- The entity providing the dataset must be the **authoritative** or original source (for example, a dataset of geologic hazards as identified by the Utah Geological Survey must come from the UGS, not another organization).
- Datasets should have a reasonable **update schedule** included in the metadata.
  - We may add datasets that result from a one-time project and won't be updated in the future, but this should be clearly stated in the metadata.
- Datasets must not contain any information considered `private`, `protected`, or `controlled` under the Utah [Government Records Access and Management Act (GRAMA)](https://archives.utah.gov/opengovernment/) or any other personally identifiable information (PII).

### SGID Index Qualifications
{: .text-left}

These criteria apply to all datasets added only to the [SGID Index]({% link sgid/index.html %}#sgid-index) and not anywhere else in the SGID (for example, download links for resources hosted on an entity's own server).

- Datasets should be **publicly available** without requiring a login.
  - We may add references to datasets that are restricted due to safety or security concerns as a way to raise awareness that the datasets exist but are restricted.
- Dataset links should be **stable** and maintained for the forseeable future. Frequently changing links are difficult to maintain, and dead or out-of-date links damage our collective credibility and the public's confidence in our data.

### SGID Open Data Qualifications
{: .text-left}

These criteria apply to ArcGIS Online items shared through the [SGID Open Data site](https://opendata.gis.utah.gov).

- Datasets must be **publicly available** without an ArcGIS login.
- Datasets should have a **stable schema**. Clients might be using the services directly, and deleting or renaming fields can break pop-ups, definition queries, and other schema-dependent actions.
  - Just adding new fields is generally ok.
- All datasets from a single entity must be shared from the same **ArcGIS Online user** OR have a custom and consistent organization name specified in the ArcGIS Online item metadata as described in the "Source" note in the [SGID Open Data  sharing process]({% link sharing/open-data/index.md %}).
- Datasets must define the following metadata items in the ArcGIS Online item:
  - The **title** should include "Utah" if the rest of the title is not immediately and uniquely identifiable as a Utah dataset.
  - The **description** must include a summary of the dataset. The first line should include the date the dataset was last updated.
  - The **tags** should include the source entity's name and any other relevant words not found in the title (please refer to Esri's [post about using tags effectively](https://www.esri.com/arcgis-blog/products/arcgis-online/data-management/using-tags-effectively/) for more information).
- Datasets should enable the "Allow others to export data to different formats" option in their ArcGIS Online settings to enable end users to **download** the dataset as a file geodatabase.

We strongly encourage dataset owners to follow these ArcGIS Online-specific guidelines, even though the SGID Open Data site does not use them directly:

- The items' **thumbnails** appear when a user searches for the dataset on ArcGIS Online or in ArcGIS Pro. A [branded thumbnail](https://www.esri.com/arcgis-blog/products/arcgis-online/data-management/put-your-best-thumbnail-forward/) tells users that this is an authoritative dataset. For example, we use thumbnails that include the category logo for all the SGID data we share in ArcGIS Online.
- Mark the item as **authoritative** in ArcGIS Online. This helps users decide which dataset to use when their search in ArcGIS Online returns several similar results.

### Open SGID Qualifications
{: .text-left}

These criteria apply to datasets delivered to UGRC for inclusion in the [Open SGID]({% link sgid/index.html %}#open-sgid).

- Datasets should be useful to **multiple agencies or organizations'** daily activities or decision-making. Datasets primarily used internally by a single agency aren't great candidates for the Open SGID; instead, it would be great to have references to them in the SGID Open Data site or the SGID Index.
- The entity providing the dataset should lack the internal **capability** to publicly serve the data (such as through an existing ArcGIS Online organization).
  - We may chose not include a dataset if an entity has the capability to share it but lacks server capacity or is trying to reduce data storage costs.
- Datasets should be a **core and vital** GIS layer for the state (for example, land ownership category boundaries).
- Datasets should have a **stable schema**. Clients may be using the datasets directly from the database and may be relying on the presence and order of specific fields.
- Datasets should have **accurate metadata** that meets our [minimum metadata standards]({% link about/policy/metadata/index.md %}).

---

## Dataset Deprecation and Removal

Datasets being removed from the SGID must follow these policies.

### General Removal Policies
{: .text-left}

- We reserve the right to remove any dataset at any time.
- Removals should be tracked in [Porter](https://github.com/agrc/porter).
- The steward should give users a heads up at least two weeks prior to removal whenever possible.
  - UGRC should post removal and deprecation notices on the [@MapUtah](https://twitter.com/maputah) Twitter account.
- Stewards of ArcGIS Online services should perform a brownout by marking the data as `Deprecated` in the item's settings and including "deprecated" in the item's title.
- When possible, UGRC will change the sharing level of items being removed from our own ArcGIS Online organization from public to private two weeks before deleting the items completely to allow quick restoration if end users need time to find an alternative.
  - End users should not rely on this two-week blackout.
  - When possible, we encourage other stewards to adopt this same two-week sharing blackout as well.

### Reasons for Removal
{: .text-left}

Many items were added to the SGID before we adopted these policies and guidelines. We may evaluate them from time to time for removal. In the spirit of continuity, we do not intend to do an immediate, wholesale trimming of the SGID.

While not comprehensive, the following list includes the most common reasons for removing datasets:

- Datasets that cease to meet any of the qualifications above.
- A dataset's schema has substantially changed.
  - A new dataset with the new schema should be introduced instead of breaking the existing schema.
- The dataset is out-of-date.
- The dataset is no longer being updated by the steward.
- The steward has requested us to remove the dataset.
- A more authoritative source for the dataset exists elsewhere.
- A link has been abandoned and no longer returns a proper web page.

In addition, we may remove any ArcGIS Online items from SGID Open Data that aren't shared through the [sharing process]({% link sharing/open-data/index.md %}). We may remove items from the staging group if the submitter fails to provide adequate information according to the guidelines in the [sharing process]({% link sharing/open-data/index.md%}).

### "Static" Datasets
{: .text-left}

We anticipate some SGID datasets historically made available through the SDE connection or currently hosted in the Open SGID won't receive future updates, such as the boundary lines for adjacent counties in the surrounding states. We will remove these datasets from the Open SGID but leave in ArcGIS Online, where they will be tagged as `static` and remain members of a Utah SGID group.
### "Shelved" Datasets
{: .text-left}

Over time, we will remove datasets from the Open SGID that are no longer current but continue to have historical value (e.g., Census/ACS data or previous tax district boundaries). Their associated ArcGIS Online items will be tagged as `shelved` and placed in the public [UGRC Shelf](http://utah.maps.arcgis.com/home/group.html?id=8765687b7b0545668fff02d1b750f7a9) ArcGIS Online group for future reference. Shelved datasets are not included in the SGID Open Data site.

---

## Miscellaneous Policies

### Dates in Dataset Names
{: .text-left }

We will include dates in the names of datasets in the `census`, `political`, or `tax` categories to identify datasets where the most current data may not reflect the current calendar year, such as the latest Census demographic data.

For all other categories, dates should only be used for datasets that are no longer effective/active or are soon-to-be effective/active. This implies that the **most current and relevant** data contains **no date suffix**. Historical or future data should contain a date suffix to help identification at a glance.

The best way to identify a dataset's vintage or time frame is to view the metadata on its [data page]({% link data/index.html %}).

### Internal Database Standards
{: .text-left}

The SGID uses the ESRI default Resolution and Tolerance:

- XY Resolution: 0.0001 Meter
- XY Tolerance: 0.001 Meter

Any coded-value domain codes must match their values (for example, `"Interstate Highway" - "Interstate Highway"` instead of `1 - "Interstate Highway"`).

### Editing Policies
{: .text-left}

No edits or updates should be made to the internal geodatabase from 7:00PM to 10:00AM MST to allow automated scripts to push dataset updates to ArcGIS Online and the Open SGID. UGRC should ensure that data are production-ready before the editing window ends.

All bulk data updates being pushed into the SGID should be run through [Sweeper](https://github.com/agrc/sweeper) or another automated process to review and fix common data and metadata problems.

Whenever a dataset is updated, the `Last update date` must be updated in the following places:

- The [Data Stewardship spreadsheet](https://docs.google.com/spreadsheets/d/11ASS7LnxgpnD0jN4utzklREgMf1pcvYjcXcIcESHweQ/edit#gid=0)
- The dataset's data page
- The first line of the metadata's `Description` field

UGRC should implement a unified metadata database and associated automated tools to capture the last update date in a single location.

Any time a schema change or update is performed, the editor should also update any coded-value domain descriptions that do not match the domain value. See this [document](https://docs.google.com/document/d/12bdtmtv-ZVF9g-lFshbobx8DbKX9LfbL44HawLjFTVw/edit?usp=sharing) for more on this effort.
