# Story

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int64** |  | [optional] 
**Uuid** | Pointer to **string** |  | [optional] 
**UuidTitle** | Pointer to **string** |  | [optional] 
**PublishTime** | Pointer to **time.Time** |  | [optional] 
**PublishTimeDiff** | Pointer to **float32** |  | [optional] 
**Title** | Pointer to **string** |  | [optional] 
**Description** | Pointer to **string** |  | [optional] 
**FullText** | Pointer to **bool** |  | [optional] 
**Category** | Pointer to **string** |  | [optional] 
**Url** | Pointer to **string** |  | [optional] 
**ExpandedUrl** | Pointer to **string** |  | [optional] 
**Lang** | Pointer to **string** |  | [optional] 
**DuplicatesCount** | Pointer to **int32** |  | [optional] 
**ReadCount** | Pointer to **int32** |  | [optional] 
**Paywall** | Pointer to **bool** |  | [optional] 
**RegistrationRequired** | Pointer to **bool** |  | [optional] 
**AuthorImageUrl** | Pointer to **string** |  | [optional] 
**AuthorScreenName** | Pointer to **string** |  | [optional] 
**AuthorFollowersCount** | Pointer to **int32** |  | [optional] 
**FriendsCount** | Pointer to **int32** |  | [optional] 
**DomainId** | Pointer to **int32** |  | [optional] 
**DomainName** | Pointer to **string** |  | [optional] 
**DomainHost** | Pointer to **string** |  | [optional] 
**DomainCachedLogoUrl** | Pointer to **string** |  | [optional] 
**ShowPath** | Pointer to **string** |  | [optional] 
**Type** | Pointer to **string** |  | [optional] 
**Liked** | Pointer to **bool** |  | [optional] 
**Disliked** | Pointer to **bool** |  | [optional] 
**Bookmarked** | Pointer to **bool** |  | [optional] 
**SimilarStoriesCount** | Pointer to **int32** |  | [optional] 
**Score** | Pointer to **float32** |  | [optional] 

## Methods

### NewStory

`func NewStory() *Story`

NewStory instantiates a new Story object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStoryWithDefaults

`func NewStoryWithDefaults() *Story`

NewStoryWithDefaults instantiates a new Story object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *Story) GetId() int64`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Story) GetIdOk() (*int64, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Story) SetId(v int64)`

SetId sets Id field to given value.

### HasId

`func (o *Story) HasId() bool`

HasId returns a boolean if a field has been set.

### GetUuid

`func (o *Story) GetUuid() string`

GetUuid returns the Uuid field if non-nil, zero value otherwise.

### GetUuidOk

`func (o *Story) GetUuidOk() (*string, bool)`

GetUuidOk returns a tuple with the Uuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUuid

`func (o *Story) SetUuid(v string)`

SetUuid sets Uuid field to given value.

### HasUuid

`func (o *Story) HasUuid() bool`

HasUuid returns a boolean if a field has been set.

### GetUuidTitle

`func (o *Story) GetUuidTitle() string`

GetUuidTitle returns the UuidTitle field if non-nil, zero value otherwise.

### GetUuidTitleOk

`func (o *Story) GetUuidTitleOk() (*string, bool)`

GetUuidTitleOk returns a tuple with the UuidTitle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUuidTitle

`func (o *Story) SetUuidTitle(v string)`

SetUuidTitle sets UuidTitle field to given value.

### HasUuidTitle

`func (o *Story) HasUuidTitle() bool`

HasUuidTitle returns a boolean if a field has been set.

### GetPublishTime

`func (o *Story) GetPublishTime() time.Time`

GetPublishTime returns the PublishTime field if non-nil, zero value otherwise.

### GetPublishTimeOk

`func (o *Story) GetPublishTimeOk() (*time.Time, bool)`

GetPublishTimeOk returns a tuple with the PublishTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublishTime

`func (o *Story) SetPublishTime(v time.Time)`

SetPublishTime sets PublishTime field to given value.

### HasPublishTime

`func (o *Story) HasPublishTime() bool`

HasPublishTime returns a boolean if a field has been set.

### GetPublishTimeDiff

`func (o *Story) GetPublishTimeDiff() float32`

GetPublishTimeDiff returns the PublishTimeDiff field if non-nil, zero value otherwise.

### GetPublishTimeDiffOk

`func (o *Story) GetPublishTimeDiffOk() (*float32, bool)`

GetPublishTimeDiffOk returns a tuple with the PublishTimeDiff field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublishTimeDiff

`func (o *Story) SetPublishTimeDiff(v float32)`

