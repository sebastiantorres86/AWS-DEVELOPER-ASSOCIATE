### QUESTION 1

## Which IAM entity can you use to delegate access to trusted entities such as IAM users, applications, or AWS services such as EC2?

- [ ] IAM User
- [x] IAM Role
- [ ] IAM Group
- [ ] IAM Web Identity Federation

<details>
<summary>Answer Explanation:</summary>

> You can use IAM roles to delegate access to IAM users managed within your account, to IAM users under a different AWS account, to a web service offered by AWS such as Amazon Elastic Compute Cloud (Amazon EC2), or to an external user authenticated by an external identity provider (IdP) service that is compatible with SAML 2.0 or OpenID Connect, or a custom-built identity broker. [IAM Roles](https://docs.aws.amazon.com/IAM/latest/UserGuide/id_roles.html).

</details>

---

### QUESTION 2

## What is an IAM Policy?

- [x] A JSON document which defines one or more permissions
- [ ] A file containing a user's private SSH key
- [ ] The policy which determines how your AWS bill will be paid
- [ ] A CVS file which contains a user Access Key and Secret Access Key

---

### QUESTION 3

## Which is the best way to enable S3 read-access for an EC2 instance?

- [ ] Create a new IAM group and grant read access to S3. Store the group's credentials locally on the EC2 instance and configure your application to supply the credentials with each API request
- [ ] Create a new IAM user and grant read access to S3. Store the user's credentials locally on the EC2 instance and configure your application to supply the credentials with each API request
- [ ] Configure a bucket policy which grants read-access based on the EC2 instance name
- [x] Create an IAM role with read-access to S3 and assign the role to the EC2 instance

<details>
<summary>Answer Explanation:</summary>

> Correct. IAM roles allow applications to securely make API requests from instances, without requiring you to manage the security credentials that the application use.

</details>

---

### QUESTION 4

## Which of the following is NOT a feature of IAM?

- [ ] Fine-grained access control to AWS resources
- [x] Allows you to setup biometric authentication, so that no password are required
- [ ] Centralized control of your AWS account
- [ ] Integrates with existing active directory account allowing single sign on

---

### QUESTION 5

## In IAM, what is IAM used for?

- [x] Managing access to AWS services
- [x] Creating and managing users and groups
- [x] Assigning permissions to allow and deny access to AWS resources
- [ ] Secure VPN access to AWS

---

### QUESTION 6

## Which statement best describes IAM?

- [ ] IAM allows you to manage user's passwords only. AWS staff must create new users for your organization. This is done by raising a ticket.
- [x] IAM allows you to manage users, groups, and roles and their corresponding level of access to the AWS Platform.
- [ ] IAM allows you to manage permissions for AWS resources only.
- [ ] IAM stands for Improvised Application Management, and it allows you to deploy and manage applications in the AWS Cloud.

---

### QUESTION 7

## AWS recommends that EC2 instances have credentials stored on them so that the instances can access other resources (such as S3 buckets).

- [x] False
- [ ] True

---
