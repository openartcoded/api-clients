# \CacheControllerApi

All URIs are relative to *http://localhost:9000*

Method | HTTP request | Description
------------- | ------------- | -------------
[**clear**](CacheControllerApi.md#clear) | **DELETE** /api/cache/clear | 
[**find_all9**](CacheControllerApi.md#find_all9) | **POST** /api/cache/find-all | 



## clear

> models::Restore200Response clear(name)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**name** | **String** |  | [required] |

### Return type

[**models::Restore200Response**](restore_200_response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## find_all9

> Vec<String> find_all9()


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

