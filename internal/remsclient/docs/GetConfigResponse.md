# GetConfigResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DefaultLanguage** | **string** |  | 
**ExtraPages** | [**[]ExtraPage**](ExtraPage.md) |  | 
**ShowResourcesSection** | Pointer to **bool** |  | [optional] 
**EnableVoting** | Pointer to **bool** |  | [optional] 
**ShowAttachmentZipAction** | Pointer to **bool** |  | [optional] 
**AlternativeLoginUrl** | **NullableString** |  | 
**Tables** | Pointer to **map[string]map[string]map[string]interface{}** |  | [optional] 
**EntitlementDefaultLengthDays** | **NullableInt64** |  | 
**EnableCart** | Pointer to **bool** |  | [optional] 
**EnableCatalogueTree** | Pointer to **bool** |  | [optional] 
**CatalogueIsPublic** | **bool** |  | 
**EnableAutosave** | Pointer to **bool** |  | [optional] 
**Authentication** | **string** |  | 
**EnableDoi** | Pointer to **bool** |  | [optional] 
**EnableCatalogueTable** | Pointer to **bool** |  | [optional] 
**OidcExtraAttributes** | [**[]GetConfigResponseOidcExtraAttributes**](GetConfigResponseOidcExtraAttributes.md) |  | 
**AttachmentMaxSize** | **NullableInt64** |  | 
**CatalogueTreeShowMatchingParents** | Pointer to **bool** |  | [optional] 
**ApplicationIdColumn** | **string** |  | 
**Languages** | **[]string** |  | 
**ApplicationListHiddenColumns** | Pointer to **[]string** |  | [optional] 
**EnableDuo** | Pointer to **bool** |  | [optional] 
**EnableProcessingStates** | Pointer to **bool** |  | [optional] 
**EnableAssignExternalIdUi** | **bool** |  | 
**Dev** | **bool** |  | 
**ShowPdfAction** | Pointer to **bool** |  | [optional] 

## Methods

### NewGetConfigResponse

`func NewGetConfigResponse(defaultLanguage string, extraPages []ExtraPage, alternativeLoginUrl NullableString, entitlementDefaultLengthDays NullableInt64, catalogueIsPublic bool, authentication string, oidcExtraAttributes []GetConfigResponseOidcExtraAttributes, attachmentMaxSize NullableInt64, applicationIdColumn string, languages []string, enableAssignExternalIdUi bool, dev bool, ) *GetConfigResponse`

NewGetConfigResponse instantiates a new GetConfigResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetConfigResponseWithDefaults

`func NewGetConfigResponseWithDefaults() *GetConfigResponse`

NewGetConfigResponseWithDefaults instantiates a new GetConfigResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDefaultLanguage

`func (o *GetConfigResponse) GetDefaultLanguage() string`

GetDefaultLanguage returns the DefaultLanguage field if non-nil, zero value otherwise.

### GetDefaultLanguageOk

`func (o *GetConfigResponse) GetDefaultLanguageOk() (*string, bool)`

GetDefaultLanguageOk returns a tuple with the DefaultLanguage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultLanguage

`func (o *GetConfigResponse) SetDefaultLanguage(v string)`

SetDefaultLanguage sets DefaultLanguage field to given value.


### GetExtraPages

`func (o *GetConfigResponse) GetExtraPages() []ExtraPage`

GetExtraPages returns the ExtraPages field if non-nil, zero value otherwise.

### GetExtraPagesOk

`func (o *GetConfigResponse) GetExtraPagesOk() (*[]ExtraPage, bool)`

GetExtraPagesOk returns a tuple with the ExtraPages field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExtraPages

`func (o *GetConfigResponse) SetExtraPages(v []ExtraPage)`

SetExtraPages sets ExtraPages field to given value.


### GetShowResourcesSection

`func (o *GetConfigResponse) GetShowResourcesSection() bool`

GetShowResourcesSection returns the ShowResourcesSection field if non-nil, zero value otherwise.

### GetShowResourcesSectionOk

`func (o *GetConfigResponse) GetShowResourcesSectionOk() (*bool, bool)`

GetShowResourcesSectionOk returns a tuple with the ShowResourcesSection field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShowResourcesSection

`func (o *GetConfigResponse) SetShowResourcesSection(v bool)`

SetShowResourcesSection sets ShowResourcesSection field to given value.

