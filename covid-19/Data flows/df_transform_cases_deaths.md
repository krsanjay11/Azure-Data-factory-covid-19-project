# Create data flow to transform cases and deaths file
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/ae028dd0-470f-4154-9d0b-bbcc3a39d0b9)

## Details flows acitivity
### 1. Add source
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/1fb64760-4e83-42ff-81dc-abf5aef67527)
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/1bf6bfaa-2f56-4895-87ff-970a5992f0cf)
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/26c89f18-ece9-4439-84ad-2c9336c2d819)
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/948eb242-d1df-4890-b840-705b8186b7cb)
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/a2451535-e54c-4408-83e3-484bc558a159)

### 2. Apply filter to get only europe data
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/cf87b11f-796d-4e77-afb5-d3c64fa96217)
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/eca21138-2e25-4b24-9783-c3d25acbc33c)
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/fba8d62a-71d5-4b0b-8f9a-a65436a29b0a)
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/840e57a2-4fc1-4073-9b0e-15ea3ce28871)

### 3. Select only required columns
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/9fecad4f-6a1f-48ee-b8f0-9028c6805c42)
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/07fcf324-390c-48ef-9209-1d804d6734b6)
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/e6ef8bf4-54cf-438a-8f23-e09d5d63ea28)
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/c7fe254a-5234-4018-a903-dd1e6de54e1a)
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/a426a7d7-54ea-4e69-975c-74bb4de262a2)

### 4. pivot data
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/25dc7eb7-66a1-4fa1-b1cd-76a2c32dc020)
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/6d7dc425-89cc-4c32-8c9e-cea6ddfa89b8)
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/1ab2d39f-97ce-4f22-911b-dcdab7c7814c)
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/0a67eeb4-64a1-4152-a3cf-906bf9e4500f)
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/7cd6cb55-0aaf-4361-9706-a644d7d48d3a)
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/2e719664-d2d6-4572-a204-2aa83b57349b)

### 5. Apply lookup 
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/05941062-f81a-4309-8b83-fa7b870fb99e)
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/28c86d08-ea93-4a8d-a57c-1c8aa04e6d08)
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/acb6a92d-8f35-40ae-a4e0-a8e466b03fc9)
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/a6b1392a-a5e0-4c28-b471-1944227007e6)
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/ed985634-acd2-4e17-a9ca-a67767e150a5)
## from country source
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/7db81a2b-2d72-4863-b488-9938173f0bd8)
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/f43f9cc9-295d-487a-919e-2c78ae4506a0)
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/1e922b9b-8001-4d12-9a13-fc154f79db81)
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/48bc205b-5591-42ec-bbd9-7664688554da)
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/0028d6bd-eec2-4bd2-83b4-86c7cb7b609b)

### 6. Select final columns for sink
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/e7a54d3e-1eeb-47ff-bd28-d7a6b6e4b18e)
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/11b0b91f-d840-419e-8978-10ab71421844)
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/460941c2-fb3d-4f54-a29d-7c1aa03a0b4a)
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/b416fb13-5c7a-4321-8a5f-c5e753737ee7)
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/4efbe24e-3270-4198-acae-38f53ae76c39)

### 7. Create sink file
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/23cf7232-e90f-499d-9c9a-2b3436fedfc1)
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/3f2583e7-84ca-4d70-b526-fe1085d34e69)
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/a994971d-3202-4588-888d-389daae157e2)
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/739a2066-0cca-4952-8410-0d497fda8b6e)
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/e0584113-77c5-4ee6-bbff-1eac320851bc)
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/80b73bc4-13b8-47c8-8cd7-f7dfac900731)