SetPublishTimeDiff sets PublishTimeDiff field to given value.

### HasPublishTimeDiff

`func (o *Story) HasPublishTimeDiff() bool`

HasPublishTimeDiff returns a boolean if a field has been set.

### GetTitle

`func (o *Story) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *Story) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *Story) SetTitle(v string)`

SetTitle sets Title field to given value.

### HasTitle

`func (o *Story) HasTitle() bool`

HasTitle returns a boolean if a field has been set.

### GetDescription

`func (o *Story) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *Story) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *Story) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *Story) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetFullText

`func (o *Story) GetFullText() bool`

GetFullText returns the FullText field if non-nil, zero value otherwise.

### GetFullTextOk

`func (o *Story) GetFullTextOk() (*bool, bool)`

GetFullTextOk returns a tuple with the FullText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFullText

`func (o *Story) SetFullText(v bool)`

SetFullText sets FullText field to given value.

### HasFullText

`func (o *Story) HasFullText() bool`

HasFullText returns a boolean if a field has been set.

### GetCategory

`func (o *Story) GetCategory() string`

GetCategory returns the Category field if non-nil, zero value otherwise.

### GetCategoryOk

`func (o *Story) GetCategoryOk() (*string, bool)`

GetCategoryOk returns a tuple with the Category field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategory

`func (o *Story) SetCategory(v string)`

SetCategory sets Category field to given value.

### HasCategory

`func (o *Story) HasCategory() bool`

HasCategory returns a boolean if a field has been set.

### GetUrl

`func (o *Story) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *Story) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *Story) SetUrl(v string)`

SetUrl sets Url field to given value.

### HasUrl

`func (o *Story) HasUrl() bool`

HasUrl returns a boolean if a field has been set.

### GetExpandedUrl

`func (o *Story) GetExpandedUrl() string`

GetExpandedUrl returns the ExpandedUrl field if non-nil, zero value otherwise.

### GetExpandedUrlOk

`func (o *Story) GetExpandedUrlOk() (*string, bool)`

GetExpandedUrlOk returns a tuple with the ExpandedUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpandedUrl

`func (o *Story) SetExpandedUrl(v string)`

SetExpandedUrl sets ExpandedUrl field to given value.

### HasExpandedUrl

`func (o *Story) HasExpandedUrl() bool`

HasExpandedUrl returns a boolean if a field has been set.

### GetLang

`func (o *Story) GetLang() string`

GetLang returns the Lang field if non-nil, zero value otherwise.

### GetLangOk

`func (o *Story) GetLangOk() (*string, bool)`

GetLangOk returns a tuple with the Lang field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLang

`func (o *Story) SetLang(v string)`

SetLang sets Lang field to given value.

### HasLang

`func (o *Story) HasLang() bool`

HasLang returns a boolean if a field has been set.

### GetDuplicatesCount

`func (o *Story) GetDuplicatesCount() int32`

GetDuplicatesCount returns the DuplicatesCount field if non-nil, zero value otherwise.

### GetDuplicatesCountOk

`func (o *Story) GetDuplicatesCountOk() (*int32, bool)`

GetDuplicatesCountOk returns a tuple with the DuplicatesCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDuplicatesCount

`func (o *Story) SetDuplicatesCount(v int32)`

SetDuplicatesCount sets DuplicatesCount field to given value.

### HasDuplicatesCount

`func (o *Story) HasDuplicatesCount() bool`

HasDuplicatesCount returns a boolean if a field has been set.

### GetReadCount

`func (o *Story) GetReadCount() int32`

GetReadCount returns the ReadCount field if non-nil, zero value otherwise.

### GetReadCountOk

`func (o *Story) GetReadCountOk() (*int32, bool)`

GetReadCountOk returns a tuple with the ReadCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReadCount

`func (o *Story) SetReadCount(v int32)`

SetReadCount sets ReadCount field to given value.

### HasReadCount

`func (o *Story) HasReadCount() bool`

HasReadCount returns a boolean if a field has been set.

### GetPaywall

`func (o *Story) GetPaywall() bool`

GetPaywall returns the Paywall field if non-nil, zero value otherwise.

### GetPaywallOk

`func (o *Story) GetPaywallOk() (*bool, bool)`

GetPaywallOk returns a tuple with the Paywall field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaywall

`func (o *Story) SetPaywall(v bool)`

SetPaywall sets Paywall field to given value.

### HasPaywall

`func (o *Story) HasPaywall() bool`

HasPaywall returns a boolean if a field has been set.

### GetRegistrationRequired

`func (o *Story) GetRegistrationRequired() bool`

GetRegistrationRequired returns the RegistrationRequired field if non-nil, zero value otherwise.

### GetRegistrationRequiredOk

`func (o *Story) GetRegistrationRequiredOk() (*bool, bool)`

GetRegistrationRequiredOk returns a tuple with the RegistrationRequired field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegistrationRequired

`func (o *Story) SetRegistrationRequired(v bool)`

SetRegistrationRequired sets RegistrationRequired field to given value.

### HasRegistrationRequired

`func (o *Story) HasRegistrationRequired() bool`

HasRegistrationRequired returns a boolean if a field has been set.

### GetAuthorImageUrl

`func (o *Story) GetAuthorImageUrl() string`

GetAuthorImageUrl returns the AuthorImageUrl field if non-nil, zero value otherwise.

### GetAuthorImageUrlOk

`func (o *Story) GetAuthorImageUrlOk() (*string, bool)`

GetAuthorImageUrlOk returns a tuple with the AuthorImageUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthorImageUrl

`func (o *Story) SetAuthorImageUrl(v string)`

SetAuthorImageUrl sets AuthorImageUrl field to given value.

### HasAuthorImageUrl

`func (o *Story) HasAuthorImageUrl() bool`

HasAuthorImageUrl returns a boolean if a field has been set.

### GetAuthorScreenName

`func (o *Story) GetAuthorScreenName() string`

GetAuthorScreenName returns the AuthorScreenName field if non-nil, zero value otherwise.

### GetAuthorScreenNameOk

`func (o *Story) GetAuthorScreenNameOk() (*string, bool)`

GetAuthorScreenNameOk returns a tuple with the AuthorScreenName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthorScreenName

`func (o *Story) SetAuthorScreenName(v string)`

SetAuthorScreenName sets AuthorScreenName field to given value.

### HasAuthorScreenName

`func (o *Story) HasAuthorScreenName() bool`

HasAuthorScreenName returns a boolean if a field has been set.

### GetAuthorFollowersCount

`func (o *Story) GetAuthorFollowersCount() int32`

GetAuthorFollowersCount returns the AuthorFollowersCount field if non-nil, zero value otherwise.

### GetAuthorFollowersCountOk

`func (o *Story) GetAuthorFollowersCountOk() (*int32, bool)`

GetAuthorFollowersCountOk returns a tuple with the AuthorFollowersCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthorFollowersCount

`func (o *Story) SetAuthorFollowersCount(v int32)`

SetAuthorFollowersCount sets AuthorFollowersCount field to given value.

### HasAuthorFollowersCount

`func (o *Story) HasAuthorFollowersCount() bool`

HasAuthorFollowersCount returns a boolean if a field has been set.

### GetFriendsCount

`func (o *Story) GetFriendsCount() int32`

GetFriendsCount returns the FriendsCount field if non-nil, zero value otherwise.

### GetFriendsCountOk

`func (o *Story) GetFriendsCountOk() (*int32, bool)`

GetFriendsCountOk returns a tuple with the FriendsCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFriendsCount

`func (o *Story) SetFriendsCount(v int32)`

SetFriendsCount sets FriendsCount field to given value.

### HasFriendsCount

`func (o *Story) HasFriendsCount() bool`

HasFriendsCount returns a boolean if a field has been set.

### GetDomainId

`func (o *Story) GetDomainId() int32`

GetDomainId returns the DomainId field if non-nil, zero value otherwise.

### GetDomainIdOk

`func (o *Story) GetDomainIdOk() (*int32, bool)`

GetDomainIdOk returns a tuple with the DomainId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomainId

`func (o *Story) SetDomainId(v int32)`

SetDomainId sets DomainId field to given value.

### HasDomainId

`func (o *Story) HasDomainId() bool`

HasDomainId returns a boolean if a field has been set.

### GetDomainName

`func (o *Story) GetDomainName() string`

GetDomainName returns the DomainName field if non-nil, zero value otherwise.

### GetDomainNameOk

`func (o *Story) GetDomainNameOk() (*string, bool)`

GetDomainNameOk returns a tuple with the DomainName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomainName

`func (o *Story) SetDomainName(v string)`

SetDomainName sets DomainName field to given value.

### HasDomainName

`func (o *Story) HasDomainName() bool`

HasDomainName returns a boolean if a field has been set.

### GetDomainHost

`func (o *Story) GetDomainHost() string`

GetDomainHost returns the DomainHost field if non-nil, zero value otherwise.

### GetDomainHostOk

`func (o *Story) GetDomainHostOk() (*string, bool)`

GetDomainHostOk returns a tuple with the DomainHost field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomainHost

`func (o *Story) SetDomainHost(v string)`

SetDomainHost sets DomainHost field to given value.

### HasDomainHost

`func (o *Story) HasDomainHost() bool`

HasDomainHost returns a boolean if a field has been set.

### GetDomainCachedLogoUrl

`func (o *Story) GetDomainCachedLogoUrl() string`

GetDomainCachedLogoUrl returns the DomainCachedLogoUrl field if non-nil, zero value otherwise.

### GetDomainCachedLogoUrlOk

`func (o *Story) GetDomainCachedLogoUrlOk() (*string, bool)`

GetDomainCachedLogoUrlOk returns a tuple with the DomainCachedLogoUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomainCachedLogoUrl

`func (o *Story) SetDomainCachedLogoUrl(v string)`

SetDomainCachedLogoUrl sets DomainCachedLogoUrl field to given value.

### HasDomainCachedLogoUrl

`func (o *Story) HasDomainCachedLogoUrl() bool`

HasDomainCachedLogoUrl returns a boolean if a field has been set.

### GetShowPath

`func (o *Story) GetShowPath() string`

GetShowPath returns the ShowPath field if non-nil, zero value otherwise.

### GetShowPathOk

`func (o *Story) GetShowPathOk() (*string, bool)`

GetShowPathOk returns a tuple with the ShowPath field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShowPath

`func (o *Story) SetShowPath(v string)`

SetShowPath sets ShowPath field to given value.

### HasShowPath

`func (o *Story) HasShowPath() bool`

HasShowPath returns a boolean if a field has been set.

### GetType

`func (o *Story) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *Story) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *Story) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *Story) HasType() bool`

HasType returns a boolean if a field has been set.

### GetLiked

`func (o *Story) GetLiked() bool`

GetLiked returns the Liked field if non-nil, zero value otherwise.

### GetLikedOk

`func (o *Story) GetLikedOk() (*bool, bool)`

GetLikedOk returns a tuple with the Liked field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLiked

`func (o *Story) SetLiked(v bool)`

SetLiked sets Liked field to given value.

### HasLiked

`func (o *Story) HasLiked() bool`

HasLiked returns a boolean if a field has been set.

### GetDisliked

`func (o *Story) GetDisliked() bool`

GetDisliked returns the Disliked field if non-nil, zero value otherwise.

### GetDislikedOk

`func (o *Story) GetDislikedOk() (*bool, bool)`

GetDislikedOk returns a tuple with the Disliked field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDisliked

`func (o *Story) SetDisliked(v bool)`

SetDisliked sets Disliked field to given value.

### HasDisliked

`func (o *Story) HasDisliked() bool`

HasDisliked returns a boolean if a field has been set.

### GetBookmarked

`func (o *Story) GetBookmarked() bool`

GetBookmarked returns the Bookmarked field if non-nil, zero value otherwise.

### GetBookmarkedOk

`func (o *Story) GetBookmarkedOk() (*bool, bool)`

GetBookmarkedOk returns a tuple with the Bookmarked field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBookmarked

`func (o *Story) SetBookmarked(v bool)`

SetBookmarked sets Bookmarked field to given value.

### HasBookmarked

`func (o *Story) HasBookmarked() bool`

HasBookmarked returns a boolean if a field has been set.

### GetSimilarStoriesCount

`func (o *Story) GetSimilarStoriesCount() int32`

GetSimilarStoriesCount returns the SimilarStoriesCount field if non-nil, zero value otherwise.

### GetSimilarStoriesCountOk

`func (o *Story) GetSimilarStoriesCountOk() (*int32, bool)`

GetSimilarStoriesCountOk returns a tuple with the SimilarStoriesCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSimilarStoriesCount

`func (o *Story) SetSimilarStoriesCount(v int32)`

SetSimilarStoriesCount sets SimilarStoriesCount field to given value.

### HasSimilarStoriesCount

`func (o *Story) HasSimilarStoriesCount() bool`

HasSimilarStoriesCount returns a boolean if a field has been set.

### GetScore

`func (o *Story) GetScore() float32`

GetScore returns the Score field if non-nil, zero value otherwise.

### GetScoreOk

`func (o *Story) GetScoreOk() (*float32, bool)`

GetScoreOk returns a tuple with the Score field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScore

`func (o *Story) SetScore(v float32)`

SetScore sets Score field to given value.

### HasScore

`func (o *Story) HasScore() bool`

HasScore returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


