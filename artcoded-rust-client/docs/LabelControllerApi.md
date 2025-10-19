# \LabelControllerApi

All URIs are relative to *http://localhost:9000*

Method | HTTP request | Description
------------- | ------------- | -------------
[**find_all3**](LabelControllerApi.md#find_all3) | **POST** /api/label/find-all | 
[**find_by_name**](LabelControllerApi.md#find_by_name) | **POST** /api/label/find-by-name | 
[**update_all**](LabelControllerApi.md#update_all) | **POST** /api/label/update-all | 



## find_all3

> Vec<models::Label> find_all3()


### Parameters

This endpoint does not need any parameter.

### Return type

[**Vec<models::Label>**](Label.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## find_by_name

> models::Label find_by_name(name)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**name** | **String** |  | [required] |

### Return type

[**models::Label**](Label.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## update_all

> Vec<models::Label> update_all(label)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**label** | [**Vec<models::Label>**](Label.md) |  | [required] |

### Return type

[**Vec<models::Label>**](Label.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

