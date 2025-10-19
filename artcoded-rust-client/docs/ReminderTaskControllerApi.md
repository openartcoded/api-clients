# \ReminderTaskControllerApi

All URIs are relative to *http://localhost:9000*

Method | HTTP request | Description
------------- | ------------- | -------------
[**allowed_actions**](ReminderTaskControllerApi.md#allowed_actions) | **GET** /api/reminder-task/allowed-actions | 
[**delete6**](ReminderTaskControllerApi.md#delete6) | **DELETE** /api/reminder-task | 
[**find_by_id7**](ReminderTaskControllerApi.md#find_by_id7) | **GET** /api/reminder-task/find-by-id | 
[**find_next10_tasks**](ReminderTaskControllerApi.md#find_next10_tasks) | **GET** /api/reminder-task/find-next-ten-tasks | 
[**get**](ReminderTaskControllerApi.md#get) | **GET** /api/reminder-task/find-all | 
[**get_action_results**](ReminderTaskControllerApi.md#get_action_results) | **GET** /api/reminder-task/action-results | 
[**save**](ReminderTaskControllerApi.md#save) | **POST** /api/reminder-task/save | 
[**validate_cron_expression**](ReminderTaskControllerApi.md#validate_cron_expression) | **GET** /api/reminder-task/validate-cron-expression | 



## allowed_actions

> Vec<models::ActionMetadata> allowed_actions()


### Parameters

This endpoint does not need any parameter.

### Return type

[**Vec<models::ActionMetadata>**](ActionMetadata.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## delete6

> delete6(id)


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


## find_by_id7

> models::ReminderTask find_by_id7(id)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **String** |  | [required] |

### Return type

[**models::ReminderTask**](ReminderTask.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## find_next10_tasks

> Vec<models::ReminderTask> find_next10_tasks()


### Parameters

This endpoint does not need any parameter.

### Return type

[**Vec<models::ReminderTask>**](ReminderTask.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get

> Vec<models::ReminderTask> get()


### Parameters

This endpoint does not need any parameter.

### Return type

[**Vec<models::ReminderTask>**](ReminderTask.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_action_results

> models::PagedModelActionResult get_action_results(key, arg1)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**key** | **String** |  | [required] |
**arg1** | [**Pageable**](.md) |  | [required] |

### Return type

[**models::PagedModelActionResult**](PagedModelActionResult.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## save

> save(reminder_task)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**reminder_task** | [**ReminderTask**](ReminderTask.md) |  | [required] |

### Return type

 (empty response body)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## validate_cron_expression

> models::ValidateCronExpression200Response validate_cron_expression(cron_expression)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**cron_expression** | **String** |  | [required] |

### Return type

[**models::ValidateCronExpression200Response**](validateCronExpression_200_response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

