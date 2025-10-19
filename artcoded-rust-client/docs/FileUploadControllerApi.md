# \FileUploadControllerApi

All URIs are relative to *http://localhost:9000*

Method | HTTP request | Description
------------- | ------------- | -------------
[**delete5**](FileUploadControllerApi.md#delete5) | **DELETE** /api/resource/delete-by-id | 
[**delete_all**](FileUploadControllerApi.md#delete_all) | **DELETE** /api/resource/delete-all | 
[**download2**](FileUploadControllerApi.md#download2) | **GET** /api/resource/download | 
[**find_all1**](FileUploadControllerApi.md#find_all1) | **POST** /api/resource/find-all | 
[**find_by_correlation_id**](FileUploadControllerApi.md#find_by_correlation_id) | **GET** /api/resource/find-by-correlation-id | 
[**find_by_correlation_id_public**](FileUploadControllerApi.md#find_by_correlation_id_public) | **GET** /api/resource/public/find-by-correlation-id | 
[**find_by_id6**](FileUploadControllerApi.md#find_by_id6) | **GET** /api/resource/find-by-id | 
[**find_by_id_public**](FileUploadControllerApi.md#find_by_id_public) | **GET** /api/resource/public/find-by-id | 
[**find_by_ids4**](FileUploadControllerApi.md#find_by_ids4) | **GET** /api/resource/find-by-ids | 
[**get_correlation_links**](FileUploadControllerApi.md#get_correlation_links) | **POST** /api/resource/correlation-links | 
[**public_download**](FileUploadControllerApi.md#public_download) | **GET** /api/resource/public/download/{id} | 
[**toggle_bookmarked**](FileUploadControllerApi.md#toggle_bookmarked) | **POST** /api/resource/toggle-bookmarked | 
[**upload**](FileUploadControllerApi.md#upload) | **POST** /api/resource/upload | 



## delete5

> models::Restore200Response delete5(id)


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


## delete_all

> models::Restore200Response delete_all()


### Parameters

This endpoint does not need any parameter.

### Return type

[**models::Restore200Response**](restore_200_response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## download2

> std::path::PathBuf download2(id)


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


## find_all1

> models::PagedModelFileUpload find_all1(arg1, file_upload_search_criteria)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**arg1** | [**Pageable**](.md) |  | [required] |
**file_upload_search_criteria** | [**FileUploadSearchCriteria**](FileUploadSearchCriteria.md) |  | [required] |

### Return type

[**models::PagedModelFileUpload**](PagedModelFileUpload.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## find_by_correlation_id

> Vec<models::FileUpload> find_by_correlation_id(correlation_id)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**correlation_id** | **String** |  | [required] |

### Return type

[**Vec<models::FileUpload>**](FileUpload.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## find_by_correlation_id_public

> Vec<models::FileUpload> find_by_correlation_id_public(correlation_id)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**correlation_id** | **String** |  | [required] |

### Return type

[**Vec<models::FileUpload>**](FileUpload.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## find_by_id6

> models::FileUpload find_by_id6(id)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **String** |  | [required] |

### Return type

[**models::FileUpload**](FileUpload.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## find_by_id_public

> models::FileUpload find_by_id_public(id)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **String** |  | [required] |

### Return type

[**models::FileUpload**](FileUpload.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## find_by_ids4

> Vec<models::FileUpload> find_by_ids4(id)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | [**Vec<String>**](String.md) |  | [required] |

### Return type

[**Vec<models::FileUpload>**](FileUpload.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_correlation_links

> std::collections::HashMap<String, String> get_correlation_links()


### Parameters

This endpoint does not need any parameter.

### Return type

**std::collections::HashMap<String, String>**

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## public_download

> std::path::PathBuf public_download(id)


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


## toggle_bookmarked

> models::FileUpload toggle_bookmarked(id)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **String** |  | [required] |

### Return type

[**models::FileUpload**](FileUpload.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## upload

> models::FileUpload upload(file, correlation_id, public_resource)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**file** | **std::path::PathBuf** |  | [required] |
**correlation_id** | Option<**String**> |  |  |
**public_resource** | Option<**bool**> |  |  |[default to false]

### Return type

[**models::FileUpload**](FileUpload.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

