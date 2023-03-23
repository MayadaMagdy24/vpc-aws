# vpc-aws
- creating a vpc (10.0.0.0/16)# 
![Screenshot (618)](https://user-images.githubusercontent.com/93229250/227207136-7d540e6d-69b3-4ed7-8f2d-a8e80945d8dc.png)

- creating an internet gateway
![Screenshot (619)](https://user-images.githubusercontent.com/93229250/227207252-cd1168ab-a0c8-49a6-b31c-5bc996f4bdd5.png)

- attach igw to vpc
![Screenshot (620)](https://user-images.githubusercontent.com/93229250/227207439-0d7006d0-0b67-4fae-add7-87b1bd4a80a2.png)

- creating public (10.0.0.0/24) and private (10.0.1.0/24)subnets
![Screenshot (621)](https://user-images.githubusercontent.com/93229250/227207617-d9c94ed4-9a67-445e-a623-94d56a17de66.png)

- creating a nat on public subnet attached to private subnet
![Screenshot (622)](https://user-images.githubusercontent.com/93229250/227207831-1ceaab17-b2df-455e-b36a-9615f43a3430.png)

- creating route table for private subnet
![Screenshot (623)](https://user-images.githubusercontent.com/93229250/227207994-ceee52a5-0f10-4ac8-a655-be39ede2f0a7.png)

- creating route table for public subnet
![Screenshot (624)](https://user-images.githubusercontent.com/93229250/227208105-4f2c8ea0-998d-4214-8565-009d556022e6.png)
- set associations to public and privte subnets
![Screenshot (627)](https://user-images.githubusercontent.com/93229250/227209739-84bfe3c7-def4-498f-87a9-e2e80e07c525.png)

- launch public instance 
![Screenshot (628)](https://user-images.githubusercontent.com/93229250/227209968-1e7bd418-07ab-4f85-8539-df7b359067eb.png)

- running public ip for public insance with apache installed on it
![Screenshot (630)](https://user-images.githubusercontent.com/93229250/227210158-887db64b-0cd3-4002-995d-e188c154a454.png)
-  launch private instance 
![Screenshot (629)](https://user-images.githubusercontent.com/93229250/227210073-0582ba3c-f517-44e4-a826-83112f4ad6c0.png)

- show logs for private insance with apache installed on it
![Screenshot (631)](https://user-images.githubusercontent.com/93229250/227210539-8f4a5fe9-0067-4d24-8b2c-6a2cddc8b071.png)

