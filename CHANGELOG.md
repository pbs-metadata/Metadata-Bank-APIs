## v0.42.0
   * MBANK v0.42.0 - Update event SNS to include two additional fields ReferentType and ReleaseQualifier.
   * MBANK v0.42.0 - Release Date logic for Series, Season, Episode, Manifestation, Compilation and Supplemental (GET) to calculate release date based on earliest linear and vod events.
## v0.41.0
   * MBANK v0.41.0 - SNS Topic - Disable AlternateID POST and DELETE from generic SNS topics(in-progress, internal-publish and external-publish) and dedicated to alternate-id SNS topic.
## v0.40.2
   * MBANK v0.40.2 - Postman collection - The new field USTVRating added with Enum values for Series, Season, Episode POST, PUT and GET.
   * MBANK v0.40.2 - JSON schema - The Enum values added in the field USTVRating for Series, Season and Episode POST and PUT. 
   * MBANK v0.40.2 - Postman collection - The new Type "Intercompany Rights Out" added to Permission POST, PUT and GET.

## v0.40.1
   * MBANK v0.40.1 - Postman collection - The query param filename is added in File search endpoint.
   * MBANK v0.40.1 - JSON schema - Additional Enum values added in the field DeliveryChannel for Policy POST and PUT. The field DeliveryChannel removed from Supplemental POST & PUT. 
   * MBANK v0.40.1 - Postman collection - The SNS is implemented for AlternateID POST and PUT. The SNS is implemented for One-Time-Only Episodes with Internally or Externally published records.

## v0.39.0
   * MBANK v0.39.0 - Postman collection - The new field DeliveryChannel added with Enum values for Supplemental POST & PUT.
   * MBANK v0.39.0 - JSON schema - The new field DeliveryChannel added with Enum value for Supplemental POST & PUT.

## v0.38.0
   * MBANK v0.38.0 - Postman collection - The new Enum values are added to EndOperator fieldEndOperator and additionalData added for Series POST & PUT. The Supplemental is added in Compilation EntryList.
   * MBANK v0.38.0 - JSON schema - The Enum value is added to EndOperator fields and additionalData object added for all entities. The Supplemental is added in Compilation EntryList.

## v0.37.0
   * MBANK v0.37.0 - Postman collection - The new Enum values are added to StartEvent & StartOperator fields and new field WindowsStartDurationType added to Permission & Policy endpoints. The EIDRID parameter is added in episode, season, series and catalog Search endpoints.
   * MBANK v0.37.0 - JSON schema - The Enum value is added to StartEvent & StartOperator fields and new field WindowsStartDurationType added to Permission & Policy endpoints.

## v1.0.36.0
   * MBANK v0.36.0 - Postman collection - Payload structure changes on Permission payload[Moved existing permission fields “PlayType, Calculated, UnitType, Count, EnsureExclusivity, MaximumExploitation, MaximumSimultaneousLimit” to Refinement], Added OrganizationList in Permission and Season. Added new Season, Permission delete endpoints to de-associate with Organization and added File search endpoints
   * MBANK v0.36.0 - JSON schema - The Payload changes on Permission, Added new endpoints for Season, Permission delete for Organization de-association. Added File search endpoints.

## v1.0.33.0
   * MBANK v0.33.0 - Postman collection - New Edit - Publish Status endpoints is added, The Edit[Title, AlternateContentID] & Supplemental[AlternateContentID] fieldname changed & Play Run Removed from VOD Events.
   * MBANK v0.33.0 - JSON schema - The Edit[Title, AlternateContentID] & Supplemental[AlternateContentID] fieldname changed & Play Run Removed from VOD Events.

## v1.0.30.0
   * MBANK v0.30.0 - Postman collection - New POST, PUT and DELETE endpoints are added to policy OrganizationList
   * MBANK v0.30.0 - JSON schema - The ReferentType is removed and the PolicyType field renamed to PolicyClass for from Policy POST and PUT shema.

## v1.0.29.0
   * MBANK v0.29.0 - Postman collection - New endpoints are added for keywords deletes for Series, Season & Episode
   * MBANK v0.29.0 - JSON schema - The ReferentType is removed from Edit POST and PUT & New column FileFormat is added to File entity.
   
## v1.0.28.0
   * MBANK v0.28.0 - Postman collection - New endpoints are added for Season & Compilation to remove the existing contentID and implemented SNS for it.
   * MBANK v0.28.0 - Postman collection - New endpoints are added for Policy & Prohibition to remove the existing LogicalAsssetID and implemented SNS for it.
   * MBANK v0.28.0 - Postman collection - The SNS is implemetned for Manifestation UseWindowTermList addition and deletion endpoints.

## v1.0.27.1
   * MBANK v0.27.1 - Postman collection - The EpisodeNumber data type is changed from Integer to String for Episode POST & PUT
   * MBANK v0.27.1 - JSON schema - The EpisodeNumber data type is changed from Integer to String for Episode POST & PUT.

## v1.0.26.0
   * MBANK v0.26.0 - Postman collection - The new endpoint is added to delete alternateeditid id for Edit.
   
## v1.0.25.0
   * MBANK v0.25.0 - Postman collection - The new endpoint is added to delete content id for series.
   * MBANK v0.25.0 - JSON schema - The 'Podcasting' enum value is added to RightsIn's Mediacontext field.
   
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
 