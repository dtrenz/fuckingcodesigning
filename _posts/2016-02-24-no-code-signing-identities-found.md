---
layout: post
title:  "\"No Code Signing Identities Found\""
categories: identities
---

__This is just a sample post. The goal of this site is not to simply repost
Apple docs, don't worry.__

From [Apple](https://developer.apple.com/library/ios/documentation/IDEs/Conceptual/AppDistributionGuide/Troubleshooting/Troubleshooting.html#//apple_ref/doc/uid/TP40012582-CH5-SW2):

>Xcode detects when you’re missing a signing identity. Typically, this happens
when you move from one Mac to another. Follow the steps in Creating the Team
Provisioning Profile to create your signing identity and add it to the team
provisioning profile. You’ll have the option of importing your signing identity
from another Mac or resetting it. If you use a custom development provisioning
profile that you manage yourself, it becomes invalid after revoking the
development certificate. Read Editing Provisioning Profiles in Member Center to
regenerate it.
>
>To avoid this problem, export your certificates as a developer profile file on
the other Mac, and then import them on your new Mac, as described in Exporting
and Importing Certificates and Profiles.
