During the June 2022 OGC Member Meeting in Madrid Spain, the joint CRS DWG/SWG working groups approved a motion to work on the adoption of a JSON Schema for Coordinate references to be defined in parallel with the CRS WKT Standard and derived from ISO 19111 and OGC Topic 2.  The full text of the CRS SWG charter with updated scope to cover the CRS JSON scheme encoding can be 
found at: https://portal.ogc.org/files/?artifact_id=102055&version=1

For convenience, the relevant portion of the charter document has been repeated 
here:

To support an encoding of the self-contained and compact description of Coordinate Reference Systems and Coordinate Operations through a simple JSON schema. The implementation specification delivered will be consistent 
with OGC Abstract Specification Topic 2 and ISO 19111.  This offers the following advantages:
  *Provides a JSON encoding of coordinate reference systems descriptions for use where JSON may be considered a more natural data schema than Well Known Text.
  *Ensures that a JSON schema is available that will be kept in alignment with OGC Abstract Specification Topic 2 and ISO 19111
  *Recognizing the PROJ6 origins of the PROJJSON schema contribution being used as the starting point of this work, effort will be made to try to avoid compatibility issues and to clearly document any issues identified or object names that deviate from the original OGC Abstract Specification Topic 2 and ISO 19111.  If an unresolvable conflict is identified, OGC Abstract Specification Topic 2 and ISO 19111 will guide the resolution and such an issue will be clearly documented.

The CRS SWG has recently completed work on:
  22-010r4 Topic 24 Functional Model for Crustal Deformation (https://portal.ogc.org/files/?artifact_id=106827&version=1 [portal.ogc.org])
  22-051r7 GGXF geodetic data grid exchange format v1.0 (https://portal.ogc.org/files/?artifact_id=106828&version=1 [portal.ogc.org])
And are now able to begin the important work of vetting and documenting the CRS JSON encoding.  As discussed in the CRS SWG charter, this encoding will align with OGC Abstract Specification topic 2 and ISO 19111, and will be informed by the existing PROJ JSON schema, aiming for compatibility with the existing PROJ JSON schema where practical.

In the March 2024 Delft joint CRS SWG/DWG working group meeting, it was agreed that we would set up this github repo to serve as an open public repository to gather up any issues identified in alignment of the existing PROJ JSON Schema with OGC Abstract Specification topic 2 and ISO 19111.  Reviewers are asked to submit issues for any alignment issues they identify.  These issues will be the topic of discussion at the June joint CRS SWG/DWG meeting in Montreal Canada (date and time still TBD).

The PROJSON Schema documentation can be found at: https://proj.org/en/9.4/specifications/projjson.html
