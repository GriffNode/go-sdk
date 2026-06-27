# GetStats200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | **interface{}** |  | 
**Data** | [**GetStats200ResponseData**](GetStats200ResponseData.md) |  | 

## Methods

### NewGetStats200Response

`func NewGetStats200Response(success interface{}, data GetStats200ResponseData, ) *GetStats200Response`

NewGetStats200Response instantiates a new GetStats200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetStats200ResponseWithDefaults

`func NewGetStats200ResponseWithDefaults() *GetStats200Response`

NewGetStats200ResponseWithDefaults instantiates a new GetStats200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *GetStats200Response) GetSuccess() interface{}`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *GetStats200Response) GetSuccessOk() (*interface{}, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *GetStats200Response) SetSuccess(v interface{})`

SetSuccess sets Success field to given value.


### SetSuccessNil

`func (o *GetStats200Response) SetSuccessNil(b bool)`

 SetSuccessNil sets the value for Success to be an explicit nil

### UnsetSuccess
`func (o *GetStats200Response) UnsetSuccess()`

UnsetSuccess ensures that no value is present for Success, not even an explicit nil
### GetData

`func (o *GetStats200Response) GetData() GetStats200ResponseData`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *GetStats200Response) GetDataOk() (*GetStats200ResponseData, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *GetStats200Response) SetData(v GetStats200ResponseData)`

SetData sets Data field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


