# DlpRedactionResponse

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**RedactedText** | **string** | The redacted text with PII removed or replaced, or the original text if no disallowed PII was found. | [optional] [default to null]
**CleanResult** | **bool** | True if no disallowed PII or sensitive data types were detected; false if any disallowed type was found and redacted. | [optional] [default to null]
**ContainsEmailAddress** | **bool** | True if the input contains email addresses. | [optional] [default to null]
**ContainsPhoneNumber** | **bool** | True if the input contains phone numbers. | [optional] [default to null]
**ContainsStreetAddress** | **bool** | True if the input contains street addresses. | [optional] [default to null]
**ContainsPersonName** | **bool** | True if the input contains person names. | [optional] [default to null]
**ContainsBirthDate** | **bool** | True if the input contains birth dates. | [optional] [default to null]
**ContainsPassportNumber** | **bool** | True if the input contains passport numbers. | [optional] [default to null]
**ContainsDriversLicense** | **bool** | True if the input contains drivers license numbers. | [optional] [default to null]
**ContainsSocialSecurityNumber** | **bool** | True if the input contains social security numbers. | [optional] [default to null]
**ContainsTaxpayerID** | **bool** | True if the input contains taxpayer IDs. | [optional] [default to null]
**ContainsCreditCardNumber** | **bool** | True if the input contains credit card numbers. | [optional] [default to null]
**ContainsCreditCardExpirationDate** | **bool** | True if the input contains credit card expiration dates. | [optional] [default to null]
**ContainsCreditCardVerificationCode** | **bool** | True if the input contains credit card verification codes. | [optional] [default to null]
**ContainsBankAccountNumber** | **bool** | True if the input contains bank account numbers. | [optional] [default to null]
**ContainsIBAN** | **bool** | True if the input contains IBANs. | [optional] [default to null]
**ContainsHealthInsuranceNumber** | **bool** | True if the input contains health insurance numbers. | [optional] [default to null]
**ContainsBearerToken** | **bool** | True if the input contains bearer tokens. | [optional] [default to null]
**ContainsHttpCookie** | **bool** | True if the input contains HTTP cookies. | [optional] [default to null]
**ContainsPrivateKeys** | **bool** | True if the input contains private keys. | [optional] [default to null]
**ContainsCredentials** | **bool** | True if the input contains credentials (usernames/passwords). | [optional] [default to null]
**ContainsDeepWebUrls** | **bool** | True if the input contains deep web URLs (.onion). | [optional] [default to null]
**ContainsSourceCode** | **bool** | True if the input contains source code. | [optional] [default to null]
**ContainsIpAddress** | **bool** | True if the input contains IP addresses. | [optional] [default to null]
**ContainsMacAddress** | **bool** | True if the input contains MAC addresses. | [optional] [default to null]

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


