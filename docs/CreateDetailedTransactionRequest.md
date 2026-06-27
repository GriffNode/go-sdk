# CreateDetailedTransactionRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Crypto** | [**CryptoSymbol**](CryptoSymbol.md) |  | 
**CurrencyFiat** | Pointer to [**FiatCurrency**](FiatCurrency.md) |  | [optional] [default to FIATCURRENCY_USD]
**Items** | [**[]LineItem**](LineItem.md) |  | 
**OrderId** | **string** |  | 
**Metadata** | Pointer to **map[string]string** | Free-form key/value (≤20 keys, string values ≤500 chars, ≤4 KB total). | [optional] 
**CustomerEmail** | Pointer to **NullableString** |  | [optional] 
**SuccessUrl** | Pointer to **NullableString** |  | [optional] 
**CancelUrl** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewCreateDetailedTransactionRequest

`func NewCreateDetailedTransactionRequest(crypto CryptoSymbol, items []LineItem, orderId string, ) *CreateDetailedTransactionRequest`

NewCreateDetailedTransactionRequest instantiates a new CreateDetailedTransactionRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateDetailedTransactionRequestWithDefaults

`func NewCreateDetailedTransactionRequestWithDefaults() *CreateDetailedTransactionRequest`

NewCreateDetailedTransactionRequestWithDefaults instantiates a new CreateDetailedTransactionRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCrypto

`func (o *CreateDetailedTransactionRequest) GetCrypto() CryptoSymbol`

GetCrypto returns the Crypto field if non-nil, zero value otherwise.

### GetCryptoOk

`func (o *CreateDetailedTransactionRequest) GetCryptoOk() (*CryptoSymbol, bool)`

GetCryptoOk returns a tuple with the Crypto field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCrypto

`func (o *CreateDetailedTransactionRequest) SetCrypto(v CryptoSymbol)`

SetCrypto sets Crypto field to given value.


### GetCurrencyFiat

`func (o *CreateDetailedTransactionRequest) GetCurrencyFiat() FiatCurrency`

GetCurrencyFiat returns the CurrencyFiat field if non-nil, zero value otherwise.

### GetCurrencyFiatOk

`func (o *CreateDetailedTransactionRequest) GetCurrencyFiatOk() (*FiatCurrency, bool)`

GetCurrencyFiatOk returns a tuple with the CurrencyFiat field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrencyFiat

`func (o *CreateDetailedTransactionRequest) SetCurrencyFiat(v FiatCurrency)`

SetCurrencyFiat sets CurrencyFiat field to given value.

### HasCurrencyFiat

`func (o *CreateDetailedTransactionRequest) HasCurrencyFiat() bool`

HasCurrencyFiat returns a boolean if a field has been set.

### GetItems

`func (o *CreateDetailedTransactionRequest) GetItems() []LineItem`

GetItems returns the Items field if non-nil, zero value otherwise.

### GetItemsOk

`func (o *CreateDetailedTransactionRequest) GetItemsOk() (*[]LineItem, bool)`

GetItemsOk returns a tuple with the Items field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItems

`func (o *CreateDetailedTransactionRequest) SetItems(v []LineItem)`

SetItems sets Items field to given value.


### GetOrderId

`func (o *CreateDetailedTransactionRequest) GetOrderId() string`

GetOrderId returns the OrderId field if non-nil, zero value otherwise.

### GetOrderIdOk

`func (o *CreateDetailedTransactionRequest) GetOrderIdOk() (*string, bool)`

GetOrderIdOk returns a tuple with the OrderId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderId

`func (o *CreateDetailedTransactionRequest) SetOrderId(v string)`

SetOrderId sets OrderId field to given value.


### GetMetadata

`func (o *CreateDetailedTransactionRequest) GetMetadata() map[string]string`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *CreateDetailedTransactionRequest) GetMetadataOk() (*map[string]string, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *CreateDetailedTransactionRequest) SetMetadata(v map[string]string)`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *CreateDetailedTransactionRequest) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.

### GetCustomerEmail

`func (o *CreateDetailedTransactionRequest) GetCustomerEmail() string`

GetCustomerEmail returns the CustomerEmail field if non-nil, zero value otherwise.

### GetCustomerEmailOk

`func (o *CreateDetailedTransactionRequest) GetCustomerEmailOk() (*string, bool)`

GetCustomerEmailOk returns a tuple with the CustomerEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerEmail

`func (o *CreateDetailedTransactionRequest) SetCustomerEmail(v string)`

SetCustomerEmail sets CustomerEmail field to given value.

### HasCustomerEmail

`func (o *CreateDetailedTransactionRequest) HasCustomerEmail() bool`

HasCustomerEmail returns a boolean if a field has been set.

### SetCustomerEmailNil

`func (o *CreateDetailedTransactionRequest) SetCustomerEmailNil(b bool)`

 SetCustomerEmailNil sets the value for CustomerEmail to be an explicit nil

### UnsetCustomerEmail
`func (o *CreateDetailedTransactionRequest) UnsetCustomerEmail()`

UnsetCustomerEmail ensures that no value is present for CustomerEmail, not even an explicit nil
### GetSuccessUrl

`func (o *CreateDetailedTransactionRequest) GetSuccessUrl() string`

GetSuccessUrl returns the SuccessUrl field if non-nil, zero value otherwise.

### GetSuccessUrlOk

`func (o *CreateDetailedTransactionRequest) GetSuccessUrlOk() (*string, bool)`

GetSuccessUrlOk returns a tuple with the SuccessUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccessUrl

`func (o *CreateDetailedTransactionRequest) SetSuccessUrl(v string)`

SetSuccessUrl sets SuccessUrl field to given value.

### HasSuccessUrl

`func (o *CreateDetailedTransactionRequest) HasSuccessUrl() bool`

HasSuccessUrl returns a boolean if a field has been set.

### SetSuccessUrlNil

`func (o *CreateDetailedTransactionRequest) SetSuccessUrlNil(b bool)`

 SetSuccessUrlNil sets the value for SuccessUrl to be an explicit nil

### UnsetSuccessUrl
`func (o *CreateDetailedTransactionRequest) UnsetSuccessUrl()`

UnsetSuccessUrl ensures that no value is present for SuccessUrl, not even an explicit nil
### GetCancelUrl

`func (o *CreateDetailedTransactionRequest) GetCancelUrl() string`

GetCancelUrl returns the CancelUrl field if non-nil, zero value otherwise.

### GetCancelUrlOk

`func (o *CreateDetailedTransactionRequest) GetCancelUrlOk() (*string, bool)`

GetCancelUrlOk returns a tuple with the CancelUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCancelUrl

`func (o *CreateDetailedTransactionRequest) SetCancelUrl(v string)`

SetCancelUrl sets CancelUrl field to given value.

### HasCancelUrl

`func (o *CreateDetailedTransactionRequest) HasCancelUrl() bool`

HasCancelUrl returns a boolean if a field has been set.

### SetCancelUrlNil

`func (o *CreateDetailedTransactionRequest) SetCancelUrlNil(b bool)`

 SetCancelUrlNil sets the value for CancelUrl to be an explicit nil

### UnsetCancelUrl
`func (o *CreateDetailedTransactionRequest) UnsetCancelUrl()`

UnsetCancelUrl ensures that no value is present for CancelUrl, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


