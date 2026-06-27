# Transaction

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**TransactionId** | **string** |  | 
**Status** | [**TransactionStatus**](TransactionStatus.md) |  | 
**Type** | Pointer to **string** |  | [optional] 
**Crypto** | [**CryptoSymbol**](CryptoSymbol.md) |  | 
**DepositAddress** | Pointer to **string** |  | [optional] 
**AmountCrypto** | Pointer to **float32** |  | [optional] 
**AmountFiat** | **float32** |  | 
**AmountUsd** | **float32** |  | 
**AmountPaid** | Pointer to **float32** |  | [optional] 
**AmountRemaining** | Pointer to **float32** |  | [optional] 
**CurrencyFiat** | [**FiatCurrency**](FiatCurrency.md) |  | [default to FIATCURRENCY_USD]
**FiatToUsdRate** | Pointer to **float32** |  | [optional] 
**ExchangeRate** | Pointer to **float32** | USD per unit of crypto, locked at creation. | [optional] 
**ConfirmationsRequired** | Pointer to **int32** |  | [optional] 
**PaymentUrl** | Pointer to **string** |  | [optional] 
**OrderId** | Pointer to **NullableString** |  | [optional] 
**CustomerEmail** | Pointer to **NullableString** |  | [optional] 
**Items** | Pointer to [**[]LineItem**](LineItem.md) |  | [optional] 
**Payments** | Pointer to [**[]PaymentSplit**](PaymentSplit.md) | On-chain payments detected toward this transaction. | [optional] 
**Metadata** | Pointer to **map[string]string** | Free-form key/value (≤20 keys, string values ≤500 chars, ≤4 KB total). | [optional] 
**SuccessUrl** | Pointer to **NullableString** |  | [optional] 
**CancelUrl** | Pointer to **NullableString** |  | [optional] 
**CreatedAt** | **time.Time** |  | 
**UpdatedAt** | Pointer to **time.Time** |  | [optional] 
**ExpiresAt** | **time.Time** |  | 

## Methods

### NewTransaction

`func NewTransaction(transactionId string, status TransactionStatus, crypto CryptoSymbol, amountFiat float32, amountUsd float32, currencyFiat FiatCurrency, createdAt time.Time, expiresAt time.Time, ) *Transaction`

NewTransaction instantiates a new Transaction object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTransactionWithDefaults

`func NewTransactionWithDefaults() *Transaction`

NewTransactionWithDefaults instantiates a new Transaction object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTransactionId

`func (o *Transaction) GetTransactionId() string`

GetTransactionId returns the TransactionId field if non-nil, zero value otherwise.

### GetTransactionIdOk

`func (o *Transaction) GetTransactionIdOk() (*string, bool)`

GetTransactionIdOk returns a tuple with the TransactionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransactionId

`func (o *Transaction) SetTransactionId(v string)`

SetTransactionId sets TransactionId field to given value.


### GetStatus

`func (o *Transaction) GetStatus() TransactionStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *Transaction) GetStatusOk() (*TransactionStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *Transaction) SetStatus(v TransactionStatus)`

SetStatus sets Status field to given value.


### GetType

`func (o *Transaction) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *Transaction) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *Transaction) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *Transaction) HasType() bool`

HasType returns a boolean if a field has been set.

### GetCrypto

`func (o *Transaction) GetCrypto() CryptoSymbol`

GetCrypto returns the Crypto field if non-nil, zero value otherwise.

### GetCryptoOk

`func (o *Transaction) GetCryptoOk() (*CryptoSymbol, bool)`

GetCryptoOk returns a tuple with the Crypto field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCrypto

`func (o *Transaction) SetCrypto(v CryptoSymbol)`

SetCrypto sets Crypto field to given value.


### GetDepositAddress

`func (o *Transaction) GetDepositAddress() string`

GetDepositAddress returns the DepositAddress field if non-nil, zero value otherwise.

### GetDepositAddressOk

`func (o *Transaction) GetDepositAddressOk() (*string, bool)`

GetDepositAddressOk returns a tuple with the DepositAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDepositAddress

`func (o *Transaction) SetDepositAddress(v string)`

