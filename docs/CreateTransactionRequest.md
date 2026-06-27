# CreateTransactionRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Crypto** | [**CryptoSymbol**](CryptoSymbol.md) |  | 
**Amount** | **float32** | Fiat amount (≥ 1.00 USD equivalent). | 
**CurrencyFiat** | Pointer to [**FiatCurrency**](FiatCurrency.md) |  | [optional] [default to FIATCURRENCY_USD]
**Metadata** | Pointer to **map[string]string** | Free-form key/value (≤20 keys, string values ≤500 chars, ≤4 KB total). | [optional] 
**CustomerEmail** | Pointer to **NullableString** |  | [optional] 
**SuccessUrl** | Pointer to **NullableString** |  | [optional] 
**CancelUrl** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewCreateTransactionRequest

`func NewCreateTransactionRequest(crypto CryptoSymbol, amount float32, ) *CreateTransactionRequest`

NewCreateTransactionRequest instantiates a new CreateTransactionRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateTransactionRequestWithDefaults

`func NewCreateTransactionRequestWithDefaults() *CreateTransactionRequest`

NewCreateTransactionRequestWithDefaults instantiates a new CreateTransactionRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCrypto

`func (o *CreateTransactionRequest) GetCrypto() CryptoSymbol`

GetCrypto returns the Crypto field if non-nil, zero value otherwise.

### GetCryptoOk

`func (o *CreateTransactionRequest) GetCryptoOk() (*CryptoSymbol, bool)`

GetCryptoOk returns a tuple with the Crypto field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCrypto

`func (o *CreateTransactionRequest) SetCrypto(v CryptoSymbol)`

SetCrypto sets Crypto field to given value.


### GetAmount

`func (o *CreateTransactionRequest) GetAmount() float32`

GetAmount returns the Amount field if non-nil, zero value otherwise.

### GetAmountOk

`func (o *CreateTransactionRequest) GetAmountOk() (*float32, bool)`

GetAmountOk returns a tuple with the Amount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmount

`func (o *CreateTransactionRequest) SetAmount(v float32)`

SetAmount sets Amount field to given value.


### GetCurrencyFiat

`func (o *CreateTransactionRequest) GetCurrencyFiat() FiatCurrency`

GetCurrencyFiat returns the CurrencyFiat field if non-nil, zero value otherwise.

### GetCurrencyFiatOk

`func (o *CreateTransactionRequest) GetCurrencyFiatOk() (*FiatCurrency, bool)`

GetCurrencyFiatOk returns a tuple with the CurrencyFiat field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrencyFiat

`func (o *CreateTransactionRequest) SetCurrencyFiat(v FiatCurrency)`

SetCurrencyFiat sets CurrencyFiat field to given value.

### HasCurrencyFiat

`func (o *CreateTransactionRequest) HasCurrencyFiat() bool`

HasCurrencyFiat returns a boolean if a field has been set.

### GetMetadata

`func (o *CreateTransactionRequest) GetMetadata() map[string]string`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *CreateTransactionRequest) GetMetadataOk() (*map[string]string, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *CreateTransactionRequest) SetMetadata(v map[string]string)`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *CreateTransactionRequest) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.

### GetCustomerEmail

`func (o *CreateTransactionRequest) GetCustomerEmail() string`

GetCustomerEmail returns the CustomerEmail field if non-nil, zero value otherwise.

### GetCustomerEmailOk

`func (o *CreateTransactionRequest) GetCustomerEmailOk() (*string, bool)`

GetCustomerEmailOk returns a tuple with the CustomerEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerEmail

`func (o *CreateTransactionRequest) SetCustomerEmail(v string)`

SetCustomerEmail sets CustomerEmail field to given value.

### HasCustomerEmail

`func (o *CreateTransactionRequest) HasCustomerEmail() bool`

HasCustomerEmail returns a boolean if a field has been set.

### SetCustomerEmailNil

`func (o *CreateTransactionRequest) SetCustomerEmailNil(b bool)`

 SetCustomerEmailNil sets the value for CustomerEmail to be an explicit nil

### UnsetCustomerEmail
`func (o *CreateTransactionRequest) UnsetCustomerEmail()`

UnsetCustomerEmail ensures that no value is present for CustomerEmail, not even an explicit nil
### GetSuccessUrl

`func (o *CreateTransactionRequest) GetSuccessUrl() string`

GetSuccessUrl returns the SuccessUrl field if non-nil, zero value otherwise.

### GetSuccessUrlOk

`func (o *CreateTransactionRequest) GetSuccessUrlOk() (*string, bool)`

GetSuccessUrlOk returns a tuple with the SuccessUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccessUrl

`func (o *CreateTransactionRequest) SetSuccessUrl(v string)`

SetSuccessUrl sets SuccessUrl field to given value.

### HasSuccessUrl

`func (o *CreateTransactionRequest) HasSuccessUrl() bool`

HasSuccessUrl returns a boolean if a field has been set.

### SetSuccessUrlNil

`func (o *CreateTransactionRequest) SetSuccessUrlNil(b bool)`

 SetSuccessUrlNil sets the value for SuccessUrl to be an explicit nil

### UnsetSuccessUrl
`func (o *CreateTransactionRequest) UnsetSuccessUrl()`

UnsetSuccessUrl ensures that no value is present for SuccessUrl, not even an explicit nil
### GetCancelUrl

`func (o *CreateTransactionRequest) GetCancelUrl() string`

GetCancelUrl returns the CancelUrl field if non-nil, zero value otherwise.

### GetCancelUrlOk

`func (o *CreateTransactionRequest) GetCancelUrlOk() (*string, bool)`

GetCancelUrlOk returns a tuple with the CancelUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCancelUrl

`func (o *CreateTransactionRequest) SetCancelUrl(v string)`

SetCancelUrl sets CancelUrl field to given value.

### HasCancelUrl

`func (o *CreateTransactionRequest) HasCancelUrl() bool`

HasCancelUrl returns a boolean if a field has been set.

### SetCancelUrlNil

`func (o *CreateTransactionRequest) SetCancelUrlNil(b bool)`

 SetCancelUrlNil sets the value for CancelUrl to be an explicit nil

### UnsetCancelUrl
`func (o *CreateTransactionRequest) UnsetCancelUrl()`

UnsetCancelUrl ensures that no value is present for CancelUrl, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


