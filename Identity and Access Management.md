# IAM

## Create Groups

Create groups of users. Users could be in multiple groups. However, cannot create a group within another one
## IAM Policies Structure

- Version
- Id: for the policy
- Statement
- Sid
- Effect
- Principal

## IAM Multi Factor Authentication

- Password Policy
  - Minimum length
  - Requrie specific char types
  - Password expiration

You want to protect Root Accounts and IAM users by MFA

MFA = password you know + security device you own (physical device).

**MFA devices options**

- Virtual MFA Device: Google authenticator, Authy
- Universal 2nd Factor security key: YubiKey
- Hardware key fob MFA device

## AWS CLI

Access aws with command line. There is also another tool called TerraForm.