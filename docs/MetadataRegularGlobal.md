# MetadataRegularGlobal

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**TopicId** | Pointer to **int64** |  | [optional] 
**TopicName** | Pointer to **string** |  | [optional] 
**TopicTickers** | Pointer to **[]string** |  | [optional] 
**Groups** | Pointer to [**[]MetadataRegularGlobalGroup**](MetadataRegularGlobalGroup.md) |  | [optional] 
**Tickers** | Pointer to [**[]MetadataRegularGlobalTicker**](MetadataRegularGlobalTicker.md) |  | [optional] 

## Methods

### NewMetadataRegularGlobal

`func NewMetadataRegularGlobal() *MetadataRegularGlobal`

NewMetadataRegularGlobal instantiates a new MetadataRegularGlobal object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMetadataRegularGlobalWithDefaults

`func NewMetadataRegularGlobalWithDefaults() *MetadataRegularGlobal`

NewMetadataRegularGlobalWithDefaults instantiates a new MetadataRegularGlobal object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTopicId

`func (o *MetadataRegularGlobal) GetTopicId() int64`

GetTopicId returns the TopicId field if non-nil, zero value otherwise.

### GetTopicIdOk

`func (o *MetadataRegularGlobal) GetTopicIdOk() (*int64, bool)`

GetTopicIdOk returns a tuple with the TopicId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTopicId

`func (o *MetadataRegularGlobal) SetTopicId(v int64)`

SetTopicId sets TopicId field to given value.

### HasTopicId

`func (o *MetadataRegularGlobal) HasTopicId() bool`

HasTopicId returns a boolean if a field has been set.

### GetTopicName

`func (o *MetadataRegularGlobal) GetTopicName() string`

GetTopicName returns the TopicName field if non-nil, zero value otherwise.

### GetTopicNameOk

`func (o *MetadataRegularGlobal) GetTopicNameOk() (*string, bool)`

GetTopicNameOk returns a tuple with the TopicName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTopicName

`func (o *MetadataRegularGlobal) SetTopicName(v string)`

SetTopicName sets TopicName field to given value.

### HasTopicName

`func (o *MetadataRegularGlobal) HasTopicName() bool`

HasTopicName returns a boolean if a field has been set.

### GetTopicTickers

`func (o *MetadataRegularGlobal) GetTopicTickers() []string`

GetTopicTickers returns the TopicTickers field if non-nil, zero value otherwise.

### GetTopicTickersOk

`func (o *MetadataRegularGlobal) GetTopicTickersOk() (*[]string, bool)`

GetTopicTickersOk returns a tuple with the TopicTickers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTopicTickers

`func (o *MetadataRegularGlobal) SetTopicTickers(v []string)`

SetTopicTickers sets TopicTickers field to given value.

### HasTopicTickers

`func (o *MetadataRegularGlobal) HasTopicTickers() bool`

HasTopicTickers returns a boolean if a field has been set.

### GetGroups

`func (o *MetadataRegularGlobal) GetGroups() []MetadataRegularGlobalGroup`

GetGroups returns the Groups field if non-nil, zero value otherwise.

### GetGroupsOk

`func (o *MetadataRegularGlobal) GetGroupsOk() (*[]MetadataRegularGlobalGroup, bool)`

GetGroupsOk returns a tuple with the Groups field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroups

`func (o *MetadataRegularGlobal) SetGroups(v []MetadataRegularGlobalGroup)`

SetGroups sets Groups field to given value.

### HasGroups

`func (o *MetadataRegularGlobal) HasGroups() bool`

HasGroups returns a boolean if a field has been set.

### GetTickers

`func (o *MetadataRegularGlobal) GetTickers() []MetadataRegularGlobalTicker`

GetTickers returns the Tickers field if non-nil, zero value otherwise.

### GetTickersOk

`func (o *MetadataRegularGlobal) GetTickersOk() (*[]MetadataRegularGlobalTicker, bool)`

GetTickersOk returns a tuple with the Tickers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTickers

`func (o *MetadataRegularGlobal) SetTickers(v []MetadataRegularGlobalTicker)`

SetTickers sets Tickers field to given value.

### HasTickers

`func (o *MetadataRegularGlobal) HasTickers() bool`

HasTickers returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


