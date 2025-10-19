# \PersonalInfoControllerApi

All URIs are relative to *http://localhost:9000*

Method | HTTP request | Description
------------- | ------------- | -------------
[**get1**](PersonalInfoControllerApi.md#get1) | **GET** /api/personal-info | 
[**me**](PersonalInfoControllerApi.md#me) | **GET** /api/personal-info/@me | 
[**save1**](PersonalInfoControllerApi.md#save1) | **POST** /api/personal-info/submit | 



## get1

> models::PersonalInfo get1()


### Parameters

This endpoint does not need any parameter.

### Return type

[**models::PersonalInfo**](PersonalInfo.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## me

> models::User me()


### Parameters

This endpoint does not need any parameter.

### Return type

[**models::User**](User.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## save1

> models::PersonalInfo save1(ceo_full_name, note, organization_address, demo_mode, finance_charge, organization_city, organization_name, organization_bank_account, organization_bank_bic, organization_email_address, organization_post_code, country_code, max_days_to_pay, organization_phone_number, accountants, vat_number, signature, logo, initial)


### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**ceo_full_name** | **String** |  | [required] |
**note** | **String** |  | [required] |
**organization_address** | **String** |  | [required] |
**demo_mode** | **bool** |  | [required] |
**finance_charge** | **f64** |  | [required] |
**organization_city** | **String** |  | [required] |
**organization_name** | **String** |  | [required] |
**organization_bank_account** | **String** |  | [required] |
**organization_bank_bic** | **String** |  | [required] |
**organization_email_address** | **String** |  | [required] |
**organization_post_code** | **String** |  | [required] |
**country_code** | **String** |  | [required] |
**max_days_to_pay** | **i32** |  | [required] |
**organization_phone_number** | **String** |  | [required] |
**accountants** | **String** |  | [required] |
**vat_number** | **String** |  | [required] |
**signature** | Option<**std::path::PathBuf**> |  |  |
**logo** | Option<**std::path::PathBuf**> |  |  |
**initial** | Option<**std::path::PathBuf**> |  |  |

### Return type

[**models::PersonalInfo**](PersonalInfo.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

