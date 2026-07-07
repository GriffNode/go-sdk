# \TransactionsAPI

All URIs are relative to *https://api.griffnode.com/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateDetailedTransaction**](TransactionsAPI.md#CreateDetailedTransaction) | **Post** /transactions/create-detailed | Create an itemized transaction (Professional/Enterprise plans)
[**CreateTransaction**](TransactionsAPI.md#CreateTransaction) | **Post** /transactions/create | Create a payment transaction
[**GetTransaction**](TransactionsAPI.md#GetTransaction) | **Get** /transactions/{transaction_id} | Retrieve a single transaction
[**ListTransactions**](TransactionsAPI.md#ListTransactions) | **Get** /transactions/list | List the merchant&#39;s transactions (newest first)



## CreateDetailedTransaction

> TransactionEnvelope CreateDetailedTransaction(ctx).CreateDetailedTransactionRequest(createDetailedTransactionRequest).XIdempotencyKey(xIdempotencyKey).Execute()

Create an itemized transaction (Professional/Enterprise plans)

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
	createDetailedTransactionRequest := *openapiclient.NewCreateDetailedTransactionRequest(openapiclient.CryptoSymbol("BTC"), []openapiclient.LineItem{*openapiclient.NewLineItem("Name_example", float32(123))}, "OrderId_example") // CreateDetailedTransactionRequest | 
	xIdempotencyKey := "xIdempotencyKey_example" // string | Optional unique key for a create request (e.g. a UUID). A retried create with the same key returns the original transaction instead of creating a duplicate — send it on every create so a network retry can't double-charge the customer.  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TransactionsAPI.CreateDetailedTransaction(context.Background()).CreateDetailedTransactionRequest(createDetailedTransactionRequest).XIdempotencyKey(xIdempotencyKey).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TransactionsAPI.CreateDetailedTransaction``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateDetailedTransaction`: TransactionEnvelope
	fmt.Fprintf(os.Stdout, "Response from `TransactionsAPI.CreateDetailedTransaction`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateDetailedTransactionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createDetailedTransactionRequest** | [**CreateDetailedTransactionRequest**](CreateDetailedTransactionRequest.md) |  | 
 **xIdempotencyKey** | **string** | Optional unique key for a create request (e.g. a UUID). A retried create with the same key returns the original transaction instead of creating a duplicate — send it on every create so a network retry can&#39;t double-charge the customer.  | 

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


## CreateTransaction

> TransactionEnvelope CreateTransaction(ctx).CreateTransactionRequest(createTransactionRequest).XIdempotencyKey(xIdempotencyKey).Execute()

Create a payment transaction

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
	createTransactionRequest := *openapiclient.NewCreateTransactionRequest(openapiclient.CryptoSymbol("BTC"), float32(123)) // CreateTransactionRequest | 
	xIdempotencyKey := "xIdempotencyKey_example" // string | Optional unique key for a create request (e.g. a UUID). A retried create with the same key returns the original transaction instead of creating a duplicate — send it on every create so a network retry can't double-charge the customer.  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TransactionsAPI.CreateTransaction(context.Background()).CreateTransactionRequest(createTransactionRequest).XIdempotencyKey(xIdempotencyKey).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TransactionsAPI.CreateTransaction``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateTransaction`: TransactionEnvelope
	fmt.Fprintf(os.Stdout, "Response from `TransactionsAPI.CreateTransaction`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateTransactionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createTransactionRequest** | [**CreateTransactionRequest**](CreateTransactionRequest.md) |  | 
 **xIdempotencyKey** | **string** | Optional unique key for a create request (e.g. a UUID). A retried create with the same key returns the original transaction instead of creating a duplicate — send it on every create so a network retry can&#39;t double-charge the customer.  | 

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


## GetTransaction

> TransactionEnvelope GetTransaction(ctx, transactionId).Execute()

Retrieve a single transaction

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
	transactionId := "transactionId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TransactionsAPI.GetTransaction(context.Background(), transactionId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TransactionsAPI.GetTransaction``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetTransaction`: TransactionEnvelope
	fmt.Fprintf(os.Stdout, "Response from `TransactionsAPI.GetTransaction`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**transactionId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetTransactionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**TransactionEnvelope**](TransactionEnvelope.md)

### Authorization

[SecretKey](../README.md#SecretKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListTransactions

> ListTransactions200Response ListTransactions(ctx).Limit(limit).Offset(offset).Status(status).Crypto(crypto).Execute()

List the merchant's transactions (newest first)

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
	limit := int32(56) // int32 |  (optional) (default to 20)
	offset := int32(56) // int32 |  (optional) (default to 0)
	status := openapiclient.TransactionStatus("pending") // TransactionStatus |  (optional)
	crypto := openapiclient.CryptoSymbol("BTC") // CryptoSymbol |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TransactionsAPI.ListTransactions(context.Background()).Limit(limit).Offset(offset).Status(status).Crypto(crypto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TransactionsAPI.ListTransactions``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListTransactions`: ListTransactions200Response
	fmt.Fprintf(os.Stdout, "Response from `TransactionsAPI.ListTransactions`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListTransactionsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **limit** | **int32** |  | [default to 20]
 **offset** | **int32** |  | [default to 0]
 **status** | [**TransactionStatus**](TransactionStatus.md) |  | 
 **crypto** | [**CryptoSymbol**](CryptoSymbol.md) |  | 

### Return type

[**ListTransactions200Response**](ListTransactions200Response.md)

### Authorization

[SecretKey](../README.md#SecretKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

