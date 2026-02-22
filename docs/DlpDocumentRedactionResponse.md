# DlpDocumentRedactionResponse

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**RedactedDocument** | **string** | The redacted document as a rasterized PDF with PII regions blurred, or the original file if no disallowed PII was found. | [optional] [default to null]
**CleanResult** | **bool** | True if no disallowed PII or sensitive data types were detected; false if any disallowed type was found and redacted. | [optional] [default to null]
**ContainsEmailAddress** | **bool** | True if the document contains email addresses. | [optional] [default to null]
**ContainsPhoneNumber** | **bool** | True if the document contains phone numbers. | [optional] [default to null]
**ContainsStreetAddress** | **bool** | True if the document contains street addresses. | [optional] [default to null]
**ContainsPersonName** | **bool** | True if the document contains person names. | [optional] [default to null]
**ContainsBirthDate** | **bool** | True if the document contains birth dates. | [optional] [default to null]
**ContainsPassportNumber** | **bool** | True if the document contains passport numbers. | [optional] [default to null]
**ContainsDriversLicense** | **bool** | True if the document contains drivers license numbers. | [optional] [default to null]
**ContainsSocialSecurityNumber** | **bool** | True if the document contains social security numbers. | [optional] [default to null]
**ContainsTaxpayerID** | **bool** | True if the document contains taxpayer IDs. | [optional] [default to null]
**ContainsCreditCardNumber** | **bool** | True if the document contains credit card numbers. | [optional] [default to null]
**ContainsCreditCardExpirationDate** | **bool** | True if the document contains credit card expiration dates. | [optional] [default to null]
**ContainsCreditCardVerificationCode** | **bool** | True if the document contains credit card verification codes. | [optional] [default to null]
**ContainsBankAccountNumber** | **bool** | True if the document contains bank account numbers. | [optional] [default to null]
**ContainsIBAN** | **bool** | True if the document contains IBANs. | [optional] [default to null]
**ContainsHealthInsuranceNumber** | **bool** | True if the document contains health insurance numbers. | [optional] [default to null]
**ContainsBearerToken** | **bool** | True if the document contains bearer tokens. | [optional] [default to null]
**ContainsHttpCookie** | **bool** | True if the document contains HTTP cookies. | [optional] [default to null]
**ContainsPrivateKeys** | **bool** | True if the document contains private keys. | [optional] [default to null]
**ContainsCredentials** | **bool** | True if the document contains credentials (usernames/passwords). | [optional] [default to null]
**ContainsDeepWebUrls** | **bool** | True if the document contains deep web URLs (.onion). | [optional] [default to null]
**ContainsSourceCode** | **bool** | True if the document contains source code. | [optional] [default to null]
**ContainsIpAddress** | **bool** | True if the document contains IP addresses. | [optional] [default to null]
**ContainsMacAddress** | **bool** | True if the document contains MAC addresses. | [optional] [default to null]
**PagesRedacted** | [**[]RedactedPageInfo**](RedactedPageInfo.md) | List of pages that were redacted (had PII regions blurred). | [optional] [default to null]

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


