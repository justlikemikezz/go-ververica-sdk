# \NamespacesApi

All URIs are relative to *https://ververica.prod.bird.co*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateNamespaceUsingPOST**](NamespacesApi.md#CreateNamespaceUsingPOST) | **Post** /namespaces/v1/namespaces | createNamespace
[**DeleteNamespaceUsingDELETE**](NamespacesApi.md#DeleteNamespaceUsingDELETE) | **Delete** /namespaces/v1/namespaces/{ns} | deleteNamespace
[**GetNamespaceUsingGET**](NamespacesApi.md#GetNamespaceUsingGET) | **Get** /namespaces/v1/namespaces/{ns} | getNamespace
[**ListNamespacesUsingGET**](NamespacesApi.md#ListNamespacesUsingGET) | **Get** /namespaces/v1/namespaces | listNamespaces
[**UpdateNamespaceUsingPUT**](NamespacesApi.md#UpdateNamespaceUsingPUT) | **Put** /namespaces/v1/namespaces/{ns} | updateNamespace


# **CreateNamespaceUsingPOST**
> CreateNamespaceResponse CreateNamespaceUsingPOST(ctx, namespace)
createNamespace

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **namespace** | [**Namespace**](Namespace.md)| namespace | 

### Return type

[**CreateNamespaceResponse**](CreateNamespaceResponse.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **DeleteNamespaceUsingDELETE**
> DeleteNamespaceResponse DeleteNamespaceUsingDELETE(ctx, ns)
deleteNamespace

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **ns** | **string**| ns | 

### Return type

[**DeleteNamespaceResponse**](DeleteNamespaceResponse.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetNamespaceUsingGET**
> GetNamespaceResponse GetNamespaceUsingGET(ctx, ns)
getNamespace

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **ns** | **string**| ns | 

### Return type

[**GetNamespaceResponse**](GetNamespaceResponse.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **ListNamespacesUsingGET**
> ListNamespacesResponse ListNamespacesUsingGET(ctx, )
listNamespaces

### Required Parameters
This endpoint does not need any parameter.

### Return type

[**ListNamespacesResponse**](ListNamespacesResponse.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **UpdateNamespaceUsingPUT**
> UpdateNamespaceResponse UpdateNamespaceUsingPUT(ctx, namespace, ns)
updateNamespace

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **namespace** | [**Namespace**](Namespace.md)| namespace | 
  **ns** | **string**| ns | 

### Return type

[**UpdateNamespaceResponse**](UpdateNamespaceResponse.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

