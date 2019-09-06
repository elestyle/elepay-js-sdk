# ElepayApi.ElepayError

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **String** | エラーコードとメッセージ | [optional] 
**code** | **String** | エラーコード | [optional] 
**message** | **String** | エラーメッセージ | [optional] 



## Enum: TypeEnum


* `not_found_error` (value: `"not_found_error"`)

* `invalid_request_error` (value: `"invalid_request_error"`)

* `channel_validation_error` (value: `"channel_validation_error"`)

* `channel_error` (value: `"channel_error"`)

* `provider_error` (value: `"provider_error"`)

* `connection_error` (value: `"connection_error"`)

* `process_error` (value: `"process_error"`)

* `authentication_error` (value: `"authentication_error"`)

* `forbidden_error` (value: `"forbidden_error"`)

* `rate_limit_error` (value: `"rate_limit_error"`)

* `api_error` (value: `"api_error"`)

* `api_connection_error` (value: `"api_connection_error"`)





## Enum: CodeEnum


* `not_found` (value: `"not_found"`)

* `not_found_charge` (value: `"not_found_charge"`)

* `auth_invalid_credential` (value: `"auth_invalid_credential"`)

* `auth_invalid_provider` (value: `"auth_invalid_provider"`)

* `invalid_request` (value: `"invalid_request"`)

* `invalid_order_no` (value: `"invalid_order_no"`)

* `invalid_payment_method` (value: `"invalid_payment_method"`)

* `invalid_amount` (value: `"invalid_amount"`)

* `invalid_token` (value: `"invalid_token"`)

* `invalid_front_url` (value: `"invalid_front_url"`)

* `invalid_cancel_url` (value: `"invalid_cancel_url"`)

* `invalid_contract_number` (value: `"invalid_contract_number"`)

* `invalid_username` (value: `"invalid_username"`)

* `invalid_email` (value: `"invalid_email"`)

* `invalid_password` (value: `"invalid_password"`)

* `invalid_order_no_length` (value: `"invalid_order_no_length"`)

* `invalid_status_change` (value: `"invalid_status_change"`)

* `invalid_status_change_by_app` (value: `"invalid_status_change_by_app"`)

* `invalid_status_change_by_provider` (value: `"invalid_status_change_by_provider"`)

* `invalid_provider_unique_id` (value: `"invalid_provider_unique_id"`)

* `invalid_provider_capture_id` (value: `"invalid_provider_capture_id"`)

* `invalid_channel_group` (value: `"invalid_channel_group"`)

* `invalid_buyer_name` (value: `"invalid_buyer_name"`)

* `invalid_buyer_phone` (value: `"invalid_buyer_phone"`)

* `invalid_buyer_email` (value: `"invalid_buyer_email"`)

* `invalid_buyer_zip` (value: `"invalid_buyer_zip"`)

* `invalid_buyer_address1` (value: `"invalid_buyer_address1"`)

* `invalid_buyer_address2` (value: `"invalid_buyer_address2"`)

* `invalid_code_url` (value: `"invalid_code_url"`)

* `invalid_shop_id` (value: `"invalid_shop_id"`)

* `invalid_shop_name` (value: `"invalid_shop_name"`)

* `invalid_shop_no` (value: `"invalid_shop_no"`)

* `invalid_product_id` (value: `"invalid_product_id"`)

* `invalid_product_name` (value: `"invalid_product_name"`)

* `invalid_product_price` (value: `"invalid_product_price"`)

* `invalid_product_count` (value: `"invalid_product_count"`)

* `invalid_setting_type` (value: `"invalid_setting_type"`)

* `invalid_setting_name` (value: `"invalid_setting_name"`)

* `invalid_category_id` (value: `"invalid_category_id"`)

* `invalid_category_name` (value: `"invalid_category_name"`)

* `invalid_order_amount` (value: `"invalid_order_amount"`)

* `invalid_order_amount_change` (value: `"invalid_order_amount_change"`)

* `invalid_product_inactive` (value: `"invalid_product_inactive"`)

* `invalid_name` (value: `"invalid_name"`)

* `invalid_role` (value: `"invalid_role"`)

* `invalid_campaign_name` (value: `"invalid_campaign_name"`)

* `invalid_campaign_time` (value: `"invalid_campaign_time"`)

* `invalid_campaign_start_time` (value: `"invalid_campaign_start_time"`)

* `invalid_campaign_expired_time` (value: `"invalid_campaign_expired_time"`)

* `invalid_campaign_discount_type` (value: `"invalid_campaign_discount_type"`)

* `invalid_campaign_discount_value` (value: `"invalid_campaign_discount_value"`)

* `invalid_campaign_condition_type` (value: `"invalid_campaign_condition_type"`)

* `invalid_value` (value: `"invalid_value"`)

* `invalid_theme_name` (value: `"invalid_theme_name"`)

* `invalid_label_name` (value: `"invalid_label_name"`)

* `invalid_sku` (value: `"invalid_sku"`)

* `invalid_charge` (value: `"invalid_charge"`)

* `invalid_from` (value: `"invalid_from"`)

* `invalid_to` (value: `"invalid_to"`)

* `invalid_export_data_date_range` (value: `"invalid_export_data_date_range"`)

* `invalid_secret_key` (value: `"invalid_secret_key"`)

* `invalid_auth_code` (value: `"invalid_auth_code"`)

