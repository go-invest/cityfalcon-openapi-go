# \CompaniesApi

All URIs are relative to *https://www.cityfalcon.com/webapi/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ListStories**](CompaniesApi.md#ListStories) | **Get** /webapi/v1/stories | 



## ListStories

> Stories ListStories(ctx).OrderBy(orderBy).FoldSimilarStories(foldSimilarStories).TimeFilter(timeFilter).Query(query).Categories(categories).Languages(languages).MinScore(minScore).Execute()





### Example

```go
package main

import (
    "context"
    "fmt"
    "os"
    openapiclient "./openapi"
)

func main() {
    orderBy := "orderBy_example" // string | string order_by (name or id) of the stories
    foldSimilarStories := "foldSimilarStories_example" // string | string fold_similar_stories (name or id) of the stories
    timeFilter := "timeFilter_example" // string | string time_filter (name or id) of the stories
    query := "query_example" // string | string query (name or id) of the stories
    categories := "categories_example" // string | string categories (name or id) of the stories (optional)
    languages := "languages_example" // string | string languages (name or id) of the stories (optional)
    minScore := "minScore_example" // string | string min_score (name or id) of the stories (optional)

    configuration := openapiclient.NewConfiguration()
    api_client := openapiclient.NewAPIClient(configuration)
    resp, r, err := api_client.CompaniesApi.ListStories(context.Background()).OrderBy(orderBy).FoldSimilarStories(foldSimilarStories).TimeFilter(timeFilter).Query(query).Categories(categories).Languages(languages).MinScore(minScore).Execute()
    if err.Error() != "" {
        fmt.Fprintf(os.Stderr, "Error when calling `CompaniesApi.ListStories``: %v\n", err)
        fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
    }
    // response from `ListStories`: Stories
    fmt.Fprintf(os.Stdout, "Response from `CompaniesApi.ListStories`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListStoriesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **orderBy** | **string** | string order_by (name or id) of the stories | 
 **foldSimilarStories** | **string** | string fold_similar_stories (name or id) of the stories | 
 **timeFilter** | **string** | string time_filter (name or id) of the stories | 
 **query** | **string** | string query (name or id) of the stories | 
 **categories** | **string** | string categories (name or id) of the stories | 
 **languages** | **string** | string languages (name or id) of the stories | 
 **minScore** | **string** | string min_score (name or id) of the stories | 

### Return type

[**Stories**](stories.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

