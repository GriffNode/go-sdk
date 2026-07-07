# \AccountAPI

All URIs are relative to *https://api.griffnode.com/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetAccount**](AccountAPI.md#GetAccount) | **Get** /account | Merchant plan, usage and limits
[**GetStats**](AccountAPI.md#GetStats) | **Get** /stats | Merchant transaction analytics
[**ListBalances**](AccountAPI.md#ListBalances) | **Get** /balances | On-platform balances (for overage/top-up; NOT crypto settlement)
[**ListInvoices**](AccountAPI.md#ListInvoices) | **Get** /invoices | GriffNode billing invoices (platform ↔ merchant)
[**ListPlans**](AccountAPI.md#ListPlans) | **Get** /plans | Plan catalogue and pricing



## GetAccount

> GetAccount200Response GetAccount(ctx).Execute()

Merchant plan, usage and limits

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
	resp, r, err := apiClient.AccountAPI.GetAccount(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AccountAPI.GetAccount``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAccount`: GetAccount200Response
	fmt.Fprintf(os.Stdout, "Response from `AccountAPI.GetAccount`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetAccountRequest struct via the builder pattern


### Return type

[**GetAccount200Response**](GetAccount200Response.md)

### Authorization

[SecretKey](../README.md#SecretKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetStats

> GetStats200Response GetStats(ctx).Execute()

Merchant transaction analytics

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
	resp, r, err := apiClient.AccountAPI.GetStats(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AccountAPI.GetStats``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetStats`: GetStats200Response
	fmt.Fprintf(os.Stdout, "Response from `AccountAPI.GetStats`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetStatsRequest struct via the builder pattern


### Return type

[**GetStats200Response**](GetStats200Response.md)

### Authorization

[SecretKey](../README.md#SecretKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListBalances

> ListBalances200Response ListBalances(ctx).Execute()

On-platform balances (for overage/top-up; NOT crypto settlement)

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
	resp, r, err := apiClient.AccountAPI.ListBalances(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AccountAPI.ListBalances``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListBalances`: ListBalances200Response
	fmt.Fprintf(os.Stdout, "Response from `AccountAPI.ListBalances`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiListBalancesRequest struct via the builder pattern


### Return type

[**ListBalances200Response**](ListBalances200Response.md)

### Authorization

[SecretKey](../README.md#SecretKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListInvoices

> ListInvoices200Response ListInvoices(ctx).Limit(limit).Offset(offset).Execute()

GriffNode billing invoices (platform ↔ merchant)

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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AccountAPI.ListInvoices(context.Background()).Limit(limit).Offset(offset).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AccountAPI.ListInvoices``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListInvoices`: ListInvoices200Response
	fmt.Fprintf(os.Stdout, "Response from `AccountAPI.ListInvoices`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListInvoicesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **limit** | **int32** |  | [default to 20]
 **offset** | **int32** |  | [default to 0]

### Return type

[**ListInvoices200Response**](ListInvoices200Response.md)

### Authorization

[SecretKey](../README.md#SecretKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListPlans

> ListPlans200Response ListPlans(ctx).Execute()

Plan catalogue and pricing

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
	resp, r, err := apiClient.AccountAPI.ListPlans(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AccountAPI.ListPlans``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListPlans`: ListPlans200Response
	fmt.Fprintf(os.Stdout, "Response from `AccountAPI.ListPlans`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiListPlansRequest struct via the builder pattern


### Return type

[**ListPlans200Response**](ListPlans200Response.md)

### Authorization

[SecretKey](../README.md#SecretKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

