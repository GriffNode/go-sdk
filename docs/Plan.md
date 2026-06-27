# Plan

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Tier** | Pointer to [**PlanTier**](PlanTier.md) |  | [optional] 
**MonthlyPriceUsd** | Pointer to **NullableFloat32** |  | [optional] 
**YearlyPriceUsd** | Pointer to **NullableFloat32** |  | [optional] 
**MonthlyTransactionLimit** | Pointer to **NullableInt32** |  | [optional] 
**OverageCostPerTx** | Pointer to **float32** |  | [optional] 
**WebhookSupport** | Pointer to **bool** |  | [optional] 
**WebhookLimit** | Pointer to **NullableInt32** |  | [optional] 
**IpWhitelist** | Pointer to **bool** |  | [optional] 
**ApiRateLimitPerMinute** | Pointer to **int32** |  | [optional] 
**ApiRateLimitPerHour** | Pointer to **int32** |  | [optional] 
**CustomPricing** | Pointer to **bool** |  | [optional] 

## Methods

### NewPlan

`func NewPlan() *Plan`

NewPlan instantiates a new Plan object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPlanWithDefaults

`func NewPlanWithDefaults() *Plan`

NewPlanWithDefaults instantiates a new Plan object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTier

`func (o *Plan) GetTier() PlanTier`

GetTier returns the Tier field if non-nil, zero value otherwise.

### GetTierOk

`func (o *Plan) GetTierOk() (*PlanTier, bool)`

GetTierOk returns a tuple with the Tier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTier

`func (o *Plan) SetTier(v PlanTier)`

SetTier sets Tier field to given value.

### HasTier

`func (o *Plan) HasTier() bool`

HasTier returns a boolean if a field has been set.

### GetMonthlyPriceUsd

`func (o *Plan) GetMonthlyPriceUsd() float32`

GetMonthlyPriceUsd returns the MonthlyPriceUsd field if non-nil, zero value otherwise.

### GetMonthlyPriceUsdOk

`func (o *Plan) GetMonthlyPriceUsdOk() (*float32, bool)`

GetMonthlyPriceUsdOk returns a tuple with the MonthlyPriceUsd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMonthlyPriceUsd

`func (o *Plan) SetMonthlyPriceUsd(v float32)`

SetMonthlyPriceUsd sets MonthlyPriceUsd field to given value.

### HasMonthlyPriceUsd

`func (o *Plan) HasMonthlyPriceUsd() bool`

HasMonthlyPriceUsd returns a boolean if a field has been set.

### SetMonthlyPriceUsdNil

`func (o *Plan) SetMonthlyPriceUsdNil(b bool)`

 SetMonthlyPriceUsdNil sets the value for MonthlyPriceUsd to be an explicit nil

### UnsetMonthlyPriceUsd
`func (o *Plan) UnsetMonthlyPriceUsd()`

UnsetMonthlyPriceUsd ensures that no value is present for MonthlyPriceUsd, not even an explicit nil
### GetYearlyPriceUsd

`func (o *Plan) GetYearlyPriceUsd() float32`

GetYearlyPriceUsd returns the YearlyPriceUsd field if non-nil, zero value otherwise.

### GetYearlyPriceUsdOk

`func (o *Plan) GetYearlyPriceUsdOk() (*float32, bool)`

GetYearlyPriceUsdOk returns a tuple with the YearlyPriceUsd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYearlyPriceUsd

`func (o *Plan) SetYearlyPriceUsd(v float32)`

SetYearlyPriceUsd sets YearlyPriceUsd field to given value.

### HasYearlyPriceUsd

`func (o *Plan) HasYearlyPriceUsd() bool`

HasYearlyPriceUsd returns a boolean if a field has been set.

### SetYearlyPriceUsdNil

`func (o *Plan) SetYearlyPriceUsdNil(b bool)`

 SetYearlyPriceUsdNil sets the value for YearlyPriceUsd to be an explicit nil

### UnsetYearlyPriceUsd
`func (o *Plan) UnsetYearlyPriceUsd()`

UnsetYearlyPriceUsd ensures that no value is present for YearlyPriceUsd, not even an explicit nil
### GetMonthlyTransactionLimit

`func (o *Plan) GetMonthlyTransactionLimit() int32`

GetMonthlyTransactionLimit returns the MonthlyTransactionLimit field if non-nil, zero value otherwise.

### GetMonthlyTransactionLimitOk

`func (o *Plan) GetMonthlyTransactionLimitOk() (*int32, bool)`

GetMonthlyTransactionLimitOk returns a tuple with the MonthlyTransactionLimit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMonthlyTransactionLimit

`func (o *Plan) SetMonthlyTransactionLimit(v int32)`

SetMonthlyTransactionLimit sets MonthlyTransactionLimit field to given value.

### HasMonthlyTransactionLimit

`func (o *Plan) HasMonthlyTransactionLimit() bool`

HasMonthlyTransactionLimit returns a boolean if a field has been set.

### SetMonthlyTransactionLimitNil

`func (o *Plan) SetMonthlyTransactionLimitNil(b bool)`

 SetMonthlyTransactionLimitNil sets the value for MonthlyTransactionLimit to be an explicit nil

### UnsetMonthlyTransactionLimit
`func (o *Plan) UnsetMonthlyTransactionLimit()`

