# \DossierControllerApi

All URIs are relative to *http://localhost:9000*

Method | HTTP request | Description
------------- | ------------- | -------------
[**active_dossier**](DossierControllerApi.md#active_dossier) | **POST** /api/dossier/active-dossier | 
[**add_document_to_dossier**](DossierControllerApi.md#add_document_to_dossier) | **POST** /api/dossier/add-document | 
[**bookmarked**](DossierControllerApi.md#bookmarked) | **POST** /api/dossier/bookmarked | 
[**close_active_dossier**](DossierControllerApi.md#close_active_dossier) | **POST** /api/dossier/close-active-dossier | 
[**delete3**](DossierControllerApi.md#delete3) | **DELETE** /api/dossier/active-dossier | 
[**find_all8**](DossierControllerApi.md#find_all8) | **POST** /api/dossier/find-all | 
[**find_all_paged**](DossierControllerApi.md#find_all_paged) | **POST** /api/dossier/find-all-paged | 
[**find_by_fee_id**](DossierControllerApi.md#find_by_fee_id) | **POST** /api/dossier/find-by-fee-id | 
[**find_by_id3**](DossierControllerApi.md#find_by_id3) | **POST** /api/dossier/find-by-id | 
[**generate_summary**](DossierControllerApi.md#generate_summary) | **GET** /api/dossier/generate-summary | 
[**get_dossier_total_size**](DossierControllerApi.md#get_dossier_total_size) | **POST** /api/dossier/size | 
[**get_import_dossier_xlsx_example**](DossierControllerApi.md#get_import_dossier_xlsx_example) | **GET** /api/dossier/import-example | 
[**get_summaries**](DossierControllerApi.md#get_summaries) | **POST** /api/dossier/summaries | 
[**get_summaries1**](DossierControllerApi.md#get_summaries1) | **POST** /api/dossier/find-all-summaries | 
[**get_summary**](DossierControllerApi.md#get_summary) | **POST** /api/dossier/summary | 
[**import_dossier_from_zip**](DossierControllerApi.md#import_dossier_from_zip) | **POST** /api/dossier/import | 
[**new_dossier**](DossierControllerApi.md#new_dossier) | **POST** /api/dossier/new-dossier | 
[**new_from_previous**](DossierControllerApi.md#new_from_previous) | **POST** /api/dossier/new-from-previous | 
[**process_fees_for_dossier**](DossierControllerApi.md#process_fees_for_dossier) | **POST** /api/dossier/process-fees | 
[**process_invoice_for_dossier**](DossierControllerApi.md#process_invoice_for_dossier) | **POST** /api/dossier/process-invoice | 
[**recall_for_modification**](DossierControllerApi.md#recall_for_modification) | **POST** /api/dossier/recall-for-modification | 
[**remove_document**](DossierControllerApi.md#remove_document) | **POST** /api/dossier/remove-document | 
[**remove_fee**](DossierControllerApi.md#remove_fee) | **POST** /api/dossier/remove-fee | 
[**remove_invoice**](DossierControllerApi.md#remove_invoice) | **POST** /api/dossier/remove-invoice | 
[**toggle_bookmarked3**](DossierControllerApi.md#toggle_bookmarked3) | **POST** /api/dossier/toggle-bookmarked | 
[**update_active_dossier**](DossierControllerApi.md#update_active_dossier) | **POST** /api/dossier/update-dossier | 



## active_dossier

> models::Dossier active_dossier()


### Parameters

This endpoint does not need any parameter.

### Return type

[**models::Dossier**](Dossier.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## add_document_to_dossier

> add_document_to_dossier(id)


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


## bookmarked

> models::PagedModelDossier bookmarked(arg0)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**arg0** | [**Pageable**](.md) |  | [required] |

### Return type

[**models::PagedModelDossier**](PagedModelDossier.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## close_active_dossier

> models::Dossier close_active_dossier()


### Parameters

This endpoint does not need any parameter.

### Return type

[**models::Dossier**](Dossier.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## delete3

> models::Restore200Response delete3()


### Parameters

This endpoint does not need any parameter.

### Return type

[**models::Restore200Response**](restore_200_response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## find_all8

> Vec<models::Dossier> find_all8(closed)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**closed** | Option<**bool**> |  |  |[default to false]

### Return type

[**Vec<models::Dossier>**](Dossier.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## find_all_paged

> models::PagedModelDossier find_all_paged(arg1, closed)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**arg1** | [**Pageable**](.md) |  | [required] |
**closed** | Option<**bool**> |  |  |[default to false]

### Return type

[**models::PagedModelDossier**](PagedModelDossier.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## find_by_fee_id

> models::Dossier find_by_fee_id(id)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **String** |  | [required] |

### Return type

[**models::Dossier**](Dossier.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## find_by_id3

> models::Dossier find_by_id3(id)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **String** |  | [required] |

### Return type

[**models::Dossier**](Dossier.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## generate_summary

> std::path::PathBuf generate_summary(id)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **String** |  | [required] |

### Return type

[**std::path::PathBuf**](std::path::PathBuf.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_dossier_total_size

> i64 get_dossier_total_size(id)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **String** |  | [required] |

### Return type

**i64**

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_import_dossier_xlsx_example

> std::path::PathBuf get_import_dossier_xlsx_example()


### Parameters

This endpoint does not need any parameter.

### Return type

[**std::path::PathBuf**](std::path::PathBuf.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_summaries

> Vec<models::DossierSummary> get_summaries(id)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | [**Vec<String>**](String.md) |  | [required] |

### Return type

[**Vec<models::DossierSummary>**](DossierSummary.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_summaries1

> Vec<models::DossierSummary> get_summaries1(closed)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**closed** | Option<**bool**> |  |  |[default to false]

### Return type

[**Vec<models::DossierSummary>**](DossierSummary.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_summary

> models::DossierSummary get_summary(id)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **String** |  | [required] |

### Return type

[**models::DossierSummary**](DossierSummary.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## import_dossier_from_zip

> import_dossier_from_zip(zip)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**zip** | **std::path::PathBuf** |  | [required] |

### Return type

 (empty response body)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## new_dossier

> models::Dossier new_dossier(dossier)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**dossier** | [**Dossier**](Dossier.md) |  | [required] |

### Return type

[**models::Dossier**](Dossier.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## new_from_previous

> models::Dossier new_from_previous()


### Parameters

This endpoint does not need any parameter.

### Return type

[**models::Dossier**](Dossier.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## process_fees_for_dossier

> process_fees_for_dossier(request_body)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**request_body** | [**Vec<String>**](String.md) |  | [required] |

### Return type

 (empty response body)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## process_invoice_for_dossier

> process_invoice_for_dossier(id)


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


## recall_for_modification

> models::Dossier recall_for_modification(dossier)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**dossier** | [**Dossier**](Dossier.md) |  | [required] |

### Return type

[**models::Dossier**](Dossier.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## remove_document

> models::Dossier remove_document(id)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **String** |  | [required] |

### Return type

[**models::Dossier**](Dossier.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## remove_fee

> models::Dossier remove_fee(fee_id)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**fee_id** | **String** |  | [required] |

### Return type

[**models::Dossier**](Dossier.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## remove_invoice

> models::Dossier remove_invoice(id)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **String** |  | [required] |

### Return type

[**models::Dossier**](Dossier.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## toggle_bookmarked3

> models::Dossier toggle_bookmarked3(id)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **String** |  | [required] |

### Return type

[**models::Dossier**](Dossier.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## update_active_dossier

> models::Dossier update_active_dossier(dossier)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**dossier** | [**Dossier**](Dossier.md) |  | [required] |

### Return type

[**models::Dossier**](Dossier.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

