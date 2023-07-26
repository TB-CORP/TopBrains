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
| Code  | Brand      |
| :---: | :--------- |
| 0---- | common     |
| 1---- | top-brains |

### TopBrains
| Code  | Resource          |
| :---: | :---------------- |
| 10--- | common            |
| 11--- | auth-source       |
| 12--- | role              |
| 13--- | permission        |
| 14--- | status            |
| 15--- | attachment-type   |
| 16--- | delivery-type     |
| 17--- | subscription-type |
#### Auth Source
| Code  | Indicator    |
| :---: | :----------- |
| 11001 | phone-number |
| 11002 | google       |
| 11003 | facebook     |
#### Role
| Code  | Indicator |
| :---: | :-------- |
| 12001 | student   |
| 12002 | author    |
| 12003 | manager   |
| 12004 | admin     |
#### Permission
| Code  | Indicator                                           |
| :---: | :-------------------------------------------------- |
| 13001 | tb-sh-ra/user/user/get                              |
| 13002 | tb-sh-ra/user/user/delete                           |
| 13003 | tb-sh-ra/user/user/update                           |
| 13004 | tb-sh-ra/user/access-token/refresh                  |
| 13005 | tb-sh-ra/user/feedback/add                          |
| 13006 | tb-sh-ra/user/user-promo-code/list                  |
| 13007 | tb-sh-ra/user/user-promo-code/submit                |
| 13008 | tb-sh-ra/user/user-promo-code/get                   |
| 13009 | tb-sh-ra/user/user-course/enroll                    |
| 13010 | tb-sh-ra/user/user-course/list                      |
| 13011 | tb-sh-ra/user/user-course/get                       |
| 13012 | tb-sh-ra/user/user-lesson/interact                  |
| 13013 | tb-sh-ra/user/user-lesson/get                       |
| 13014 | tb-sh-ra/user/user-lesson/list                      |
| 13015 | tb-sh-ra/user/user-lesson-comment/reply-get         |
| 13016 | tb-sh-ra/user/user-lesson-comment/reply-list        |
| 13017 | tb-sh-ra/user/user-lesson-comment/delete            |
| 13018 | tb-sh-ra/user/user-lesson-comment/edit              |
| 13019 | tb-sh-ra/user/user-lesson-comment/add               |
| 13020 | tb-sh-ra/user/user-lesson-comment/get               |
| 13021 | tb-sh-ra/user/user-lesson-comment/list              |
| 13022 | tb-sh-ra/user/user-subscription/cancel              |
| 13023 | tb-sh-ra/user/user-subscription/list                |
| 13024 | tb-sh-ra/user/user-subscription/get                 |
| 13025 | tb-sh-ra/user/user-auth-source/phone-number-sign-up |
| 13026 | tb-sh-ra/user/user-auth-source/google-auth          |
| 13027 | tb-sh-ra/user/user-auth-source/facebook-auth        |
| 13028 | tb-sh-ra/user/user-auth-source/log-out              |
| 13029 | tb-sh-ra/user/user-auth-source/phone-number-reset   |
| 13030 | tb-sh-ra/user/user-auth-source/phone-number-log-in  |
| 13031 | tb-sh-ra/course/course/list                         |
| 13032 | tb-sh-ra/course/course/get                          |
| 13033 | tb-sh-ra/course/chapter/get                         |
| 13034 | tb-sh-ra/course/chapter/list                        |
| 13035 | tb-sh-ra/course/lesson/list                         |
| 13036 | tb-sh-ra/course/lesson/get                          |
| 13037 | tb-sh-ra/course/lesson-attachment/get               |
| 13038 | tb-sh-ra/course/lesson-attachment/list              |
| 13039 | tb-sh-ra/subscription/subscription/list             |
| 13040 | tb-sh-ra/subscription/subscription/get              |
| 13041 | tb-sh-ra/subscription/course-subscription/get       |
| 13042 | tb-sh-ra/subscription/course-subscription/list      |
| 13043 | tb-sh-ra/payment/payment-log/click-complete         |
| 13044 | tb-sh-ra/payment/payment-log/purchase               |
| 13045 | tb-sh-ra/payment/payment-log/payme                  |
| 13046 | tb-sh-ra/payment/payment-log/click-prepare          |
| 13047 | tb-sh-ra/lookup/language/get                        |
| 13048 | tb-sh-ra/lookup/language/list                       |
| 13049 | tb-sh-ra/lookup/currency/get                        |
| 13050 | tb-sh-ra/lookup/currency/list                       |
#### Status
| Code  | Indicator  |
| :---: | :--------- |
| 14001 | active     |
| 14002 | inactive   |
| 14003 | deleted    |
| 14004 | failed     |
| 14005 | validating |
| 14006 | completing |
| 14007 | denied     |
| 14008 | processing |
#### Attachment Type
| Code  | Indicator     |
| :---: | :------------ |
| 15001 | internal-link |
| 15002 | external-link |
| 15003 | pdf-document  |
#### Delivery Type
| Code  | Indicator |
| :---: | :-------- |
| 16... | ...       |
#### Subscription Type
| Code  | Indicator    |
| :---: | :----------- |
| 17001 | semiannual   |
| 17002 | annual       |
| 17003 | per-resource |

## See also
- [Common terms](./common-terms.md)

#knowledge-base