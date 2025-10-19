# \BillableClientControllerApi

All URIs are relative to *http://localhost:9000*

Method | HTTP request | Description
------------- | ------------- | -------------
[**delete13**](BillableClientControllerApi.md#delete13) | **DELETE** /api/billable-client | 
[**delete_upload**](BillableClientControllerApi.md#delete_upload) | **DELETE** /api/billable-client/upload | 
[**find_all14**](BillableClientControllerApi.md#find_all14) | **GET** /api/billable-client/find-all | 
[**find_by_contract_status**](BillableClientControllerApi.md#find_by_contract_status) | **GET** /api/billable-client/find-by-contract-status | 
[**save7**](BillableClientControllerApi.md#save7) | **POST** /api/billable-client/save | 
[**upload1**](BillableClientControllerApi.md#upload1) | **POST** /api/billable-client/upload | 



## delete13

> delete13(id)


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


## delete_upload

> delete_upload(id, upload_id)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **String** |  | [required] |
**upload_id** | **String** |  | [required] |

### Return type

 (empty response body)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## find_all14

> Vec<models::BillableClient> find_all14()


### Parameters

This endpoint does not need any parameter.

### Return type

[**Vec<models::BillableClient>**](BillableClient.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## find_by_contract_status

> Vec<models::BillableClient> find_by_contract_status(contract_status)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**contract_status** | **String** |  | [required] |

### Return type

[**Vec<models::BillableClient>**](BillableClient.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## save7

> models::BillableClient save7(billable_client)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**billable_client** | [**BillableClient**](BillableClient.md) |  | [required] |

### Return type

[**models::BillableClient**](BillableClient.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## upload1

> upload1(document, id)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**document** | **std::path::PathBuf** |  | [required] |
**id** | Option<**String**> |  |  |

### Return type

 (empty response body)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

