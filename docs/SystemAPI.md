# \SystemAPI

All URIs are relative to *https://api.griffnode.com/v1*

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

> HostedCheckoutRedirect(ctx).Pk(pk).Amount(amount).Crypto(crypto).Currency(currency).Link(link).Execute()

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
	currency := "currency_example" // string | Fiat currency of `amount`. Ignored when `link` is set: a payment link always uses its own amount and currency. (optional) (default to "USD")
	link := "link_example" // string | Payment-link slug. The link's own amount, currency, expiry and single-use rules apply (410 if expired, 409 if a single-use link was already paid). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.SystemAPI.HostedCheckoutRedirect(context.Background()).Pk(pk).Amount(amount).Crypto(crypto).Currency(currency).Link(link).Execute()
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
 **currency** | **string** | Fiat currency of &#x60;amount&#x60;. Ignored when &#x60;link&#x60; is set: a payment link always uses its own amount and currency. | [default to &quot;USD&quot;]
 **link** | **string** | Payment-link slug. The link&#39;s own amount, currency, expiry and single-use rules apply (410 if expired, 409 if a single-use link was already paid). | 

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

