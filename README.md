# :open_file_folder: Project1-Api

## :page_facing_up: API Test Report
## :memo: How to run this project
### 🖥 Run by Postman
* Clone this repository.
* Import collection and environment file/link.
* Run the collection on Postman.
### 🖥 Run by Newman
* Clone this repository.
* Open cmd to the file location.
* Run Command:
```console
newman run Project1.postman_collection.json -e Project1.postman_environment.json
```
* Run Command for Report:

For html:
```console
newman run Project1.postman_collection.json -e Project1.postman_environment.json -r cli,html
```
For htmlextra:
```console
newman run Project1.postman_collection.json -e Project1.postman_environment.json -r cli,htmlextra
```
### :technologist: Technology used
<img src="https://voyager.postman.com/logo/postman-logo-icon-orange.svg"  width="15" height="15"> Postman & Newman

### Prerequisite
- Jdk
- Node Js
- Newman
- Html Report Library

### Newman and Report Installation Process
- Newman Install Command:
``` console
npm install -g newman-reporter-htmlextra
```
- Newman Html Report Install Command:
``` console
npm install -g newman-reporter-htmlextra
```
### API Documentations
[PDF](https://drive.google.com/file/d/1cTcDTPmWr46HHxMjB1WNLAG8ou9PUvCa/view?usp=sharing)
#### Postman Documentations
[Postman](https://documenter.getpostman.com/view/24594715/2s93m622tB)
## Test case list:

### POST
#### -Create Student
https://thetestingworldapi.com/api/studentsDetails

Body :
{ "first_name": "", "middle_name": "", "last_name": "", "date_of_birth": "{{DOB}}"
}
#### - Create Student Address
https://thetestingworldapi.com/api/addresses

Body :
{
    "Permanent_Address": {
        "House_Number": "",
        "City": "",
        "State": "",
        "Country": "",
        "PhoneNumber": [
            {
                "Std_Code": "",
                "Home": "Yes",
                "Mobile": ""
            },
            {
                "Std_Code": "",
                "Home": "No",
                "Mobile": ""
            }
        ]
    },

    "stId": 
}
#### -Create Technical Skill
https://thetestingworldapi.com/api/technicalskills

Body :
{
"id": 1,
"language": [
"",
""
],
"yearexp": "",
"lastused": "",
"st_id": 
}
#### GET
#### - Get Student
https://thetestingworldapi.com/api/studentsDetails

#### - Get Specific Student
https://thetestingworldapi.com/api/studentsDetails/{{Id}}

#### Get Final Student Details
https://thetestingworldapi.com/api/FinalStudentDetails/{{Id}}



# :clipboard: Newman Report
![image](https://github.com/Sayid1218/Project1-Api/assets/97175166/c1d0a9ae-9f22-45cb-ac78-9f76e0515078)
![image](https://github.com/Sayid1218/Project1-Api/assets/97175166/508da6b9-4631-4753-bdd0-d2b3e8e30677)
![image](https://github.com/Sayid1218/Project1-Api/assets/97175166/dbf37ccb-f41b-4d82-8814-ef0c11d7cffd)
![image](https://github.com/Sayid1218/Project1-Api/assets/97175166/62263922-0acc-476f-9dda-e919f2d6fbff)

