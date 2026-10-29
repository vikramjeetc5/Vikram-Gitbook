# How to Configure VPN

A VPN (Virtual Private Network) gives you a secure connection to company systems when you work remotely. This guide shows you how to set up the VPN, connect, check that it works, and disconnect.

{% hint style="info" %}
The exact screens depend on the VPN client IT gives you. Always use the settings IT provides.
{% endhint %}

| Owner         | Document type | Version | Last updated    |
| ------------- | ------------- | ------- | --------------- |
| IT Department | How-to guide  | 1.0     | 29 October 2026 |

### Before You Start

You need:

* A company-issued or approved device and a stable internet connection
* VPN access approved for your account (see  [how-to-request-software-access.md](how-to-request-software-access.md "mention"))
* Your company account and your MFA method
* The VPN client and settings from IT

{% hint style="danger" %}
Do not use personal VPN services, unapproved VPN apps, or configuration files from unknown sources to reach company systems.
{% endhint %}

### Connection Details

| Setting        | Value                      |
| -------------- | -------------------------- |
| VPN client     | VC Secure Connect          |
| Server address | vpn.vctechnologies.example |
| Protocol       | IKEv2                      |
| Profile name   | VC-Corporate               |
| Sign-in method | Company account and MFA    |

{% hint style="info" %}
If IT gave you a configuration profile, import it instead of typing the settings by hand. Never guess the server address, and never put passwords or private keys in any document.
{% endhint %}

### Connect to the VPN

{% stepper %}
{% step %}
#### Confirm you have access

Check with IT Support that your role needs the VPN and that access is switched on for your account.
{% endstep %}

{% step %}
#### Install the VPN client

Get the client from the company software portal, as described on **Tools and Software**. Restart your device if asked. If installation needs administrator rights, ask IT Support.
{% endstep %}

{% step %}
#### Add the company profile

Open the VPN app. If the VC-Corporate profile is already there, select it. If not, import the profile from IT, or add a new connection using the settings in the table above, and save it.
{% endstep %}

{% step %}
#### Connect

Select the profile and click **Connect**. Enter your company credentials and complete MFA when asked, then wait for the app to show **Connected**.
{% endstep %}

{% step %}
#### Check the connection

Open an internal company site or system that needs the VPN and make sure it loads. Report anything you cannot reach to IT Support.
{% endstep %}
{% endstepper %}

#### Where to find the VPN app

{% tabs %}
{% tab title="Windows" %}
Click the up arrow at the bottom right of the taskbar to find the VPN icon, or search for the app by name in the Start menu.
{% endtab %}

{% tab title="macOS" %}
Look for the VPN icon in the menu bar at the top right of the screen, or open the app from the Applications folder.
{% endtab %}
{% endtabs %}

{% hint style="warning" %}
A **Connected** status does not mean every service will open. Some systems need extra permissions. See the **Access Control Policy**.
{% endhint %}

### Is It Working?

| What you see                                      | What to do                                                                                                             |
| ------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| The app does not show **Connected**               | Check your internet and credentials, then retry MFA. If it still fails, note the error message and contact IT Support. |
| **Connected**, but an internal site does not load | Check your permissions, then contact IT Support with the name of the system.                                           |
| **Connected**, and the internal site loads        | You are ready to work.                                                                                                 |

### Troubleshooting

<details>

<summary>The connection keeps failing</summary>

Check that your internet works without the VPN, then restart the VPN app and try again. Note the exact error message and contact IT Support if it keeps happening.

</details>

<details>

<summary>I see a certificate or authentication error</summary>

Do not change security settings or install certificates from other sources. Contact IT Support with a screenshot, after checking that it shows no sensitive information.

</details>

<details>

<summary>I am connected but cannot open a company system</summary>

Your account may not have access to that system yet. Check your access request, or contact IT Support with the name of the system.

</details>

<details>

<summary>The VPN client will not install or open</summary>

Use the approved installation method only. If it asks for administrator rights, ask IT Support to help.

</details>

### Disconnect

Open the VPN app, select the active profile, click **Disconnect**, and check that the status changes to disconnected.

{% hint style="info" %}
Some managed devices use an always-on VPN. If yours does, do not turn it off.
{% endhint %}

### Security Rules

{% hint style="warning" %}
* Use only the VPN client and settings approved by the company.
* Keep the client updated and do not turn off endpoint protection to connect.
* Never share your VPN credentials with anyone.
* Report unexpected prompts or security warnings straight away.
{% endhint %}

A VPN does not replace your other security duties. Password, MFA, and device rules still apply (see the **Device Control Guidelines**).

### Contact IT Support

Contact IT Support if you have not received VPN access, cannot install or open the client, cannot connect, see certificate errors, cannot reach required systems, or suspect that your credentials or device are compromised.

| Contact         | Details                                  |
| --------------- | ---------------------------------------- |
| Email           | it-support@vctechnologies.example        |
| Helpdesk portal | https://helpdesk.vctechnologies.example  |
| Support hours   | Monday to Friday, 9:00 AM to 6:00 PM IST |
| Security issues | security@vctechnologies.example          |

{% hint style="info" %}
In your ticket, include your username, your operating system, the VPN client name and version, the time of the problem, the error message, and whether the internet works without the VPN. Never include passwords, MFA codes, or private keys.
{% endhint %}
