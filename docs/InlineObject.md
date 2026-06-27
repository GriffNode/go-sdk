# InlineObject

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | **interface{}** |  | 
**Error** | **string** | Machine-readable code. | 
**Message** | **string** | Human-readable description. | 
**ExistingTransaction** | Pointer to [**InlineObjectAllOfExistingTransaction**](InlineObjectAllOfExistingTransaction.md) |  | [optional] 

## Methods

### NewInlineObject

`func NewInlineObject(success interface{}, error_ string, message string, ) *InlineObject`

NewInlineObject instantiates a new InlineObject object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInlineObjectWithDefaults

`func NewInlineObjectWithDefaults() *InlineObject`

NewInlineObjectWithDefaults instantiates a new InlineObject object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *InlineObject) GetSuccess() interface{}`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *InlineObject) GetSuccessOk() (*interface{}, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *InlineObject) SetSuccess(v interface{})`

SetSuccess sets Success field to given value.


### SetSuccessNil

`func (o *InlineObject) SetSuccessNil(b bool)`

 SetSuccessNil sets the value for Success to be an explicit nil

### UnsetSuccess
`func (o *InlineObject) UnsetSuccess()`

UnsetSuccess ensures that no value is present for Success, not even an explicit nil
### GetError

`func (o *InlineObject) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *InlineObject) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *InlineObject) SetError(v string)`

SetError sets Error field to given value.


### GetMessage

`func (o *InlineObject) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *InlineObject) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *InlineObject) SetMessage(v string)`

SetMessage sets Message field to given value.


### GetExistingTransaction

`func (o *InlineObject) GetExistingTransaction() InlineObjectAllOfExistingTransaction`

GetExistingTransaction returns the ExistingTransaction field if non-nil, zero value otherwise.

### GetExistingTransactionOk

`func (o *InlineObject) GetExistingTransactionOk() (*InlineObjectAllOfExistingTransaction, bool)`

GetExistingTransactionOk returns a tuple with the ExistingTransaction field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExistingTransaction

`func (o *InlineObject) SetExistingTransaction(v InlineObjectAllOfExistingTransaction)`

SetExistingTransaction sets ExistingTransaction field to given value.

### HasExistingTransaction

`func (o *InlineObject) HasExistingTransaction() bool`

HasExistingTransaction returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


