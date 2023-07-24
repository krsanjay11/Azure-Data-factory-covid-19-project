# Create data flow to transform transform hospital admissions
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/1feee054-3903-405a-b028-bb071cc49d7b)
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/bbf48769-cac2-4fd7-83e6-967c05ff4599)

### 1. Create source file
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/825e2d35-6dbe-4f0d-a36a-67b9b7688d6b)
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/e5188138-2225-401d-b379-a99c791d3272)
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/7f7091b2-22d6-4ce4-8d98-279254950d48)
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/2ffee81a-dca7-4729-934d-673628135961)
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/860550c4-0871-4bf0-a8ce-791f095ad423)

### 2. select columns
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/5adb60dd-faed-407f-9fca-0f07ccb2b070)
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/0cc36458-5143-4883-8dd9-c8357bc82eb5)
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/93184982-5ec2-445d-a3e0-2150f2ab65ee)
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/caa1c767-3acb-4133-8814-7cbad23b556f)
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/b72c0352-757e-4f45-82a8-ff9d264ac4cd)

### 3. apply lookup
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/6a40791b-0e93-426d-b666-58b2920e84f1)
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/f63c4cdc-a051-4c18-b7f4-bc35dee40338)
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/c8153578-0b2d-4804-82f1-422c152de468)
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/d4fd083e-8e83-4339-afa8-a283f8386e40)

## From
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/3a6a5421-9277-46cf-9a07-fcbffb7f91a7)
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/2f05f05f-b28a-4d2d-a9b3-7f0e676d1b09)
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/8096513e-67f9-4863-a50e-3fe8f758f0f6)
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/c910b7a7-52e9-41d7-847e-e3b25acb37d4)
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/06101d2a-5502-4b58-8286-bec1c781f019)

### 4. select required field
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/093b8a71-7a9c-4b7a-b781-308995a46194)
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/9263a444-d3fc-45c6-9cb9-030e59746d93)
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/671e3131-79e6-41c8-9625-b85b3a7ae5b3)
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/27c96319-fc9e-4f65-a663-910df25febeb)
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/307aef78-f08b-4933-86d0-e2be04a176d8)

### 5. split data into daily and weekly
### 5.1 split weekly
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/1cd21295-c7d7-4c0a-9937-ca1c0814a07d)
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/38825558-5191-4d52-a16b-5a9b5712edad)
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/27b0f047-db4e-46fd-b06f-a9aea0f61d40)
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/b06c3969-7b33-4a70-8c5b-7d9299057cd9)
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/e8ec9206-7fee-41c5-a73a-73166d26fb65)
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/48815938-6831-4d0d-8c6c-22d95cc1034b)

### 5.2 Join with date using aggregate
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/2e3d862a-1f69-4cc4-aaf3-513d30dca89d)
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/3af38e4b-9010-48b8-91be-8957d685be6a)
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/a1d5db7a-275d-4c0c-960d-d8fa771a66d5)
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/49a0e0a6-cf3e-461c-b143-9ef2098e4125)
![image](https://github.com/krsanjay11/Azure-Data-factory-covid-19-project/assets/21271522/ffa5701c-70c9-4dea-95e3-ae5d8f5a15ae)
## aggregate from









