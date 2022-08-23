
 name: Windows-CRD

on: 
  workflow_dispatch:
    inputs:
      authcode:
        description: 'Enter CRD code'
        required: true
      pincode:
        description: 'Six digit Pin'
        required: true
  

