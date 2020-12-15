## v1.0.24.0
   * MBANK v0.24.0 - Postman collection - The new endpoints are added to get basic information for series, Season, Episode and its Manifestation.
   * MBANK v0.24.0 - Postman collection - The new event search endpoint is added to get Event information based on startdate and enddate.
   * MBANK v0.24.0 - Postman collection - The field CommonCarriage is added to event entity.
   * MBANK v0.24.0 - Postman collection - The parameter enddatetime is added to linear show schedule search.
   
## v1.0.23.0
   * MBANK v0.23.0 - Postman collection - The new endpoints are added to get permission by PermissionID

## v1.0.22.1
 * MBANK v0.22.1 - JSON schema - The new field Title120 & keywords are added to Series. The keywords field is added to Season and Episode Entity.
 * MBANK v0.22.1 - Postman collection - The new field Title120 & keywords are added to Series. The keywords["Mood", "TimePeriod", "Theme", "Character", "Setting", "Subject", "General" - String of Ayray] field is added to Season and Episode Entity
 * MBANK v0.22.1 - Postman collection - The new endpoints are added to delete the existing ContentId, LogicalAssetID and AlternateSupplementalID for Manifestation, Rights and Supplemental entities respectively.
 
## v1.0.22
 * MBANK v0.22 - JSON schema - The new field FileDeliveryStatus is added to Edit and renamed Title to Description and ApproximateLength to ActualLength and removed MediaInventoryHouseNumber, SynopsisLong and PublishedStatus fields.
 * MBANK v0.22 - Postman collection - The new field FileDeliveryStatus is added to Edit and renamed Title to Description and ApproximateLength to ActualLength and removed MediaInventoryHouseNumber, SynopsisLong and PublishedStatus fields.
 * MBANK v0.22 - Postman collection - The Edit search endpoint is added for Edit 
 
## v1.0.21
 * MBANK v0.21 - JSON schema - The new field TitleLong is added to Episode & series entities & The standalone episode will be created without parent.
 * MBANK v0.21 - Postman collection - The new field TitleLong is added to Episode & series entities & The standalone episode will be created without parent.
 
## v1.0.20
 * MBANK v0.20 - JSON schema - The GeospatialNamedArea Enum values are changed for Policy's Permission POST and PUT.
 * MBANK v0.20 - Postman collection - Added new endpoints to search Policy's Permission.

## v1.0.19
 * MBANK v0.19 - JSON schema - Added new field Title19 in Series & Episode and the DviLanguage firl for Event Linear's POST & PUT endpoints.
 * MBANK v0.19 - JSON schema - The Enum values are changed for Episode[Primary Genre & Secondary Genre, CreditList - Role], Series[CreditList - Role], Manifestation[AudioType, VChip] and File[FileClass] fields in POST and PUT.
 * MBANK v0.19 - JSON schema - The GeospatialName field type is changed from String to Array of String for Policy Permission's POST & PUT.
 * MBANK v0.19 - Postman collection - Added new fields Title19 & DviLanguage for Series, Episode and Events Respectively and The GeospatialName type is changed from String to Array for Policy Permission.
 * MBANK v0.19 - Postman collection - The Enum values are changed for Episode[Primary Genre & Secondary Genre, CreditList - Role], Series[CreditList - Role], Manifestation[AudioType, VChip] and File[FileClass]
 
## v1.0.18
 * MBANK v0.18 - JSON schema - Added new fields in schema for Supplemental & Permission in MBank Policy, Policy-Permission & Policy-Prohibitions POST & PUT, Supplemental Endpoints
 * MBANK v0.18 - Postman collection - Added new fields for Policy's Permission and Supplemental.
 * MBANK v0.18 - Postman collection - Added new change log endpoints for Policy's Permission and Supplemental.
 
## v1.0.17
 * MBANK v0.17 - JSON schema - Added new schema for Supplemental & Edit and updated for MBank Policy, Policy-Permission & Policy-Prohibitions POST & PUT
 * MBANK v0.17 - Postman collection - Added new endpoints for Policy's permission and prohibition
 * MBANK v0.17 - Postman collection - Added new entities Supplemental and Edit[GET, POST, PUT, DELETE, Register Alternative Id, Publish-Status]
 
