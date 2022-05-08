# Roles, Claims, Tokens

![img](https://i.ytimg.com/vi/cbtK3U2aOlg/maxresdefault.jpg)

<br><hr>

## Claim based authorization

Claim based authorization is used to check the value of a claim and allows access to resources based on the value of the claim.
Like checking birthday for selling cigarettes, you must be +18 years old to buy them.

<br><hr>

## Authentication vs Authorization

Authentication: Identifying who the user is.
Authorization: What's this user allowed to access or do.

<br><hr>

## JSON web Token (JWT)

The process of encoding JSON files and using them as keys to have access.

a JTW consists of:
1. Header: the algorithm used to understand the file.
2. Payload: contains data related to tokens.
3. Signature: The result of adding the Header & Payload & encrypting them using Base64URL.








