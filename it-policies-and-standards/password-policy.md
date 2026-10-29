# Password Policy

### 1. Overview

The Password Policy of **\[Company Name]** establishes the requirements for creating, using, protecting, and managing passwords for company accounts, applications, devices, and information systems.

Passwords are a critical component of access control and information security. Weak, reused, or compromised passwords can expose company systems and sensitive information to unauthorized access.

All employees, contractors, and authorized users must follow this policy when accessing company resources.

### 2. Purpose

The purpose of this policy is to:

* Establish consistent password security requirements across the organization.
* Reduce the risk of unauthorized account access.
* Protect company information and systems from password-related attacks.
* Promote secure authentication practices.
* Define employee and IT responsibilities for password management.
* Support the organization's information security and compliance requirements.

### 3. Scope

This policy applies to all authorized users who access company-managed or company-approved resources, including:

* Company email and employee accounts.
* Laptops, desktops, and other managed devices.
* Internal applications and business systems.
* Cloud services and collaboration platforms.
* VPN and remote access services.
* Development environments, source code repositories, and databases.
* Administrative and privileged accounts.
* Other systems that use password-based authentication.

Where a system uses an alternative authentication method, such as passkeys or certificate-based authentication, the applicable system-specific security standard must be followed.

### 4. Password Requirements

All passwords must comply with the requirements established by the company's identity management system and applicable security standards.

#### 4.1 Password Length and Strength

* Use long, unique passwords or passphrases.
* Follow the minimum length and other requirements configured by the company.
* Avoid predictable passwords, common phrases, and easily guessed patterns.
* Do not use personal information, such as your name, birthday, or employee number, as the basis for a password.
* Do not use passwords that appear on known compromised-password lists.
* Follow system-specific requirements where stronger controls apply.

**Company Standard:** \[Insert Approved Minimum Password Length and Complexity Requirements]

#### 4.2 Password Uniqueness

* Use a unique password for each company account where passwords are required.
* Never reuse company passwords for personal accounts or external services.
* Avoid reusing previous passwords where the system prevents it or company policy requires it.
* Use an organization-approved password manager when available.

Password reuse increases the risk that a compromise of one account could affect other accounts.

#### 4.3 Password Confidentiality

Employees must:

* Keep passwords confidential at all times.
* Never share passwords with colleagues, contractors, or unauthorized individuals.
* Never send passwords through email, chat, or other unapproved communication channels.
* Never store passwords in plain-text files, spreadsheets, or unsecured notes.
* Never disclose passwords in support tickets or incident reports.
* Use approved credential storage methods when required.

IT Support must use approved identity verification and account recovery procedures rather than asking employees to disclose their existing passwords.

### 5. Password Creation Guidelines

When creating a password, employees should:

* Choose a long, memorable passphrase or a randomly generated password.
* Avoid predictable substitutions and commonly used patterns.
* Avoid using the same password across multiple systems.
* Use a password manager approved by the company to generate and store strong passwords.
* Follow the requirements presented by the official password creation or reset portal.

Password requirements may differ for standard user accounts, service accounts, administrative accounts, and systems with specific technical limitations.

### 6. Password Changes and Expiration

Passwords must be changed when required by the company's identity management system, a system-specific security requirement, or an authorized security response.

Employees must change their passwords promptly when:

* They suspect a password has been exposed or compromised.
* They receive a verified instruction from IT or the security team.
* A system requires a password change due to expiration or another configured condition.
* An incident investigation determines that credential replacement is necessary.

Routine password changes should follow the organization's approved authentication standard. Passwords should not be changed on an arbitrary schedule unless required by the company's approved policy or a specific system requirement.

When a password is compromised, the response may also require revoking active sessions, reviewing account activity, resetting affected credentials, and completing additional security checks.

### 7. Multifactor Authentication (MFA)

Multifactor authentication provides an additional layer of protection beyond a password.

Where MFA is supported and required, employees must:

* Enroll using the authentication method approved by the company.
* Protect their authenticator devices and recovery methods.
* Never share verification codes or recovery codes.
* Never approve an authentication request they did not initiate.
* Report unexpected MFA prompts or suspicious authentication activity promptly.
* Follow the approved recovery process if an authentication device is lost or unavailable.

MFA does not eliminate the need for strong, unique passwords where password authentication is used.

### 8. Password Storage and Management

Passwords and other authentication secrets must be stored and managed securely.

The following requirements apply:

* Use only company-approved password managers or credential storage solutions.
* Do not save passwords in unprotected documents, spreadsheets, or source code.
* Do not hard-code passwords, API keys, or other secrets into application code or configuration files.
* Use approved secrets-management systems for applications and automated workloads.
* Restrict access to stored credentials according to business need.
* Protect backups and recovery information according to company security requirements.

