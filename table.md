---
layout: default
title: Nice Table
---


# Test table 

| label (source) | cardinality | type | description | example |
|--------------- | ----------- | ---- | ----------- | ------- |
| access rights | 1 | CV/URI | Information about who can access the resource or an indication of its security status.  SHOULD use a term from the Limitations on public access code list. | https://inspire.ec.europa.eu/metadata-codelist/LimitationsOnPublicAccess/noLimitations |
| archive URL | 0..* | URI | A static data store in which the resource has been deposited, e.g. Zenodo, Figshare, HAL. Often a snapshot of the resource in a repository (dynamic data store) at a given point in time.  SHOULD use the DOI. | https://zenodo.org/records/4555755 |
| bibliographic citation | 1 | text | A bibliographic reference for the resource.  MUST use APA style. | Magee, E.; Huxley, D.; Tso, C.-.M. (2023). Random forest model to predict long-term seasonal nitrate and orthophosphate concentrations in British river reaches. NERC EDS Environmental Information Data Centre. https://doi.org/10.5285/ba208b6c-6f1a-43b1-867d-bc1adaff6445 |
| conforms to | 0..* | CV/URI | An established standard to which the described resource conforms.  If used to specify the coordinate reference system, SHOULD use the URI of a term from the OGC CRS Registry. | https://www.opengis.net/def/crs/EPSG/0/4326 |
| contact point | 1..* | URI | Relevant contact information for the cataloged resource.  SHOULD use an ORCID for people and a ROR ID for organisations. | https://ror.org/00pggkr55 |
| contributor* | 0..* | URI | An entity responsible for making contributions to the resource.  SHOULD use an ORCID for people and a ROR ID for organisations. | https://orcid.org/0000-0002-6540-8547 |
| creator* | 0..* | URI | The entity responsible for producing the resource.  SHOULD use an ORCID for people and a ROR ID for organisations. | https://orcid.org/0000-0002-6540-8547 |
| date available | 1 | date | Date that the resource became or will become available.  If embargoed, MUST use embargo end date and MUST NOT use date when metadata record was put online. MUST use the form YYYY-MM-DD. | 2025-05-19 |
| demo URL | 0..* | URI | A web app demo, visualisation, tutorial, etc. that makes use of the resource.   | https://moisture-wqmlviewer.datalabs.ceh.ac.uk/wqml_viewer |
| description | 1 | text | A free-text account of the resource.   | This R application is an implementation of state tagging approach for improved quality assurance of environmental data. The application returns state-dependent prediction intervals on input data. The states are determined based on clustering of auxiliary inputs (such as meteorological data) made on the same day. The method provides contextual information to assess the quality of observational data and is applicable to any point-based, daily time series observational data. |
| distribution | 0..* | URI | See dedicated tab | |
| has current owner | 1 | URI | Relates a resource to an agent currently having legal possession of a resource.  SHOULD use an ORCID for people and a ROR ID for organisations. | https://ror.org/04xw4m193 |
| has custodian | 1 | URI | Relates a resource to an agent having legal custody of a resource.  SHOULD use an ORCID for people and a ROR ID for organisations. | https://ror.org/04xw4m193 |
| has spatial reference system | 0..* | CV/URI | Identifies an entity that has a spatial reference system in order to interpret the result.  SHOULD use the URI of a term from the OGC CRS Registry. | https://www.opengis.net/def/crs/EPSG/0/4326 |
| identifier | 1..* | URI | A unique identifier of the resource being described or cataloged.   | https://doi.org/10.5285/44c577d3-665f-40de-adce-74ecad7b304a |
| is referenced by | 0..* | URI | A related resource, such as a publication, that references, cites, or otherwise points to the cataloged resource.  SHOULD use the DOI. MUST be used only once per resource that has referenced the subject resource (i.e. do not use twice for the DOI and for another PID of the same resource). | https://doi.org/10.3389/frwa.2023.1244024 |
| keyword/tag | | CV - TODO | A keyword or tag describing the resource.   | |
| landing page | | URI | A Web page that can be navigated to in a Web browser to gain access to the catalog, a dataset, its distributions and/or additional information.   | https://catalogue.ceh.ac.uk/documents/ba208b6c-6f1a-43b1-867d-bc1adaff6445 |
| language | 1..* | CV | A language of the resource. This refers to the natural language used for textual metadata (i.e., titles, descriptions, etc.) of a cataloged resource (i.e., dataset or service) or the textual values of a dataset distribution Repeat this property if the resource is available in multiple languages. MUST use a term from the ISO 639-1 vocabulary. | https://id.loc.gov/vocabulary/iso639-1.html |
| license | 1 | CV/URI | A legal document under which the resource is made available.  SHOULD use a term from the SPDX License List. | https://spdx.org/licenses/OGL-UK-3.0.ttl |
| previous version | 0..1 | URI | The previous version of a resource in a lineage [PAV].  SHOULD use the DOI. | https://doi.org/10.5285/18b7c387-037d-4949-98bc-e8db5ef4264c |
| publisher | | URI | The entity responsible for making the resource available.  SHOULD use an ORCID for people and a ROR ID for organisations. | https://ror.org/00pggkr55 |
| release date | 1 | date | Date of formal issuance (e.g., publication) of the resource. This property SHOULD be set using the first known date of issuance. If embargoed, MUST use date when metadata record was put online and MUST NOT use embargo end date. MUST use the form YYYY-MM-DD. | 2025-05-19 |
| replaces | 0..* | URI | A related resource that is supplanted, displaced, or superseded by the described resource [DCTERMS].  SHOULD use the DOI. | https://doi.org/10.5285/18b7c387-037d-4949-98bc-e8db5ef4264c |
| repository URL | 0..* | URI | A dynamic data store in which the resource has been deposited and can be continually updated, e.g. Github, Gitlab, Bitbucket.   | https://github.com/NERC-CEH/IDM_comparisons |
| copyright holder | 0..* | URI | A reference to the organisation that holds copyright over the content of the dataset. SHOULD use a ROR ID.   | https://ror.org/01kj2bm70 |
| copyright statement | | URI | A link to a document that includes a statement about the copyright status of the content of a dataset. The web page might include both a copyright notice for a dataset, and any relevant guidance for re-users.   | |
| copyright notice | 0..* | text | The copyright notice associated with a rights statement. A notice must typically be preserved and displayed when acknowledging the source of some data. This property is expressed as a simple literal value and so is suitable for simple copyright notices. Where a data publisher needs to reference a larger copyright statement and/or related guidance then the copyrightStatement property should be used instead.   | © UK Centre for Ecology & Hydrology |
| copyright year | 0..1 | year | The year from which copyright over the content of the dataset is asserted.   | 2015 |
| spatial representation type | 0..* | CV - TODO | raster/vector/tabular   | raster |
| spatial resolution | 0..1 | number | Minimum spatial separation resolvable in a dataset, measured in meters. If the dataset is an image or grid this should correspond to the spacing of items. For other kinds of spatial datasets, this property will usually indicate the smallest distance between items in the dataset.  | 30 |
| spatial/geographical coverage | 0..1 | bounding box | The geographical area covered by the dataset.  MUST use the WKT form. | POLYGON((-8.648 49.864, -8.648 60.861, 1.768 60.861, 1.768 49.864, -8.648 49.864)) |
| status | 1 | CV - TODO | The status of the resource in the context of a particular workflow process [VOCAB-ADMS].   | superseded |
| temporal coverage | 0..1 | date(s) | The temporal period that the dataset covers.  MUST use the form YYYY-MM-DD. | start: 2010-01-01, end: 2020-12-31 |
| temporal resolution | 0..1 | duration | Minimum time period resolvable in the dataset. If the dataset is a time-series this should correspond to the spacing of items in the series. For other kinds of dataset, this property will usually indicate the smallest time difference between items in the dataset. MUST use the form PnYnMnDTnHnMnS. | PT1H |
| theme/category | 1..* | CV - TODO | A main category of the resource. A resource can have multiple themes.   | |
| title | 1 | text | A name given to the resource.   | State tagging application for environmental data quality assurance |
| topic category | | CV | Topic category in accordance with ISO-19115 [INSPIRE-TC].  MUST use a term from the EN ISO 19115 code list. | https://inspire.ec.europa.eu/metadata-codelist/TopicCategory/climatologyMeteorologyAtmosphere |
| type/genre | | CV - TODO | The nature or genre of the resource.   | |
| update/modification date | 1 | date | Most recent date on which the resource was changed, updated or modified. The value of this property indicates a change to the actual resource, not a change to the catalog record. An absent value MAY indicate that the resource has never changed after its initial publication, or that the date of last modification is not known, or that the resource is continuously updated. MUST use the form YYYY-MM-DD. | |
| version | 1 | text | The version indicator (name or identifier) of a resource.  SHOULD use the SemVer or SchemaVer form. | 0.0.1 |
| version notes | 0..1 | text | A description of changes between this version and the previous version of the resource [VOCAB-ADMS]. In case of backward compatibility issues with the previous version of the resource, a textual description of them SHOULD be specified by using this property. MUST be used if previous version exists. | This release replaces the previous version as it addresses localised issues with the source data (Met Office monthly rainfall grids) for the period 1960 to 2000. |
| was derived from | 0..* | URI | A derivation is a transformation of an entity into another, an update of an entity resulting in a new one, or the construction of a new entity based on a pre-existing entity.  A resource (e.g. a model, a dataset) can be derived from another resource (e.g. a dataset, a model). SHOULD use the DOI. | https://doi.org/10.5285/7115bc48-3ab0-475d-84ae-fd3126c20984 |
| was generated by | 0..* | URI | An activity that generated, or provides the business context for, the creation of the dataset.   | |
| was influenced by | 0..* | URI | Influence is the capacity of an entity, activity, or agent to have an effect on the character, development, or behavior of another by means of usage, start, end, generation, invalidation, communication, derivation, attribution, association, or delegation.  A resource (e.g. a method) can be influenced by another resource (e.g. another method). SHOULD use the DOI. | https://doi.org/10.5285/7115bc48-3ab0-475d-84ae-fd3126c20984 |
| workflow format | 0..1 | CV/URI |   Required only if workflow (not method) | Argo |
| has part | 0..* | |   A method/package used in the workflow | |
| input (file format/parameter type) | 0..* | CV |    | CSV |
| output (file format/parameter type) | 0..* | CV |    | string |
| software dependency | 0..* | CV/URI |    | Python 3.0.0 |
| hardware requirement | 0..* | CV/URI |    | GPU |
| category of method/workflow??? | ?? | CV |    | |
