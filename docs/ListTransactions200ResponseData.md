# ListTransactions200ResponseData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Transactions** | [**[]Transaction**](Transaction.md) |  | 
**Pagination** | [**Pagination**](Pagination.md) |  | 

## Methods

### NewListTransactions200ResponseData

`func NewListTransactions200ResponseData(transactions []Transaction, pagination Pagination, ) *ListTransactions200ResponseData`

NewListTransactions200ResponseData instantiates a new ListTransactions200ResponseData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewListTransactions200ResponseDataWithDefaults

`func NewListTransactions200ResponseDataWithDefaults() *ListTransactions200ResponseData`

NewListTransactions200ResponseDataWithDefaults instantiates a new ListTransactions200ResponseData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTransactions

`func (o *ListTransactions200ResponseData) GetTransactions() []Transaction`

GetTransactions returns the Transactions field if non-nil, zero value otherwise.

### GetTransactionsOk

`func (o *ListTransactions200ResponseData) GetTransactionsOk() (*[]Transaction, bool)`

GetTransactionsOk returns a tuple with the Transactions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransactions

`func (o *ListTransactions200ResponseData) SetTransactions(v []Transaction)`

SetTransactions sets Transactions field to given value.


### GetPagination

`func (o *ListTransactions200ResponseData) GetPagination() Pagination`

GetPagination returns the Pagination field if non-nil, zero value otherwise.

### GetPaginationOk

`func (o *ListTransactions200ResponseData) GetPaginationOk() (*Pagination, bool)`

GetPaginationOk returns a tuple with the Pagination field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPagination

`func (o *ListTransactions200ResponseData) SetPagination(v Pagination)`

SetPagination sets Pagination field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


