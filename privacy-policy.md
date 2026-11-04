# Privacy Policy — ghealth-personal

Last updated: 2026-10-22

**ghealth-personal** is a personal, non-commercial tool built by its sole user for one purpose: reading his own health data from Google Health to produce private daily health summaries.

## Data accessed

The app requests read-only access (four Google Health scopes) to the user's own account only: steps, heart rate / resting heart rate / HRV, blood oxygen (SpO₂), sleep sessions and stages, active energy and exercise/stand activity.

## How data is used

- Fetches data from the user's own Google Health account via the open-source `ghealth` CLI, and renders it into a private daily summary for the user.
- That's it. No advertising, no analytics, no tracking.

## Data sharing

None. Data is never shared with, sold to, or disclosed to any third party. Credentials live only on the user's own machine (`~/.config/ghealth/`, file permissions 0600). Nothing is uploaded to any external server.

## Data retention and deletion

The app stores only OAuth tokens and fetched summaries locally on the user's own machine. The user may revoke access at any time from [Google Account → Third-party access](https://myaccount.google.com/permissions), which immediately stops all future data access. To delete local data, delete `~/.config/ghealth/`.

## Contact

This is a personal-use app with a single user. Questions: reach the owner through the support email registered on the OAuth consent screen.

---

## 中文说明

**ghealth-personal** 是仅供其唯一用户个人使用的非商业工具：从他自己的 Google 健康数据中读取步数、心率/HRV/血氧、睡眠、活动量等数据，生成每日健康小结。**只读权限、仅读取用户本人的账号数据；不分享、不出售、不对外上传；凭证只存放在用户自己机器上**（`~/.config/ghealth/`，权限 0600）。可随时在 [Google 账号 → 第三方访问权限](https://myaccount.google.com/permissions) 撤销授权。
