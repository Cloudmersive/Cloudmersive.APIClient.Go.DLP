# DlpAdvancedDetectionResponse

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CleanResult** | **bool** | True if no disallowed PII or sensitive data types were detected in the input text; false if any disallowed type was found. | [optional] [default to null]
**ContainsEmailAddress** | **bool** | True if the input text contains email addresses. | [optional] [default to null]
**ContainsPhoneNumber** | **bool** | True if the input text contains phone numbers. | [optional] [default to null]
**ContainsStreetAddress** | **bool** | True if the input text contains street addresses. | [optional] [default to null]
**ContainsPersonName** | **bool** | True if the input text contains person names. | [optional] [default to null]
**ContainsBirthDate** | **bool** | True if the input text contains birth dates. | [optional] [default to null]
**ContainsPassportNumber** | **bool** | True if the input text contains passport numbers. | [optional] [default to null]
**ContainsDriversLicense** | **bool** | True if the input text contains drivers license numbers. | [optional] [default to null]
**ContainsSocialSecurityNumber** | **bool** | True if the input text contains social security numbers. | [optional] [default to null]
**ContainsTaxpayerID** | **bool** | True if the input text contains taxpayer IDs. | [optional] [default to null]
**ContainsCreditCardNumber** | **bool** | True if the input text contains credit card numbers. | [optional] [default to null]
**ContainsCreditCardExpirationDate** | **bool** | True if the input text contains credit card expiration dates. | [optional] [default to null]
**ContainsCreditCardVerificationCode** | **bool** | True if the input text contains credit card verification codes. | [optional] [default to null]
**ContainsBankAccountNumber** | **bool** | True if the input text contains bank account numbers. | [optional] [default to null]
**ContainsIBAN** | **bool** | True if the input text contains IBANs. | [optional] [default to null]
**ContainsHealthInsuranceNumber** | **bool** | True if the input text contains health insurance numbers. | [optional] [default to null]
**ContainsBearerToken** | **bool** | True if the input text contains bearer tokens. | [optional] [default to null]
**ContainsHttpCookie** | **bool** | True if the input text contains HTTP cookies. | [optional] [default to null]
**ContainsPrivateKeys** | **bool** | True if the input text contains private keys. | [optional] [default to null]
**ContainsCredentials** | **bool** | True if the input text contains credentials (usernames/passwords). | [optional] [default to null]
**ContainsDeepWebUrls** | **bool** | True if the input text contains deep web URLs (.onion). | [optional] [default to null]
**ContainsSourceCode** | **bool** | True if the input text contains source code. | [optional] [default to null]
**ContainsIpAddress** | **bool** | True if the input text contains IP addresses. | [optional] [default to null]
**ContainsMacAddress** | **bool** | True if the input text contains MAC addresses. | [optional] [default to null]
**ContainsHealthInsuranceMemberID** | **bool** | True if the input text contains health insurance member IDs. | [optional] [default to null]
**ContainsHealthInjuryOrDisease** | **bool** | True if the input text contains references to injuries or diseases. | [optional] [default to null]
**ContainsHealthTypeOfTreatment** | **bool** | True if the input text contains references to types of medical treatment. | [optional] [default to null]
**ContainsHealthDateAndTimeOfTreatment** | **bool** | True if the input text contains dates and times of medical treatment. | [optional] [default to null]
**ContainsHealthPlanBeneficiaryNumber** | **bool** | True if the input text contains health plan beneficiary numbers. | [optional] [default to null]
**ContainsHealthPaymentsMadeForTreatment** | **bool** | True if the input text contains payments made for medical treatment. | [optional] [default to null]
**ContainsFaces** | **bool** | True if the document contains identifiable human faces. | [optional] [default to null]
**ContainsVehicleID** | **bool** | True if the input contains vehicle identifiers (e.g. license plates, VINs). | [optional] [default to null]
**ContainsDeviceID** | **bool** | True if the input contains device identifiers (e.g. serial numbers, IMEIs, MAC-level device IDs). | [optional] [default to null]
**ContainsNamesOfRelatives** | **bool** | True if the input contains names of relatives. | [optional] [default to null]
**ContainsHealthUniversalRecordLocator** | **bool** | True if the input contains health universal record locators (URLs). | [optional] [default to null]
**ContainsBiometrics** | **bool** | True if the input contains biometric data references (e.g. fingerprints, retinal scans, voiceprints). | [optional] [default to null]
**AnalysisRationale** | **string** | Rationale for why the conclusion was formed. Only populated when ProvideAnalysisRationale is set to true in the request. | [optional] [default to null]

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


