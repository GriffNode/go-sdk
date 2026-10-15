# RecurringWebhookPayload

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**Event** | **string** |  | 
**Timestamp** | **time.Time** |  | 
**ScheduleId** | **string** |  | 
**Reference** | Pointer to **string** | Your own customer/order id, as entered on the schedule. | [optional] 
**CustomerEmail** | Pointer to **string** |  | [optional] 
**Description** | Pointer to **string** |  | [optional] 
**AmountFiat** | Pointer to **string** | Decimal string. | [optional] 
**CurrencyFiat** | Pointer to **string** |  | [optional] 
**Interval** | Pointer to **string** |  | [optional] 
**Status** | **string** |  | 
**PeriodNo** | Pointer to **int32** | recurring.payment.* only. | [optional] 
**TransactionId** | Pointer to **string** | recurring.payment.completed only. | [optional] 
**Reason** | Pointer to **string** | recurring.stopped only. | [optional] 

## Methods

### NewRecurringWebhookPayload

`func NewRecurringWebhookPayload(id string, event string, timestamp time.Time, scheduleId string, status string, ) *RecurringWebhookPayload`

NewRecurringWebhookPayload instantiates a new RecurringWebhookPayload object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRecurringWebhookPayloadWithDefaults

`func NewRecurringWebhookPayloadWithDefaults() *RecurringWebhookPayload`

NewRecurringWebhookPayloadWithDefaults instantiates a new RecurringWebhookPayload object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *RecurringWebhookPayload) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *RecurringWebhookPayload) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *RecurringWebhookPayload) SetId(v string)`

SetId sets Id field to given value.


### GetEvent

`func (o *RecurringWebhookPayload) GetEvent() string`

GetEvent returns the Event field if non-nil, zero value otherwise.

### GetEventOk

`func (o *RecurringWebhookPayload) GetEventOk() (*string, bool)`

GetEventOk returns a tuple with the Event field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEvent

`func (o *RecurringWebhookPayload) SetEvent(v string)`

SetEvent sets Event field to given value.


### GetTimestamp

`func (o *RecurringWebhookPayload) GetTimestamp() time.Time`

GetTimestamp returns the Timestamp field if non-nil, zero value otherwise.

### GetTimestampOk

`func (o *RecurringWebhookPayload) GetTimestampOk() (*time.Time, bool)`

GetTimestampOk returns a tuple with the Timestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimestamp

`func (o *RecurringWebhookPayload) SetTimestamp(v time.Time)`

SetTimestamp sets Timestamp field to given value.


### GetScheduleId

`func (o *RecurringWebhookPayload) GetScheduleId() string`

GetScheduleId returns the ScheduleId field if non-nil, zero value otherwise.

### GetScheduleIdOk

`func (o *RecurringWebhookPayload) GetScheduleIdOk() (*string, bool)`

GetScheduleIdOk returns a tuple with the ScheduleId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScheduleId

`func (o *RecurringWebhookPayload) SetScheduleId(v string)`

SetScheduleId sets ScheduleId field to given value.


### GetReference

`func (o *RecurringWebhookPayload) GetReference() string`

GetReference returns the Reference field if non-nil, zero value otherwise.

### GetReferenceOk

`func (o *RecurringWebhookPayload) GetReferenceOk() (*string, bool)`

GetReferenceOk returns a tuple with the Reference field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReference

`func (o *RecurringWebhookPayload) SetReference(v string)`

SetReference sets Reference field to given value.

### HasReference

`func (o *RecurringWebhookPayload) HasReference() bool`

HasReference returns a boolean if a field has been set.

### GetCustomerEmail

`func (o *RecurringWebhookPayload) GetCustomerEmail() string`

GetCustomerEmail returns the CustomerEmail field if non-nil, zero value otherwise.

### GetCustomerEmailOk

`func (o *RecurringWebhookPayload) GetCustomerEmailOk() (*string, bool)`

GetCustomerEmailOk returns a tuple with the CustomerEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerEmail

`func (o *RecurringWebhookPayload) SetCustomerEmail(v string)`

SetCustomerEmail sets CustomerEmail field to given value.

### HasCustomerEmail

`func (o *RecurringWebhookPayload) HasCustomerEmail() bool`

HasCustomerEmail returns a boolean if a field has been set.

### GetDescription

`func (o *RecurringWebhookPayload) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *RecurringWebhookPayload) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *RecurringWebhookPayload) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *RecurringWebhookPayload) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetAmountFiat

