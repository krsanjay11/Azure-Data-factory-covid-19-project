# Final Pipeline to ingest population file from blob storage to Datalake GEN 2 storage- 
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/b469f3e5-1a5a-4ea7-b716-b0a38506a681)

## Step 1 - Creating Validation Pipeline
### In this, we will check if source file/dataset exist to further start the pipeline activities 
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/ba4a22c3-ac11-4383-ba61-d90b32c2f798)
### Adding properties
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/6a2a0fa5-e9d0-4029-922a-eb1642f0ac47)

![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/7d7712e9-dab8-4641-9f5e-9a70e445a3c2)

## Step 2 - Get Meta Data from the file/dataset
### Azure has some pre-define metadata activities from which we can select the required operation for our project
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/6e972935-17ed-42c7-8d47-a033f24f2da0)
### Adding Properties
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/bab3caa8-2904-47cf-9aef-ccd94cf279a1)

 ### we have different meta-data functions to extract information about the file
 ![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/2683a0b1-6362-47bf-a129-094538523c71)
 
 #### we will choose column count, size, and Exits metadata function for our project
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/c29715cf-ea00-45e7-8a8f-dbb07ab2814c)

## Step 3 - Creating Copy activity
### Before we create our copy activity, we will check some file properties and conditions extracted from metadata activities and based on the condition, we will create a condition flow i.e. If condition Activity
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/17fd731c-00d0-4e9b-9a4c-266251bc6bfb)

### 3.1 - If Condition
### Adding properties
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/76a01ca8-d7ab-472b-a704-1aa92e53a1ab)

### if the condition matches, we start True flow else False flow
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/8e9883d0-2f0f-4e7e-98da-879394c8f5fd)

Conditions - 
1. Check if the file exists
2. Size of the file
3. check if the column count is as per the requirement
   
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/ba18187b-b38b-4c39-b77c-8aef84312f48)

### 3.2 - True activity
### if all the condition met then execute True flow
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/19b04639-c73c-45de-83d8-99689d4a1c63)

#### 3.2.1 - Copy Activity
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/2f965e2e-2afd-4071-8360-5d7baa48f887)
### Adding Properties
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/351bacae-7995-4c23-a6a6-8c8348227bc6)
### Adding source
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/db144fe4-4756-4213-9834-bd3ca0d0ba48)
### Adding Sink
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/4773e2a9-0997-4ef0-9a9f-249257a98f6e)

#### 3.2.2 - Adding Delete activity after copy activity succeed
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/ec6f991b-53cb-4f40-8b73-d318efe09b85)

![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/9f8237f3-610d-4652-9a08-f63bc030fe80)

![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/3e833225-d0b9-497f-aadc-f92e31da7f0c)

### 3.3 - False Activity
### if condition not met, we can send email about the failure of pipeline
#### Select web activity
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/b571528a-1b97-480c-b2cb-9eca0b10e39b)
### Adding properties
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/2eaca796-9908-40d5-8ecf-d3a75753d5c1)
### we can give valid link with post capabilities
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/626fdc57-5ec5-4ac5-96b3-ab002f67f108)















