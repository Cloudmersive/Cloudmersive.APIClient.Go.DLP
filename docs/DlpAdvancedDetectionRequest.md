# DlpAdvancedDetectionRequest

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**InputText** | **string** | Text to scan for PII and sensitive data. | [optional] [default to null]
**AllowEmailAddress** | **bool** | Set to true to allow email addresses in the input text and not flag them as PII. | [optional] [default to null]
**AllowPhoneNumber** | **bool** | Set to true to allow phone numbers in the input text and not flag them as PII. | [optional] [default to null]
**AllowStreetAddress** | **bool** | Set to true to allow street addresses in the input text and not flag them as PII. | [optional] [default to null]
**AllowPersonName** | **bool** | Set to true to allow person names in the input text and not flag them as PII. | [optional] [default to null]
**AllowBirthDate** | **bool** | Set to true to allow birth dates in the input text and not flag them as PII. | [optional] [default to null]
**AllowPassportNumber** | **bool** | Set to true to allow passport numbers in the input text and not flag them as PII. | [optional] [default to null]
**AllowDriversLicense** | **bool** | Set to true to allow drivers license numbers in the input text and not flag them as PII. | [optional] [default to null]
**AllowSocialSecurityNumber** | **bool** | Set to true to allow social security numbers in the input text and not flag them as PII. | [optional] [default to null]
**AllowTaxpayerID** | **bool** | Set to true to allow taxpayer IDs in the input text and not flag them as PII. | [optional] [default to null]
**AllowCreditCardNumber** | **bool** | Set to true to allow credit card numbers in the input text and not flag them as PII. | [optional] [default to null]
**AllowCreditCardExpirationDate** | **bool** | Set to true to allow credit card expiration dates in the input text and not flag them as PII. | [optional] [default to null]
**AllowCreditCardVerificationCode** | **bool** | Set to true to allow credit card verification codes in the input text and not flag them as PII. | [optional] [default to null]
**AllowBankAccountNumber** | **bool** | Set to true to allow bank account numbers in the input text and not flag them as PII. | [optional] [default to null]
**AllowIBAN** | **bool** | Set to true to allow IBANs in the input text and not flag them as PII. | [optional] [default to null]
**AllowHealthInsuranceNumber** | **bool** | Set to true to allow health insurance numbers in the input text and not flag them as PII. | [optional] [default to null]
**AllowBearerToken** | **bool** | Set to true to allow bearer tokens in the input text and not flag them as PII. | [optional] [default to null]
**AllowHttpCookie** | **bool** | Set to true to allow HTTP cookies in the input text and not flag them as PII. | [optional] [default to null]
**AllowPrivateKeys** | **bool** | Set to true to allow private keys in the input text and not flag them as PII. | [optional] [default to null]
**AllowCredentials** | **bool** | Set to true to allow credentials (usernames/passwords) in the input text and not flag them as PII. | [optional] [default to null]
**AllowDeepWebUrls** | **bool** | Set to true to allow deep web URLs (.onion) in the input text and not flag them as PII. | [optional] [default to null]
**AllowSourceCode** | **bool** | Set to true to allow source code in the input text and not flag it as sensitive data. | [optional] [default to null]
**AllowIpAddress** | **bool** | Set to true to allow IP addresses in the input text and not flag them as PII. | [optional] [default to null]
**AllowMacAddress** | **bool** | Set to true to allow MAC addresses in the input text and not flag them as PII. | [optional] [default to null]
**AllowHealthInsuranceMemberID** | **bool** | Set to true to allow health insurance member IDs in the input text and not flag them as PHI. | [optional] [default to null]
**AllowHealthInjuryOrDisease** | **bool** | Set to true to allow references to injuries or diseases in the input text and not flag them as PHI. | [optional] [default to null]
**AllowHealthTypeOfTreatment** | **bool** | Set to true to allow references to types of medical treatment in the input text and not flag them as PHI. | [optional] [default to null]
**AllowHealthDateAndTimeOfTreatment** | **bool** | Set to true to allow dates and times of medical treatment in the input text and not flag them as PHI. | [optional] [default to null]
**AllowHealthPlanBeneficiaryNumber** | **bool** | Set to true to allow health plan beneficiary numbers in the input text and not flag them as PHI. | [optional] [default to null]
**AllowHealthPaymentsMadeForTreatment** | **bool** | Set to true to allow payments made for medical treatment in the input text and not flag them as PHI. | [optional] [default to null]
**AllowVehicleID** | **bool** | Set to true to allow vehicle identifiers (e.g. license plates, VINs) in the input text and not flag them as PII. | [optional] [default to null]
**AllowDeviceID** | **bool** | Set to true to allow device identifiers (e.g. serial numbers, IMEIs, MAC-level device IDs) in the input text and not flag them as PII. | [optional] [default to null]
**AllowNamesOfRelatives** | **bool** | Set to true to allow names of relatives in the input text and not flag them as PII. | [optional] [default to null]
**AllowHealthUniversalRecordLocator** | **bool** | Set to true to allow health universal record locators (URLs) in the input text and not flag them as PHI. | [optional] [default to null]
**AllowBiometrics** | **bool** | Set to true to allow biometric data references (e.g. fingerprints, retinal scans, voiceprints) in the input text and not flag them as PII. | [optional] [default to null]
**ProvideAnalysisRationale** | **bool** | Set to true to include a natural language rationale explaining why each detection conclusion was formed. | [optional] [default to null]

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


