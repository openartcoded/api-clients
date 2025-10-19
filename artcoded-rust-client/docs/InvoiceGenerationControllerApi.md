# \InvoiceGenerationControllerApi

All URIs are relative to *http://localhost:9000*

Method | HTTP request | Description
------------- | ------------- | -------------
[**add_template**](InvoiceGenerationControllerApi.md#add_template) | **POST** /api/invoice/add-template | 
[**bookmarked1**](InvoiceGenerationControllerApi.md#bookmarked1) | **GET** /api/invoice/bookmarked | 
[**delete_invoice**](InvoiceGenerationControllerApi.md#delete_invoice) | **DELETE** /api/invoice | 
[**delete_template**](InvoiceGenerationControllerApi.md#delete_template) | **DELETE** /api/invoice/delete-template | 
[**find_all_summaries**](InvoiceGenerationControllerApi.md#find_all_summaries) | **POST** /api/invoice/find-all-summaries | 
[**find_by_id**](InvoiceGenerationControllerApi.md#find_by_id) | **POST** /api/invoice/find-by-id | 
[**find_by_ids**](InvoiceGenerationControllerApi.md#find_by_ids) | **POST** /api/invoice/send-to-peppol | 
[**find_by_ids1**](InvoiceGenerationControllerApi.md#find_by_ids1) | **POST** /api/invoice/find-by-ids | 
[**list_templates**](InvoiceGenerationControllerApi.md#list_templates) | **GET** /api/invoice/list-templates | 
[**make_credit_note**](InvoiceGenerationControllerApi.md#make_credit_note) | **POST** /api/invoice/make-credit-note | 
[**manual_upload**](InvoiceGenerationControllerApi.md#manual_upload) | **POST** /api/invoice/manual-upload | 
[**new_invoice_generation_empty_template**](InvoiceGenerationControllerApi.md#new_invoice_generation_empty_template) | **POST** /api/invoice/new | 
[**new_invoice_generation_from_template**](InvoiceGenerationControllerApi.md#new_invoice_generation_from_template) | **POST** /api/invoice/from-template | 
[**page**](InvoiceGenerationControllerApi.md#page) | **POST** /api/invoice/page | 
[**restore**](InvoiceGenerationControllerApi.md#restore) | **POST** /api/invoice/restore | 
[**save4**](InvoiceGenerationControllerApi.md#save4) | **POST** /api/invoice/save | 
[**toggle_bookmarked1**](InvoiceGenerationControllerApi.md#toggle_bookmarked1) | **POST** /api/invoice/toggle-bookmarked | 
[**validate_peppol**](InvoiceGenerationControllerApi.md#validate_peppol) | **POST** /api/invoice/validate-peppol | 



## add_template

> models::InvoiceFreemarkerTemplate add_template(name, template)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**name** | **String** |  | [required] |
**template** | **std::path::PathBuf** |  | [required] |

### Return type

[**models::InvoiceFreemarkerTemplate**](InvoiceFreemarkerTemplate.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## bookmarked1

> models::PagedModelInvoiceGeneration bookmarked1(arg0)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**arg0** | [**Pageable**](.md) |  | [required] |

### Return type

[**models::PagedModelInvoiceGeneration**](PagedModelInvoiceGeneration.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## delete_invoice

> models::Restore200Response delete_invoice(id, logical)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **String** |  | [required] |
**logical** | Option<**bool**> |  |  |[default to true]

### Return type

[**models::Restore200Response**](restore_200_response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## delete_template

> delete_template(id)


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


## find_all_summaries

> Vec<models::InvoiceSummary> find_all_summaries()


### Parameters

This endpoint does not need any parameter.

### Return type

[**Vec<models::InvoiceSummary>**](InvoiceSummary.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## find_by_id

> models::InvoiceGeneration find_by_id(id)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **String** |  | [required] |

### Return type

[**models::InvoiceGeneration**](InvoiceGeneration.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## find_by_ids

> find_by_ids(id)


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


## find_by_ids1

> Vec<models::InvoiceGeneration> find_by_ids1(id)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | [**Vec<String>**](String.md) |  | [required] |

### Return type

[**Vec<models::InvoiceGeneration>**](InvoiceGeneration.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## list_templates

> Vec<models::InvoiceFreemarkerTemplate> list_templates()


### Parameters

This endpoint does not need any parameter.

### Return type

[**Vec<models::InvoiceFreemarkerTemplate>**](InvoiceFreemarkerTemplate.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## make_credit_note

> models::InvoiceGeneration make_credit_note(id)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **String** |  | [required] |

### Return type

[**models::InvoiceGeneration**](InvoiceGeneration.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## manual_upload

> manual_upload(id, manual_upload_file)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **String** |  | [required] |
**manual_upload_file** | **std::path::PathBuf** |  | [required] |

### Return type

 (empty response body)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## new_invoice_generation_empty_template

> models::InvoiceGeneration new_invoice_generation_empty_template()


### Parameters

This endpoint does not need any parameter.

### Return type

[**models::InvoiceGeneration**](InvoiceGeneration.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## new_invoice_generation_from_template

> models::InvoiceGeneration new_invoice_generation_from_template(id)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **String** |  | [required] |

### Return type

[**models::InvoiceGeneration**](InvoiceGeneration.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## page

> models::PagedModelInvoiceGeneration page(arg2, archived, logical)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**arg2** | [**Pageable**](.md) |  | [required] |
**archived** | Option<**bool**> |  |  |[default to false]
**logical** | Option<**bool**> |  |  |[default to false]

### Return type

[**models::PagedModelInvoiceGeneration**](PagedModelInvoiceGeneration.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## restore

> models::Restore200Response restore(id)


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


## save4

> models::InvoiceGeneration save4(invoice_generation)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**invoice_generation** | [**InvoiceGeneration**](InvoiceGeneration.md) |  | [required] |

### Return type

[**models::InvoiceGeneration**](InvoiceGeneration.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## toggle_bookmarked1

> models::InvoiceGeneration toggle_bookmarked1(id)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **String** |  | [required] |

### Return type

[**models::InvoiceGeneration**](InvoiceGeneration.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## validate_peppol

> models::PeppolValidationResult validate_peppol(id)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **String** |  | [required] |

### Return type

[**models::PeppolValidationResult**](PeppolValidationResult.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

