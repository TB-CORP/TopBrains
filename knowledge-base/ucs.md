# Unified Code System (UCS)
UCS (Unified Code System) are codes. A code is a unique state indicator of a certain resource in a certain brand. There is no a single purpose of using codes, UCS may include codes for various of purposes.

---

## Contents
- [Introduction](#unified-code-system-ucs)
- [Code anatomy](#code-anatomy)
- [Brands](#brands)
- [See also](#see-also)

---

## Code anatomy
Each code is 5 digit number, which are divided in 3 parts to identify the code meaning.
```
Code:
12345

Parts:
1   Brand
2   Resource
345  Indicator
```
When pronounce a code, each of its parts should be pronounced separately. In example, `12345` (one, two, thirty-four). In case of indicator containing `0`, `12001` (one, two, oh oh one).

## Brands
| Code  | Brand     |
| :---: | :-------- |
| 0---- | Common    |
| 1---- | TopBrains |

### TopBrains
| Code  | Resource          |
| :---: | :---------------- |
| 10--- | Common            |
| 11--- | Auth source       |
| 12--- | Role              |
| 13--- | Permission        |
| 14--- | Status            |
| 15--- | Attachment type   |
| 16--- | Delivery type     |
| 17--- | Subscription type |
#### Auth Source
| Code  | Indicator    |
| :---: | :----------- |
| 11001 | Phone number |
| 11002 | Google       |
| 11003 | Facebook     |
#### Role
| Code  | Indicator |
| :---: | :-------- |
| 12001 | Student   |
| 12002 | Author    |
| 12003 | Manager   |
| 12004 | Admin     |
#### Permission
| Code  | Indicator |
| :---: | :-------- |
| 13... | ...       |
#### Status
| Code  | Indicator      |
| :---: | :------------- |
| 14001 | Active         |
| 14002 | Inactive       |
| 14003 | Deleted        |
| 14004 | Failed         |
| 14005 | Validating     |
| 14006 | Completing     |
| 14007 | Not subscribed |
| 14008 | Uploading      |
| 14009 | Uploaded       |
| 14010 | Proceeding     |
#### Attachment Type
| Code  | Indicator     |
| :---: | :------------ |
| 15001 | Internal link |
| 15002 | External link |
| 15003 | PDF document  |
#### Delivery Type
| Code  | Indicator |
| :---: | :-------- |
| 16... | ...       |
#### Subscription Type
| Code  | Indicator    |
| :---: | :----------- |
| 17001 | Semiannual   |
| 17002 | Annual       |
| 17003 | Per resource |

## See also
- [Common terms](./common-terms.md)

#knowledge-base