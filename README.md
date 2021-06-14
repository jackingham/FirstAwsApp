# Spinning up an EC2 instance
## Configuring the instance
- Log into AWS
- Select EC2 
- ![image](https://user-images.githubusercontent.com/32297246/121968385-2a9b9980-cd6a-11eb-877d-7d7598153b48.png)
- Select launch instance 
- ![image](https://user-images.githubusercontent.com/32297246/121968358-1a83ba00-cd6a-11eb-8e22-b438f8ee76e6.png)
- Select Ubuntu Server 16.04 
- ![image](https://user-images.githubusercontent.com/32297246/121968511-5c146500-cd6a-11eb-9839-87cffec4f4c2.png)
- Select t2.micro
- ![image](https://user-images.githubusercontent.com/32297246/121968535-69315400-cd6a-11eb-82cf-41ca42754bb7.png)
- Change the subnet to the DevOpsStudentSubnet and enable public IP
- ![image](https://user-images.githubusercontent.com/32297246/121968632-94b43e80-cd6a-11eb-96fd-c36291d08b71.png)
- Leave storage as is and press next 
- ![image](https://user-images.githubusercontent.com/32297246/121968671-a269c400-cd6a-11eb-8da0-0e74d58b92fe.png)
- Add a name tag 
- ![image](https://user-images.githubusercontent.com/32297246/121968705-b1e90d00-cd6a-11eb-834c-22a908a0fbbc.png)
- Create a new security group or pick a pre defined one with correct rules and access
- ![image](https://user-images.githubusercontent.com/32297246/121968758-cd541800-cd6a-11eb-9f46-cb86c0a5d0bd.png)
- This allows SSH only from your own machine, allows public access to the web server on port 80 and app on port 3000
- Press review and launch then launch to launch the server!
- ![image](https://user-images.githubusercontent.com/32297246/121968877-068c8800-cd6b-11eb-8cf7-d100d033a36b.png)



