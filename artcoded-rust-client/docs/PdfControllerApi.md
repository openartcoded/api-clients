# \PdfControllerApi

All URIs are relative to *http://localhost:9000*

Method | HTTP request | Description
------------- | ------------- | -------------
[**rotate**](PdfControllerApi.md#rotate) | **POST** /api/pdf/rotate | 
[**split_pdf**](PdfControllerApi.md#split_pdf) | **POST** /api/pdf/split | 



## rotate

> rotate(id, rotation)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **String** |  | [required] |
**rotation** | Option<**i32**> |  |  |[default to 180]

### Return type

 (empty response body)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## split_pdf

> std::path::PathBuf split_pdf(pdf)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**pdf** | **std::path::PathBuf** |  | [required] |

### Return type

[**std::path::PathBuf**](std::path::PathBuf.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

