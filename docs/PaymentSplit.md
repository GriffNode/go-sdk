# PaymentSplit

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Txid** | Pointer to **string** | On-chain transaction hash (blockchain id, NOT the CryptoGate transaction_id). | [optional] 
**AmountCrypto** | Pointer to **float32** |  | [optional] 
**Confirmations** | Pointer to **int32** |  | [optional] 
**Status** | Pointer to **string** |  | [optional] 
**DetectedAt** | Pointer to **time.Time** |  | [optional] 
**ConfirmedAt** | Pointer to **NullableTime** |  | [optional] 

## Methods

### NewPaymentSplit

`func NewPaymentSplit() *PaymentSplit`

NewPaymentSplit instantiates a new PaymentSplit object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPaymentSplitWithDefaults

`func NewPaymentSplitWithDefaults() *PaymentSplit`

NewPaymentSplitWithDefaults instantiates a new PaymentSplit object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTxid

`func (o *PaymentSplit) GetTxid() string`

GetTxid returns the Txid field if non-nil, zero value otherwise.

### GetTxidOk

`func (o *PaymentSplit) GetTxidOk() (*string, bool)`

GetTxidOk returns a tuple with the Txid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTxid

`func (o *PaymentSplit) SetTxid(v string)`

SetTxid sets Txid field to given value.

### HasTxid

`func (o *PaymentSplit) HasTxid() bool`

HasTxid returns a boolean if a field has been set.

### GetAmountCrypto

`func (o *PaymentSplit) GetAmountCrypto() float32`

GetAmountCrypto returns the AmountCrypto field if non-nil, zero value otherwise.

### GetAmountCryptoOk

`func (o *PaymentSplit) GetAmountCryptoOk() (*float32, bool)`

GetAmountCryptoOk returns a tuple with the AmountCrypto field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmountCrypto

`func (o *PaymentSplit) SetAmountCrypto(v float32)`

SetAmountCrypto sets AmountCrypto field to given value.

### HasAmountCrypto

`func (o *PaymentSplit) HasAmountCrypto() bool`

HasAmountCrypto returns a boolean if a field has been set.

### GetConfirmations

`func (o *PaymentSplit) GetConfirmations() int32`

GetConfirmations returns the Confirmations field if non-nil, zero value otherwise.

### GetConfirmationsOk

`func (o *PaymentSplit) GetConfirmationsOk() (*int32, bool)`

GetConfirmationsOk returns a tuple with the Confirmations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfirmations

`func (o *PaymentSplit) SetConfirmations(v int32)`

SetConfirmations sets Confirmations field to given value.

### HasConfirmations

`func (o *PaymentSplit) HasConfirmations() bool`

HasConfirmations returns a boolean if a field has been set.

### GetStatus

`func (o *PaymentSplit) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *PaymentSplit) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *PaymentSplit) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *PaymentSplit) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetDetectedAt

`func (o *PaymentSplit) GetDetectedAt() time.Time`

GetDetectedAt returns the DetectedAt field if non-nil, zero value otherwise.

### GetDetectedAtOk

`func (o *PaymentSplit) GetDetectedAtOk() (*time.Time, bool)`

GetDetectedAtOk returns a tuple with the DetectedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetectedAt

`func (o *PaymentSplit) SetDetectedAt(v time.Time)`

SetDetectedAt sets DetectedAt field to given value.

### HasDetectedAt

`func (o *PaymentSplit) HasDetectedAt() bool`

HasDetectedAt returns a boolean if a field has been set.

### GetConfirmedAt

`func (o *PaymentSplit) GetConfirmedAt() time.Time`

GetConfirmedAt returns the ConfirmedAt field if non-nil, zero value otherwise.

### GetConfirmedAtOk

`func (o *PaymentSplit) GetConfirmedAtOk() (*time.Time, bool)`

GetConfirmedAtOk returns a tuple with the ConfirmedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfirmedAt

`func (o *PaymentSplit) SetConfirmedAt(v time.Time)`

SetConfirmedAt sets ConfirmedAt field to given value.

### HasConfirmedAt

`func (o *PaymentSplit) HasConfirmedAt() bool`

HasConfirmedAt returns a boolean if a field has been set.

### SetConfirmedAtNil

`func (o *PaymentSplit) SetConfirmedAtNil(b bool)`

 SetConfirmedAtNil sets the value for ConfirmedAt to be an explicit nil

### UnsetConfirmedAt
`func (o *PaymentSplit) UnsetConfirmedAt()`

UnsetConfirmedAt ensures that no value is present for ConfirmedAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


