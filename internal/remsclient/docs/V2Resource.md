# V2Resource

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CatalogueItemEnd** | **NullableTime** |  | 
**CatalogueItemExpired** | **bool** |  | 
**CatalogueItemEnabled** | **bool** |  | 
**ResourceId** | **int64** |  | 
**CatalogueItemTitle** | **map[string]string** | Text values keyed by languages | 
**ResourceDuo** | Pointer to [**Response7799ResourcesDuo**](Response7799ResourcesDuo.md) |  | [optional] 
**CatalogueItemInfourl** | **map[string]string** | Text values keyed by languages | 
**ResourceExtId** | **string** |  | 
**CatalogueItemStart** | **time.Time** |  | 
**CatalogueItemArchived** | **bool** |  | 
**CatalogueItemId** | **int64** |  | 

## Methods

### NewV2Resource

`func NewV2Resource(catalogueItemEnd NullableTime, catalogueItemExpired bool, catalogueItemEnabled bool, resourceId int64, catalogueItemTitle map[string]string, catalogueItemInfourl map[string]string, resourceExtId string, catalogueItemStart time.Time, catalogueItemArchived bool, catalogueItemId int64, ) *V2Resource`

NewV2Resource instantiates a new V2Resource object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV2ResourceWithDefaults

`func NewV2ResourceWithDefaults() *V2Resource`

NewV2ResourceWithDefaults instantiates a new V2Resource object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCatalogueItemEnd

`func (o *V2Resource) GetCatalogueItemEnd() time.Time`

GetCatalogueItemEnd returns the CatalogueItemEnd field if non-nil, zero value otherwise.

### GetCatalogueItemEndOk

`func (o *V2Resource) GetCatalogueItemEndOk() (*time.Time, bool)`

GetCatalogueItemEndOk returns a tuple with the CatalogueItemEnd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCatalogueItemEnd

`func (o *V2Resource) SetCatalogueItemEnd(v time.Time)`

SetCatalogueItemEnd sets CatalogueItemEnd field to given value.


### SetCatalogueItemEndNil

`func (o *V2Resource) SetCatalogueItemEndNil(b bool)`

 SetCatalogueItemEndNil sets the value for CatalogueItemEnd to be an explicit nil

### UnsetCatalogueItemEnd
`func (o *V2Resource) UnsetCatalogueItemEnd()`

UnsetCatalogueItemEnd ensures that no value is present for CatalogueItemEnd, not even an explicit nil
### GetCatalogueItemExpired

`func (o *V2Resource) GetCatalogueItemExpired() bool`

GetCatalogueItemExpired returns the CatalogueItemExpired field if non-nil, zero value otherwise.

### GetCatalogueItemExpiredOk

`func (o *V2Resource) GetCatalogueItemExpiredOk() (*bool, bool)`

GetCatalogueItemExpiredOk returns a tuple with the CatalogueItemExpired field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCatalogueItemExpired

`func (o *V2Resource) SetCatalogueItemExpired(v bool)`

SetCatalogueItemExpired sets CatalogueItemExpired field to given value.


### GetCatalogueItemEnabled

`func (o *V2Resource) GetCatalogueItemEnabled() bool`

GetCatalogueItemEnabled returns the CatalogueItemEnabled field if non-nil, zero value otherwise.

### GetCatalogueItemEnabledOk

`func (o *V2Resource) GetCatalogueItemEnabledOk() (*bool, bool)`

GetCatalogueItemEnabledOk returns a tuple with the CatalogueItemEnabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCatalogueItemEnabled

`func (o *V2Resource) SetCatalogueItemEnabled(v bool)`

SetCatalogueItemEnabled sets CatalogueItemEnabled field to given value.


### GetResourceId

`func (o *V2Resource) GetResourceId() int64`

GetResourceId returns the ResourceId field if non-nil, zero value otherwise.

### GetResourceIdOk

`func (o *V2Resource) GetResourceIdOk() (*int64, bool)`

GetResourceIdOk returns a tuple with the ResourceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResourceId

`func (o *V2Resource) SetResourceId(v int64)`

SetResourceId sets ResourceId field to given value.


### GetCatalogueItemTitle

