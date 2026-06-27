# Invoice

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**TransactionId** | Pointer to **string** |  | [optional] 
**PurchaseType** | Pointer to **string** |  | [optional] 
**AmountFiat** | Pointer to **float32** |  | [optional] 
**CurrencyFiat** | Pointer to [**FiatCurrency**](FiatCurrency.md) |  | [optional] [default to FIATCURRENCY_USD]
**Status** | Pointer to **string** |  | [optional] 
**CryptoSymbol** | Pointer to [**CryptoSymbol**](CryptoSymbol.md) |  | [optional] 
**CreatedAt** | Pointer to **time.Time** |  | [optional] 
**ConfirmedAt** | Pointer to **NullableTime** |  | [optional] 
**ExpiresAt** | Pointer to **time.Time** |  | [optional] 

## Methods

### NewInvoice

`func NewInvoice() *Invoice`

NewInvoice instantiates a new Invoice object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInvoiceWithDefaults

`func NewInvoiceWithDefaults() *Invoice`

NewInvoiceWithDefaults instantiates a new Invoice object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTransactionId

`func (o *Invoice) GetTransactionId() string`

GetTransactionId returns the TransactionId field if non-nil, zero value otherwise.

### GetTransactionIdOk

`func (o *Invoice) GetTransactionIdOk() (*string, bool)`

GetTransactionIdOk returns a tuple with the TransactionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransactionId

`func (o *Invoice) SetTransactionId(v string)`

SetTransactionId sets TransactionId field to given value.

### HasTransactionId

`func (o *Invoice) HasTransactionId() bool`

HasTransactionId returns a boolean if a field has been set.

### GetPurchaseType

`func (o *Invoice) GetPurchaseType() string`

GetPurchaseType returns the PurchaseType field if non-nil, zero value otherwise.

### GetPurchaseTypeOk

`func (o *Invoice) GetPurchaseTypeOk() (*string, bool)`

GetPurchaseTypeOk returns a tuple with the PurchaseType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPurchaseType

`func (o *Invoice) SetPurchaseType(v string)`

SetPurchaseType sets PurchaseType field to given value.

### HasPurchaseType

`func (o *Invoice) HasPurchaseType() bool`

HasPurchaseType returns a boolean if a field has been set.

### GetAmountFiat

`func (o *Invoice) GetAmountFiat() float32`

GetAmountFiat returns the AmountFiat field if non-nil, zero value otherwise.

### GetAmountFiatOk

`func (o *Invoice) GetAmountFiatOk() (*float32, bool)`

GetAmountFiatOk returns a tuple with the AmountFiat field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmountFiat

`func (o *Invoice) SetAmountFiat(v float32)`

SetAmountFiat sets AmountFiat field to given value.

### HasAmountFiat

`func (o *Invoice) HasAmountFiat() bool`

HasAmountFiat returns a boolean if a field has been set.

### GetCurrencyFiat

`func (o *Invoice) GetCurrencyFiat() FiatCurrency`

GetCurrencyFiat returns the CurrencyFiat field if non-nil, zero value otherwise.

### GetCurrencyFiatOk

`func (o *Invoice) GetCurrencyFiatOk() (*FiatCurrency, bool)`

GetCurrencyFiatOk returns a tuple with the CurrencyFiat field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrencyFiat

`func (o *Invoice) SetCurrencyFiat(v FiatCurrency)`

SetCurrencyFiat sets CurrencyFiat field to given value.

### HasCurrencyFiat

`func (o *Invoice) HasCurrencyFiat() bool`

HasCurrencyFiat returns a boolean if a field has been set.

### GetStatus

`func (o *Invoice) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *Invoice) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *Invoice) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *Invoice) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetCryptoSymbol

`func (o *Invoice) GetCryptoSymbol() CryptoSymbol`

GetCryptoSymbol returns the CryptoSymbol field if non-nil, zero value otherwise.

### GetCryptoSymbolOk

`func (o *Invoice) GetCryptoSymbolOk() (*CryptoSymbol, bool)`

GetCryptoSymbolOk returns a tuple with the CryptoSymbol field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCryptoSymbol

`func (o *Invoice) SetCryptoSymbol(v CryptoSymbol)`

SetCryptoSymbol sets CryptoSymbol field to given value.

### HasCryptoSymbol

`func (o *Invoice) HasCryptoSymbol() bool`

HasCryptoSymbol returns a boolean if a field has been set.

### GetCreatedAt

`func (o *Invoice) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *Invoice) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *Invoice) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *Invoice) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetConfirmedAt

`func (o *Invoice) GetConfirmedAt() time.Time`

GetConfirmedAt returns the ConfirmedAt field if non-nil, zero value otherwise.

### GetConfirmedAtOk

`func (o *Invoice) GetConfirmedAtOk() (*time.Time, bool)`

GetConfirmedAtOk returns a tuple with the ConfirmedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfirmedAt

`func (o *Invoice) SetConfirmedAt(v time.Time)`

SetConfirmedAt sets ConfirmedAt field to given value.

### HasConfirmedAt

`func (o *Invoice) HasConfirmedAt() bool`

HasConfirmedAt returns a boolean if a field has been set.

### SetConfirmedAtNil

`func (o *Invoice) SetConfirmedAtNil(b bool)`

 SetConfirmedAtNil sets the value for ConfirmedAt to be an explicit nil

### UnsetConfirmedAt
`func (o *Invoice) UnsetConfirmedAt()`

UnsetConfirmedAt ensures that no value is present for ConfirmedAt, not even an explicit nil
### GetExpiresAt

`func (o *Invoice) GetExpiresAt() time.Time`

GetExpiresAt returns the ExpiresAt field if non-nil, zero value otherwise.

### GetExpiresAtOk

`func (o *Invoice) GetExpiresAtOk() (*time.Time, bool)`

GetExpiresAtOk returns a tuple with the ExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiresAt

`func (o *Invoice) SetExpiresAt(v time.Time)`

SetExpiresAt sets ExpiresAt field to given value.

### HasExpiresAt

`func (o *Invoice) HasExpiresAt() bool`

HasExpiresAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