### HasShowResourcesSection

`func (o *GetConfigResponse) HasShowResourcesSection() bool`

HasShowResourcesSection returns a boolean if a field has been set.

### GetEnableVoting

`func (o *GetConfigResponse) GetEnableVoting() bool`

GetEnableVoting returns the EnableVoting field if non-nil, zero value otherwise.

### GetEnableVotingOk

`func (o *GetConfigResponse) GetEnableVotingOk() (*bool, bool)`

GetEnableVotingOk returns a tuple with the EnableVoting field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnableVoting

`func (o *GetConfigResponse) SetEnableVoting(v bool)`

SetEnableVoting sets EnableVoting field to given value.

### HasEnableVoting

`func (o *GetConfigResponse) HasEnableVoting() bool`

HasEnableVoting returns a boolean if a field has been set.

### GetShowAttachmentZipAction

`func (o *GetConfigResponse) GetShowAttachmentZipAction() bool`

GetShowAttachmentZipAction returns the ShowAttachmentZipAction field if non-nil, zero value otherwise.

### GetShowAttachmentZipActionOk

`func (o *GetConfigResponse) GetShowAttachmentZipActionOk() (*bool, bool)`

GetShowAttachmentZipActionOk returns a tuple with the ShowAttachmentZipAction field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShowAttachmentZipAction

`func (o *GetConfigResponse) SetShowAttachmentZipAction(v bool)`

SetShowAttachmentZipAction sets ShowAttachmentZipAction field to given value.

### HasShowAttachmentZipAction

`func (o *GetConfigResponse) HasShowAttachmentZipAction() bool`

HasShowAttachmentZipAction returns a boolean if a field has been set.

### GetAlternativeLoginUrl

`func (o *GetConfigResponse) GetAlternativeLoginUrl() string`

GetAlternativeLoginUrl returns the AlternativeLoginUrl field if non-nil, zero value otherwise.

### GetAlternativeLoginUrlOk

`func (o *GetConfigResponse) GetAlternativeLoginUrlOk() (*string, bool)`

GetAlternativeLoginUrlOk returns a tuple with the AlternativeLoginUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAlternativeLoginUrl

`func (o *GetConfigResponse) SetAlternativeLoginUrl(v string)`

SetAlternativeLoginUrl sets AlternativeLoginUrl field to given value.


### SetAlternativeLoginUrlNil

`func (o *GetConfigResponse) SetAlternativeLoginUrlNil(b bool)`

 SetAlternativeLoginUrlNil sets the value for AlternativeLoginUrl to be an explicit nil

### UnsetAlternativeLoginUrl
`func (o *GetConfigResponse) UnsetAlternativeLoginUrl()`

UnsetAlternativeLoginUrl ensures that no value is present for AlternativeLoginUrl, not even an explicit nil
### GetTables

`func (o *GetConfigResponse) GetTables() map[string]map[string]map[string]interface{}`

GetTables returns the Tables field if non-nil, zero value otherwise.

### GetTablesOk

`func (o *GetConfigResponse) GetTablesOk() (*map[string]map[string]map[string]interface{}, bool)`

GetTablesOk returns a tuple with the Tables field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTables

`func (o *GetConfigResponse) SetTables(v map[string]map[string]map[string]interface{})`

SetTables sets Tables field to given value.

### HasTables

`func (o *GetConfigResponse) HasTables() bool`

HasTables returns a boolean if a field has been set.

### GetEntitlementDefaultLengthDays

`func (o *GetConfigResponse) GetEntitlementDefaultLengthDays() int64`

GetEntitlementDefaultLengthDays returns the EntitlementDefaultLengthDays field if non-nil, zero value otherwise.

### GetEntitlementDefaultLengthDaysOk

`func (o *GetConfigResponse) GetEntitlementDefaultLengthDaysOk() (*int64, bool)`

GetEntitlementDefaultLengthDaysOk returns a tuple with the EntitlementDefaultLengthDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntitlementDefaultLengthDays

`func (o *GetConfigResponse) SetEntitlementDefaultLengthDays(v int64)`

SetEntitlementDefaultLengthDays sets EntitlementDefaultLengthDays field to given value.


### SetEntitlementDefaultLengthDaysNil

`func (o *GetConfigResponse) SetEntitlementDefaultLengthDaysNil(b bool)`

 SetEntitlementDefaultLengthDaysNil sets the value for EntitlementDefaultLengthDays to be an explicit nil