UnsetMonthlyTransactionLimit ensures that no value is present for MonthlyTransactionLimit, not even an explicit nil
### GetOverageCostPerTx

`func (o *Plan) GetOverageCostPerTx() float32`

GetOverageCostPerTx returns the OverageCostPerTx field if non-nil, zero value otherwise.

### GetOverageCostPerTxOk

`func (o *Plan) GetOverageCostPerTxOk() (*float32, bool)`

GetOverageCostPerTxOk returns a tuple with the OverageCostPerTx field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOverageCostPerTx

`func (o *Plan) SetOverageCostPerTx(v float32)`

SetOverageCostPerTx sets OverageCostPerTx field to given value.

### HasOverageCostPerTx

`func (o *Plan) HasOverageCostPerTx() bool`

HasOverageCostPerTx returns a boolean if a field has been set.

### GetWebhookSupport

`func (o *Plan) GetWebhookSupport() bool`

GetWebhookSupport returns the WebhookSupport field if non-nil, zero value otherwise.

### GetWebhookSupportOk

`func (o *Plan) GetWebhookSupportOk() (*bool, bool)`

GetWebhookSupportOk returns a tuple with the WebhookSupport field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWebhookSupport

`func (o *Plan) SetWebhookSupport(v bool)`

SetWebhookSupport sets WebhookSupport field to given value.

### HasWebhookSupport

`func (o *Plan) HasWebhookSupport() bool`

HasWebhookSupport returns a boolean if a field has been set.

### GetWebhookLimit

`func (o *Plan) GetWebhookLimit() int32`

GetWebhookLimit returns the WebhookLimit field if non-nil, zero value otherwise.

### GetWebhookLimitOk

`func (o *Plan) GetWebhookLimitOk() (*int32, bool)`

GetWebhookLimitOk returns a tuple with the WebhookLimit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWebhookLimit

`func (o *Plan) SetWebhookLimit(v int32)`

SetWebhookLimit sets WebhookLimit field to given value.

### HasWebhookLimit

`func (o *Plan) HasWebhookLimit() bool`

HasWebhookLimit returns a boolean if a field has been set.

### SetWebhookLimitNil

`func (o *Plan) SetWebhookLimitNil(b bool)`

 SetWebhookLimitNil sets the value for WebhookLimit to be an explicit nil

### UnsetWebhookLimit
`func (o *Plan) UnsetWebhookLimit()`

UnsetWebhookLimit ensures that no value is present for WebhookLimit, not even an explicit nil
### GetIpWhitelist

`func (o *Plan) GetIpWhitelist() bool`

GetIpWhitelist returns the IpWhitelist field if non-nil, zero value otherwise.

### GetIpWhitelistOk

`func (o *Plan) GetIpWhitelistOk() (*bool, bool)`

GetIpWhitelistOk returns a tuple with the IpWhitelist field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIpWhitelist

`func (o *Plan) SetIpWhitelist(v bool)`

SetIpWhitelist sets IpWhitelist field to given value.

### HasIpWhitelist

`func (o *Plan) HasIpWhitelist() bool`

HasIpWhitelist returns a boolean if a field has been set.

### GetApiRateLimitPerMinute

`func (o *Plan) GetApiRateLimitPerMinute() int32`

GetApiRateLimitPerMinute returns the ApiRateLimitPerMinute field if non-nil, zero value otherwise.

### GetApiRateLimitPerMinuteOk

`func (o *Plan) GetApiRateLimitPerMinuteOk() (*int32, bool)`

GetApiRateLimitPerMinuteOk returns a tuple with the ApiRateLimitPerMinute field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApiRateLimitPerMinute

`func (o *Plan) SetApiRateLimitPerMinute(v int32)`

SetApiRateLimitPerMinute sets ApiRateLimitPerMinute field to given value.

### HasApiRateLimitPerMinute

`func (o *Plan) HasApiRateLimitPerMinute() bool`

HasApiRateLimitPerMinute returns a boolean if a field has been set.

### GetApiRateLimitPerHour

`func (o *Plan) GetApiRateLimitPerHour() int32`

GetApiRateLimitPerHour returns the ApiRateLimitPerHour field if non-nil, zero value otherwise.

### GetApiRateLimitPerHourOk

`func (o *Plan) GetApiRateLimitPerHourOk() (*int32, bool)`

GetApiRateLimitPerHourOk returns a tuple with the ApiRateLimitPerHour field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApiRateLimitPerHour

`func (o *Plan) SetApiRateLimitPerHour(v int32)`

SetApiRateLimitPerHour sets ApiRateLimitPerHour field to given value.

### HasApiRateLimitPerHour

`func (o *Plan) HasApiRateLimitPerHour() bool`

HasApiRateLimitPerHour returns a boolean if a field has been set.

### GetCustomPricing

`func (o *Plan) GetCustomPricing() bool`

GetCustomPricing returns the CustomPricing field if non-nil, zero value otherwise.

### GetCustomPricingOk

`func (o *Plan) GetCustomPricingOk() (*bool, bool)`

GetCustomPricingOk returns a tuple with the CustomPricing field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomPricing

`func (o *Plan) SetCustomPricing(v bool)`

SetCustomPricing sets CustomPricing field to given value.

### HasCustomPricing

`func (o *Plan) HasCustomPricing() bool`

HasCustomPricing returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


