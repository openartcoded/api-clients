# \AdministrativeDocumenControllerApi

All URIs are relative to *http://localhost:9000*

Method | HTTP request | Description
------------- | ------------- | -------------
[**delete14**](AdministrativeDocumenControllerApi.md#delete14) | **DELETE** /api/administrative-document | 
[**find_all10**](AdministrativeDocumenControllerApi.md#find_all10) | **POST** /api/administrative-document/find-all | 
[**find_by_id4**](AdministrativeDocumenControllerApi.md#find_by_id4) | **POST** /api/administrative-document/find-by-id | 
[**find_by_ids3**](AdministrativeDocumenControllerApi.md#find_by_ids3) | **POST** /api/administrative-document/find-by-ids | 
[**save8**](AdministrativeDocumenControllerApi.md#save8) | **POST** /api/administrative-document/save | 
[**search**](AdministrativeDocumenControllerApi.md#search) | **POST** /api/administrative-document/search | 
[**toggle_bookmarked4**](AdministrativeDocumenControllerApi.md#toggle_bookmarked4) | **POST** /api/administrative-document/toggle-bookmarked | 



## delete14

> delete14(id)


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


## find_all10

> Vec<models::AdministrativeDocument> find_all10()


### Parameters

This endpoint does not need any parameter.

### Return type

[**Vec<models::AdministrativeDocument>**](AdministrativeDocument.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## find_by_id4

> models::AdministrativeDocument find_by_id4(id)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **String** |  | [required] |

### Return type

[**models::AdministrativeDocument**](AdministrativeDocument.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## find_by_ids3

> Vec<models::AdministrativeDocument> find_by_ids3(id)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | [**Vec<String>**](String.md) |  | [required] |

### Return type

[**Vec<models::AdministrativeDocument>**](AdministrativeDocument.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## save8

> save8(title, id, description, tags, document)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**title** | **String** |  | [required] |
**id** | Option<**String**> |  |  |
**description** | Option<**String**> |  |  |
**tags** | Option<[**Vec<String>**](String.md)> |  |  |
**document** | Option<**std::path::PathBuf**> |  |  |

### Return type

 (empty response body)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## search

> models::PagedModelAdministrativeDocument search(arg1, administrative_document_search_criteria)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**arg1** | [**Pageable**](.md) |  | [required] |
**administrative_document_search_criteria** | [**AdministrativeDocumentSearchCriteria**](AdministrativeDocumentSearchCriteria.md) |  | [required] |

### Return type

[**models::PagedModelAdministrativeDocument**](PagedModelAdministrativeDocument.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## toggle_bookmarked4

> models::AdministrativeDocument toggle_bookmarked4(id)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **String** |  | [required] |

### Return type

[**models::AdministrativeDocument**](AdministrativeDocument.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

