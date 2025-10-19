# \MongoManagementControllerApi

All URIs are relative to *http://localhost:9000*

Method | HTTP request | Description
------------- | ------------- | -------------
[**download**](MongoManagementControllerApi.md#download) | **POST** /api/mongo-management/download | 
[**dump_list**](MongoManagementControllerApi.md#dump_list) | **GET** /api/mongo-management | 



## download

> std::path::PathBuf download(archive_name, snapshot)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**archive_name** | **String** |  | [required] |
**snapshot** | Option<**bool**> |  |  |[default to false]

### Return type

[**std::path::PathBuf**](std::path::PathBuf.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## dump_list

> Vec<String> dump_list(snapshot)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**snapshot** | Option<**bool**> |  |  |[default to false]

### Return type

**Vec<String>**

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