### UnsetEntitlementDefaultLengthDays
`func (o *GetConfigResponse) UnsetEntitlementDefaultLengthDays()`

UnsetEntitlementDefaultLengthDays ensures that no value is present for EntitlementDefaultLengthDays, not even an explicit nil
### GetEnableCart

`func (o *GetConfigResponse) GetEnableCart() bool`

GetEnableCart returns the EnableCart field if non-nil, zero value otherwise.

### GetEnableCartOk

`func (o *GetConfigResponse) GetEnableCartOk() (*bool, bool)`

GetEnableCartOk returns a tuple with the EnableCart field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnableCart

`func (o *GetConfigResponse) SetEnableCart(v bool)`

SetEnableCart sets EnableCart field to given value.

### HasEnableCart

`func (o *GetConfigResponse) HasEnableCart() bool`

HasEnableCart returns a boolean if a field has been set.

### GetEnableCatalogueTree

`func (o *GetConfigResponse) GetEnableCatalogueTree() bool`

GetEnableCatalogueTree returns the EnableCatalogueTree field if non-nil, zero value otherwise.

### GetEnableCatalogueTreeOk

`func (o *GetConfigResponse) GetEnableCatalogueTreeOk() (*bool, bool)`

GetEnableCatalogueTreeOk returns a tuple with the EnableCatalogueTree field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnableCatalogueTree

`func (o *GetConfigResponse) SetEnableCatalogueTree(v bool)`

SetEnableCatalogueTree sets EnableCatalogueTree field to given value.

### HasEnableCatalogueTree

`func (o *GetConfigResponse) HasEnableCatalogueTree() bool`

HasEnableCatalogueTree returns a boolean if a field has been set.

### GetCatalogueIsPublic

`func (o *GetConfigResponse) GetCatalogueIsPublic() bool`

GetCatalogueIsPublic returns the CatalogueIsPublic field if non-nil, zero value otherwise.

### GetCatalogueIsPublicOk

`func (o *GetConfigResponse) GetCatalogueIsPublicOk() (*bool, bool)`

GetCatalogueIsPublicOk returns a tuple with the CatalogueIsPublic field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCatalogueIsPublic

`func (o *GetConfigResponse) SetCatalogueIsPublic(v bool)`

SetCatalogueIsPublic sets CatalogueIsPublic field to given value.


### GetEnableAutosave

`func (o *GetConfigResponse) GetEnableAutosave() bool`

GetEnableAutosave returns the EnableAutosave field if non-nil, zero value otherwise.

### GetEnableAutosaveOk

`func (o *GetConfigResponse) GetEnableAutosaveOk() (*bool, bool)`

GetEnableAutosaveOk returns a tuple with the EnableAutosave field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnableAutosave

`func (o *GetConfigResponse) SetEnableAutosave(v bool)`

SetEnableAutosave sets EnableAutosave field to given value.

### HasEnableAutosave

`func (o *GetConfigResponse) HasEnableAutosave() bool`

HasEnableAutosave returns a boolean if a field has been set.

### GetAuthentication

`func (o *GetConfigResponse) GetAuthentication() string`

GetAuthentication returns the Authentication field if non-nil, zero value otherwise.

### GetAuthenticationOk

`func (o *GetConfigResponse) GetAuthenticationOk() (*string, bool)`

GetAuthenticationOk returns a tuple with the Authentication field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthentication

`func (o *GetConfigResponse) SetAuthentication(v string)`

SetAuthentication sets Authentication field to given value.


### GetEnableDoi

`func (o *GetConfigResponse) GetEnableDoi() bool`

GetEnableDoi returns the EnableDoi field if non-nil, zero value otherwise.

### GetEnableDoiOk

`func (o *GetConfigResponse) GetEnableDoiOk() (*bool, bool)`

GetEnableDoiOk returns a tuple with the EnableDoi field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnableDoi

`func (o *GetConfigResponse) SetEnableDoi(v bool)`

SetEnableDoi sets EnableDoi field to given value.

### HasEnableDoi

`func (o *GetConfigResponse) HasEnableDoi() bool`

HasEnableDoi returns a boolean if a field has been set.

### GetEnableCatalogueTable

`func (o *GetConfigResponse) GetEnableCatalogueTable() bool`

