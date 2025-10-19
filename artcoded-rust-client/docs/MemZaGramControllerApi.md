# \MemZaGramControllerApi

All URIs are relative to *http://localhost:9000*

Method | HTTP request | Description
------------- | ------------- | -------------
[**admin_find_all**](MemZaGramControllerApi.md#admin_find_all) | **GET** /api/memzagram/all | 
[**delete7**](MemZaGramControllerApi.md#delete7) | **DELETE** /api/memzagram | 
[**find_all12**](MemZaGramControllerApi.md#find_all12) | **GET** /api/memzagram/public | 
[**increment_views_count**](MemZaGramControllerApi.md#increment_views_count) | **POST** /api/memzagram/_stat | 
[**save2**](MemZaGramControllerApi.md#save2) | **POST** /api/memzagram/submit | 



## admin_find_all

> models::PagedModelMemZaGram admin_find_all(arg0)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**arg0** | [**Pageable**](.md) |  | [required] |

### Return type

[**models::PagedModelMemZaGram**](PagedModelMemZaGram.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## delete7

> delete7(id)


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


## find_all12

> models::PagedModelMemZaGram find_all12(arg0)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**arg0** | [**Pageable**](.md) |  | [required] |

### Return type

[**models::PagedModelMemZaGram**](PagedModelMemZaGram.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## increment_views_count

> increment_views_count(id)


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


## save2

> save2(title, id, description, visible, date_of_visibility, image_upload)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**title** | **String** |  | [required] |
**id** | Option<**String**> |  |  |
**description** | Option<**String**> |  |  |
**visible** | Option<**bool**> |  |  |[default to false]
**date_of_visibility** | Option<**String**> |  |  |
**image_upload** | Option<**std::path::PathBuf**> |  |  |

### Return type

 (empty response body)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

