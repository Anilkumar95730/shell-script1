# To access S3 from by using shell script
# step 1
. First of all create the ec2 instance in linux  and start the instance
![Screenshot 2024-10-21 203022](https://github.com/user-attachments/assets/8d7fdd91-4df6-4ebb-ac1a-62f0a8a086b2)

. Connect the instance

. create s3 buckets
# step 2 
. go to IAM user

. create one user

. Give AWS S3 full access permissions

. Create access key and secret key in user

# step 3
create a file with .sh like vi file1.sh

Give executable permissions to the file shellscript.sh

Chmod 777 shellscript.sh  it can provide complete permissions
to the file read ,write execte

![Screenshot 2024-10-21 202149](https://github.com/user-attachments/assets/a001acf7-60cb-43b0-b326-a639fbd03c0c)

IN the above image i have wrote the commands to confgiure s3 access

         #!/bin/bash = write script
         aws configure = provides keys
         aws s3 ls = list the buckets
         free = check memory space
         nproc = check CPUs in server
         ps -ef = check CPU processor
         to save the file we use command :wq!

![Screenshot 2024-10-21 202127](https://github.com/user-attachments/assets/223ba0f1-5183-4cf5-9e97-7626b7e87076)

             to execte we use command ./file1.sh
The file can execute all the steps automatically by shell script as the above image
