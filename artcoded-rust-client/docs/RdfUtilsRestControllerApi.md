# \RdfUtilsRestControllerApi

All URIs are relative to *http://localhost:9000*

Method | HTTP request | Description
------------- | ------------- | -------------
[**file_to_lang**](RdfUtilsRestControllerApi.md#file_to_lang) | **POST** /api/toolbox/public/rdf/shacl-validation | 
[**file_to_lang1**](RdfUtilsRestControllerApi.md#file_to_lang1) | **POST** /api/toolbox/public/rdf/file-to-lang | 
[**get_allowed_extensions**](RdfUtilsRestControllerApi.md#get_allowed_extensions) | **GET** /api/toolbox/public/rdf/allowed-extensions | 
[**get_allowed_languages**](RdfUtilsRestControllerApi.md#get_allowed_languages) | **GET** /api/toolbox/public/rdf/allowed-languages | 
[**model_conversion1**](RdfUtilsRestControllerApi.md#model_conversion1) | **POST** /api/toolbox/public/rdf/model-to-lang | 



## file_to_lang

> String file_to_lang(model_file, shacl_file)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**model_file** | **std::path::PathBuf** |  | [required] |
**shacl_file** | **std::path::PathBuf** |  | [required] |

### Return type

**String**

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## file_to_lang1

> std::path::PathBuf file_to_lang1(lang, file)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**lang** | **String** |  | [required] |
**file** | **std::path::PathBuf** |  | [required] |

### Return type

[**std::path::PathBuf**](std::path::PathBuf.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_allowed_extensions

> Vec<String> get_allowed_extensions()


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


## get_allowed_languages

> Vec<String> get_allowed_languages()


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


## model_conversion1

> String model_conversion1(model, lang_of_model, lang)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**model** | **String** |  | [required] |
**lang_of_model** | **String** |  | [required] |
**lang** | **String** |  | [required] |

### Return type

**String**

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

