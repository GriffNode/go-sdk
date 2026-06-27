# ListPlans200ResponseData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Plans** | Pointer to [**[]Plan**](Plan.md) |  | [optional] 
**BillingCycles** | Pointer to **[]string** |  | [optional] 

## Methods

### NewListPlans200ResponseData

`func NewListPlans200ResponseData() *ListPlans200ResponseData`

NewListPlans200ResponseData instantiates a new ListPlans200ResponseData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewListPlans200ResponseDataWithDefaults

`func NewListPlans200ResponseDataWithDefaults() *ListPlans200ResponseData`

NewListPlans200ResponseDataWithDefaults instantiates a new ListPlans200ResponseData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPlans

`func (o *ListPlans200ResponseData) GetPlans() []Plan`

GetPlans returns the Plans field if non-nil, zero value otherwise.

### GetPlansOk

`func (o *ListPlans200ResponseData) GetPlansOk() (*[]Plan, bool)`

GetPlansOk returns a tuple with the Plans field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlans

`func (o *ListPlans200ResponseData) SetPlans(v []Plan)`

SetPlans sets Plans field to given value.

### HasPlans

`func (o *ListPlans200ResponseData) HasPlans() bool`

HasPlans returns a boolean if a field has been set.

### GetBillingCycles

`func (o *ListPlans200ResponseData) GetBillingCycles() []string`

GetBillingCycles returns the BillingCycles field if non-nil, zero value otherwise.

### GetBillingCyclesOk

`func (o *ListPlans200ResponseData) GetBillingCyclesOk() (*[]string, bool)`

GetBillingCyclesOk returns a tuple with the BillingCycles field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillingCycles

`func (o *ListPlans200ResponseData) SetBillingCycles(v []string)`

SetBillingCycles sets BillingCycles field to given value.

### HasBillingCycles

`func (o *ListPlans200ResponseData) HasBillingCycles() bool`

HasBillingCycles returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