SetDepositAddress sets DepositAddress field to given value.

### HasDepositAddress

`func (o *Transaction) HasDepositAddress() bool`

HasDepositAddress returns a boolean if a field has been set.

### GetAmountCrypto

`func (o *Transaction) GetAmountCrypto() float32`

GetAmountCrypto returns the AmountCrypto field if non-nil, zero value otherwise.

### GetAmountCryptoOk

`func (o *Transaction) GetAmountCryptoOk() (*float32, bool)`

GetAmountCryptoOk returns a tuple with the AmountCrypto field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmountCrypto

`func (o *Transaction) SetAmountCrypto(v float32)`

SetAmountCrypto sets AmountCrypto field to given value.

### HasAmountCrypto

`func (o *Transaction) HasAmountCrypto() bool`

HasAmountCrypto returns a boolean if a field has been set.

### GetAmountFiat

`func (o *Transaction) GetAmountFiat() float32`

GetAmountFiat returns the AmountFiat field if non-nil, zero value otherwise.

### GetAmountFiatOk

`func (o *Transaction) GetAmountFiatOk() (*float32, bool)`

GetAmountFiatOk returns a tuple with the AmountFiat field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmountFiat

`func (o *Transaction) SetAmountFiat(v float32)`

SetAmountFiat sets AmountFiat field to given value.


### GetAmountUsd

`func (o *Transaction) GetAmountUsd() float32`

GetAmountUsd returns the AmountUsd field if non-nil, zero value otherwise.

### GetAmountUsdOk

`func (o *Transaction) GetAmountUsdOk() (*float32, bool)`

GetAmountUsdOk returns a tuple with the AmountUsd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmountUsd

`func (o *Transaction) SetAmountUsd(v float32)`

SetAmountUsd sets AmountUsd field to given value.


### GetAmountPaid

`func (o *Transaction) GetAmountPaid() float32`

GetAmountPaid returns the AmountPaid field if non-nil, zero value otherwise.

### GetAmountPaidOk

`func (o *Transaction) GetAmountPaidOk() (*float32, bool)`

GetAmountPaidOk returns a tuple with the AmountPaid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmountPaid

`func (o *Transaction) SetAmountPaid(v float32)`

SetAmountPaid sets AmountPaid field to given value.

### HasAmountPaid

`func (o *Transaction) HasAmountPaid() bool`

HasAmountPaid returns a boolean if a field has been set.

### GetAmountRemaining

`func (o *Transaction) GetAmountRemaining() float32`

GetAmountRemaining returns the AmountRemaining field if non-nil, zero value otherwise.

### GetAmountRemainingOk

`func (o *Transaction) GetAmountRemainingOk() (*float32, bool)`

GetAmountRemainingOk returns a tuple with the AmountRemaining field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmountRemaining

`func (o *Transaction) SetAmountRemaining(v float32)`

SetAmountRemaining sets AmountRemaining field to given value.

### HasAmountRemaining

`func (o *Transaction) HasAmountRemaining() bool`

HasAmountRemaining returns a boolean if a field has been set.

### GetCurrencyFiat

`func (o *Transaction) GetCurrencyFiat() FiatCurrency`

GetCurrencyFiat returns the CurrencyFiat field if non-nil, zero value otherwise.

### GetCurrencyFiatOk

`func (o *Transaction) GetCurrencyFiatOk() (*FiatCurrency, bool)`

GetCurrencyFiatOk returns a tuple with the CurrencyFiat field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrencyFiat

`func (o *Transaction) SetCurrencyFiat(v FiatCurrency)`

SetCurrencyFiat sets CurrencyFiat field to given value.


### GetFiatToUsdRate

`func (o *Transaction) GetFiatToUsdRate() float32`

GetFiatToUsdRate returns the FiatToUsdRate field if non-nil, zero value otherwise.

### GetFiatToUsdRateOk

`func (o *Transaction) GetFiatToUsdRateOk() (*float32, bool)`

GetFiatToUsdRateOk returns a tuple with the FiatToUsdRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFiatToUsdRate

`func (o *Transaction) SetFiatToUsdRate(v float32)`

