# AccountLimits

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ApiRateLimitPerMinute** | Pointer to **int32** |  | [optional] 
**ApiRateLimitPerHour** | Pointer to **int32** |  | [optional] 
**WebhookSupport** | Pointer to **bool** |  | [optional] 

## Methods

### NewAccountLimits

`func NewAccountLimits() *AccountLimits`

NewAccountLimits instantiates a new AccountLimits object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAccountLimitsWithDefaults

`func NewAccountLimitsWithDefaults() *AccountLimits`

NewAccountLimitsWithDefaults instantiates a new AccountLimits object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetApiRateLimitPerMinute

`func (o *AccountLimits) GetApiRateLimitPerMinute() int32`

GetApiRateLimitPerMinute returns the ApiRateLimitPerMinute field if non-nil, zero value otherwise.

### GetApiRateLimitPerMinuteOk

`func (o *AccountLimits) GetApiRateLimitPerMinuteOk() (*int32, bool)`

GetApiRateLimitPerMinuteOk returns a tuple with the ApiRateLimitPerMinute field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApiRateLimitPerMinute

`func (o *AccountLimits) SetApiRateLimitPerMinute(v int32)`

SetApiRateLimitPerMinute sets ApiRateLimitPerMinute field to given value.

### HasApiRateLimitPerMinute

`func (o *AccountLimits) HasApiRateLimitPerMinute() bool`

HasApiRateLimitPerMinute returns a boolean if a field has been set.

### GetApiRateLimitPerHour

`func (o *AccountLimits) GetApiRateLimitPerHour() int32`

GetApiRateLimitPerHour returns the ApiRateLimitPerHour field if non-nil, zero value otherwise.

### GetApiRateLimitPerHourOk

`func (o *AccountLimits) GetApiRateLimitPerHourOk() (*int32, bool)`

GetApiRateLimitPerHourOk returns a tuple with the ApiRateLimitPerHour field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApiRateLimitPerHour

`func (o *AccountLimits) SetApiRateLimitPerHour(v int32)`

SetApiRateLimitPerHour sets ApiRateLimitPerHour field to given value.

### HasApiRateLimitPerHour

`func (o *AccountLimits) HasApiRateLimitPerHour() bool`

HasApiRateLimitPerHour returns a boolean if a field has been set.

### GetWebhookSupport

`func (o *AccountLimits) GetWebhookSupport() bool`

GetWebhookSupport returns the WebhookSupport field if non-nil, zero value otherwise.

### GetWebhookSupportOk

`func (o *AccountLimits) GetWebhookSupportOk() (*bool, bool)`

GetWebhookSupportOk returns a tuple with the WebhookSupport field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWebhookSupport

`func (o *AccountLimits) SetWebhookSupport(v bool)`

SetWebhookSupport sets WebhookSupport field to given value.

### HasWebhookSupport

`func (o *AccountLimits) HasWebhookSupport() bool`

HasWebhookSupport returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


