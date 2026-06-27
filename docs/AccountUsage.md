# AccountUsage

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**MonthlyTransactionsUsed** | Pointer to **int32** |  | [optional] 
**MonthlyTransactionLimit** | Pointer to **NullableInt32** | null &#x3D; unlimited. | [optional] 
**OverageCostPerTx** | Pointer to **float32** |  | [optional] 

## Methods

### NewAccountUsage

`func NewAccountUsage() *AccountUsage`

NewAccountUsage instantiates a new AccountUsage object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAccountUsageWithDefaults

`func NewAccountUsageWithDefaults() *AccountUsage`

NewAccountUsageWithDefaults instantiates a new AccountUsage object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMonthlyTransactionsUsed

`func (o *AccountUsage) GetMonthlyTransactionsUsed() int32`

GetMonthlyTransactionsUsed returns the MonthlyTransactionsUsed field if non-nil, zero value otherwise.

### GetMonthlyTransactionsUsedOk

`func (o *AccountUsage) GetMonthlyTransactionsUsedOk() (*int32, bool)`

GetMonthlyTransactionsUsedOk returns a tuple with the MonthlyTransactionsUsed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMonthlyTransactionsUsed

`func (o *AccountUsage) SetMonthlyTransactionsUsed(v int32)`

SetMonthlyTransactionsUsed sets MonthlyTransactionsUsed field to given value.

### HasMonthlyTransactionsUsed

`func (o *AccountUsage) HasMonthlyTransactionsUsed() bool`

HasMonthlyTransactionsUsed returns a boolean if a field has been set.

### GetMonthlyTransactionLimit

`func (o *AccountUsage) GetMonthlyTransactionLimit() int32`

GetMonthlyTransactionLimit returns the MonthlyTransactionLimit field if non-nil, zero value otherwise.

### GetMonthlyTransactionLimitOk

`func (o *AccountUsage) GetMonthlyTransactionLimitOk() (*int32, bool)`

GetMonthlyTransactionLimitOk returns a tuple with the MonthlyTransactionLimit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMonthlyTransactionLimit

`func (o *AccountUsage) SetMonthlyTransactionLimit(v int32)`

SetMonthlyTransactionLimit sets MonthlyTransactionLimit field to given value.

### HasMonthlyTransactionLimit

`func (o *AccountUsage) HasMonthlyTransactionLimit() bool`

HasMonthlyTransactionLimit returns a boolean if a field has been set.

### SetMonthlyTransactionLimitNil

`func (o *AccountUsage) SetMonthlyTransactionLimitNil(b bool)`

 SetMonthlyTransactionLimitNil sets the value for MonthlyTransactionLimit to be an explicit nil

### UnsetMonthlyTransactionLimit
`func (o *AccountUsage) UnsetMonthlyTransactionLimit()`

UnsetMonthlyTransactionLimit ensures that no value is present for MonthlyTransactionLimit, not even an explicit nil
### GetOverageCostPerTx

`func (o *AccountUsage) GetOverageCostPerTx() float32`

GetOverageCostPerTx returns the OverageCostPerTx field if non-nil, zero value otherwise.

### GetOverageCostPerTxOk

`func (o *AccountUsage) GetOverageCostPerTxOk() (*float32, bool)`

GetOverageCostPerTxOk returns a tuple with the OverageCostPerTx field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOverageCostPerTx

`func (o *AccountUsage) SetOverageCostPerTx(v float32)`

SetOverageCostPerTx sets OverageCostPerTx field to given value.

### HasOverageCostPerTx

`func (o *AccountUsage) HasOverageCostPerTx() bool`

HasOverageCostPerTx returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


