---
title: 查看您的 Git Large File Storage 使用情况
intro: '您可以审核帐户的每月带宽配额和 {% data variables.large_files.product_name_short %} 的剩余存储空间。'
redirect_from:
  - /github/setting-up-and-managing-billing-and-payments-on-github/viewing-your-git-large-file-storage-usage
  - /articles/viewing-storage-and-bandwidth-usage-for-a-personal-account/
  - /articles/viewing-storage-and-bandwidth-usage-for-an-organization/
  - /articles/viewing-your-git-large-file-storage-usage
  - /github/setting-up-and-managing-billing-and-payments-on-github/managing-billing-for-git-large-file-storage/viewing-your-git-large-file-storage-usage
versions:
  fpt: '*'
  ghec: '*'
type: how_to
topics:
  - LFS
  - Organizations
  - User account
shortTitle: 查看 Git LFS 使用情况
---

{% data reusables.large_files.owner_quota_only %} {% data reusables.large_files.does_not_carry %}

## 查看个人帐户的存储空间和带宽使用情况

{% data reusables.user_settings.access_settings %}
{% data reusables.user_settings.billing_plans %}
{% data reusables.dotcom_billing.lfs-data %}

## 查看组织的存储空间和带宽使用情况

{% data reusables.dotcom_billing.org-billing-perms %}

{% data reusables.organizations.billing-settings %}
{% data reusables.dotcom_billing.lfs-data %}

## 延伸阅读

- "[关于存储空间和带宽的使用](/articles/about-storage-and-bandwidth-usage)"
- “[升级 {% data variables.large_files.product_name_long %}](/articles/upgrading-git-large-file-storage/)”
