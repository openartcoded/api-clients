# \TimesheetControllerApi

All URIs are relative to *http://localhost:9000*

Method | HTTP request | Description
------------- | ------------- | -------------
[**close_timesheet**](TimesheetControllerApi.md#close_timesheet) | **POST** /api/timesheet/close | 
[**count**](TimesheetControllerApi.md#count) | **GET** /api/timesheet/count | 
[**delete_timesheet**](TimesheetControllerApi.md#delete_timesheet) | **DELETE** /api/timesheet | 
[**estimate_total_to_be_invoiced_this_month**](TimesheetControllerApi.md#estimate_total_to_be_invoiced_this_month) | **GET** /api/timesheet/estimate-total-to-be-invoiced-this-month | 
[**find_all_grouped_by_year_and_client_name**](TimesheetControllerApi.md#find_all_grouped_by_year_and_client_name) | **GET** /api/timesheet | 
[**find_by_id5**](TimesheetControllerApi.md#find_by_id5) | **GET** /api/timesheet/by-id | 
[**generate_invoice**](TimesheetControllerApi.md#generate_invoice) | **POST** /api/timesheet/generate-invoice | 
[**reopen_timesheet**](TimesheetControllerApi.md#reopen_timesheet) | **POST** /api/timesheet/reopen | 
[**save_or_update_timesheet**](TimesheetControllerApi.md#save_or_update_timesheet) | **POST** /api/timesheet | 
[**save_or_update_timesheet_period**](TimesheetControllerApi.md#save_or_update_timesheet_period) | **POST** /api/timesheet/save-period | 
[**update_settings**](TimesheetControllerApi.md#update_settings) | **POST** /api/timesheet/settings | 



## close_timesheet

> close_timesheet(id)


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


## count

> models::Count200Response count()


### Parameters

This endpoint does not need any parameter.

### Return type

[**models::Count200Response**](count_200_response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## delete_timesheet

> delete_timesheet(id)


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


## estimate_total_to_be_invoiced_this_month

> f64 estimate_total_to_be_invoiced_this_month()


### Parameters

This endpoint does not need any parameter.

### Return type

**f64**

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## find_all_grouped_by_year_and_client_name

> std::collections::HashMap<String, std::collections::HashMap<String, Vec<models::Timesheet>>> find_all_grouped_by_year_and_client_name(only_active_client)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**only_active_client** | Option<**bool**> |  |  |[default to true]

### Return type

[**std::collections::HashMap<String, std::collections::HashMap<String, Vec<models::Timesheet>>>**](std::collections::HashMap.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## find_by_id5

> models::Timesheet find_by_id5(id)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **String** |  | [required] |

### Return type

[**models::Timesheet**](Timesheet.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## generate_invoice

> models::Timesheet generate_invoice(id)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **String** |  | [required] |

### Return type

[**models::Timesheet**](Timesheet.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## reopen_timesheet

> reopen_timesheet(id)


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


## save_or_update_timesheet

> models::Timesheet save_or_update_timesheet(timesheet)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timesheet** | [**Timesheet**](Timesheet.md) |  | [required] |

### Return type

[**models::Timesheet**](Timesheet.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## save_or_update_timesheet_period

> models::TimesheetPeriod save_or_update_timesheet_period(id, timesheet_period)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **String** |  | [required] |
**timesheet_period** | [**TimesheetPeriod**](TimesheetPeriod.md) |  | [required] |

### Return type

[**models::TimesheetPeriod**](TimesheetPeriod.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## update_settings

> models::Timesheet update_settings(timesheet_settings_form)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timesheet_settings_form** | [**TimesheetSettingsForm**](TimesheetSettingsForm.md) |  | [required] |

### Return type

[**models::Timesheet**](Timesheet.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