GetEnableCatalogueTable returns the EnableCatalogueTable field if non-nil, zero value otherwise.

### GetEnableCatalogueTableOk

`func (o *GetConfigResponse) GetEnableCatalogueTableOk() (*bool, bool)`

GetEnableCatalogueTableOk returns a tuple with the EnableCatalogueTable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnableCatalogueTable

`func (o *GetConfigResponse) SetEnableCatalogueTable(v bool)`

SetEnableCatalogueTable sets EnableCatalogueTable field to given value.

### HasEnableCatalogueTable

`func (o *GetConfigResponse) HasEnableCatalogueTable() bool`

HasEnableCatalogueTable returns a boolean if a field has been set.

### GetOidcExtraAttributes

`func (o *GetConfigResponse) GetOidcExtraAttributes() []GetConfigResponseOidcExtraAttributes`

GetOidcExtraAttributes returns the OidcExtraAttributes field if non-nil, zero value otherwise.

### GetOidcExtraAttributesOk

`func (o *GetConfigResponse) GetOidcExtraAttributesOk() (*[]GetConfigResponseOidcExtraAttributes, bool)`

GetOidcExtraAttributesOk returns a tuple with the OidcExtraAttributes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOidcExtraAttributes

`func (o *GetConfigResponse) SetOidcExtraAttributes(v []GetConfigResponseOidcExtraAttributes)`

SetOidcExtraAttributes sets OidcExtraAttributes field to given value.


### GetAttachmentMaxSize

`func (o *GetConfigResponse) GetAttachmentMaxSize() int64`

GetAttachmentMaxSize returns the AttachmentMaxSize field if non-nil, zero value otherwise.

### GetAttachmentMaxSizeOk

`func (o *GetConfigResponse) GetAttachmentMaxSizeOk() (*int64, bool)`

GetAttachmentMaxSizeOk returns a tuple with the AttachmentMaxSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttachmentMaxSize

`func (o *GetConfigResponse) SetAttachmentMaxSize(v int64)`

SetAttachmentMaxSize sets AttachmentMaxSize field to given value.


### SetAttachmentMaxSizeNil

`func (o *GetConfigResponse) SetAttachmentMaxSizeNil(b bool)`

 SetAttachmentMaxSizeNil sets the value for AttachmentMaxSize to be an explicit nil

### UnsetAttachmentMaxSize
`func (o *GetConfigResponse) UnsetAttachmentMaxSize()`

UnsetAttachmentMaxSize ensures that no value is present for AttachmentMaxSize, not even an explicit nil
### GetCatalogueTreeShowMatchingParents

`func (o *GetConfigResponse) GetCatalogueTreeShowMatchingParents() bool`

GetCatalogueTreeShowMatchingParents returns the CatalogueTreeShowMatchingParents field if non-nil, zero value otherwise.

### GetCatalogueTreeShowMatchingParentsOk

`func (o *GetConfigResponse) GetCatalogueTreeShowMatchingParentsOk() (*bool, bool)`

GetCatalogueTreeShowMatchingParentsOk returns a tuple with the CatalogueTreeShowMatchingParents field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCatalogueTreeShowMatchingParents

`func (o *GetConfigResponse) SetCatalogueTreeShowMatchingParents(v bool)`

SetCatalogueTreeShowMatchingParents sets CatalogueTreeShowMatchingParents field to given value.

### HasCatalogueTreeShowMatchingParents

`func (o *GetConfigResponse) HasCatalogueTreeShowMatchingParents() bool`

HasCatalogueTreeShowMatchingParents returns a boolean if a field has been set.

### GetApplicationIdColumn

`func (o *GetConfigResponse) GetApplicationIdColumn() string`

GetApplicationIdColumn returns the ApplicationIdColumn field if non-nil, zero value otherwise.

### GetApplicationIdColumnOk

`func (o *GetConfigResponse) GetApplicationIdColumnOk() (*string, bool)`

GetApplicationIdColumnOk returns a tuple with the ApplicationIdColumn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationIdColumn

`func (o *GetConfigResponse) SetApplicationIdColumn(v string)`

SetApplicationIdColumn sets ApplicationIdColumn field to given value.


### GetLanguages

`func (o *GetConfigResponse) GetLanguages() []string`

GetLanguages returns the Languages field if non-nil, zero value otherwise.

### GetLanguagesOk

