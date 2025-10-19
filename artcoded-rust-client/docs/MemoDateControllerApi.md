# \MemoDateControllerApi

All URIs are relative to *http://localhost:9000*

Method | HTTP request | Description
------------- | ------------- | -------------
[**delete2**](MemoDateControllerApi.md#delete2) | **DELETE** /api/memo-date | 
[**find_all2**](MemoDateControllerApi.md#find_all2) | **POST** /api/memo-date | 
[**save3**](MemoDateControllerApi.md#save3) | **POST** /api/memo-date/save | 



## delete2

> delete2(id)


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


## find_all2

> Vec<models::MemoDate> find_all2()


### Parameters

This endpoint does not need any parameter.

### Return type

[**Vec<models::MemoDate>**](MemoDate.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## save3

> models::MemoDate save3(memo_date)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**memo_date** | [**MemoDate**](MemoDate.md) |  | [required] |

### Return type

[**models::MemoDate**](MemoDate.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

