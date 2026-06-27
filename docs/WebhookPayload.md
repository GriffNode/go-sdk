# WebhookPayload

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Event** | **string** |  | 
**Timestamp** | **time.Time** |  | 
**TransactionId** | **string** |  | 
**Status** | [**TransactionStatus**](TransactionStatus.md) |  | 
**CurrencyCrypto** | Pointer to [**CryptoSymbol**](CryptoSymbol.md) |  | [optional] 
**CurrencyFiat** | Pointer to [**FiatCurrency**](FiatCurrency.md) |  | [optional] [default to FIATCURRENCY_USD]
**AmountFiat** | Pointer to **string** | Decimal string. | [optional] 
**AmountUsd** | Pointer to **string** | Decimal string. | [optional] 
**AmountCrypto** | Pointer to **string** | Decimal string. | [optional] 
**OrderId** | Pointer to **NullableString** |  | [optional] 
**ReceiptUrl** | Pointer to **NullableString** | Present on completed/overpaid. | [optional] 
**Metadata** | Pointer to **map[string]string** | Free-form key/value (≤20 keys, string values ≤500 chars, ≤4 KB total). | [optional] 

## Methods

### NewWebhookPayload

`func NewWebhookPayload(event string, timestamp time.Time, transactionId string, status TransactionStatus, ) *WebhookPayload`

NewWebhookPayload instantiates a new WebhookPayload object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWebhookPayloadWithDefaults

`func NewWebhookPayloadWithDefaults() *WebhookPayload`

NewWebhookPayloadWithDefaults instantiates a new WebhookPayload object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEvent

`func (o *WebhookPayload) GetEvent() string`

GetEvent returns the Event field if non-nil, zero value otherwise.

### GetEventOk

`func (o *WebhookPayload) GetEventOk() (*string, bool)`

GetEventOk returns a tuple with the Event field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEvent

`func (o *WebhookPayload) SetEvent(v string)`

SetEvent sets Event field to given value.


### GetTimestamp

`func (o *WebhookPayload) GetTimestamp() time.Time`

GetTimestamp returns the Timestamp field if non-nil, zero value otherwise.

### GetTimestampOk

`func (o *WebhookPayload) GetTimestampOk() (*time.Time, bool)`

GetTimestampOk returns a tuple with the Timestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimestamp

`func (o *WebhookPayload) SetTimestamp(v time.Time)`

SetTimestamp sets Timestamp field to given value.


### GetTransactionId

`func (o *WebhookPayload) GetTransactionId() string`

GetTransactionId returns the TransactionId field if non-nil, zero value otherwise.

### GetTransactionIdOk

`func (o *WebhookPayload) GetTransactionIdOk() (*string, bool)`

GetTransactionIdOk returns a tuple with the TransactionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransactionId

`func (o *WebhookPayload) SetTransactionId(v string)`

SetTransactionId sets TransactionId field to given value.


### GetStatus

`func (o *WebhookPayload) GetStatus() TransactionStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *WebhookPayload) GetStatusOk() (*TransactionStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *WebhookPayload) SetStatus(v TransactionStatus)`

SetStatus sets Status field to given value.


### GetCurrencyCrypto

`func (o *WebhookPayload) GetCurrencyCrypto() CryptoSymbol`

GetCurrencyCrypto returns the CurrencyCrypto field if non-nil, zero value otherwise.

### GetCurrencyCryptoOk

`func (o *WebhookPayload) GetCurrencyCryptoOk() (*CryptoSymbol, bool)`

GetCurrencyCryptoOk returns a tuple with the CurrencyCrypto field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrencyCrypto

`func (o *WebhookPayload) SetCurrencyCrypto(v CryptoSymbol)`

SetCurrencyCrypto sets CurrencyCrypto field to given value.

### HasCurrencyCrypto

`func (o *WebhookPayload) HasCurrencyCrypto() bool`

HasCurrencyCrypto returns a boolean if a field has been set.

### GetCurrencyFiat

`func (o *WebhookPayload) GetCurrencyFiat() FiatCurrency`

GetCurrencyFiat returns the CurrencyFiat field if non-nil, zero value otherwise.

### GetCurrencyFiatOk

`func (o *WebhookPayload) GetCurrencyFiatOk() (*FiatCurrency, bool)`

GetCurrencyFiatOk returns a tuple with the CurrencyFiat field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrencyFiat

`func (o *WebhookPayload) SetCurrencyFiat(v FiatCurrency)`

