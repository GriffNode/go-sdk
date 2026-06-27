# ListTransactions200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | **interface{}** |  | 
**Data** | [**ListTransactions200ResponseData**](ListTransactions200ResponseData.md) |  | 

## Methods

### NewListTransactions200Response

`func NewListTransactions200Response(success interface{}, data ListTransactions200ResponseData, ) *ListTransactions200Response`

NewListTransactions200Response instantiates a new ListTransactions200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewListTransactions200ResponseWithDefaults

`func NewListTransactions200ResponseWithDefaults() *ListTransactions200Response`

NewListTransactions200ResponseWithDefaults instantiates a new ListTransactions200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *ListTransactions200Response) GetSuccess() interface{}`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *ListTransactions200Response) GetSuccessOk() (*interface{}, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *ListTransactions200Response) SetSuccess(v interface{})`

SetSuccess sets Success field to given value.


### SetSuccessNil

`func (o *ListTransactions200Response) SetSuccessNil(b bool)`

 SetSuccessNil sets the value for Success to be an explicit nil

### UnsetSuccess
`func (o *ListTransactions200Response) UnsetSuccess()`

UnsetSuccess ensures that no value is present for Success, not even an explicit nil
### GetData

`func (o *ListTransactions200Response) GetData() ListTransactions200ResponseData`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *ListTransactions200Response) GetDataOk() (*ListTransactions200ResponseData, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *ListTransactions200Response) SetData(v ListTransactions200ResponseData)`

SetData sets Data field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


