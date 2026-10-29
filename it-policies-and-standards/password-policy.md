# Password Policy

This policy sets the rules for creating, using, and protecting passwords for VC Technologies accounts, devices, and systems. It applies to all employees, contractors, and authorized users.

{% hint style="info" %}
Short on time? Read **The Rules at a Glance**, then open the sections you need. For step-by-step instructions, see **How to Reset Your Password**.
{% endhint %}

| Policy details     |                                      |
| ------------------ | ------------------------------------ |
| Owner              | IT / Information Security Department |
| Policy type        | IT policies and standards            |
| Version            | 1.0                                  |
| Effective date     | 29 October 2026                      |
| Last reviewed      | 29 October 2026                      |
| Next review        | 29 October 2027                      |
| Approval authority | Chief Information Security Officer   |

### Who This Applies To

The policy covers company email and employee accounts, managed devices, internal and cloud applications, VPN and remote access, development tools and databases, and administrative accounts. Systems that use passkeys or certificates follow their own security standard.

### The Rules at a Glance

| Rule       | Requirement                                                                                   | Level    |
| ---------- | --------------------------------------------------------------------------------------------- | -------- |
| Length     | At least 14 characters. Long passphrases are best                                             | Required |
| Uniqueness | A different password for every company account, and never one you use elsewhere               | Required |
| Sharing    | Never share your password with anyone                                                         | Required |
| Storage    | Use only the company-approved password manager                                                | Required |
| MFA        | Turn on multifactor authentication wherever it is supported                                   | Required |
| Changes    | Change it only when it may be compromised, when IT tells you to, or when a system requires it | Required |
| Reporting  | Report a suspected compromise immediately                                                     | Required |

{% hint style="danger" %}
Never share your password, send it by email or chat, write it in a document, or put it in a support ticket. IT Support will never ask you for it.
{% endhint %}

### Password Rules in Detail

<details>

<summary>Creating a strong password</summary>

* Use a long, memorable passphrase or a randomly generated password.
* Avoid personal details (your name, birthday, employee number), common phrases, predictable substitutions, and passwords found in known breach lists.
* Follow any extra rules shown on the official password page.
* Requirements can differ for standard, service, and administrative accounts, or for systems with technical limits.

</details>

<details>

<summary>Storing and managing passwords</summary>

* Store passwords only in the company-approved password manager.
* Never save passwords in plain-text files, spreadsheets, or notes.
* Developers must not put passwords, API keys, or other secrets in code or configuration files. Use the approved secrets-management system.
* Systems must never store passwords in plain text.

</details>

<details>

<summary>Changing passwords and expiry</summary>

Change your password straight away if you think it has been exposed, if IT or the security team tells you to, or if a system requires it. Do not change it on a fixed schedule unless an approved policy or a particular system requires that.

When a password is compromised, the security team may also end active sessions, review the account's activity, and reset related credentials.

</details>

<details>

<summary>Multifactor authentication (MFA)</summary>

* Enrol with the method the company approves, and protect your authenticator device and recovery codes.
* Never share verification codes, and never approve a request you did not start.
* Report unexpected MFA prompts promptly.
* If you lose your device, follow the approved recovery process.
* MFA does not replace a strong, unique password.

</details>

<details>

<summary>Temporary and default passwords</summary>

* Change a temporary password as soon as you are prompted.
* IT must deliver temporary credentials through an approved secure method and must not put them in general onboarding documents.
* Default credentials must be changed before a system is put into use.

</details>

<details>

<summary>Administrator and privileged accounts</summary>

Accounts with extra permissions need stronger protection, because a compromise could affect many systems.

* Use a separate standard account and privileged account where required.
* Protect privileged accounts with stronger authentication, and turn on MFA.
* Use them only for authorized administrative work, and never share them.
* Grant, review, and remove privileged access through the access management process (see the **Access Control Policy**).

</details>

### If You Think Your Password Is Compromised

A password may be compromised if it has been exposed in a breach, typed into a suspicious website, or used in a login attempt you did not make.

{% stepper %}
{% step %}
#### Report it straight away

Contact IT Support or the security team through the approved channel.
{% endstep %}

{% step %}
#### Change the password

Use the official reset process, if it is safe to do so. See **How to Reset Your Password**.
{% endstep %}

{% step %}
#### Secure your account

Follow the team's instructions, and complete MFA recovery or re-enrolment if asked.
{% endstep %}

{% step %}
#### Cooperate with the review

Help the security team with its investigation. They may end sessions, reset related credentials, or restrict access for a short time.
{% endstep %}
{% endstepper %}

{% hint style="info" %}
Report even if you think your own mistake caused it. Do not delay reporting.
{% endhint %}

### Responsibilities

{% tabs %}
{% tab title="Employees" %}
* Follow this policy and protect your passwords.
* Use only approved sign-in, reset, and recovery methods.
* Report suspected exposure or unauthorized access promptly.
{% endtab %}

{% tab title="IT" %}
**IT Department**

* Set up password and authentication controls in supported systems.
* Maintain the approved reset and account recovery procedures.
* Verify a user's identity before changing credentials, and support authentication issues.
{% endtab %}

{% tab title="Security" %}
**Information Security team**

* Define and review password security standards.
* Assess password-related risks.
* Lead the response to suspected credential compromise, and recommend improvements.
{% endtab %}

{% tab title="Managers" %}
**Managers and system owners**

* Make sure access to systems and applications matches business needs.
* Follow the access management procedures when granting or removing access.
{% endtab %}
{% endtabs %}

### Exceptions

An exception to this policy needs a documented reason, a risk assessment where appropriate, approval from the designated IT or Information Security authority, any extra security controls that are required, and a review or expiry date.

{% hint style="warning" %}
Never bypass a password requirement or authentication control yourself. Ask for an exception through the proper process first.
{% endhint %}

> Not following this policy can put the company at risk and may lead to corrective or disciplinary action, in line with company procedures and the law. Report suspected violations through the IT, security, HR, or compliance channel.

### Related Pages

{% content-ref url="../how-to-guides/how-to-reset-your-password.md" %}
[how-to-reset-your-password.md](../how-to-guides/how-to-reset-your-password.md)
{% endcontent-ref %}

{% content-ref url="../how-to-guides/how-to-troubleshoot-login-issues.md" %}
[how-to-troubleshoot-login-issues.md](../how-to-guides/how-to-troubleshoot-login-issues.md)
{% endcontent-ref %}

{% content-ref url="access-control-policy.md" %}
[access-control-policy.md](access-control-policy.md)
{% endcontent-ref %}
