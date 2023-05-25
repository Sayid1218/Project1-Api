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
#### Create Student
Body
{ "first_name": "", "middle_name": "", "last_name": "", "date_of_birth": "{{DOB}}"
}
- Create Student Address
#### GET
- Find Job by Keyword.
- Get job Details.
- Get applied jobs.
#### DELETE
- Delete applied job.


# Newman Report
![image](https://github.com/Sayid1218/Quick-Solution-API-Test-Report/assets/97175166/3b6cce36-6035-48f2-9f64-1dde7741dc13)
![image](https://github.com/Sayid1218/Quick-Solution-API-Test-Report/assets/97175166/c9d5fad0-ee9a-4ecc-8e67-4d1fa32a0c46)
![image](https://github.com/Sayid1218/Quick-Solution-API-Test-Report/assets/97175166/7890e125-7d8c-4c76-bc45-91221633f2de)