SetCurrencyFiat sets CurrencyFiat field to given value.

### HasCurrencyFiat

`func (o *WebhookPayload) HasCurrencyFiat() bool`

HasCurrencyFiat returns a boolean if a field has been set.

### GetAmountFiat

`func (o *WebhookPayload) GetAmountFiat() string`

GetAmountFiat returns the AmountFiat field if non-nil, zero value otherwise.

### GetAmountFiatOk

`func (o *WebhookPayload) GetAmountFiatOk() (*string, bool)`

GetAmountFiatOk returns a tuple with the AmountFiat field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmountFiat

`func (o *WebhookPayload) SetAmountFiat(v string)`

SetAmountFiat sets AmountFiat field to given value.

### HasAmountFiat

`func (o *WebhookPayload) HasAmountFiat() bool`

HasAmountFiat returns a boolean if a field has been set.

### GetAmountUsd

`func (o *WebhookPayload) GetAmountUsd() string`

GetAmountUsd returns the AmountUsd field if non-nil, zero value otherwise.

### GetAmountUsdOk

`func (o *WebhookPayload) GetAmountUsdOk() (*string, bool)`

GetAmountUsdOk returns a tuple with the AmountUsd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmountUsd

`func (o *WebhookPayload) SetAmountUsd(v string)`

SetAmountUsd sets AmountUsd field to given value.

### HasAmountUsd

`func (o *WebhookPayload) HasAmountUsd() bool`

HasAmountUsd returns a boolean if a field has been set.

### GetAmountCrypto

`func (o *WebhookPayload) GetAmountCrypto() string`

GetAmountCrypto returns the AmountCrypto field if non-nil, zero value otherwise.

### GetAmountCryptoOk

`func (o *WebhookPayload) GetAmountCryptoOk() (*string, bool)`

GetAmountCryptoOk returns a tuple with the AmountCrypto field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmountCrypto

`func (o *WebhookPayload) SetAmountCrypto(v string)`

SetAmountCrypto sets AmountCrypto field to given value.

### HasAmountCrypto

`func (o *WebhookPayload) HasAmountCrypto() bool`

HasAmountCrypto returns a boolean if a field has been set.

### GetOrderId

`func (o *WebhookPayload) GetOrderId() string`

GetOrderId returns the OrderId field if non-nil, zero value otherwise.

### GetOrderIdOk

`func (o *WebhookPayload) GetOrderIdOk() (*string, bool)`

GetOrderIdOk returns a tuple with the OrderId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderId

`func (o *WebhookPayload) SetOrderId(v string)`

SetOrderId sets OrderId field to given value.

### HasOrderId

`func (o *WebhookPayload) HasOrderId() bool`

HasOrderId returns a boolean if a field has been set.

### SetOrderIdNil

`func (o *WebhookPayload) SetOrderIdNil(b bool)`

 SetOrderIdNil sets the value for OrderId to be an explicit nil

### UnsetOrderId
`func (o *WebhookPayload) UnsetOrderId()`

UnsetOrderId ensures that no value is present for OrderId, not even an explicit nil
### GetReceiptUrl

`func (o *WebhookPayload) GetReceiptUrl() string`

GetReceiptUrl returns the ReceiptUrl field if non-nil, zero value otherwise.

### GetReceiptUrlOk

`func (o *WebhookPayload) GetReceiptUrlOk() (*string, bool)`

GetReceiptUrlOk returns a tuple with the ReceiptUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReceiptUrl

`func (o *WebhookPayload) SetReceiptUrl(v string)`

SetReceiptUrl sets ReceiptUrl field to given value.

### HasReceiptUrl

`func (o *WebhookPayload) HasReceiptUrl() bool`

HasReceiptUrl returns a boolean if a field has been set.

### SetReceiptUrlNil

`func (o *WebhookPayload) SetReceiptUrlNil(b bool)`

 SetReceiptUrlNil sets the value for ReceiptUrl to be an explicit nil

### UnsetReceiptUrl
`func (o *WebhookPayload) UnsetReceiptUrl()`

UnsetReceiptUrl ensures that no value is present for ReceiptUrl, not even an explicit nil
### GetMetadata

`func (o *WebhookPayload) GetMetadata() map[string]string`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *WebhookPayload) GetMetadataOk() (*map[string]string, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *WebhookPayload) SetMetadata(v map[string]string)`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *WebhookPayload) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


