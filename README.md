# CREATION IN WEB APPLICATION FOR TEST ENVIRONMENT

## AIM

To Creation in Web Application for Test Environment.

## PROBLEM STATEMENT

Setting up test environments for web applications is time-consuming and complex. Developers need an efficient way to replicate real-world conditions while ensuring security and consistency. A simplified solution can streamline the process and improve testing outcomes.

## ALGORITHM

### Steps 1:

Launch an EC2 instance in AWS using an Amazon Linux 2 AMI with a Security Group allowing HTTP and SSH traffic.

### Steps 2:

Connect to the instance using SSH and install a web server like Apache.

### Steps 3:

Create a simple HTML file in the server's default directory.

### Steps 4:

Enter the content you want to be displayed in the website.

### Steps 5:

Access the instance's public IP in a browser to verify the HTML page is displayed.

## COMMANDS

### To install httpd:

```
yum install httpd -y
```

### To enable and start httpd :

```
systemctl enable httpd
systemctl start httpd
```

### HTML code :

```html
<!DOCTYPE html>
<html>
<body>
<h1>My First PHP page</h1>
<?php
echo "Hello World";
?>
</body>
</html>
```

## OUTPUT

### REG NUMBER: 212222100047
### NAME: SANTHOSH S

### Terminal:

![6a](https://github.com/user-attachments/assets/2a7858a0-7d02-4346-9567-1c000f38d9ee)

### Website:

![6b](https://github.com/user-attachments/assets/aad1031c-1fb1-495c-b736-56f589032d84)

## RESULT

Thus the web application for test environment has successfully been created and executed.
