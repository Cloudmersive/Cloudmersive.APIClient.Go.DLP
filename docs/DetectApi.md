# \DetectApi

All URIs are relative to *https://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**DetectDocument**](DetectApi.md#DetectDocument) | **Post** /dlp/detect/document | Detect User Data in Document Image
[**DetectDocumentAdvanced**](DetectApi.md#DetectDocumentAdvanced) | **Post** /dlp/detect/document/advanced | Detect User Data in Document Image (Advanced)
[**DetectText**](DetectApi.md#DetectText) | **Post** /dlp/detect/text | Detect User Data in Input Text
[**DetectTextAdvanced**](DetectApi.md#DetectTextAdvanced) | **Post** /dlp/detect/text/advanced | Detect User Data in Input Text (Advanced)


# **DetectDocument**
> DlpDetectionResponse DetectDocument(ctx, optional)
Detect User Data in Document Image

Detects configurable types of user data in a document image (PDF, DOCX, PNG, JPG) using Advanced AI.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***DetectApiDetectDocumentOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DetectApiDetectDocumentOpts struct

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**optional.Interface of DlpDocumentDetectionRequest**](DlpDocumentDetectionRequest.md)| Input request | 

### Return type

[**DlpDetectionResponse**](DlpDetectionResponse.md)

### Authorization

[Apikey](../README.md#Apikey)

### HTTP request headers

 - **Content-Type**: application/json, text/json, application/_*+json
 - **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **DetectDocumentAdvanced**
> DlpAdvancedDetectionResponse DetectDocumentAdvanced(ctx, optional)
Detect User Data in Document Image (Advanced)

Detects 29 configurable types of user data including health-related PHI in a document image (PDF, DOCX, PNG, JPG) using Advanced AI.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***DetectApiDetectDocumentAdvancedOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DetectApiDetectDocumentAdvancedOpts struct

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**optional.Interface of DlpAdvancedDocumentDetectionRequest**](DlpAdvancedDocumentDetectionRequest.md)| Input request | 

### Return type

[**DlpAdvancedDetectionResponse**](DlpAdvancedDetectionResponse.md)

### Authorization

[Apikey](../README.md#Apikey)

### HTTP request headers

 - **Content-Type**: application/json, text/json, application/_*+json
 - **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **DetectText**
> DlpDetectionResponse DetectText(ctx, optional)
Detect User Data in Input Text

Detects configurable types of user data in an input text string using Advanced AI.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***DetectApiDetectTextOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DetectApiDetectTextOpts struct

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**optional.Interface of DlpDetectionRequest**](DlpDetectionRequest.md)| Input request | 

### Return type

[**DlpDetectionResponse**](DlpDetectionResponse.md)

### Authorization

[Apikey](../README.md#Apikey)

### HTTP request headers

 - **Content-Type**: application/json, text/json, application/_*+json
 - **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **DetectTextAdvanced**
> DlpAdvancedDetectionResponse DetectTextAdvanced(ctx, optional)
Detect User Data in Input Text (Advanced)

Detects 29 configurable types of user data including health-related PHI in an input text string using Advanced AI.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***DetectApiDetectTextAdvancedOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DetectApiDetectTextAdvancedOpts struct

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**optional.Interface of DlpAdvancedDetectionRequest**](DlpAdvancedDetectionRequest.md)| Input request | 

### Return type

[**DlpAdvancedDetectionResponse**](DlpAdvancedDetectionResponse.md)

### Authorization

[Apikey](../README.md#Apikey)

### HTTP request headers

 - **Content-Type**: application/json, text/json, application/_*+json
 - **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

