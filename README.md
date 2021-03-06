![validation-master-logo](https://i.ibb.co/Htjd9kY/logo.png)

> validation-master is a tiny module which provides lots of validation methods.Currently, It has 17 methods which are mentioned below.

|Method|Description|
|----|-----|
|pincodeValidator|Validates pincode number and returns a boolean value.|
|birthYearValidator|Validates birth year and returns a boolean value.|
|phoneNumberValidator|Validates phone number and returns a boolean value.|
|panCardValidator|Validates pancard number and returns a boolean value.|
|drivingLicenseValidator|Validates driving license number and returns a boolean value.|
|aadharCardValidator|Validates aadhaar card number and returns a boolean value.|
|emailValidator|Validates email address and returns a boolean value.|
|isAlphabetic|Checks if string is alphabetic and returns a boolean value.|
|isNumeric|Checks if string is numeric and returns a boolean value.|
|isAlphaNumeric|Checks if string is alphanumeric and returns a boolean value.|
|isValidDate|Checks if date is in valid format and returns an array containing boolean value and date.If you pass true in third parameter isBoolean then it will return an array containing boolean value and a date with ISO format|
|isFutureDate|Checks if date is future date and returns boolean value.|
|isPastDate|Checks if date is past date and returns boolean value.|
|isCurrentDate|Checks if date is current date and returns boolean value.|
|isEighteenPlus|Checks if age is eighteen plus and returns an array containing boolean value and age.|
|isEmpty|Checks if string is empty string and returns boolean value.|
|isURL|Checks if string is url and returns boolean value.|

### pincodeValidator

Validates pincode number and returns a boolean value.

_Example_

```
const pincode = "Your_Area_Pincode"
console.log(pincodeValidator(pincode))
```

### birthYearValidator

Validates birth year and returns a boolean value.

_Example_

```
const birthYear = "Your_Birth_Year"
console.log(birthYearValidator(birthYear))
```

### phoneNumberValidator

Validates phone number and returns a boolean value.

_Example_

```
const phoneNumber = "Your_Phone_Number"
console.log(phoneNumberValidator(phoneNumber))
```

### panCardValidator

Validates pancard number and returns a boolean value.

_Example_

```
const pancardNumber = "Your_Pancard_Number"
console.log(panCardValidator(pancardNumber))
```

### drivingLicenseValidator

Validates driving license number and returns a boolean value.

_Example_

```
const drivingLicenseNumber = "Your_Driving_License_Number"
console.log(drivingLicenseValidator(drivingLicenseNumber))
```

### aadharCardValidator

Validates aadhaar card number and returns a boolean value.

_Example_

```
const aadhaarCardNumber = "Your_Aadhaar_Card_Number"
console.log(aadharCardValidator(aadhaarCardNumber))
```

### emailValidator

Validates email address and returns a boolean value.

_Example_

```
const emailAddress = "Your_Email_Address"
console.log(emailValidator(emailAddress))
```

### isAlphabetic

Checks if string is alphabetic and returns a boolean value.

_Example_

```
const customString = "xyz"
console.log(isAlphabetic(customString))
```

### isNumeric

Checks if string is numeric and returns a boolean value.

_Example_

```
const customString = "123"
console.log(isNumeric(customString))
```

### isAlphaNumeric

Checks if string is alphanumeric and returns a boolean value.

_Example_

```
const customString = "xyz123"
console.log(isAlphaNumeric(customString))
```

### isValidDate

Checks if date is in valid format and returns an array containing boolean value and date.<br />
It also corrects date and month if it is entered in single digit.<br />
Supported Date Formats -> DD-MM-YYYY, DD/MM/YYYY, DD.MM.YYYY<br />
If you pass true in third parameter isBoolean then it will return an array containing boolean value and a date with ISO format (YYYY-MM-DD).

_Example_

```
const date = "01-07-2021"
console.log(isValidDate(date, "-", false))
```

### isFutureDate

Checks if date is future date and returns boolean value.

_Example_

```
const date = "02-07-2021"
console.log(isFutureDate(date))
```

### isPastDate

Checks if date is past date and returns boolean value.

_Example_

```
const date = "30-06-2021"
console.log(isPastDate(date))
```

### isCurrentDate

Checks if date is current date and returns boolean value.

_Example_

```
const date = "30-06-2021"
console.log(isCurrentDate(date))
```

### isEighteenPlus

Checks if age is eighteen plus and returns an array containing boolean value and age.

_Example_

```
const date = "01-01-2003"
console.log(isEighteenPlus(date, "-"))
```

### isEmpty

Checks if string is empty string and returns boolean value.

_Example_

```
const string = ""
console.log(isEmpty(string))
```

### isURL

Checks if string is url and returns boolean value.

_Example_

```
const url = "https://www.google.com"
console.log(isURL(url))
```