# \BillingAPI

All URIs are relative to *https://api.griffnode.com/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateBillingCheckout**](BillingAPI.md#CreateBillingCheckout) | **Post** /billing/checkout | Start a plan upgrade or account top-up



## CreateBillingCheckout

> TransactionEnvelope CreateBillingCheckout(ctx).CreateBillingCheckoutRequest(createBillingCheckoutRequest).Execute()

Start a plan upgrade or account top-up

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
	createBillingCheckoutRequest := *openapiclient.NewCreateBillingCheckoutRequest(openapiclient.PlanTier("starter")) // CreateBillingCheckoutRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BillingAPI.CreateBillingCheckout(context.Background()).CreateBillingCheckoutRequest(createBillingCheckoutRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BillingAPI.CreateBillingCheckout``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateBillingCheckout`: TransactionEnvelope
	fmt.Fprintf(os.Stdout, "Response from `BillingAPI.CreateBillingCheckout`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateBillingCheckoutRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createBillingCheckoutRequest** | [**CreateBillingCheckoutRequest**](CreateBillingCheckoutRequest.md) |  | 

### Return type

[**TransactionEnvelope**](TransactionEnvelope.md)

### Authorization

[SecretKey](../README.md#SecretKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

