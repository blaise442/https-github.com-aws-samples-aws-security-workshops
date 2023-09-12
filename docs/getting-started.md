# Getting Started

## Create an AWS account

In order to complete the hands-on content on this site, you'll need an <a href="https://aws.amazon.com/getting-started/" target="_blank">AWS Account</a>. We strongly recommend that you use a personal account or create a new AWS account to ensure you have the necessary access and that you do not accidentally modify corporate resources. Do **not** use an AWS account from the company you work for unless they provide sandbox accounts just for this purpose.

## Create an IAM user <small> (with admin permissions) </small>

If you don't already have an AWS IAM user with admin permissions, please use the following instructions to create one:

1.  Browse to the <a href="https://console.aws.amazon.com/iam/" target="_blank">AWS IAM</a> console.
2.  Click **Users** on the left navigation and then click **Add User**.
3.  Enter a **User Name**, check the checkbox for **AWS Management Console access**, enter a **Custom Password**, and click **Next:Permissions**.
4.  Click **Attach existing policies directly**, click the checkbox next to the **AdministratorAccess**, and click **Next:review**.
5.  Click **Create User**
6.  Click **Dashboard** on the left navigation and use the **IAM users sign-in link** to login as the admin user you just created.

## Add credits <small> (optional) </small>

If you are doing this workshop as part of an AWS sponsored event that doesn't provide AWS accounts, you will receive credits to cover the costs.  Below are the instructions for entering the credits:

1.  Browse to the <a href="https://console.aws.amazon.com/billing/home?#/credits" target="_blank">AWS Account Settings</a> console.
2.  Enter the **Promo Code** you received (these will be handed out at the beginning of the workshop).
3.  Enter the **Security Check** and click **Redeem**.



??? info "Click here if the workshop you are doing requires a Cloud9 instance" 

	If the workshop you are doing requires you to run commands or scripts you will need to launch a an <a href="https://aws.amazon.com/cloud9/" target="_blank">AWS Cloud9</a> instance which will provide you with a cloud-based integrated development environment (IDE) that lets you write, run, and debug your code with just a browser. The workshop instructions will specify if this needed.  Below are the instructions for launching an instance:

	1.  Browse to the <a href="https://console.aws.amazon.com/cloud9" target="_blank">AWS Cloud9</a> console.
	2.  Click **Create environment** on the right side.
	3.  Enter a **Name** (security-workshop-ide) and click **Next step**.
	4.  Leave all the defaults and click **Next step**.
	5.  Click **Create environment**.
	6.  The environment will open automatically after it has been provisioned.  Browse back to the <a href="https://console.aws.amazon.com/cloud9" target="_blank">AWS Cloud9</a> console and you can click **Open IDE** on the environment you created to access it at anytime.

## Choose your workshop

You are now setup for the workshops!  The site is broken down into two different types.  Click on one of the types below to be taken to the directory:

* **[Builder Sessions](/builder-sessions/)** - A 1 hour hands-on deep dive focused on a specific topic or AWS service.
* **[Workshops](/workshops/)** - A 2 hour hands-on deep dive using a broader set of AWS services together and covering multiple aspects of a particular security domain. 
