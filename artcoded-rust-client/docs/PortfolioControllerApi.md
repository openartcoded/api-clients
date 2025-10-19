# \PortfolioControllerApi

All URIs are relative to *http://localhost:9000*

Method | HTTP request | Description
------------- | ------------- | -------------
[**delete10**](PortfolioControllerApi.md#delete10) | **DELETE** /api/finance/portfolio | 
[**delete_tick_from_portfolio**](PortfolioControllerApi.md#delete_tick_from_portfolio) | **DELETE** /api/finance/portfolio/tick | 
[**find_all5**](PortfolioControllerApi.md#find_all5) | **POST** /api/finance/portfolio/find-all | 
[**find_by_id1**](PortfolioControllerApi.md#find_by_id1) | **POST** /api/finance/portfolio/find-by-id | 
[**save5**](PortfolioControllerApi.md#save5) | **POST** /api/finance/portfolio/save | 
[**update_tag**](PortfolioControllerApi.md#update_tag) | **POST** /api/finance/portfolio/update-ticks | 



## delete10

> models::Restore200Response delete10(id)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **String** |  | [required] |

### Return type

[**models::Restore200Response**](restore_200_response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## delete_tick_from_portfolio

> models::Restore200Response delete_tick_from_portfolio(id, symbol)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **String** |  | [required] |
**symbol** | **String** |  | [required] |

### Return type

[**models::Restore200Response**](restore_200_response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## find_all5

> Vec<models::Portfolio> find_all5()


### Parameters

This endpoint does not need any parameter.

### Return type

[**Vec<models::Portfolio>**](Portfolio.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## find_by_id1

> models::Portfolio find_by_id1(id)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **String** |  | [required] |

### Return type

[**models::Portfolio**](Portfolio.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## save5

> models::Portfolio save5(portfolio)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**portfolio** | [**Portfolio**](Portfolio.md) |  | [required] |

### Return type

[**models::Portfolio**](Portfolio.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## update_tag

> update_tag(id, tick)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **String** |  | [required] |
**tick** | [**Vec<models::Tick>**](Tick.md) |  | [required] |

### Return type

 (empty response body)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

