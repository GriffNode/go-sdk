# \MarketDataAPI

All URIs are relative to *https://api.griffnode.com/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetPrices**](MarketDataAPI.md#GetPrices) | **Get** /prices | Current crypto and fiat exchange rates (USD-denominated)
[**ListCryptocurrencies**](MarketDataAPI.md#ListCryptocurrencies) | **Get** /cryptos/list | All supported cryptocurrencies and tokens
[**ListMerchantCryptocurrencies**](MarketDataAPI.md#ListMerchantCryptocurrencies) | **Get** /merchant/cryptos | Cryptocurrencies this merchant has wallets configured for



## GetPrices

> GetPrices200Response GetPrices(ctx).Execute()

Current crypto and fiat exchange rates (USD-denominated)

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
	resp, r, err := apiClient.MarketDataAPI.GetPrices(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MarketDataAPI.GetPrices``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPrices`: GetPrices200Response
	fmt.Fprintf(os.Stdout, "Response from `MarketDataAPI.GetPrices`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetPricesRequest struct via the builder pattern


### Return type

[**GetPrices200Response**](GetPrices200Response.md)

### Authorization

[SecretKey](../README.md#SecretKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListCryptocurrencies

> ListCryptocurrencies200Response ListCryptocurrencies(ctx).Execute()

All supported cryptocurrencies and tokens

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
	resp, r, err := apiClient.MarketDataAPI.ListCryptocurrencies(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MarketDataAPI.ListCryptocurrencies``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListCryptocurrencies`: ListCryptocurrencies200Response
	fmt.Fprintf(os.Stdout, "Response from `MarketDataAPI.ListCryptocurrencies`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiListCryptocurrenciesRequest struct via the builder pattern


### Return type

[**ListCryptocurrencies200Response**](ListCryptocurrencies200Response.md)

### Authorization

[SecretKey](../README.md#SecretKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListMerchantCryptocurrencies

> ListCryptocurrencies200Response ListMerchantCryptocurrencies(ctx).Execute()

Cryptocurrencies this merchant has wallets configured for

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
	resp, r, err := apiClient.MarketDataAPI.ListMerchantCryptocurrencies(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MarketDataAPI.ListMerchantCryptocurrencies``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListMerchantCryptocurrencies`: ListCryptocurrencies200Response
	fmt.Fprintf(os.Stdout, "Response from `MarketDataAPI.ListMerchantCryptocurrencies`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiListMerchantCryptocurrenciesRequest struct via the builder pattern


### Return type

[**ListCryptocurrencies200Response**](ListCryptocurrencies200Response.md)

### Authorization

[SecretKey](../README.md#SecretKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

