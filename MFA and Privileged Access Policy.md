# **Multi Factor Authentication & Privilege Access Policy** 

## **For Privileged User Accounts** 

### **Objective** 

To protect privileged user accounts and access to XML tools against service interruption, credential stuffing, and phishing risks. 

#### **Scope** 

Applies to all employees, contractors, and third-party vendors utilizing elevated or administrative privileges. 

#### **Requirements** 

##### **Multi-Factor Authentication** 

- Require mandatory Multi-Factor Authentication (e.g. TOTP application, hardware token) for all remote and privileged network access. 

##### **Rate-Limiting & Secondary Verification** 

- Limit the number of requests that can be made by an account within a specific time window and block extra traffic. 

- Critical XML commands require secondary verification via a documented MakerChecker workflow prior to execution. 

##### **Strengthen Privileged Access** 

- Enforce least privilege by giving users and systems the bare minimum permissions required to complete their tasks. 

##### **Incident Trigger** 

If VPN compromise is suspected: 

- The affected VPN account must be immediately blocked by the IT department within 30 minutes of a confirmed high-severity security alert being logged. 

- All privileged credentials tied to the XML tool must be rotated. 

- The XML command interface must be disabled temporarily. 

#### **Evidence Requirements** 

- Admin audit logs show the exact timestamp when active VPN account was blocked. 

- Automated system logs verifying that the rotation of privileged credentials of the XML tool was initiated and completed. 

- Admin audit logs show the exact timestamp when XML command interface was disabled. 

#### **References** 

- **ISO 27001:2022 Control:** Annex A 5.15 (Access Control) & Annex A 5.17 (Authentication Information). 

- **ISO 27001:2022 Technological:** Annex A 8.2 (Privileged Access Rights) & Annex A 8.5 (Secure Authentication). 

