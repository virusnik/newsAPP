# DefaultApi

All URIs are relative to *https://newsapi.org*

Method | HTTP request | Description
------------- | ------------- | -------------
[**v2EverythingGet**](DefaultApi.md#v2EverythingGet) | **GET** /v2/everything | 


<a name="v2EverythingGet"></a>
# **v2EverythingGet**
> v2EverythingGet(q, apiKey, from, sortBy, to)



Auto generated using Swagger Inspector

### Example
```kotlin
// Import classes:
//import org.openapitools.client.infrastructure.*
//import org.openapitools.client.models.*

val apiInstance = DefaultApi()
val q : kotlin.String = apple // kotlin.String | 
val apiKey : kotlin.String = efa12c02cba74bcfbfc150cb9e9c4b3b // kotlin.String | 
val from : kotlin.String = 2020-07-12 // kotlin.String | 
val sortBy : kotlin.String = popularity // kotlin.String | 
val to : kotlin.String = 2020-07-12 // kotlin.String | 
try {
    apiInstance.v2EverythingGet(q, apiKey, from, sortBy, to)
} catch (e: ClientException) {
    println("4xx response calling DefaultApi#v2EverythingGet")
    e.printStackTrace()
} catch (e: ServerException) {
    println("5xx response calling DefaultApi#v2EverythingGet")
    e.printStackTrace()
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **q** | **kotlin.String**|  | [optional]
 **apiKey** | **kotlin.String**|  | [optional]
 **from** | **kotlin.String**|  | [optional]
 **sortBy** | **kotlin.String**|  | [optional]
 **to** | **kotlin.String**|  | [optional]

### Return type

null (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

