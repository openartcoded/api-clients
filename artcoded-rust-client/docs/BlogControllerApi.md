# \BlogControllerApi

All URIs are relative to *http://localhost:9000*

Method | HTTP request | Description
------------- | ------------- | -------------
[**admin_search**](BlogControllerApi.md#admin_search) | **POST** /api/blog/admin-search | 
[**delete12**](BlogControllerApi.md#delete12) | **DELETE** /api/blog | 
[**generate_pdf**](BlogControllerApi.md#generate_pdf) | **GET** /api/blog/generate-pdf | 
[**get_latest**](BlogControllerApi.md#get_latest) | **GET** /api/blog/latest | 
[**get_post_by_id**](BlogControllerApi.md#get_post_by_id) | **POST** /api/blog/post-by-id | 
[**get_public_post_by_id**](BlogControllerApi.md#get_public_post_by_id) | **GET** /api/blog/post/{title}/{id} | 
[**get_tags**](BlogControllerApi.md#get_tags) | **GET** /api/blog/tags | 
[**new_post**](BlogControllerApi.md#new_post) | **POST** /api/blog/new-post | 
[**public_search**](BlogControllerApi.md#public_search) | **POST** /api/blog/public-search | 
[**reset_post_count**](BlogControllerApi.md#reset_post_count) | **POST** /api/blog/post/{id}/reset-count | 
[**save6**](BlogControllerApi.md#save6) | **POST** /api/blog/submit | 



## admin_search

> models::PagedModelPost admin_search(arg1, post_search_criteria)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**arg1** | [**Pageable**](.md) |  | [required] |
**post_search_criteria** | [**PostSearchCriteria**](PostSearchCriteria.md) |  | [required] |

### Return type

[**models::PagedModelPost**](PagedModelPost.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## delete12

> models::Restore200Response delete12(id)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **String** |  | [required] |

### Return type

[**models::Restore200Response**](restore_200_response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## generate_pdf

> std::path::PathBuf generate_pdf(id)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **String** |  | [required] |

### Return type

[**std::path::PathBuf**](std::path::PathBuf.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_latest

> models::PagedModelPost get_latest()


### Parameters

This endpoint does not need any parameter.

### Return type

[**models::PagedModelPost**](PagedModelPost.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_post_by_id

> models::Post get_post_by_id(id)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **String** |  | [required] |

### Return type

[**models::Post**](Post.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_public_post_by_id

> models::Post get_public_post_by_id(title, id)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**title** | **String** |  | [required] |
**id** | **String** |  | [required] |

### Return type

[**models::Post**](Post.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_tags

> Vec<String> get_tags()


### Parameters

This endpoint does not need any parameter.

### Return type

**Vec<String>**

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## new_post

> models::Post new_post()


### Parameters

This endpoint does not need any parameter.

### Return type

[**models::Post**](Post.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## public_search

> models::PagedModelPost public_search(arg1, post_search_criteria)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**arg1** | [**Pageable**](.md) |  | [required] |
**post_search_criteria** | [**PostSearchCriteria**](PostSearchCriteria.md) |  | [required] |

### Return type

[**models::PagedModelPost**](PagedModelPost.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## reset_post_count

> reset_post_count(id)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **String** |  | [required] |

### Return type

 (empty response body)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## save6

> models::Post save6(id, title, description, tags, content, draft, cover)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **String** |  | [required] |
**title** | **String** |  | [required] |
**description** | **String** |  | [required] |
**tags** | [**Vec<String>**](String.md) |  | [required] |
**content** | **String** |  | [required] |
**draft** | Option<**bool**> |  |  |[default to false]
**cover** | Option<**std::path::PathBuf**> |  |  |

### Return type

[**models::Post**](Post.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

