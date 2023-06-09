---
description: These restrictions ONLY apply to free/normal apple accounts
---

# Restrictions

## 3 App Limit

This limit is imposed by iOS and makes it, so apps installed with a normal apple account to your phone can only have a max of three active apps _including_ the Scarlet app.

## Expiration

Apps will expire 7 days after their registration, the expiration can be viewed in Scarlet by clicking the icon of the app you want to view the expiration for. You'll also see a refresh button to bring back the days to 7 days.



This restriction is imposed by the mobileprovision which is required for app installs, these files are signed by apple with the certificate created with it so the **expiration can't be bypassed or modified.**

## Anisette

Anisette is a somewhat unknown (specifically how they are generated) cryptography by Apple which is required for a majority of the login process with your account. Currently ScarletCloud uses an anisette server with some built-in techniques to go against the [-36607 error](36607-anisette-abuse.md).