* `invalid_terminal_id` (value: `"invalid_terminal_id"`)

* `invalid_lang` (value: `"invalid_lang"`)

* `invalid_title` (value: `"invalid_title"`)

* `invalid_content` (value: `"invalid_content"`)

* `invalid_type` (value: `"invalid_type"`)

* `invalid_legal_registration_no` (value: `"invalid_legal_registration_no"`)

* `invalid_country` (value: `"invalid_country"`)

* `invalid_publish_date` (value: `"invalid_publish_date"`)

* `invalid_json_format` (value: `"invalid_json_format"`)

* `invalid_title_length` (value: `"invalid_title_length"`)

* `invalid_name_length` (value: `"invalid_name_length"`)

* `invalid_ref_type_length` (value: `"invalid_ref_type_length"`)

* `invalid_ref_id_length` (value: `"invalid_ref_id_length"`)

* `invalid_type_length` (value: `"invalid_type_length"`)

* `invalid_desc_length` (value: `"invalid_desc_length"`)

* `invalid_key_length` (value: `"invalid_key_length"`)

* `invalid_code_length` (value: `"invalid_code_length"`)

* `invalid_legal_registration_no_length` (value: `"invalid_legal_registration_no_length"`)

* `invalid_establishment_date_length` (value: `"invalid_establishment_date_length"`)

* `invalid_country_length` (value: `"invalid_country_length"`)

* `invalid_bank_code_length` (value: `"invalid_bank_code_length"`)

* `invalid_branch_code_length` (value: `"invalid_branch_code_length"`)

* `invalid_bank_account_number_length` (value: `"invalid_bank_account_number_length"`)

* `invalid_birthday_length` (value: `"invalid_birthday_length"`)

* `invalid_email_length` (value: `"invalid_email_length"`)

* `invalid_zip_length` (value: `"invalid_zip_length"`)

* `invalid_tel_length` (value: `"invalid_tel_length"`)

* `invalid_fax_length` (value: `"invalid_fax_length"`)

* `invalid_sort_order_length` (value: `"invalid_sort_order_length"`)

* `invalid_parking_rack_no` (value: `"invalid_parking_rack_no"`)

* `invalid_parking_rack_status` (value: `"invalid_parking_rack_status"`)

* `invalid_parking_rack_status_not_used` (value: `"invalid_parking_rack_status_not_used"`)

* `invalid_parking_rack_status_opened` (value: `"invalid_parking_rack_status_opened"`)

* `invalid_parking_rack_status_locked` (value: `"invalid_parking_rack_status_locked"`)

* `invalid_parking_rack_status_connect_fail` (value: `"invalid_parking_rack_status_connect_fail"`)

* `invalid_parking_no_or_rack_no` (value: `"invalid_parking_no_or_rack_no"`)

* `invalid_parking_pin_code` (value: `"invalid_parking_pin_code"`)

* `incorrect_currency` (value: `"incorrect_currency"`)

* `incorrect_card_number` (value: `"incorrect_card_number"`)

* `incorrect_amount` (value: `"incorrect_amount"`)

* `incorrect_merchant_id` (value: `"incorrect_merchant_id"`)

* `incorrect_product_id` (value: `"incorrect_product_id"`)

* `incorrect_export_data_date_range` (value: `"incorrect_export_data_date_range"`)

* `incorrect_status` (value: `"incorrect_status"`)

* `provider_response_result_failed` (value: `"provider_response_result_failed"`)

* `no_such_token` (value: `"no_such_token"`)

* `duplicate_order_no` (value: `"duplicate_order_no"`)

* `duplicate_shop_no` (value: `"duplicate_shop_no"`)

* `duplicate_contract_number` (value: `"duplicate_contract_number"`)

* `duplicate_email` (value: `"duplicate_email"`)

* `duplicate_legal_registration_no` (value: `"duplicate_legal_registration_no"`)

* `duplicate_key` (value: `"duplicate_key"`)

* `duplicate_category_name` (value: `"duplicate_category_name"`)

* `expired_card` (value: `"expired_card"`)

* `card_declined` (value: `"card_declined"`)

* `processing_card_error` (value: `"processing_card_error"`)

* `required_key` (value: `"required_key"`)

* `charge_already_captured` (value: `"charge_already_captured"`)

* `charge_already_refunded` (value: `"charge_already_refunded"`)

* `refused_refund` (value: `"refused_refund"`)

* `refused_refund_constraint_day` (value: `"refused_refund_constraint_day"`)

* `refused_refund_non_captured` (value: `"refused_refund_non_captured"`)

* `inactive_application` (value: `"inactive_application"`)

* `inactive_payment_method` (value: `"inactive_payment_method"`)

* `inactive_product` (value: `"inactive_product"`)

* `exist_payment_method` (value: `"exist_payment_method"`)

* `campaign_already_started` (value: `"campaign_already_started"`)

* `over_shop_limit_count` (value: `"over_shop_limit_count"`)

* `over_product_limit_count` (value: `"over_product_limit_count"`)

* `process_error` (value: `"process_error"`)

* `api_connection_error` (value: `"api_connection_error"`)

* `provider_config_error` (value: `"provider_config_error"`)

* `api_error` (value: `"api_error"`)

* `forbidden` (value: `"forbidden"`)

* `forbidden_close_self` (value: `"forbidden_close_self"`)

* `recaptcha_fail` (value: `"recaptcha_fail"`)