`func (o *RecurringWebhookPayload) GetAmountFiat() string`

GetAmountFiat returns the AmountFiat field if non-nil, zero value otherwise.

### GetAmountFiatOk

`func (o *RecurringWebhookPayload) GetAmountFiatOk() (*string, bool)`

GetAmountFiatOk returns a tuple with the AmountFiat field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmountFiat

`func (o *RecurringWebhookPayload) SetAmountFiat(v string)`

SetAmountFiat sets AmountFiat field to given value.

### HasAmountFiat

`func (o *RecurringWebhookPayload) HasAmountFiat() bool`

HasAmountFiat returns a boolean if a field has been set.

### GetCurrencyFiat

`func (o *RecurringWebhookPayload) GetCurrencyFiat() string`

GetCurrencyFiat returns the CurrencyFiat field if non-nil, zero value otherwise.

### GetCurrencyFiatOk

`func (o *RecurringWebhookPayload) GetCurrencyFiatOk() (*string, bool)`

GetCurrencyFiatOk returns a tuple with the CurrencyFiat field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrencyFiat

`func (o *RecurringWebhookPayload) SetCurrencyFiat(v string)`

SetCurrencyFiat sets CurrencyFiat field to given value.

### HasCurrencyFiat

`func (o *RecurringWebhookPayload) HasCurrencyFiat() bool`

HasCurrencyFiat returns a boolean if a field has been set.

### GetInterval

`func (o *RecurringWebhookPayload) GetInterval() string`

GetInterval returns the Interval field if non-nil, zero value otherwise.

### GetIntervalOk

`func (o *RecurringWebhookPayload) GetIntervalOk() (*string, bool)`

GetIntervalOk returns a tuple with the Interval field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInterval

`func (o *RecurringWebhookPayload) SetInterval(v string)`

SetInterval sets Interval field to given value.

### HasInterval

`func (o *RecurringWebhookPayload) HasInterval() bool`

HasInterval returns a boolean if a field has been set.

### GetStatus

`func (o *RecurringWebhookPayload) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *RecurringWebhookPayload) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *RecurringWebhookPayload) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetPeriodNo

`func (o *RecurringWebhookPayload) GetPeriodNo() int32`

GetPeriodNo returns the PeriodNo field if non-nil, zero value otherwise.

### GetPeriodNoOk

`func (o *RecurringWebhookPayload) GetPeriodNoOk() (*int32, bool)`

GetPeriodNoOk returns a tuple with the PeriodNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriodNo

`func (o *RecurringWebhookPayload) SetPeriodNo(v int32)`

SetPeriodNo sets PeriodNo field to given value.

### HasPeriodNo

`func (o *RecurringWebhookPayload) HasPeriodNo() bool`

HasPeriodNo returns a boolean if a field has been set.

### GetTransactionId

`func (o *RecurringWebhookPayload) GetTransactionId() string`

GetTransactionId returns the TransactionId field if non-nil, zero value otherwise.

### GetTransactionIdOk

`func (o *RecurringWebhookPayload) GetTransactionIdOk() (*string, bool)`

GetTransactionIdOk returns a tuple with the TransactionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransactionId

`func (o *RecurringWebhookPayload) SetTransactionId(v string)`

SetTransactionId sets TransactionId field to given value.

### HasTransactionId

`func (o *RecurringWebhookPayload) HasTransactionId() bool`

HasTransactionId returns a boolean if a field has been set.

### GetReason

`func (o *RecurringWebhookPayload) GetReason() string`

GetReason returns the Reason field if non-nil, zero value otherwise.

### GetReasonOk

`func (o *RecurringWebhookPayload) GetReasonOk() (*string, bool)`

GetReasonOk returns a tuple with the Reason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReason

`func (o *RecurringWebhookPayload) SetReason(v string)`

SetReason sets Reason field to given value.

### HasReason

`func (o *RecurringWebhookPayload) HasReason() bool`

HasReason returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


