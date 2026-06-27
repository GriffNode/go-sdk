# TransactionEnvelope

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | **interface{}** |  | 
**Data** | [**Transaction**](Transaction.md) |  | 

## Methods

### NewTransactionEnvelope

`func NewTransactionEnvelope(success interface{}, data Transaction, ) *TransactionEnvelope`

NewTransactionEnvelope instantiates a new TransactionEnvelope object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTransactionEnvelopeWithDefaults

`func NewTransactionEnvelopeWithDefaults() *TransactionEnvelope`

NewTransactionEnvelopeWithDefaults instantiates a new TransactionEnvelope object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *TransactionEnvelope) GetSuccess() interface{}`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *TransactionEnvelope) GetSuccessOk() (*interface{}, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *TransactionEnvelope) SetSuccess(v interface{})`

SetSuccess sets Success field to given value.


### SetSuccessNil

`func (o *TransactionEnvelope) SetSuccessNil(b bool)`

 SetSuccessNil sets the value for Success to be an explicit nil

### UnsetSuccess
`func (o *TransactionEnvelope) UnsetSuccess()`

UnsetSuccess ensures that no value is present for Success, not even an explicit nil
### GetData

`func (o *TransactionEnvelope) GetData() Transaction`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *TransactionEnvelope) GetDataOk() (*Transaction, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *TransactionEnvelope) SetData(v Transaction)`

SetData sets Data field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


