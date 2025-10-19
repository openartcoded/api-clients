# \MenuLinkControllerApi

All URIs are relative to *http://localhost:9000*

Method | HTTP request | Description
------------- | ------------- | -------------
[**clicked**](MenuLinkControllerApi.md#clicked) | **POST** /api/settings/menu-link/clicked | 
[**create_or_update**](MenuLinkControllerApi.md#create_or_update) | **POST** /api/settings/menu-link/save | 
[**delete4**](MenuLinkControllerApi.md#delete4) | **DELETE** /api/settings/menu-link | 
[**find_all11**](MenuLinkControllerApi.md#find_all11) | **GET** /api/settings/menu-link | 
[**import_all**](MenuLinkControllerApi.md#import_all) | **POST** /api/settings/menu-link/import | 
[**top3**](MenuLinkControllerApi.md#top3) | **GET** /api/settings/menu-link/top-3 | 



## clicked

> clicked(id)


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


## create_or_update

> models::MenuLink create_or_update(menu_link)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**menu_link** | [**MenuLink**](MenuLink.md) |  | [required] |

### Return type

[**models::MenuLink**](MenuLink.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## delete4

> delete4(id)


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


## find_all11

> Vec<models::MenuLink> find_all11()


### Parameters

This endpoint does not need any parameter.

### Return type

[**Vec<models::MenuLink>**](MenuLink.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## import_all

> import_all(menu_link)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**menu_link** | [**Vec<models::MenuLink>**](MenuLink.md) |  | [required] |

### Return type

 (empty response body)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## top3

> Vec<models::MenuLink> top3()


### Parameters

This endpoint does not need any parameter.

### Return type

[**Vec<models::MenuLink>**](MenuLink.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

