# gpc-cicd-cloudfunctions

In order to deploy via Cloud Build located in project MANAGEMENT to CloudFunction located in project STAGING,PROD you will need:

In project MANAGEMENT, get email of account for xxxxxxxx@cloudbuild.gserviceaccount.com

In project STAGING and PROD add this account as princial into IAM and add Roles:

IAM Role Name	IAM Role Permission
Cloud Functions Developer	roles/cloudfunctions.developer
Service Account User	roles/iam.serviceAccountUser
Copyleft (c) by Denis Astahov