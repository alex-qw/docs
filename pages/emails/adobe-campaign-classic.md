## Overview

![Adobe-Campaign-Classic](/_assets/img/pages/email/adobe-campaign-classic/adobe-campaign-classic.png)

This guide will walk you through how to setup your email campaigns with **[Adobe Campaign Classic](https://www.adobe.com/marketing-cloud/campaign.html){:target="\_blank"}** using Branch Universal Email to automatically convert your email links into **multi-platform deep links**

{! ingredients/email/overview-steps.md !}

## Setup

{! ingredients/email/prerequisites.md !}

## Configure your ESP

### Setup a custom click tracking domain

Add a custom click tracking domain at the **Brand Configuration** page in the field called **External URL of the tracking server**.

![image](/_assets/img/pages/email/adobe-campaign-classic/create-domain.png)

!!! tip "Adding a custom click-tracking domain"
    If you need help with setting up a custom click-tracking domain - please ask your account manager or request support at Adobe Campaign Classic.

{! ingredients/email/cname.md !}

## Activate integration

### Choose your email service provider

Navigate to the [Universal Email](https://dashboard.branch.io/email){:target="\_blank"} section of the Branch dashboard. Select **Adobe Campaign Classic** and click **Enable**.

{! ingredients/email/link-setup.md !}

### Tell us your click tracking domain

You can retrieve your click tracking domain from the **Brand Configuration** page in the field called **External URL of the tracking server**. If you have not added a custom click tracking domain yet, follow the instructions [here](#setup-a-custom-click-tracking-domain).

![image](/_assets/img/pages/email/adobe-campaign-classic/setup-config.png)

{! ingredients/email/technical-setup.md !}

{! ingredients/email/validate-test.md !}

!!! warning "Important Notice"
    Please reach out to your CSM or the Support team to configure the Host for your integration.

{! ingredients/email/usage-auto.md !}

## Configure your mobile app

{! ingredients/email/technical-setup-app.md !}

{! ingredients/email/associated-domains.md !}

{! ingredients/email/bounce-web.md !}

{! ingredients/email/continue-user-activity.md !}

## Using Universal email

{! ingredients/email/usage.md !}

{! ingredients/email/usage-auto-bounce-deep.md !}

{! ingredients/email/usage-auto-bounce-web.md !}

## Support

{! ingredients/email/support.md !}
