# 隐私政策 / Privacy Policy

**最后更新 / Last updated: 2026-05-27**

---

## 简体中文版

### 概述

「秒秒进账」（以下称"本 App"）由独立开发者维护，致力于在你的工作时段实时展示当日已赚收入。本 App 在设计上**不收集、不上传、不分析**任何用户数据。

### 我们收集哪些信息？

**我们不收集任何信息。**

本 App 所有功能都在你的 iPhone 本地完成。包括但不限于：

- 你的月薪 / 时薪、工作时段、加班倍率等设置项
- 每天的开工 / 收工时间、当日金额
- 历史记录、月度统计、节假日 override

以上数据全部仅保存在你 iPhone 系统的 `UserDefaults` 中，永不离开你的设备。

### 我们使用哪些第三方服务？

**没有。**

本 App 不包含任何第三方 SDK，包括但不限于：

- 不接入数据分析（无 Firebase / Mixpanel / Amplitude 等）
- 不接入崩溃上报（无 Crashlytics / Sentry / Bugsnag 等）
- 不接入广告（无 AdMob / Meta Audience 等）
- 不接入登录系统（无 Sign in with Apple / Google / Facebook 登录）

### 网络请求

本 App **不发起任何网络请求**。你可以在飞行模式下正常使用全部功能。

### iCloud 同步？

**v1.2 版本不包含 iCloud 同步功能。** 你的数据由 iOS 系统的自动 iCloud Backup 机制（如你开启了 iCloud 备份）兜底，但这是 iOS 系统级行为，本 App 不参与也不调用 CloudKit 接口。

未来版本（v1.3+）可能引入 iCloud 同步功能，届时会更新本政策。

### 跟踪？

**没有跟踪。** 本 App 的 [Privacy Manifest](https://developer.apple.com/documentation/bundleresources/privacy_manifest_files) 明确声明：

- `NSPrivacyTracking = false`
- `NSPrivacyTrackingDomains = []`
- `NSPrivacyCollectedDataTypes = []`
- `NSPrivacyAccessedAPIType` 仅声明 `UserDefaults`（用于在你设备本地保存设置）

### 儿童隐私

本 App 不针对 13 岁以下儿童设计。由于不收集任何数据，不存在儿童隐私问题。

### 你的权利

- **查看数据**：所有数据都在你的 iPhone 上，App 内首页 + 历史页即可看到
- **删除数据**：iPhone 设置 → 通用 → iPhone 储存空间 → 找到 TickTill → 删除 App，所有数据随之删除
- **联系开发者**：1162805600@qq.com

### 政策变更

如本政策有重大变更，会在本页更新「最后更新」日期。建议偶尔回来看看。

---

## English Version

### Overview

TickTill (the "App") is maintained by an independent developer and shows your real-time daily earnings during your working hours. The App is designed to **not collect, upload, or analyze** any user data.

### What information do we collect?

**We collect nothing.**

All features run locally on your iPhone, including:

- Your monthly / hourly rate, working hours, overtime multipliers, and other settings
- Daily clock-in / clock-out times and earned amounts
- History, monthly summaries, and holiday overrides

All such data is stored only in your iPhone's `UserDefaults` and never leaves your device.

### Third-party services?

**None.**

The App contains no third-party SDKs, including but not limited to:

- No analytics (no Firebase / Mixpanel / Amplitude / etc.)
- No crash reporting (no Crashlytics / Sentry / Bugsnag / etc.)
- No ads (no AdMob / Meta Audience / etc.)
- No login systems (no Sign in with Apple / Google / Facebook)

### Network requests

The App **makes no network requests**. All functionality works in Airplane Mode.

### iCloud sync?

**v1.2 does not include iCloud sync.** Your data is incidentally protected by iOS automatic iCloud Backup (if you have it enabled), but that is a system-level behavior — the App itself does not call CloudKit or any sync API.

Future versions (v1.3+) may introduce iCloud sync. This policy will be updated accordingly.

### Tracking?

**None.** The App's [Privacy Manifest](https://developer.apple.com/documentation/bundleresources/privacy_manifest_files) explicitly declares:

- `NSPrivacyTracking = false`
- `NSPrivacyTrackingDomains = []`
- `NSPrivacyCollectedDataTypes = []`
- `NSPrivacyAccessedAPIType` declares only `UserDefaults` (for saving settings locally)

### Children's privacy

The App is not designed for children under 13. As we collect no data, there is no children's privacy concern.

### Your rights

- **View your data**: It's all on your iPhone — visible inside the App's Home and History views
- **Delete your data**: Settings → General → iPhone Storage → TickTill → Delete App. All data is removed
- **Contact the developer**: 1162805600@qq.com

### Changes to this policy

Material changes will be reflected in the "Last updated" date above. Please check back occasionally.
