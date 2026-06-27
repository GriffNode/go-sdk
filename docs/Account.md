# Account

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Plan** | Pointer to [**AccountPlan**](AccountPlan.md) |  | [optional] 
**Usage** | Pointer to [**AccountUsage**](AccountUsage.md) |  | [optional] 
**Limits** | Pointer to [**AccountLimits**](AccountLimits.md) |  | [optional] 

## Methods

### NewAccount

`func NewAccount() *Account`

NewAccount instantiates a new Account object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAccountWithDefaults

`func NewAccountWithDefaults() *Account`

NewAccountWithDefaults instantiates a new Account object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPlan

`func (o *Account) GetPlan() AccountPlan`

GetPlan returns the Plan field if non-nil, zero value otherwise.

### GetPlanOk

`func (o *Account) GetPlanOk() (*AccountPlan, bool)`

GetPlanOk returns a tuple with the Plan field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlan

`func (o *Account) SetPlan(v AccountPlan)`

SetPlan sets Plan field to given value.

### HasPlan

`func (o *Account) HasPlan() bool`

HasPlan returns a boolean if a field has been set.

### GetUsage

`func (o *Account) GetUsage() AccountUsage`

GetUsage returns the Usage field if non-nil, zero value otherwise.

### GetUsageOk

`func (o *Account) GetUsageOk() (*AccountUsage, bool)`

GetUsageOk returns a tuple with the Usage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsage

`func (o *Account) SetUsage(v AccountUsage)`

SetUsage sets Usage field to given value.

### HasUsage

`func (o *Account) HasUsage() bool`

HasUsage returns a boolean if a field has been set.

### GetLimits

`func (o *Account) GetLimits() AccountLimits`

GetLimits returns the Limits field if non-nil, zero value otherwise.

### GetLimitsOk

`func (o *Account) GetLimitsOk() (*AccountLimits, bool)`

GetLimitsOk returns a tuple with the Limits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimits

`func (o *Account) SetLimits(v AccountLimits)`

SetLimits sets Limits field to given value.

### HasLimits

`func (o *Account) HasLimits() bool`

HasLimits returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


