# MetadataRegularGlobal

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**TopicId** | Pointer to **int64** |  | [optional] 
**TopicName** | Pointer to **string** |  | [optional] 
**TopicTickers** | Pointer to **[]string** |  | [optional] 
**TopicLegalEntities** | Pointer to **string** |  | [optional] 
**OrderPriority** | Pointer to **int64** |  | [optional] 
**Attributes** | Pointer to [**MetadataRegularGlobalAttributes**](MetadataRegularGlobalAttributes.md) |  | [optional] 
**Groups** | Pointer to [**[]MetadataRegularGlobalGroup**](MetadataRegularGlobalGroup.md) |  | [optional] 
**Tickers** | Pointer to [**[]MetadataRegularGlobalTicker**](MetadataRegularGlobalTicker.md) |  | [optional] 
**TradingViewTicker** | Pointer to **string** |  | [optional] 
**Figis** | Pointer to **string** |  | [optional] 
**CompanyDomains** | Pointer to **string** |  | [optional] 
**Score** | Pointer to **string** |  | [optional] 
**Highlight** | Pointer to **string** |  | [optional] 
**Permalink** | Pointer to **string** |  | [optional] 
**IsinAliases** | Pointer to **string** |  | [optional] 
**AssetClassSearchKeywords** | Pointer to **string** |  | [optional] 

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

### GetTopicLegalEntities

`func (o *MetadataRegularGlobal) GetTopicLegalEntities() string`

GetTopicLegalEntities returns the TopicLegalEntities field if non-nil, zero value otherwise.

### GetTopicLegalEntitiesOk

`func (o *MetadataRegularGlobal) GetTopicLegalEntitiesOk() (*string, bool)`

GetTopicLegalEntitiesOk returns a tuple with the TopicLegalEntities field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTopicLegalEntities

`func (o *MetadataRegularGlobal) SetTopicLegalEntities(v string)`

SetTopicLegalEntities sets TopicLegalEntities field to given value.

### HasTopicLegalEntities

`func (o *MetadataRegularGlobal) HasTopicLegalEntities() bool`

HasTopicLegalEntities returns a boolean if a field has been set.

### GetOrderPriority

`func (o *MetadataRegularGlobal) GetOrderPriority() int64`

GetOrderPriority returns the OrderPriority field if non-nil, zero value otherwise.

### GetOrderPriorityOk

`func (o *MetadataRegularGlobal) GetOrderPriorityOk() (*int64, bool)`

GetOrderPriorityOk returns a tuple with the OrderPriority field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderPriority

`func (o *MetadataRegularGlobal) SetOrderPriority(v int64)`

SetOrderPriority sets OrderPriority field to given value.

### HasOrderPriority

`func (o *MetadataRegularGlobal) HasOrderPriority() bool`

HasOrderPriority returns a boolean if a field has been set.

### GetAttributes

`func (o *MetadataRegularGlobal) GetAttributes() MetadataRegularGlobalAttributes`

GetAttributes returns the Attributes field if non-nil, zero value otherwise.

### GetAttributesOk

`func (o *MetadataRegularGlobal) GetAttributesOk() (*MetadataRegularGlobalAttributes, bool)`

GetAttributesOk returns a tuple with the Attributes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttributes

`func (o *MetadataRegularGlobal) SetAttributes(v MetadataRegularGlobalAttributes)`

SetAttributes sets Attributes field to given value.

### HasAttributes

`func (o *MetadataRegularGlobal) HasAttributes() bool`

HasAttributes returns a boolean if a field has been set.

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

### GetTradingViewTicker

`func (o *MetadataRegularGlobal) GetTradingViewTicker() string`

GetTradingViewTicker returns the TradingViewTicker field if non-nil, zero value otherwise.

### GetTradingViewTickerOk

`func (o *MetadataRegularGlobal) GetTradingViewTickerOk() (*string, bool)`

GetTradingViewTickerOk returns a tuple with the TradingViewTicker field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTradingViewTicker

`func (o *MetadataRegularGlobal) SetTradingViewTicker(v string)`

SetTradingViewTicker sets TradingViewTicker field to given value.

### HasTradingViewTicker

`func (o *MetadataRegularGlobal) HasTradingViewTicker() bool`

HasTradingViewTicker returns a boolean if a field has been set.

### GetFigis

`func (o *MetadataRegularGlobal) GetFigis() string`

GetFigis returns the Figis field if non-nil, zero value otherwise.

