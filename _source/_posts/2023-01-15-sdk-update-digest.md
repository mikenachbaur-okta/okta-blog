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

## Workforce Identity Cloud (WIC)

### Backend SDKs

#### okta-sdk-dotnet

*Releases:*
[6.0.1](https://github.com/okta/okta-sdk-dotnet/releases/tag/v6.0.1)

#### okta-sdk-golang

*Releases:*
[2.15.0](https://github.com/okta/okta-sdk-golang/releases/tag/v2.15.0),
[2.16.0](https://github.com/okta/okta-sdk-golang/releases/tag/v2.16.0),
[3.0.0](https://github.com/okta/okta-sdk-golang/releases/tag/v3.0.0),
[3.0.1](https://github.com/okta/okta-sdk-golang/releases/tag/v3.0.1)

#### okta-sdk-java

*Releases:*
[10.0.0](https://github.com/okta/okta-sdk-java/releases/tag/okta-sdk-root-10.0.0)

#### okta-sdk-nodejs

Adds support for custom attributes in UserProfile and GroupProfile, and fixes path and type signature issues for MemoryStore.

*Releases:*
[6.6.0](https://github.com/okta/okta-sdk-nodejs/releases/tag/okta-sdk-nodejs-6.6.0)

### Client SDKs

#### okta-auth-js

*Releases:*
[7.0.0](https://github.com/okta/okta-auth-js/releases/tag/okta-auth-js-7.0.0),
[7.0.1](https://github.com/okta/okta-auth-js/releases/tag/okta-auth-js-7.0.1),
[7.1.0](https://github.com/okta/okta-auth-js/releases/tag/okta-auth-js-7.1.0),
[7.0.2](https://github.com/okta/okta-auth-js/releases/tag/okta-auth-js-7.0.2),
[7.1.1](https://github.com/okta/okta-auth-js/releases/tag/okta-auth-js-7.1.1),
[7.2.0](https://github.com/okta/okta-auth-js/releases/tag/okta-auth-js-7.2.0)

#### okta-idx-swift

The most impactful update through these releases was the introduction of support for the "Device Token" cookie, which enables MFA policies to "Remember this device", allowing multi-factor verification steps to be skipped on subsequent sign ins. Additionally, user profile information was introduced to the User object, providing more context to the user being signed in.

The rest of these updates were related to bumping the upstream [okta-mobile-swift](#okta-mobile-swift] dependency versions, or improving the sample application.

*Releases:*
[3.0.2](https://github.com/okta/okta-idx-swift/releases/tag/3.0.2),
[3.0.3](https://github.com/okta/okta-idx-swift/releases/tag/3.0.3),
[3.0.4](https://github.com/okta/okta-idx-swift/releases/tag/3.0.4),
[3.0.5](https://github.com/okta/okta-idx-swift/releases/tag/3.0.5),
[3.0.6](https://github.com/okta/okta-idx-swift/releases/tag/3.0.6)

#### okta-mobile-kotlin

*Releases:*

#### okta-mobile-swift

Some releases were made to [okta-mobile-swift](https://github.com/okta/okta-mobile-swift) to improve token refresh handling and when tokens are stored within the keychain. Additional features were added to make downstream SDKs (such as [okta-idx-swift](https://github.com/okta/okta-idx-swift)) better able to customize URLRequest handling.

*Releases:*
[1.1.2](https://github.com/okta/okta-mobile-swift/releases/tag/1.1.2),
[1.1.3](https://github.com/okta/okta-mobile-swift/releases/tag/1.1.3),
[1.1.4](https://github.com/okta/okta-mobile-swift/releases/tag/1.1.4),
[1.1.5](https://github.com/okta/okta-mobile-swift/releases/tag/1.1.5),
[1.2.0](https://github.com/okta/okta-mobile-swift/releases/tag/1.2.0)

## Consumer Identity Cloud (CIC)

**TBD**