`func (o *GetConfigResponse) GetLanguagesOk() (*[]string, bool)`

GetLanguagesOk returns a tuple with the Languages field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanguages

`func (o *GetConfigResponse) SetLanguages(v []string)`

SetLanguages sets Languages field to given value.


### GetApplicationListHiddenColumns

`func (o *GetConfigResponse) GetApplicationListHiddenColumns() []string`

GetApplicationListHiddenColumns returns the ApplicationListHiddenColumns field if non-nil, zero value otherwise.

### GetApplicationListHiddenColumnsOk

`func (o *GetConfigResponse) GetApplicationListHiddenColumnsOk() (*[]string, bool)`

GetApplicationListHiddenColumnsOk returns a tuple with the ApplicationListHiddenColumns field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationListHiddenColumns

`func (o *GetConfigResponse) SetApplicationListHiddenColumns(v []string)`

SetApplicationListHiddenColumns sets ApplicationListHiddenColumns field to given value.

### HasApplicationListHiddenColumns

`func (o *GetConfigResponse) HasApplicationListHiddenColumns() bool`

HasApplicationListHiddenColumns returns a boolean if a field has been set.

### GetEnableDuo

`func (o *GetConfigResponse) GetEnableDuo() bool`

GetEnableDuo returns the EnableDuo field if non-nil, zero value otherwise.

### GetEnableDuoOk

`func (o *GetConfigResponse) GetEnableDuoOk() (*bool, bool)`

GetEnableDuoOk returns a tuple with the EnableDuo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnableDuo

`func (o *GetConfigResponse) SetEnableDuo(v bool)`

SetEnableDuo sets EnableDuo field to given value.

### HasEnableDuo

`func (o *GetConfigResponse) HasEnableDuo() bool`

HasEnableDuo returns a boolean if a field has been set.

### GetEnableProcessingStates

`func (o *GetConfigResponse) GetEnableProcessingStates() bool`

GetEnableProcessingStates returns the EnableProcessingStates field if non-nil, zero value otherwise.

### GetEnableProcessingStatesOk

`func (o *GetConfigResponse) GetEnableProcessingStatesOk() (*bool, bool)`

GetEnableProcessingStatesOk returns a tuple with the EnableProcessingStates field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnableProcessingStates

`func (o *GetConfigResponse) SetEnableProcessingStates(v bool)`

SetEnableProcessingStates sets EnableProcessingStates field to given value.

### HasEnableProcessingStates

`func (o *GetConfigResponse) HasEnableProcessingStates() bool`

HasEnableProcessingStates returns a boolean if a field has been set.

### GetEnableAssignExternalIdUi

`func (o *GetConfigResponse) GetEnableAssignExternalIdUi() bool`

GetEnableAssignExternalIdUi returns the EnableAssignExternalIdUi field if non-nil, zero value otherwise.

### GetEnableAssignExternalIdUiOk

`func (o *GetConfigResponse) GetEnableAssignExternalIdUiOk() (*bool, bool)`

GetEnableAssignExternalIdUiOk returns a tuple with the EnableAssignExternalIdUi field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnableAssignExternalIdUi

`func (o *GetConfigResponse) SetEnableAssignExternalIdUi(v bool)`

SetEnableAssignExternalIdUi sets EnableAssignExternalIdUi field to given value.


### GetDev

`func (o *GetConfigResponse) GetDev() bool`

GetDev returns the Dev field if non-nil, zero value otherwise.

### GetDevOk

`func (o *GetConfigResponse) GetDevOk() (*bool, bool)`

GetDevOk returns a tuple with the Dev field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDev

`func (o *GetConfigResponse) SetDev(v bool)`

SetDev sets Dev field to given value.


### GetShowPdfAction

`func (o *GetConfigResponse) GetShowPdfAction() bool`

GetShowPdfAction returns the ShowPdfAction field if non-nil, zero value otherwise.

### GetShowPdfActionOk

`func (o *GetConfigResponse) GetShowPdfActionOk() (*bool, bool)`

GetShowPdfActionOk returns a tuple with the ShowPdfAction field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShowPdfAction

`func (o *GetConfigResponse) SetShowPdfAction(v bool)`

SetShowPdfAction sets ShowPdfAction field to given value.

### HasShowPdfAction

`func (o *GetConfigResponse) HasShowPdfAction() bool`

HasShowPdfAction returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


