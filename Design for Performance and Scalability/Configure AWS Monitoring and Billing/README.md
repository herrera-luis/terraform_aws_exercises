## Configure AWS Monitoring and Billing

### Configure a CloudWatch Billing Alarm

* A billing alarm is configured to send an alarm to a valid email address when a $5 billing threshold is met

* The billing alarm has a status of GREEN OK after a refresh period of 5-10 minutes

### Create and Configure IAM Users and Groups

* A group named `CloudTrailAdmins` has been created and has the two `CloudTrail` privileges.
* A group named `Reviewers` has been created and has the Billing privilege.
* A user named `CloudTrail` is created and assigned to the CloudTrailAdmins group.
* A user named `Accountant` is created and assigned to the Reviewers group.
Both users have AWS Console access


### Update AWS password policy

Password policy meets or exceeds these requirements:

* Minimum password length = 8
* Require at least one uppercase letter
* Require at least one lowercase letter
* Require at least one number
* Require at least one non-alphanumeric character.