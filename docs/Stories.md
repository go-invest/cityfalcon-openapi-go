# Stories

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**NextPageToken** | Pointer to **string** |  | [optional] 
**ExpandedQuery** | Pointer to **string** |  | [optional] 
**Stories** | Pointer to [**[]Story**](Story.md) |  | [optional] 

## Methods

### NewStories

`func NewStories() *Stories`

NewStories instantiates a new Stories object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStoriesWithDefaults

`func NewStoriesWithDefaults() *Stories`

NewStoriesWithDefaults instantiates a new Stories object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetNextPageToken

`func (o *Stories) GetNextPageToken() string`

GetNextPageToken returns the NextPageToken field if non-nil, zero value otherwise.

### GetNextPageTokenOk

`func (o *Stories) GetNextPageTokenOk() (*string, bool)`

GetNextPageTokenOk returns a tuple with the NextPageToken field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextPageToken

`func (o *Stories) SetNextPageToken(v string)`

SetNextPageToken sets NextPageToken field to given value.

### HasNextPageToken

`func (o *Stories) HasNextPageToken() bool`

HasNextPageToken returns a boolean if a field has been set.

### GetExpandedQuery

`func (o *Stories) GetExpandedQuery() string`

GetExpandedQuery returns the ExpandedQuery field if non-nil, zero value otherwise.

### GetExpandedQueryOk

`func (o *Stories) GetExpandedQueryOk() (*string, bool)`

GetExpandedQueryOk returns a tuple with the ExpandedQuery field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpandedQuery

`func (o *Stories) SetExpandedQuery(v string)`

SetExpandedQuery sets ExpandedQuery field to given value.

### HasExpandedQuery

`func (o *Stories) HasExpandedQuery() bool`

HasExpandedQuery returns a boolean if a field has been set.

### GetStories

`func (o *Stories) GetStories() []Story`

GetStories returns the Stories field if non-nil, zero value otherwise.

### GetStoriesOk

`func (o *Stories) GetStoriesOk() (*[]Story, bool)`

GetStoriesOk returns a tuple with the Stories field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStories

`func (o *Stories) SetStories(v []Story)`

SetStories sets Stories field to given value.

### HasStories

`func (o *Stories) HasStories() bool`

HasStories returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


