# CreateBillingCheckoutRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Tier** | [**PlanTier**](PlanTier.md) |  | 
**BillingMonths** | Pointer to **int32** |  | [optional] [default to 1]
**PaymentMethod** | Pointer to **string** |  | [optional] [default to "crypto"]

## Methods

### NewCreateBillingCheckoutRequest

`func NewCreateBillingCheckoutRequest(tier PlanTier, ) *CreateBillingCheckoutRequest`

NewCreateBillingCheckoutRequest instantiates a new CreateBillingCheckoutRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateBillingCheckoutRequestWithDefaults

`func NewCreateBillingCheckoutRequestWithDefaults() *CreateBillingCheckoutRequest`

NewCreateBillingCheckoutRequestWithDefaults instantiates a new CreateBillingCheckoutRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTier

`func (o *CreateBillingCheckoutRequest) GetTier() PlanTier`

GetTier returns the Tier field if non-nil, zero value otherwise.

### GetTierOk

`func (o *CreateBillingCheckoutRequest) GetTierOk() (*PlanTier, bool)`

GetTierOk returns a tuple with the Tier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTier

`func (o *CreateBillingCheckoutRequest) SetTier(v PlanTier)`

SetTier sets Tier field to given value.


### GetBillingMonths

`func (o *CreateBillingCheckoutRequest) GetBillingMonths() int32`

GetBillingMonths returns the BillingMonths field if non-nil, zero value otherwise.

### GetBillingMonthsOk

`func (o *CreateBillingCheckoutRequest) GetBillingMonthsOk() (*int32, bool)`

GetBillingMonthsOk returns a tuple with the BillingMonths field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillingMonths

`func (o *CreateBillingCheckoutRequest) SetBillingMonths(v int32)`

SetBillingMonths sets BillingMonths field to given value.

### HasBillingMonths

`func (o *CreateBillingCheckoutRequest) HasBillingMonths() bool`

HasBillingMonths returns a boolean if a field has been set.

### GetPaymentMethod

`func (o *CreateBillingCheckoutRequest) GetPaymentMethod() string`

GetPaymentMethod returns the PaymentMethod field if non-nil, zero value otherwise.

### GetPaymentMethodOk

`func (o *CreateBillingCheckoutRequest) GetPaymentMethodOk() (*string, bool)`

GetPaymentMethodOk returns a tuple with the PaymentMethod field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentMethod

`func (o *CreateBillingCheckoutRequest) SetPaymentMethod(v string)`

SetPaymentMethod sets PaymentMethod field to given value.

### HasPaymentMethod

`func (o *CreateBillingCheckoutRequest) HasPaymentMethod() bool`

HasPaymentMethod returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