### GetFigisOk

`func (o *MetadataRegularGlobal) GetFigisOk() (*string, bool)`

GetFigisOk returns a tuple with the Figis field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFigis

`func (o *MetadataRegularGlobal) SetFigis(v string)`

SetFigis sets Figis field to given value.

### HasFigis

`func (o *MetadataRegularGlobal) HasFigis() bool`

HasFigis returns a boolean if a field has been set.

### GetCompanyDomains

`func (o *MetadataRegularGlobal) GetCompanyDomains() string`

GetCompanyDomains returns the CompanyDomains field if non-nil, zero value otherwise.

### GetCompanyDomainsOk

`func (o *MetadataRegularGlobal) GetCompanyDomainsOk() (*string, bool)`

GetCompanyDomainsOk returns a tuple with the CompanyDomains field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompanyDomains

`func (o *MetadataRegularGlobal) SetCompanyDomains(v string)`

SetCompanyDomains sets CompanyDomains field to given value.

### HasCompanyDomains

`func (o *MetadataRegularGlobal) HasCompanyDomains() bool`

HasCompanyDomains returns a boolean if a field has been set.

### GetScore

`func (o *MetadataRegularGlobal) GetScore() string`

GetScore returns the Score field if non-nil, zero value otherwise.

### GetScoreOk

`func (o *MetadataRegularGlobal) GetScoreOk() (*string, bool)`

GetScoreOk returns a tuple with the Score field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScore

`func (o *MetadataRegularGlobal) SetScore(v string)`

SetScore sets Score field to given value.

### HasScore

`func (o *MetadataRegularGlobal) HasScore() bool`

HasScore returns a boolean if a field has been set.

### GetHighlight

`func (o *MetadataRegularGlobal) GetHighlight() string`

GetHighlight returns the Highlight field if non-nil, zero value otherwise.

### GetHighlightOk

`func (o *MetadataRegularGlobal) GetHighlightOk() (*string, bool)`

GetHighlightOk returns a tuple with the Highlight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHighlight

`func (o *MetadataRegularGlobal) SetHighlight(v string)`

SetHighlight sets Highlight field to given value.

### HasHighlight

`func (o *MetadataRegularGlobal) HasHighlight() bool`

HasHighlight returns a boolean if a field has been set.

### GetPermalink

`func (o *MetadataRegularGlobal) GetPermalink() string`

GetPermalink returns the Permalink field if non-nil, zero value otherwise.

### GetPermalinkOk

`func (o *MetadataRegularGlobal) GetPermalinkOk() (*string, bool)`

GetPermalinkOk returns a tuple with the Permalink field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPermalink

`func (o *MetadataRegularGlobal) SetPermalink(v string)`

SetPermalink sets Permalink field to given value.

### HasPermalink

`func (o *MetadataRegularGlobal) HasPermalink() bool`

HasPermalink returns a boolean if a field has been set.

### GetIsinAliases

`func (o *MetadataRegularGlobal) GetIsinAliases() string`

GetIsinAliases returns the IsinAliases field if non-nil, zero value otherwise.

### GetIsinAliasesOk

`func (o *MetadataRegularGlobal) GetIsinAliasesOk() (*string, bool)`

GetIsinAliasesOk returns a tuple with the IsinAliases field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsinAliases

`func (o *MetadataRegularGlobal) SetIsinAliases(v string)`

SetIsinAliases sets IsinAliases field to given value.

### HasIsinAliases

`func (o *MetadataRegularGlobal) HasIsinAliases() bool`

HasIsinAliases returns a boolean if a field has been set.

### GetAssetClassSearchKeywords

`func (o *MetadataRegularGlobal) GetAssetClassSearchKeywords() string`

GetAssetClassSearchKeywords returns the AssetClassSearchKeywords field if non-nil, zero value otherwise.

### GetAssetClassSearchKeywordsOk

`func (o *MetadataRegularGlobal) GetAssetClassSearchKeywordsOk() (*string, bool)`

GetAssetClassSearchKeywordsOk returns a tuple with the AssetClassSearchKeywords field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssetClassSearchKeywords

`func (o *MetadataRegularGlobal) SetAssetClassSearchKeywords(v string)`

SetAssetClassSearchKeywords sets AssetClassSearchKeywords field to given value.

### HasAssetClassSearchKeywords

`func (o *MetadataRegularGlobal) HasAssetClassSearchKeywords() bool`

HasAssetClassSearchKeywords returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


