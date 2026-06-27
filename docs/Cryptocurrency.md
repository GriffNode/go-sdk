# Cryptocurrency

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Symbol** | Pointer to [**CryptoSymbol**](CryptoSymbol.md) |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**Blockchain** | Pointer to **string** |  | [optional] 
**Network** | Pointer to **string** |  | [optional] 
**Type** | Pointer to **string** |  | [optional] 

## Methods

### NewCryptocurrency

`func NewCryptocurrency() *Cryptocurrency`

NewCryptocurrency instantiates a new Cryptocurrency object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCryptocurrencyWithDefaults

`func NewCryptocurrencyWithDefaults() *Cryptocurrency`

NewCryptocurrencyWithDefaults instantiates a new Cryptocurrency object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSymbol

`func (o *Cryptocurrency) GetSymbol() CryptoSymbol`

GetSymbol returns the Symbol field if non-nil, zero value otherwise.

### GetSymbolOk

`func (o *Cryptocurrency) GetSymbolOk() (*CryptoSymbol, bool)`

GetSymbolOk returns a tuple with the Symbol field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSymbol

`func (o *Cryptocurrency) SetSymbol(v CryptoSymbol)`

SetSymbol sets Symbol field to given value.

### HasSymbol

`func (o *Cryptocurrency) HasSymbol() bool`

HasSymbol returns a boolean if a field has been set.

### GetName

`func (o *Cryptocurrency) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *Cryptocurrency) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *Cryptocurrency) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *Cryptocurrency) HasName() bool`

HasName returns a boolean if a field has been set.

### GetBlockchain

`func (o *Cryptocurrency) GetBlockchain() string`

GetBlockchain returns the Blockchain field if non-nil, zero value otherwise.

### GetBlockchainOk

`func (o *Cryptocurrency) GetBlockchainOk() (*string, bool)`

GetBlockchainOk returns a tuple with the Blockchain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBlockchain

`func (o *Cryptocurrency) SetBlockchain(v string)`

SetBlockchain sets Blockchain field to given value.

### HasBlockchain

`func (o *Cryptocurrency) HasBlockchain() bool`

HasBlockchain returns a boolean if a field has been set.

### GetNetwork

`func (o *Cryptocurrency) GetNetwork() string`

GetNetwork returns the Network field if non-nil, zero value otherwise.

### GetNetworkOk

`func (o *Cryptocurrency) GetNetworkOk() (*string, bool)`

GetNetworkOk returns a tuple with the Network field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetwork

`func (o *Cryptocurrency) SetNetwork(v string)`

SetNetwork sets Network field to given value.

### HasNetwork

`func (o *Cryptocurrency) HasNetwork() bool`

HasNetwork returns a boolean if a field has been set.

### GetType

`func (o *Cryptocurrency) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *Cryptocurrency) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *Cryptocurrency) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *Cryptocurrency) HasType() bool`

HasType returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


