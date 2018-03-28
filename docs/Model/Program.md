# Program

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id_program** | **string** | The program id | 
**locale** | **string** | The Softonic locale | [optional] [default to 'en']
**legal_advisory** | **string** | Type of legal advisory.  *              It can assume the following values: AUTO, WITHTOOLBAR, MANUAL, DISABLED | [optional] [default to 'null']
**legal_note** | **string** | Legal note, in case the advisory type is MANUAL. It can be up to 65535 bytes. | [optional] [default to 'null']
**show_download_button** | **bool** | If the download button is shown for the program, DEPRECATED | [optional] [default to false]
**dont_allow_download** | **bool** | If true no download button should be shown | [optional] [default to false]
**force_external_download** | **bool** | If the download for the program is forced to external | [optional] [default to false]
**is_top** | **bool** | Arbitrary value to say that it is an important program, affects compliance rules | [optional] [default to false]
**is_sales_client** | **bool** | This program pays in some way to the company, affects compliance rules | [optional] [default to false]

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


