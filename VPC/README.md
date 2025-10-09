#🔀 VPC Peering🔀

Here i have created two VPC bwtween different reason and peer them. Then test the communication between instances in each VPC.

### Singapoor reason VPC✅
Here i have created the VPC for Singapoor reson 
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/fc24d414-8291-43ac-a834-06894b0586f4" />

### Subnet
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/51a51399-8bcd-4132-a73d-8c50f7ab5591" />

### Internet gatway 
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/ef6fd87f-e421-4877-92e5-3088b715d1e6" />

### Routing table 
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/61ade0c3-bedf-4c2a-8772-2ff168fad8d5" />

### Security group
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/e2781a23-21d0-46d3-a5bb-3e0de50aa96c" />

### Singapoor Instance
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/9f9a488e-d46f-4799-a256-eecbcca02a52" />

## Explination:-
Here i have created the Singapoor VPC with igw,routing table and subnet attached security group , and then launch the instance wich is in **private** .

### Mumbai reason VPC✅
Here i have created other VPC for mumbai reason
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/6b9acab4-0613-49a3-bc29-4bffeec89378" />

### Subnet
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/01debdd7-8307-4e13-8f38-e2c11ae12bbf" />

### Internet gatway 
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/5cb4355c-7246-468e-a950-ccd47d99ffaa" />

### Routing table 
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/73b47401-3aad-406a-9fd0-15b28908bb29" />

### Mumbai Instance
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/55ffb15a-908d-4461-9eea-0d2aee443a03" />

### Trying to ping fron singapoor to mumbai but we fail
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/38dc6f88-69ed-40d6-8fbc-c61d7cb71275" />

### Now we need to create peering connection
Here we have created peering connection ist successfull 
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/eeda707e-a2e1-4afe-8568-92eade6e54d4" />

<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/a6d4f494-6ad6-480d-af4c-6a8ef6f180d5" />

### Accept the connection from mumbai reason
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/67e056cc-33c1-47a1-88fc-bbfb7725a8cc" />

<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/0d6d9e57-5e0b-4372-925f-72a1eafddda4" />

### Finally the Peering betwwn two VPC is Succesfull 🔥
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/b6f30dbe-d0d4-493e-b92d-77c52ed189f1" />


