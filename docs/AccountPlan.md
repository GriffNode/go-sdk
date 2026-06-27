# AccountPlan

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Tier** | Pointer to [**PlanTier**](PlanTier.md) |  | [optional] 
**BillingCycle** | Pointer to **string** |  | [optional] 
**AutoRenewal** | Pointer to **bool** |  | [optional] 
**ExpiresAt** | Pointer to **NullableTime** |  | [optional] 

## Methods

### NewAccountPlan

`func NewAccountPlan() *AccountPlan`

NewAccountPlan instantiates a new AccountPlan object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAccountPlanWithDefaults

`func NewAccountPlanWithDefaults() *AccountPlan`

NewAccountPlanWithDefaults instantiates a new AccountPlan object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTier

`func (o *AccountPlan) GetTier() PlanTier`

GetTier returns the Tier field if non-nil, zero value otherwise.

### GetTierOk

`func (o *AccountPlan) GetTierOk() (*PlanTier, bool)`

GetTierOk returns a tuple with the Tier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTier

`func (o *AccountPlan) SetTier(v PlanTier)`

SetTier sets Tier field to given value.

### HasTier

`func (o *AccountPlan) HasTier() bool`

HasTier returns a boolean if a field has been set.

### GetBillingCycle

`func (o *AccountPlan) GetBillingCycle() string`

GetBillingCycle returns the BillingCycle field if non-nil, zero value otherwise.

### GetBillingCycleOk

`func (o *AccountPlan) GetBillingCycleOk() (*string, bool)`

GetBillingCycleOk returns a tuple with the BillingCycle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillingCycle

`func (o *AccountPlan) SetBillingCycle(v string)`

SetBillingCycle sets BillingCycle field to given value.

### HasBillingCycle

`func (o *AccountPlan) HasBillingCycle() bool`

HasBillingCycle returns a boolean if a field has been set.

### GetAutoRenewal

`func (o *AccountPlan) GetAutoRenewal() bool`

GetAutoRenewal returns the AutoRenewal field if non-nil, zero value otherwise.

### GetAutoRenewalOk

`func (o *AccountPlan) GetAutoRenewalOk() (*bool, bool)`

GetAutoRenewalOk returns a tuple with the AutoRenewal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAutoRenewal

`func (o *AccountPlan) SetAutoRenewal(v bool)`

SetAutoRenewal sets AutoRenewal field to given value.

### HasAutoRenewal

`func (o *AccountPlan) HasAutoRenewal() bool`

HasAutoRenewal returns a boolean if a field has been set.

### GetExpiresAt

`func (o *AccountPlan) GetExpiresAt() time.Time`

GetExpiresAt returns the ExpiresAt field if non-nil, zero value otherwise.

### GetExpiresAtOk

`func (o *AccountPlan) GetExpiresAtOk() (*time.Time, bool)`

GetExpiresAtOk returns a tuple with the ExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiresAt

`func (o *AccountPlan) SetExpiresAt(v time.Time)`

SetExpiresAt sets ExpiresAt field to given value.

### HasExpiresAt

`func (o *AccountPlan) HasExpiresAt() bool`

HasExpiresAt returns a boolean if a field has been set.

### SetExpiresAtNil

`func (o *AccountPlan) SetExpiresAtNil(b bool)`

 SetExpiresAtNil sets the value for ExpiresAt to be an explicit nil

### UnsetExpiresAt
`func (o *AccountPlan) UnsetExpiresAt()`

UnsetExpiresAt ensures that no value is present for ExpiresAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


