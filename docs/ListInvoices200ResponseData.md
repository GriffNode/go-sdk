# ListInvoices200ResponseData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Invoices** | Pointer to [**[]Invoice**](Invoice.md) |  | [optional] 
**Pagination** | Pointer to [**Pagination**](Pagination.md) |  | [optional] 

## Methods

### NewListInvoices200ResponseData

`func NewListInvoices200ResponseData() *ListInvoices200ResponseData`

NewListInvoices200ResponseData instantiates a new ListInvoices200ResponseData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewListInvoices200ResponseDataWithDefaults

`func NewListInvoices200ResponseDataWithDefaults() *ListInvoices200ResponseData`

NewListInvoices200ResponseDataWithDefaults instantiates a new ListInvoices200ResponseData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetInvoices

`func (o *ListInvoices200ResponseData) GetInvoices() []Invoice`

GetInvoices returns the Invoices field if non-nil, zero value otherwise.

### GetInvoicesOk

`func (o *ListInvoices200ResponseData) GetInvoicesOk() (*[]Invoice, bool)`

GetInvoicesOk returns a tuple with the Invoices field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvoices

`func (o *ListInvoices200ResponseData) SetInvoices(v []Invoice)`

SetInvoices sets Invoices field to given value.

### HasInvoices

`func (o *ListInvoices200ResponseData) HasInvoices() bool`

HasInvoices returns a boolean if a field has been set.

### GetPagination

`func (o *ListInvoices200ResponseData) GetPagination() Pagination`

GetPagination returns the Pagination field if non-nil, zero value otherwise.

### GetPaginationOk

`func (o *ListInvoices200ResponseData) GetPaginationOk() (*Pagination, bool)`

GetPaginationOk returns a tuple with the Pagination field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPagination

`func (o *ListInvoices200ResponseData) SetPagination(v Pagination)`

SetPagination sets Pagination field to given value.

### HasPagination

`func (o *ListInvoices200ResponseData) HasPagination() bool`

HasPagination returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


