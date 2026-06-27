# GetPrices200ResponseData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Crypto** | Pointer to **map[string]float32** | USD price per unit, keyed by crypto symbol (active coins only). | [optional] 
**Fiat** | Pointer to **map[string]float32** | USD value of one unit of each fiat currency. | [optional] 
**FetchedAt** | Pointer to **time.Time** |  | [optional] 

## Methods

### NewGetPrices200ResponseData

`func NewGetPrices200ResponseData() *GetPrices200ResponseData`

NewGetPrices200ResponseData instantiates a new GetPrices200ResponseData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetPrices200ResponseDataWithDefaults

`func NewGetPrices200ResponseDataWithDefaults() *GetPrices200ResponseData`

NewGetPrices200ResponseDataWithDefaults instantiates a new GetPrices200ResponseData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCrypto

`func (o *GetPrices200ResponseData) GetCrypto() map[string]float32`

GetCrypto returns the Crypto field if non-nil, zero value otherwise.

### GetCryptoOk

`func (o *GetPrices200ResponseData) GetCryptoOk() (*map[string]float32, bool)`

GetCryptoOk returns a tuple with the Crypto field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCrypto

`func (o *GetPrices200ResponseData) SetCrypto(v map[string]float32)`

SetCrypto sets Crypto field to given value.

### HasCrypto

`func (o *GetPrices200ResponseData) HasCrypto() bool`

HasCrypto returns a boolean if a field has been set.

### GetFiat

`func (o *GetPrices200ResponseData) GetFiat() map[string]float32`

GetFiat returns the Fiat field if non-nil, zero value otherwise.

### GetFiatOk

`func (o *GetPrices200ResponseData) GetFiatOk() (*map[string]float32, bool)`

GetFiatOk returns a tuple with the Fiat field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFiat

`func (o *GetPrices200ResponseData) SetFiat(v map[string]float32)`

SetFiat sets Fiat field to given value.

### HasFiat

`func (o *GetPrices200ResponseData) HasFiat() bool`

HasFiat returns a boolean if a field has been set.

### GetFetchedAt

`func (o *GetPrices200ResponseData) GetFetchedAt() time.Time`

GetFetchedAt returns the FetchedAt field if non-nil, zero value otherwise.

### GetFetchedAtOk

`func (o *GetPrices200ResponseData) GetFetchedAtOk() (*time.Time, bool)`

GetFetchedAtOk returns a tuple with the FetchedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFetchedAt

`func (o *GetPrices200ResponseData) SetFetchedAt(v time.Time)`

SetFetchedAt sets FetchedAt field to given value.

### HasFetchedAt

`func (o *GetPrices200ResponseData) HasFetchedAt() bool`

HasFetchedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


