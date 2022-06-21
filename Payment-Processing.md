# Payment Processing

![img](https://homebusinessmag.com/wp-content/uploads/2017/01/authorizing.jpg)


## Authorize.net

An integration for payment processing in .NET framework, 


## Features
1. Mobile device authentication.
2. EMV & non EMV transaction processing.
3. Customer Email receipt
4. Transaction reporting.


# UI

1. Background Color
2. Text Font Color
3. Button Font Color
4. Button Background Color
5. Banner Image
6. Banner Background Color
7. Background Image


## Creating payment profile object

```

CustomerPaymentProfileType *customerPaymentProfile = [CustomerPaymentProfileType customerPaymentProfileType];
        
CustomerAddressType *address =  [CustomerAddressType customerAddressType];

address.firstName = @"firstName";

address.lastName = @"lastName";

address.city = @"Amman";

address.state = @"Amman";

address.country = @"Jordan";

address.zip = @"21051";

address.company = @"LTUC";

address.phoneNumber = @"02014585485";

address.address = @"street"; 

address.faxNumber = @"654198416";

customerPaymentProfile.billTo = address;
```
