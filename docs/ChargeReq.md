# ElepayApi.ChargeReq

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**amount** | **Number** | 金額 | [optional] 
**currency** | **String** | 通貨コード (ISO_4217) | [optional] [default to &#39;JPY&#39;]
**paymentMethod** | [**PaymentMethodType**](PaymentMethodType.md) |  | [optional] 
**orderNo** | **String** | お客様側のシステムオーダーNo（例：注文番号、決済IDなど） | [optional] 
**description** | **String** | 決済に関する説明 | [optional] 
**extra** | **{String: Object}** | 決済に関する追加情報がある場合に利用します。 | [optional] 
**metadata** | **{String: Object}** | メタデータ | [optional] 
**clientIp** | **String** | Client IP アドレス | [optional] 