## v1.0.16
 * MBANK v0.16 - JSON schema updated for MBank Policy, Policy-Permission & Policy-Prohibitions for MediaContext field changed from String to Array
 * MBANK v0.16 - Postman collection - Added new endpoints to de-associate Organization and Series & Episodes
 * MBANK v0.16 - Postman collection - The OrganizationList is removed from Episodes for all search endpoints.
 
## v1.0.14
 * MBANK v0.14 - JSON schema updated for MBank Series, Episode for dar, haw, hmo, psm, swz, wam language code support. 
 *		Event Linear & VOD Post and PUT for Qualifier new Enum value updates - Mono, Stereo Surround, Surround 5.1
 *		New scheam addred for Policy Prohibition POST & PUT.
 * MBANK v0.14 - Postman collection - Added new policy prohibition endpoints.
 
## v1.0.11
 * MBANK v0.12 - Postman collection - Added new endpoint to delete existing alternate eventId.
 
## v1.0.10
 * Beta-v0.11 - JSON schema updated for MBank Event Linear & VOD Post and PUT for Qualifier Enum validation.
 * Beta-v0.11 - Postman collection - Added providersource in showschedule search endpoint.

## v1.0.9
 * Beta-v0.10 - JSON schema Updated for MBank Event Linear Post and Playtype PUT for playday validation.
 * Beta-v0.10 - Postman collection - Changed PlayDate to Playday in Event payload as well as in playtype PUT endpoints.

## v1.0.8
 * Beta-v0.9 - JSON schema Updated for all MBank entities POST & PUT for user readable validation message for Bank API.
 * Beta-v0.9 - Postman collection - Added PlayDate in Event payload as well as in playtype PUT endpoints.

## v1.0.7
 * Beta-v0.8 - JSON schema Updated for Compilation POST in Bank API.
 * Beta-v0.8 - Postman collection - Modified Event's UID in all Event endpoints.

## v1.0.6
 * Beta-v0.7 - JSON schema for Funder removed in Bank and moved to Core API.
 * Beta-v0.7 - Postman collection - Removed GetSeasonsBySeriesUID, GetSeasonBySUIDSeriesUD, GetEpisodesBySeriesUID, GetEpisodeByEUIDSeriesUID, GetEpisodesBySeasonUID, GetEpisodeByEUIDSeasonUID Updated endpoints from Metadata Bank-v0.7
 * Beta-v0.7 - Postman collection - Moved funder and Media-Inevntory endpoints to Metadata Core API project.
 
## v1.0.5
 * Beta-v2 metadata-bank json schema changes for ParentUID changes on Season, Episode, Manifestation, File and new schema are added for PUT endpoints.
 * Beta-v2 Postman collection - Updated for endpoints for Changelog's DeletedEntityList, Pagiantion links, ParentID changed to ParentUID. 

## v1.0.4
 * Beta-v2 metadata-bank json schema changes for ParentUID changes on Season, Episode, Manifestation, File and new schema are added for PUT endpoints.
 * Beta-v2 Postman collection - Updated for endpoints for Changelog's DeletedEntityList, Pagiantion links, ParentID changed to ParentUID.

## v1.0.3
 * UAT4 - Beta-v1 metadata-bank json schema changes for Series, Season, Episode, Manifestation, Compilation, Policy, File, EventLinear, EventVOD and Funder.
 * UAT4 -  Beta-v1 Postman collection - Series, Season, Episode, Manifestation, Compilation, Policy, File, Event, Funder and Catalog.

## v1.0.1.1
 * UAT3-Micro-release-v11.9.c - Schema changes on Event & Event Linear - The Enumeration value is removed for ProviderSourceName and it supports any string value.
 * UAT3 Postman collection - Micro-release-v11.9.c - The alternateeventId is added in showschedule Linear and VOD endpoints
 
## v1.0.1
 * UAT3 metadata-bank json schema for Series, Season, Episode, Manifestation, Compilation, Policy, File, Event.
 * UAT3 Postman collection - Series, Season, Episode, Manifestation, Compilation, Policy, File, Event and Catalog.

## v1.0.0
 * UAT2 metadata-bank json schema for Series, Season, Episode, Manifestation, Compilation, Policy.
 * UAT2 Postman collection - Series, Season, Episode, Manifestation, Compilation, Policy. 
 