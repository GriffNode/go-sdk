# GetPrices200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | **interface{}** |  | 
**Data** | [**GetPrices200ResponseData**](GetPrices200ResponseData.md) |  | 

## Methods

### NewGetPrices200Response

`func NewGetPrices200Response(success interface{}, data GetPrices200ResponseData, ) *GetPrices200Response`

NewGetPrices200Response instantiates a new GetPrices200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetPrices200ResponseWithDefaults

`func NewGetPrices200ResponseWithDefaults() *GetPrices200Response`

NewGetPrices200ResponseWithDefaults instantiates a new GetPrices200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *GetPrices200Response) GetSuccess() interface{}`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *GetPrices200Response) GetSuccessOk() (*interface{}, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *GetPrices200Response) SetSuccess(v interface{})`

SetSuccess sets Success field to given value.


### SetSuccessNil

`func (o *GetPrices200Response) SetSuccessNil(b bool)`

 SetSuccessNil sets the value for Success to be an explicit nil

### UnsetSuccess
`func (o *GetPrices200Response) UnsetSuccess()`

UnsetSuccess ensures that no value is present for Success, not even an explicit nil
### GetData

`func (o *GetPrices200Response) GetData() GetPrices200ResponseData`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *GetPrices200Response) GetDataOk() (*GetPrices200ResponseData, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *GetPrices200Response) SetData(v GetPrices200ResponseData)`

SetData sets Data field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


