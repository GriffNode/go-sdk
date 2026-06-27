# \DefaultAPI

All URIs are relative to *https://api.cryptogate.live/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**PaymentWebhook**](DefaultAPI.md#PaymentWebhook) | **Post** /paymentEvent | Payment lifecycle event delivered to the merchant&#39;s webhook URL



## PaymentWebhook

> PaymentWebhook(ctx).WebhookPayload(webhookPayload).Execute()

Payment lifecycle event delivered to the merchant's webhook URL



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
	webhookPayload :=  // WebhookPayload |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.DefaultAPI.PaymentWebhook(context.Background()).WebhookPayload(webhookPayload).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.PaymentWebhook``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiPaymentWebhookRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **webhookPayload** | [**WebhookPayload**](WebhookPayload.md) |  | 

### Return type

 (empty response body)

### Authorization

[SecretKey](../README.md#SecretKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