SetFiatToUsdRate sets FiatToUsdRate field to given value.

### HasFiatToUsdRate

`func (o *Transaction) HasFiatToUsdRate() bool`

HasFiatToUsdRate returns a boolean if a field has been set.

### GetExchangeRate

`func (o *Transaction) GetExchangeRate() float32`

GetExchangeRate returns the ExchangeRate field if non-nil, zero value otherwise.

### GetExchangeRateOk

`func (o *Transaction) GetExchangeRateOk() (*float32, bool)`

GetExchangeRateOk returns a tuple with the ExchangeRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExchangeRate

`func (o *Transaction) SetExchangeRate(v float32)`

SetExchangeRate sets ExchangeRate field to given value.

### HasExchangeRate

`func (o *Transaction) HasExchangeRate() bool`

HasExchangeRate returns a boolean if a field has been set.

### GetConfirmationsRequired

`func (o *Transaction) GetConfirmationsRequired() int32`

GetConfirmationsRequired returns the ConfirmationsRequired field if non-nil, zero value otherwise.

### GetConfirmationsRequiredOk

`func (o *Transaction) GetConfirmationsRequiredOk() (*int32, bool)`

GetConfirmationsRequiredOk returns a tuple with the ConfirmationsRequired field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfirmationsRequired

`func (o *Transaction) SetConfirmationsRequired(v int32)`

SetConfirmationsRequired sets ConfirmationsRequired field to given value.

### HasConfirmationsRequired

`func (o *Transaction) HasConfirmationsRequired() bool`

HasConfirmationsRequired returns a boolean if a field has been set.

### GetPaymentUrl

`func (o *Transaction) GetPaymentUrl() string`

GetPaymentUrl returns the PaymentUrl field if non-nil, zero value otherwise.

### GetPaymentUrlOk

`func (o *Transaction) GetPaymentUrlOk() (*string, bool)`

GetPaymentUrlOk returns a tuple with the PaymentUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentUrl

`func (o *Transaction) SetPaymentUrl(v string)`

SetPaymentUrl sets PaymentUrl field to given value.

### HasPaymentUrl

`func (o *Transaction) HasPaymentUrl() bool`

HasPaymentUrl returns a boolean if a field has been set.

### GetOrderId

`func (o *Transaction) GetOrderId() string`

GetOrderId returns the OrderId field if non-nil, zero value otherwise.

### GetOrderIdOk

`func (o *Transaction) GetOrderIdOk() (*string, bool)`

GetOrderIdOk returns a tuple with the OrderId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderId

`func (o *Transaction) SetOrderId(v string)`

SetOrderId sets OrderId field to given value.

### HasOrderId

`func (o *Transaction) HasOrderId() bool`

HasOrderId returns a boolean if a field has been set.

### SetOrderIdNil

`func (o *Transaction) SetOrderIdNil(b bool)`

 SetOrderIdNil sets the value for OrderId to be an explicit nil

### UnsetOrderId
`func (o *Transaction) UnsetOrderId()`

UnsetOrderId ensures that no value is present for OrderId, not even an explicit nil
### GetCustomerEmail

`func (o *Transaction) GetCustomerEmail() string`

GetCustomerEmail returns the CustomerEmail field if non-nil, zero value otherwise.

### GetCustomerEmailOk

`func (o *Transaction) GetCustomerEmailOk() (*string, bool)`

GetCustomerEmailOk returns a tuple with the CustomerEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerEmail

`func (o *Transaction) SetCustomerEmail(v string)`

SetCustomerEmail sets CustomerEmail field to given value.

### HasCustomerEmail

`func (o *Transaction) HasCustomerEmail() bool`

HasCustomerEmail returns a boolean if a field has been set.

### SetCustomerEmailNil

`func (o *Transaction) SetCustomerEmailNil(b bool)`

 SetCustomerEmailNil sets the value for CustomerEmail to be an explicit nil

### UnsetCustomerEmail
`func (o *Transaction) UnsetCustomerEmail()`

UnsetCustomerEmail ensures that no value is present for CustomerEmail, not even an explicit nil
### GetItems

