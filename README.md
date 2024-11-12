# sqlinjection
Exploiting SQL Injection vulnerability

# AIM:
To exploit SQL Injection vulnerability using Multidae web application in Metasploitable2

## DESIGN STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode


### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:

Open terminal and try execute some kali linux commands

## EXECUTION STEPS AND ITS OUTPUT:

SQL Injection is a sort of infusion assault that makes it conceivable to execute malicious SQL statements. These statements control a database server behind a web application. Assailants can utilize SQL Injection vulnerabilities to sidestep application safety efforts. They can circumvent authentication and authorization of a page or web application and recover the content of the whole SQL database. Identify IP address using ifconfig in Metasploitable2 i

![image](https://github.com/user-attachments/assets/d70319cb-35ca-43eb-87c8-873e30a7484f)

![image](https://github.com/user-attachments/assets/d48d3f50-92ea-4401-a99f-c35773a22def)

![image](https://github.com/user-attachments/assets/fa6281c4-047b-4e06-a1cc-7005161b1c83)

![image](https://github.com/user-attachments/assets/b363132c-8491-4f07-9307-806ae56c227b)
![image](https://github.com/user-attachments/assets/d315fdf2-9fea-4b4d-8a5a-5b94dd147ef6)
![image](https://github.com/user-attachments/assets/497aa444-b977-4969-a03f-c460e16d75aa)
The login structure we will use in our examples is straightforward. It contains two input fields (username and password), which are both vulnerable. The back-end content creates a query to approve the username and secret key given by the client. Here is an outline of the page rationale:



($query = “SELECT * FROM users WHERE username=’$_POST[username]’ AND password=’$_POST[password]’“;). For the username put “ganesh” or “anything” and for the password put (anything’ or ‘1’=’1) or (admin’ or ‘1’=’1) then try to log in, and you’ll be presented with an admin login page.
![image](https://github.com/user-attachments/assets/dce909fe-0b80-4f02-b3de-0e7c0b3b37af)
![image](https://github.com/user-attachments/assets/8df3ee76-196a-4ded-9587-901edef9be03)
![image](https://github.com/user-attachments/assets/56d0e0ca-1472-48cf-9875-9c4b1697a478)
![image](https://github.com/user-attachments/assets/cd877ac5-d716-4902-b5bd-302329064020)

## RESULT:
The SQL Injection vulnerability is successfully exploited using the Multidae web application in Metasploitable2.
