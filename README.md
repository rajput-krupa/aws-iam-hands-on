# aws-iam-hands-on
A practical project for AWS IAM using real screenshots and steps

# AWS IAM Hands-On Lab Project

This project documents my hands-on experience setting up AWS IAM (Identity and Access Management). It includes real screenshots, permission policies, best practices, and use cases for working with IAM users, groups, and roles.

---

## 📋 IAM Setup Summary

- 👤 IAM Users: `yashraj`, `alex`
- 👥 IAM Group: `admin`
- 🔐 Permissions: 
  - `AdministratorAccess`
  - `IAMUserChangePassword`

---

## 🗂 Project Structure

- `use-cases/` → Step-by-step use-case documents with screenshots
- `policies/` → JSON permission policies
- `diagrams/` → Visual IAM structure
- `screenshots/` → Real screenshots from AWS Console

---


## 🧠 Key Learnings

- Always avoid using root account for regular work
- IAM is a global service — not tied to a specific region
- Use groups to manage users efficiently
- Grant only necessary permissions (Principle of Least Privilege)
- Always enable MFA and strong password policies

---

> Built with 💡by Krupa Rajput while learning AWS
