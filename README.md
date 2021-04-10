# Audio Server API
#### Generalized test case

Input 1 :-
```
ID = <INT ID INPUT>
Name = <File Name input>
Duration = <Duration of file in seconds>
```

Output 1 :-
```
HTTP <callback> OK
Allow: GET, POST, HEAD, OPTIONS
Content-Type: application/json
Vary: Accept

{
  {
    "id": <INT ID OUTPUT>
    "name": <File Name OUTPUT>
    "Duration": <Duration of file in seconds>
    "UploadTime": <Time of Upload of file>
  }
}

```

---
#### Test case 1 (Test case for INSERT)
*The input in the INT, TEXT/FILE, INT, DATE-TIME field are maped to the database via the ```POST``` button*
Input 1 :-
```
ID = 01
Name = Summertime Sadness
Duration = 185
```

Output 1 :-
```
URL :- KINDLY ADD URL HERE
```
```
HTTP 200 OK
Allow: GET, POST, HEAD, OPTIONS
Content-Type: application/json
Vary: Accept

{
  {
    "id": 01
    "name": "Summertime Sadness"
    "Duration": 185
    "UploadTime": "2021-04-10 IST:12:35:36"
  }
}

```
---
#### Test case 2 (Test case for DELETE)
*The input in the INT, TEXT/FILE, INT, DATE-TIME field are maped/comitted to the database via the ```DELETE``` button*

```ADD similar input and output fields for delete and update. Make sure that delete option is tested when nultiple files are present in the Database.```