`func (o *Transaction) GetItems() []LineItem`

GetItems returns the Items field if non-nil, zero value otherwise.

### GetItemsOk

`func (o *Transaction) GetItemsOk() (*[]LineItem, bool)`

GetItemsOk returns a tuple with the Items field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItems

`func (o *Transaction) SetItems(v []LineItem)`

SetItems sets Items field to given value.

### HasItems

`func (o *Transaction) HasItems() bool`

HasItems returns a boolean if a field has been set.

### SetItemsNil

`func (o *Transaction) SetItemsNil(b bool)`

 SetItemsNil sets the value for Items to be an explicit nil

### UnsetItems
`func (o *Transaction) UnsetItems()`

UnsetItems ensures that no value is present for Items, not even an explicit nil
### GetPayments

`func (o *Transaction) GetPayments() []PaymentSplit`

GetPayments returns the Payments field if non-nil, zero value otherwise.

### GetPaymentsOk

`func (o *Transaction) GetPaymentsOk() (*[]PaymentSplit, bool)`

GetPaymentsOk returns a tuple with the Payments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPayments

`func (o *Transaction) SetPayments(v []PaymentSplit)`

SetPayments sets Payments field to given value.

### HasPayments

`func (o *Transaction) HasPayments() bool`

HasPayments returns a boolean if a field has been set.

### GetMetadata

`func (o *Transaction) GetMetadata() map[string]string`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *Transaction) GetMetadataOk() (*map[string]string, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *Transaction) SetMetadata(v map[string]string)`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *Transaction) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.

### GetSuccessUrl

`func (o *Transaction) GetSuccessUrl() string`

GetSuccessUrl returns the SuccessUrl field if non-nil, zero value otherwise.

### GetSuccessUrlOk

`func (o *Transaction) GetSuccessUrlOk() (*string, bool)`

GetSuccessUrlOk returns a tuple with the SuccessUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccessUrl

`func (o *Transaction) SetSuccessUrl(v string)`

SetSuccessUrl sets SuccessUrl field to given value.

### HasSuccessUrl

`func (o *Transaction) HasSuccessUrl() bool`

HasSuccessUrl returns a boolean if a field has been set.

### SetSuccessUrlNil

`func (o *Transaction) SetSuccessUrlNil(b bool)`

 SetSuccessUrlNil sets the value for SuccessUrl to be an explicit nil

### UnsetSuccessUrl
`func (o *Transaction) UnsetSuccessUrl()`

UnsetSuccessUrl ensures that no value is present for SuccessUrl, not even an explicit nil
### GetCancelUrl

`func (o *Transaction) GetCancelUrl() string`

GetCancelUrl returns the CancelUrl field if non-nil, zero value otherwise.

### GetCancelUrlOk

`func (o *Transaction) GetCancelUrlOk() (*string, bool)`

GetCancelUrlOk returns a tuple with the CancelUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCancelUrl

`func (o *Transaction) SetCancelUrl(v string)`

SetCancelUrl sets CancelUrl field to given value.

### HasCancelUrl

`func (o *Transaction) HasCancelUrl() bool`

HasCancelUrl returns a boolean if a field has been set.

### SetCancelUrlNil

`func (o *Transaction) SetCancelUrlNil(b bool)`

 SetCancelUrlNil sets the value for CancelUrl to be an explicit nil

### UnsetCancelUrl
`func (o *Transaction) UnsetCancelUrl()`

UnsetCancelUrl ensures that no value is present for CancelUrl, not even an explicit nil
### GetCreatedAt

`func (o *Transaction) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *Transaction) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *Transaction) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *Transaction) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *Transaction) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *Transaction) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *Transaction) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### GetExpiresAt

`func (o *Transaction) GetExpiresAt() time.Time`

GetExpiresAt returns the ExpiresAt field if non-nil, zero value otherwise.

### GetExpiresAtOk

`func (o *Transaction) GetExpiresAtOk() (*time.Time, bool)`

GetExpiresAtOk returns a tuple with the ExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiresAt

`func (o *Transaction) SetExpiresAt(v time.Time)`

SetExpiresAt sets ExpiresAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