Where technical systems support it, passwords must be protected using appropriate secure authentication mechanisms and must never be stored in plaintext.

### 9. Administrative and Privileged Accounts

Accounts with elevated permissions require additional protection because their compromise may affect multiple systems or sensitive resources.

Users with administrative privileges must:

* Use separate standard and privileged accounts where required.
* Protect privileged credentials with stronger authentication controls.
* Enable MFA wherever required by the company's privileged access standard.
* Use administrative accounts only for authorized administrative activities.
* Never share privileged credentials.
* Store service credentials and other secrets only in approved secure systems.
* Report suspected compromise immediately.

Privileged access must be granted, reviewed, and revoked according to the organization's access management procedures.

### 10. Password Reset and Account Recovery

Password resets and account recovery must be completed through approved company processes.

Employees must:

* Use the official password reset portal or approved support channel.
* Complete the required identity verification steps.
* Protect recovery codes and verification methods.
* Contact IT Support when self-service recovery is unavailable.
* Follow additional instructions provided during a suspected account compromise.

IT personnel must verify the user's identity according to the approved recovery procedure before making changes to account credentials or authentication methods.

Refer to the **How to Reset Your Password** guide for step-by-step instructions.

### 11. Default Passwords and Initial Account Setup

Default or temporary credentials must be handled securely.

* Employees must change temporary passwords when prompted or required by company procedures.
* Default credentials must not remain in place on systems where they are required to be changed.
* IT administrators must configure systems using approved secure deployment practices.
* Temporary credentials must be delivered through an approved secure method.
* Initial account activation must follow the organization's identity verification process.

Passwords must not be transmitted through unsecured channels or included in general onboarding documentation.

### 12. Suspected Password Compromise

A password may be considered compromised if it has been disclosed, exposed through a data breach, entered into a suspicious website, or used in an unauthorized login attempt.

If compromise is suspected, employees must:

1. Report the issue immediately through the designated IT or security channel.
2. Change the affected password using the official process, if safe and possible.
3. Follow instructions to secure the account and any related systems.
4. Complete any required MFA recovery or re-enrollment.
5. Cooperate with authorized security investigations.

The security team may require additional measures, such as revoking active sessions, resetting related credentials, or temporarily restricting access.

Employees must not delay reporting an incident because they believe the issue was caused by their own mistake.

### 13. Roles and Responsibilities

#### Employees and Authorized Users

Employees are responsible for:

* Following this policy.
* Creating and protecting passwords in accordance with company requirements.
* Using approved authentication and recovery methods.
* Reporting suspected credential exposure or unauthorized access promptly.

#### IT Department

The IT Department is responsible for:

* Configuring password and authentication controls in supported systems.
* Maintaining approved password reset and account recovery procedures.
* Providing guidance and support for authentication issues.
* Applying appropriate access controls and security configurations.

#### Information Security Team

Where applicable, the Information Security team is responsible for:

* Defining and reviewing password security standards.
* Assessing password-related risks.
* Coordinating responses to suspected credential compromise.
* Recommending improvements to authentication controls.

#### Managers and System Owners

Managers and system owners are responsible for ensuring that access to systems and applications is appropriate for business requirements and follows approved access management procedures.

### 14. Compliance and Policy Violations

Failure to comply with this policy may expose the organization to security risks and may result in corrective or disciplinary action in accordance with company procedures and applicable law.

Suspected violations should be reported through the designated IT, security, HR, or compliance channel.

Exceptions to this policy must be documented, assessed for risk, and approved by the authorized person or team before implementation.

### 15. Exceptions

Any exception to the password requirements must:

* Have a documented business or technical justification.
* Include a risk assessment where appropriate.
* Be approved by the designated IT or Information Security authority.
* Include compensating security controls where necessary.
* Have a defined review date or expiration where appropriate.

Employees must not independently bypass password requirements or authentication controls.

### 16. Related Documentation

Refer to the following documents for additional guidance:

* **How to Reset Your Password** — Step-by-step password recovery instructions.
* **How to Troubleshoot Login Issues** — Guidance for resolving authentication problems.
* **Company Policies** — General employee and IT security responsibilities.
* **Access Control Policy** — Requirements for account permissions and authorization.
* **Multifactor Authentication Standard** — Requirements for additional authentication controls.
* **Incident Response Policy** — Procedures for reporting and responding to security incidents.

***

**Document Owner:** \[IT / Information Security Department]

**Policy Type:** IT Policies and Standards

**Version:** 1.0

**Effective Date:** \[Date]

**Last Reviewed:** \[Date]

**Next Review Date:** \[Date]

**Approval Authority:** \[Authorized Approver]
