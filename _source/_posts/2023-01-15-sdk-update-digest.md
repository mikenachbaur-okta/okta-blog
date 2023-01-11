---
layout: blog_post
title: "SDK Update Digest for January, 2023"
author: mike-nachbaur
by: internal-contributor
communities: []
description: "In this first of a monthly series we'll be discussing the changes and updates to our public SDKs."
tags: []
tweets:
---

At Okta we build and support a number of SDKs that help developers closely integrate with our platform, and to solve real-world problems. But what happens after you've integrated with our tools? We continue to innovate, add features, fix bugs, and generally improve our SDKs, but unless you check back often, it might be difficult to keep up-to-date on these improvements.

Starting with this post we're beginning a monthly digest of updates to our SDKs, highlighting important changes, and giving guidance on things that matter most to you. Since this is the first in our series, we'll cover more ground than we normally would, to provide a recap of the major updates from the past quarter.

If you would like to receive these updates in the future, feel free to subscribe to our email digest, which will be released along with future digest updates. **TBD**

{% include toc.md %}

## Workforce Identity Cloud [WIC)

### Backend SDKs

### Client SDKs

#### okta-idx-swift

The most impactful update through these releases was the introduction of support for the "Device Token" cookie, which enables MFA policies to "Remember this device", allowing multi-factor verification steps to be skipped on subsequent sign ins. Additionally, user profile information was introduced to the User object, providing more context to the user being signed in.

The rest of these updates were related to bumping the upstream [okta-mobile-swift](#okta-mobile-swift] dependency versions, or improving the sample application.

* Feature improvements
  * [3.0.2](https://github.com/okta/okta-idx-swift/releases/tag/3.0.2)
  * [3.0.3](https://github.com/okta/okta-idx-swift/releases/tag/3.0.3)
  * [3.0.5](https://github.com/okta/okta-idx-swift/releases/tag/3.0.5)
* Dependency updates
  * [3.0.4](https://github.com/okta/okta-idx-swift/releases/tag/3.0.4)
* Bug fixes
  * [3.0.6](https://github.com/okta/okta-idx-swift/releases/tag/3.0.6)

#### okta-mobile-swift

Some releases were made to [okta-mobile-swift](https://github.com/okta/okta-mobile-swift) to improve token refresh handling and when tokens are stored within the keychain. Additional features were added to make downstream SDKs (such as [okta-idx-swift](https://github.com/okta/okta-idx-swift)) better able to customize URLRequest handling.

* Feature improvements
  * [1.2.0](https://github.com/okta/okta-mobile-swift/releases/tag/1.2.0)
* Bug fixes
  * [1.1.2](https://github.com/okta/okta-mobile-swift/releases/tag/1.1.2)
  * [1.1.3](https://github.com/okta/okta-mobile-swift/releases/tag/1.1.3)
  * [1.1.4](https://github.com/okta/okta-mobile-swift/releases/tag/1.1.4)
  * [1.1.5](https://github.com/okta/okta-mobile-swift/releases/tag/1.1.5)

## Consumer Identity Cloud [CIC)

**TBD**


