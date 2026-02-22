# DlpAdvancedDocumentRedactionRequest

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**InputFile** | **string** | Document file bytes (PDF, DOCX, PNG, or JPG) to scan for PII and redact. | [optional] [default to null]
**FileName** | **string** | Optional. Name of the input file including extension, used for format detection. If not provided, format is detected from file contents. | [optional] [default to null]
**RecognitionMode** | **string** | Optional. Recognition mode for image processing. Options: null (default), \&quot;Fast\&quot;, \&quot;FastPlus\&quot;, \&quot;FastMini\&quot;. | [optional] [default to null]
**RedactionMode** | **string** | Redaction mode for PII regions. Options: \&quot;BlackOut\&quot; (default) draws black rectangles over PII rows, \&quot;Blur\&quot; applies Gaussian blur to PII rows, \&quot;BlackOutEntirePage\&quot; blacks out entire dirty pages, \&quot;BlurEntirePage\&quot; blurs entire dirty pages. | [optional] [default to null]
**AllowEmailAddress** | **bool** | Set to true to allow email addresses in the document and not redact them. | [optional] [default to null]
**AllowPhoneNumber** | **bool** | Set to true to allow phone numbers in the document and not redact them. | [optional] [default to null]
**AllowStreetAddress** | **bool** | Set to true to allow street addresses in the document and not redact them. | [optional] [default to null]
**AllowPersonName** | **bool** | Set to true to allow person names in the document and not redact them. | [optional] [default to null]
**AllowBirthDate** | **bool** | Set to true to allow birth dates in the document and not redact them. | [optional] [default to null]
**AllowPassportNumber** | **bool** | Set to true to allow passport numbers in the document and not redact them. | [optional] [default to null]
**AllowDriversLicense** | **bool** | Set to true to allow drivers license numbers in the document and not redact them. | [optional] [default to null]
**AllowSocialSecurityNumber** | **bool** | Set to true to allow social security numbers in the document and not redact them. | [optional] [default to null]
**AllowTaxpayerID** | **bool** | Set to true to allow taxpayer IDs in the document and not redact them. | [optional] [default to null]
**AllowCreditCardNumber** | **bool** | Set to true to allow credit card numbers in the document and not redact them. | [optional] [default to null]
**AllowCreditCardExpirationDate** | **bool** | Set to true to allow credit card expiration dates in the document and not redact them. | [optional] [default to null]
**AllowCreditCardVerificationCode** | **bool** | Set to true to allow credit card verification codes in the document and not redact them. | [optional] [default to null]
**AllowBankAccountNumber** | **bool** | Set to true to allow bank account numbers in the document and not redact them. | [optional] [default to null]
**AllowIBAN** | **bool** | Set to true to allow IBANs in the document and not redact them. | [optional] [default to null]
**AllowHealthInsuranceNumber** | **bool** | Set to true to allow health insurance numbers in the document and not redact them. | [optional] [default to null]
**AllowBearerToken** | **bool** | Set to true to allow bearer tokens in the document and not redact them. | [optional] [default to null]
**AllowHttpCookie** | **bool** | Set to true to allow HTTP cookies in the document and not redact them. | [optional] [default to null]
**AllowPrivateKeys** | **bool** | Set to true to allow private keys in the document and not redact them. | [optional] [default to null]
**AllowCredentials** | **bool** | Set to true to allow credentials (usernames/passwords) in the document and not redact them. | [optional] [default to null]
**AllowDeepWebUrls** | **bool** | Set to true to allow deep web URLs (.onion) in the document and not redact them. | [optional] [default to null]
**AllowSourceCode** | **bool** | Set to true to allow source code in the document and not redact it. | [optional] [default to null]
**AllowIpAddress** | **bool** | Set to true to allow IP addresses in the document and not redact them. | [optional] [default to null]
**AllowMacAddress** | **bool** | Set to true to allow MAC addresses in the document and not redact them. | [optional] [default to null]
**AllowHealthInsuranceMemberID** | **bool** | Set to true to allow health insurance member IDs in the document and not redact them. | [optional] [default to null]
**AllowHealthInjuryOrDisease** | **bool** | Set to true to allow references to injuries or diseases in the document and not redact them. | [optional] [default to null]
**AllowHealthTypeOfTreatment** | **bool** | Set to true to allow references to types of medical treatment in the document and not redact them. | [optional] [default to null]
**AllowHealthDateAndTimeOfTreatment** | **bool** | Set to true to allow dates and times of medical treatment in the document and not redact them. | [optional] [default to null]
**AllowHealthPlanBeneficiaryNumber** | **bool** | Set to true to allow health plan beneficiary numbers in the document and not redact them. | [optional] [default to null]
**AllowHealthPaymentsMadeForTreatment** | **bool** | Set to true to allow payments made for medical treatment in the document and not redact them. | [optional] [default to null]
**AllowFaces** | **bool** | Set to true to allow identifiable human faces in the document and not redact them. | [optional] [default to null]
**AllowVehicleID** | **bool** | Set to true to allow vehicle identifiers (e.g. license plates, VINs) in the document and not redact them. | [optional] [default to null]
**AllowDeviceID** | **bool** | Set to true to allow device identifiers (e.g. serial numbers, IMEIs, MAC-level device IDs) in the document and not redact them. | [optional] [default to null]
**AllowNamesOfRelatives** | **bool** | Set to true to allow names of relatives in the document and not redact them. | [optional] [default to null]
**AllowHealthUniversalRecordLocator** | **bool** | Set to true to allow health universal record locators (URLs) in the document and not redact them. | [optional] [default to null]
**AllowBiometrics** | **bool** | Set to true to allow biometric data references (e.g. fingerprints, retinal scans, voiceprints) in the document and not redact them. | [optional] [default to null]
**ProvideAnalysisRationale** | **bool** | Set to true to include a natural language rationale explaining why each detection conclusion was formed. | [optional] [default to null]

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


