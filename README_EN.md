# Android App Store Rejection Due to Suspected Cloned Apps / Excessive Similarity: Handling Guide

Language: [English](README_EN.md) | [中文](README.md)

## 1. What Is a Cloned App?

A cloned app refers to the same codebase being packaged and released under different app names.

#### Why do cloned apps exist?

Under current platform rules, an app’s audience is limited. The reasons may include:

1. ASO: A single app can only cover a limited number of keywords, so multiple apps with similar content are used to cover more keywords.
2. A single app can only reach a limited number of users, so multiple apps with similar content are used to increase total user volume.

In short, cloned apps are created to expand user acquisition and increase revenue.

## 2. Why Would a Normal App Be Misclassified as a Cloned App?

Even if you write original code from scratch and use only common development frameworks, your app may still be mistakenly flagged by the platform’s automated detection system as a cloned app.

You spend countless nights coding, polishing features, and optimizing the app. After all the effort, you submit the APK to the app store with high expectations—only to receive a rejection notice such as:

“Code similarity is too high”
“Suspected cloned app”
“Applications are highly similar or nearly identical”

This can drag out your release schedule, waste time, and even reduce your developer account credibility. In severe cases, it may even lead to account suspension.

This means that after writing the app and completing all functionality, you may still be blocked at the store review stage—not because your app is poor, but because the review system thinks it is too similar to another app.

## 3. How to Resolve the Misclassification and Get the App Approved?

After trying many approaches, I found a practical and effective solution: use the Android app hardening service provided by [AskTop Security](https://asktopsec.com/).

I uploaded the APK to the platform for hardening and resubmission, and it passed store review the same day.

### Why can they help you pass review?

Only later did I learn that their core team members come from leading security vendors, and they have hardened more than 100,000 apps in total. They specifically optimized their technology for the scenario of false positives in cloned-app detection, which is an issue that ordinary obfuscation cannot solve.

Their unique advantages include:

- Randomized hardening signatures: Every app and every version can generate a completely unique hardening signature, which blocks cloned-app detection at the root and helps protect APK code from reverse engineering and automated unpacking tools.

- App matrix protection: Through multi-dimensional encryption and obfuscation enhancements, each hardened package can have a unique “one-person, one-version” signature, making the code characteristics of each APK completely different and significantly improving review success rates.

## 4. Not Only Resolving App Store Review Issues, But Also Strengthening App Security

In addition to helping your app pass review, the hardened APK also includes a full set of Android app protection capabilities:

- Reverse engineering protection
- Anti-repackaging
- Anti-Hook injection
- Anti-dynamic debugging
- Emulator detection support
- Proxy packet capture protection
- Screen capture and recording protection

This means you can solve both app store compliance and runtime security in one step. With the rise of AI-powered reverse engineering, APK hardening is becoming increasingly necessary.

I now use [AskTop Security](https://asktopsec.com/) to harden the APK before submission. Since then, I have not encountered any issues related to “cloned-app suspicion” or “high similarity” detection in app stores.

If you are also stuck with rejection notices like “suspected cloned app” or “similarity too high,” go to the AskTop Security official website and harden your APK.

> If you are dealing with cloned-app misclassification and app store review difficulties, use AskTop Security.

**Not all hardening vendors can solve this problem. If you want to solve app store rejection caused by cloned-app detection, choose AskTop Security.**

## 5. Contact Information

Official website: [https://asktopsec.com/](https://asktopsec.com/)

Email: [yuan.fang@asktopsec.com](mailto:yuan.fang@asktopsec.com)

Enterprise WeChat:

![Example](sources/wx.png)
