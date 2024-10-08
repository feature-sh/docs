---
description: Create crypto-incentives in one click
---

# 🪄 Auto dealing

To make creating deals even easier, FEATURE allows organizations to manage special wallets that can be used to automatically sign the blockchain transaction that is required to create a new deal.

Using auto dealing, you will simply have to label an issue with a _FEATURE label_ and the deal will be created automatically without further action ✨.

{% hint style="warning" %}
Auto dealing only works with issue labelling as of now.
{% endhint %}

1\) Enable auto dealing in your [organization settings](https://dashboard.feature.sh/settings/wallets) as shown below:

![Enable auto dealing](../.gitbook/assets/capture-dashboard-auto-dealing-enable.png)

And don't forget to save the configuration with **Save.**

2\) Manage your organization wallets and set the one you want to use for auto dealing by selecting it as the default.

![Organization wallets](../.gitbook/assets/select\_organization\_wallet.png)

3\) Label an issue with a Feature label and let the magic happen 🪄. The transaction can take up to a few seconds to be processed, but fortunately the Bot will keep you updated about the progress!

![Automatic Success Deal](../.gitbook/assets/capture-github-label-with-autodeal.png)

{% hint style="warning" %}
The selected wallet should have the necessary funds to create the deal, otherwise an error message will be thrown by the bot.
{% endhint %}

![Fail Deal](../.gitbook/assets/capture-github-autodeal-fail.png)
