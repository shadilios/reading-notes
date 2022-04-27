# Identity / Authentication

![img](https://camo.githubusercontent.com/0427d39b818259cdea3e5a3320f50e13d4b3e9e0cccd900958add737b09920d7/68747470733a2f2f636873616b656c6c2e66696c65732e776f726470726573732e636f6d2f323031382f30342f6173706e65742d636f72652d6964656e746974792d31332e706e67)

## ASP.NET Identity

It's an API that supports user interface login functionality to manage users, passwords & email confirmations & more.

* It uses SQL databases to save passwords & Profiles.
* It can also use an extrenal source of tables to save those datas.



## Claims

* Represents a single fact about the user (Exmaple: First Name, Email, number).
* It represents the claim class in ASP.NET which holds a constructor that contains the Type & Value for each Claim.



## Claims Identity

* Represents a way to confirm your identity in ASP.NET.
* Each Claim Identity holds many claims.



## Claim Principal

* Represents the user as a whole.
* Can Contain multiple Claim Identities.


## Verbs

The commands that can be used in Identity, which are:

    1. Authenticate
    2. Challenge
    3. SignIn
    4. SignOut
    5. Forbid




