# ElepayApi.RefundDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **String** | Refund ID | [optional] 
**_object** | **String** | 対象種類の表記 | [optional] [default to &#39;refund&#39;]
**chargeId** | **String** | Charge ID | [optional] 
**liveMode** | **Boolean** | 本番モードかどうか - false テストモード - true 本番モード  | [optional] 
**amount** | **Number** | 返金金額。全額返金、及び amount を指定することで金額の部分返金を行うことができます。 | [optional] 
**currency** | **String** | 通貨コード (ISO_4217) | [optional] 
**reason** | **String** | 返金理由 | [optional] 
**status** | **String** | 返金状態 | [optional] 
**refundedTime** | **Number** | 返金を行う時間のUTCタイムスタンプ。 | [optional] 
**createTime** | **Number** | 返金新規時間のUTCタイムスタンプ。 | [optional] 