`func (o *V2Resource) GetCatalogueItemTitle() map[string]string`

GetCatalogueItemTitle returns the CatalogueItemTitle field if non-nil, zero value otherwise.

### GetCatalogueItemTitleOk

`func (o *V2Resource) GetCatalogueItemTitleOk() (*map[string]string, bool)`

GetCatalogueItemTitleOk returns a tuple with the CatalogueItemTitle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCatalogueItemTitle

`func (o *V2Resource) SetCatalogueItemTitle(v map[string]string)`

SetCatalogueItemTitle sets CatalogueItemTitle field to given value.


### GetResourceDuo

`func (o *V2Resource) GetResourceDuo() Response7799ResourcesDuo`

GetResourceDuo returns the ResourceDuo field if non-nil, zero value otherwise.

### GetResourceDuoOk

`func (o *V2Resource) GetResourceDuoOk() (*Response7799ResourcesDuo, bool)`

GetResourceDuoOk returns a tuple with the ResourceDuo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResourceDuo

`func (o *V2Resource) SetResourceDuo(v Response7799ResourcesDuo)`

SetResourceDuo sets ResourceDuo field to given value.

### HasResourceDuo

`func (o *V2Resource) HasResourceDuo() bool`

HasResourceDuo returns a boolean if a field has been set.

### GetCatalogueItemInfourl

`func (o *V2Resource) GetCatalogueItemInfourl() map[string]string`

GetCatalogueItemInfourl returns the CatalogueItemInfourl field if non-nil, zero value otherwise.

### GetCatalogueItemInfourlOk

`func (o *V2Resource) GetCatalogueItemInfourlOk() (*map[string]string, bool)`

GetCatalogueItemInfourlOk returns a tuple with the CatalogueItemInfourl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCatalogueItemInfourl

`func (o *V2Resource) SetCatalogueItemInfourl(v map[string]string)`

SetCatalogueItemInfourl sets CatalogueItemInfourl field to given value.


### GetResourceExtId

`func (o *V2Resource) GetResourceExtId() string`

GetResourceExtId returns the ResourceExtId field if non-nil, zero value otherwise.

### GetResourceExtIdOk

`func (o *V2Resource) GetResourceExtIdOk() (*string, bool)`

GetResourceExtIdOk returns a tuple with the ResourceExtId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResourceExtId

`func (o *V2Resource) SetResourceExtId(v string)`

SetResourceExtId sets ResourceExtId field to given value.


### GetCatalogueItemStart

`func (o *V2Resource) GetCatalogueItemStart() time.Time`

GetCatalogueItemStart returns the CatalogueItemStart field if non-nil, zero value otherwise.

### GetCatalogueItemStartOk

`func (o *V2Resource) GetCatalogueItemStartOk() (*time.Time, bool)`

GetCatalogueItemStartOk returns a tuple with the CatalogueItemStart field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCatalogueItemStart

`func (o *V2Resource) SetCatalogueItemStart(v time.Time)`

SetCatalogueItemStart sets CatalogueItemStart field to given value.


### GetCatalogueItemArchived

`func (o *V2Resource) GetCatalogueItemArchived() bool`

GetCatalogueItemArchived returns the CatalogueItemArchived field if non-nil, zero value otherwise.

### GetCatalogueItemArchivedOk

`func (o *V2Resource) GetCatalogueItemArchivedOk() (*bool, bool)`

GetCatalogueItemArchivedOk returns a tuple with the CatalogueItemArchived field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCatalogueItemArchived

`func (o *V2Resource) SetCatalogueItemArchived(v bool)`

SetCatalogueItemArchived sets CatalogueItemArchived field to given value.


### GetCatalogueItemId

`func (o *V2Resource) GetCatalogueItemId() int64`

GetCatalogueItemId returns the CatalogueItemId field if non-nil, zero value otherwise.

### GetCatalogueItemIdOk

`func (o *V2Resource) GetCatalogueItemIdOk() (*int64, bool)`

GetCatalogueItemIdOk returns a tuple with the CatalogueItemId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCatalogueItemId

`func (o *V2Resource) SetCatalogueItemId(v int64)`

SetCatalogueItemId sets CatalogueItemId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


