The below is to Achive SPN Backup and create

The playbook should run on a Linux machine, provided that the necessary tools and permissions are in place. Here are some prerequisites and steps to ensure successful execution:

Install LDAP Tools: Ensure that the **ldapsearch** command is available. You can install it using:

For Debian-based systems (Ubuntu, etc.): **sudo apt-get install ldap-utils**
For Red Hat-based systems (CentOS, etc.): **sudo yum install openldap-clients**
Ensure Network Connectivity: The Linux machine must be able to connect to your LDAP server.

Adjust Permissions: Ensure that the user running the Ansible playbook has the necessary permissions to perform the LDAP search.
