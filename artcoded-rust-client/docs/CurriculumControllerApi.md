# \CurriculumControllerApi

All URIs are relative to *http://localhost:9000*

Method | HTTP request | Description
------------- | ------------- | -------------
[**add_template1**](CurriculumControllerApi.md#add_template1) | **POST** /api/cv/add-template | 
[**admin_download**](CurriculumControllerApi.md#admin_download) | **GET** /api/cv/admin-download | 
[**delete_download_cv_requests**](CurriculumControllerApi.md#delete_download_cv_requests) | **DELETE** /api/cv/download-requests | 
[**delete_template1**](CurriculumControllerApi.md#delete_template1) | **DELETE** /api/cv/delete-template | 
[**download1**](CurriculumControllerApi.md#download1) | **POST** /api/cv/download | 
[**get2**](CurriculumControllerApi.md#get2) | **GET** /api/cv | 
[**get_download_cv_requests**](CurriculumControllerApi.md#get_download_cv_requests) | **POST** /api/cv/download-requests | 
[**get_full_cv**](CurriculumControllerApi.md#get_full_cv) | **POST** /api/cv/full | 
[**list_templates1**](CurriculumControllerApi.md#list_templates1) | **GET** /api/cv/list-templates | 
[**update2**](CurriculumControllerApi.md#update2) | **POST** /api/cv/update | 



## add_template1

> models::CurriculumFreemarkerTemplate add_template1(name, template)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**name** | **String** |  | [required] |
**template** | **std::path::PathBuf** |  | [required] |

### Return type

[**models::CurriculumFreemarkerTemplate**](CurriculumFreemarkerTemplate.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## admin_download

> std::path::PathBuf admin_download()


### Parameters

This endpoint does not need any parameter.

### Return type

[**std::path::PathBuf**](std::path::PathBuf.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## delete_download_cv_requests

> delete_download_cv_requests(id)


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


## delete_template1

> delete_template1(id)


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


## download1

> std::path::PathBuf download1(download_cv_request)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**download_cv_request** | [**DownloadCvRequest**](DownloadCvRequest.md) |  | [required] |

### Return type

[**std::path::PathBuf**](std::path::PathBuf.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get2

> models::Curriculum get2()


### Parameters

This endpoint does not need any parameter.

### Return type

[**models::Curriculum**](Curriculum.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_download_cv_requests

> Vec<models::DownloadCvRequest> get_download_cv_requests()


### Parameters

This endpoint does not need any parameter.

### Return type

[**Vec<models::DownloadCvRequest>**](DownloadCvRequest.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_full_cv

> models::Curriculum get_full_cv()


### Parameters

This endpoint does not need any parameter.

### Return type

[**models::Curriculum**](Curriculum.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## list_templates1

> Vec<models::CurriculumFreemarkerTemplate> list_templates1()


### Parameters

This endpoint does not need any parameter.

### Return type

[**Vec<models::CurriculumFreemarkerTemplate>**](CurriculumFreemarkerTemplate.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## update2

> models::Curriculum update2(curriculum)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**curriculum** | [**Curriculum**](Curriculum.md) |  | [required] |

### Return type

[**models::Curriculum**](Curriculum.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

