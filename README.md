# SnipeIT_Ansible

Notes:
Must use PHP ver between 7.2 to 8.2 or else the Composer will fail while installing.  
<s>SQL user login (Root/snipeit1) should be same login which is used to login into the MySQL server of the target machine.</s>  
You can use mysql_test.yml file to change the blank root password automatically, But comment it out in main.yml of tasks folder the 2nd time you run it on same existing installation.  
