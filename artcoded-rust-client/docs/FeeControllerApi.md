# \FeeControllerApi

All URIs are relative to *http://localhost:9000*

Method | HTTP request | Description
------------- | ------------- | -------------
[**delete11**](FeeControllerApi.md#delete11) | **DELETE** /api/fee | 
[**find_all6**](FeeControllerApi.md#find_all6) | **POST** /api/fee/search | 
[**find_all7**](FeeControllerApi.md#find_all7) | **POST** /api/fee/find-all | 
[**find_by_id2**](FeeControllerApi.md#find_by_id2) | **POST** /api/fee/find-by-id | 
[**find_by_ids2**](FeeControllerApi.md#find_by_ids2) | **POST** /api/fee/find-by-ids | 
[**manual_submit**](FeeControllerApi.md#manual_submit) | **POST** /api/fee/manual-submit | 
[**remove_attachment**](FeeControllerApi.md#remove_attachment) | **POST** /api/fee/remove-attachment | 
[**summaries**](FeeControllerApi.md#summaries) | **POST** /api/fee/summaries | 
[**toggle_bookmarked2**](FeeControllerApi.md#toggle_bookmarked2) | **POST** /api/fee/toggle-bookmarked | 
[**update_price**](FeeControllerApi.md#update_price) | **POST** /api/fee/update-price | 
[**update_tag1**](FeeControllerApi.md#update_tag1) | **POST** /api/fee/update-tag | 



## delete11

> models::Restore200Response delete11(id)


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


## find_all6

> models::PagedModelFee find_all6(arg1, fee_search_criteria)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**arg1** | [**Pageable**](.md) |  | [required] |
**fee_search_criteria** | [**FeeSearchCriteria**](FeeSearchCriteria.md) |  | [required] |

### Return type

[**models::PagedModelFee**](PagedModelFee.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## find_all7

> Vec<models::Fee> find_all7()


### Parameters

This endpoint does not need any parameter.

### Return type

[**Vec<models::Fee>**](Fee.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## find_by_id2

> models::Fee find_by_id2(id)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **String** |  | [required] |

### Return type

[**models::Fee**](Fee.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## find_by_ids2

> Vec<models::Fee> find_by_ids2(id)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | [**Vec<String>**](String.md) |  | [required] |

### Return type

[**Vec<models::Fee>**](Fee.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## manual_submit

> models::Fee manual_submit(subject, body, files)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**subject** | **String** |  | [required] |
**body** | **String** |  | [required] |
**files** | [**Vec<std::path::PathBuf>**](std::path::PathBuf.md) |  | [required] |

### Return type

[**models::Fee**](Fee.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## remove_attachment

> models::Fee remove_attachment(id, attachment_id)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **String** |  | [required] |
**attachment_id** | **String** |  | [required] |

### Return type

[**models::Fee**](Fee.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## summaries

> Vec<models::FeeSummary> summaries()


### Parameters

This endpoint does not need any parameter.

### Return type

[**Vec<models::FeeSummary>**](FeeSummary.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## toggle_bookmarked2

> models::Fee toggle_bookmarked2(id)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **String** |  | [required] |

### Return type

[**models::Fee**](Fee.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## update_price

> models::Fee update_price(id, price_h_vat, vat)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **String** |  | [required] |
**price_h_vat** | **f64** |  | [required] |
**vat** | **f64** |  | [required] |

### Return type

[**models::Fee**](Fee.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## update_tag1

> Vec<models::Fee> update_tag1(tag, request_body)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**tag** | **String** |  | [required] |
**request_body** | [**Vec<String>**](String.md) |  | [required] |

### Return type

[**Vec<models::Fee>**](Fee.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

