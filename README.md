# Docker-Project

Here is an insight on launching wordpress which is an open source software used to create many kind of websites, blog or app.This is done via docker upon redhat8 linux.

Detailed description of the project So, i have installed docker on the top of redhat8 linux. After that , i pulled the image of wordpress and mysql . Now,i have ensured while making my project that if in any case the containers crash or get deleted , it should not hamper my data. For this , i have created persistent volume for both wordpress and mysql. Then i launched mysql followed by wordpress by appropiately specifying username and password.While configuring wordpress, a particular post is specified which will redirect the user towards wordpress where they can first create their account and start designing and developing websites,apps or blogs.

Now in order to avoid these steps again and again, i created a docker-compose which contains all necessary steps written as code in yaml file with .yml extension. Then at last we can do "docker-compose up" in order to execute it.

my project image can be installed from docker hub:
docker pull aayu1001/wordpress
This wordpress require database which can be taken from 
docker pull aayu1001/database


![Screenshot from 2020-05-09 18-01-18](https://user-images.githubusercontent.com/65100683/81495174-f2ef3200-92cb-11ea-9287-e28265f2ab12.png)





