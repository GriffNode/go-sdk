# \SystemAPI

All URIs are relative to *https://api.cryptogate.live/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetHealth**](SystemAPI.md#GetHealth) | **Get** /health | API health check
[**HostedCheckoutRedirect**](SystemAPI.md#HostedCheckoutRedirect) | **Get** /pay | Hosted-checkout redirect (browser flow, publishable key)



## GetHealth

> GetHealth200Response GetHealth(ctx).Execute()

API health check

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SystemAPI.GetHealth(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SystemAPI.GetHealth``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetHealth`: GetHealth200Response
	fmt.Fprintf(os.Stdout, "Response from `SystemAPI.GetHealth`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetHealthRequest struct via the builder pattern


### Return type

[**GetHealth200Response**](GetHealth200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## HostedCheckoutRedirect

> HostedCheckoutRedirect(ctx).Pk(pk).Amount(amount).Crypto(crypto).Link(link).Execute()

Hosted-checkout redirect (browser flow, publishable key)



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	pk := "pk_example" // string | Publishable key, pk_live_… / pk_test_…
	amount := "amount_example" // string | Fiat amount (≥ 1.00 USD equivalent).
	crypto := openapiclient.CryptoSymbol("BTC") // CryptoSymbol | 
	link := "link_example" // string | Payment-link slug for attribution. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.SystemAPI.HostedCheckoutRedirect(context.Background()).Pk(pk).Amount(amount).Crypto(crypto).Link(link).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SystemAPI.HostedCheckoutRedirect``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiHostedCheckoutRedirectRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **pk** | **string** | Publishable key, pk_live_… / pk_test_… | 
 **amount** | **string** | Fiat amount (≥ 1.00 USD equivalent). | 
 **crypto** | [**CryptoSymbol**](CryptoSymbol.md) |  | 
 **link** | **string** | Payment-link slug for attribution. | 

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

