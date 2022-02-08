# 1640-Enterprise-Web-Software-Development
Table of Contents
Table of Contents	1
List of Figures	4
List of Tables	9
Cover page	10
I.	Introduction	11
II.	Requirement	11
1.	Functional 1:	13
2.	Functional 2:	14
3.	Functional 3:	15
4.	Functional 4:	15
5.	Functional 5:	16
6.	Functional 6:	17
7.	Functional 7:	17
8.	Functional 8:	18
9.	Functional 9:	19
10.	Functional 10:	19
11.	Functional 11:	20
12.	Functional 12:	22
13.	Functional 13:	22
14.	Functional 14:	23
III.	Database	24
1.	Introduction	24
2.	Physical design:	25
IV.	Design	33
1.	Sitemap	33
2.	Wireframes	34
a.	Home page	34
b.	Login page	35
c.	Admin	36
d.	Marketing Manager	44
e.	Marketing Coordinator	49
f.	Student	54
g.	Guest	58
3.	Interface	60
a.	Home page	60
b.	Login page	60
c.	Admin	61
d.	Marketing Manager	66
e.	Marketing Coordinator	69
f.	Student	71
g.	Guest	73
V.	Implementation	74
1.	Techniques	74
a.	Back-end	74
b.	Front-end	75
c.	Database	75
d.	Hosting	76
2.	Flowcharts and features	77
a.	Marketing Manager	77
b.	Marketing Coordinator	84
c.	Student	90
d.	Admin	94
e.	Guest	97
VI.	Testing	100
1.1. Test plan	100
1.1.1. Team members	100
1.1.2. Scope	100
1.1.3. Test Approach	101
1.1.4. Test Environment	101
1.1.5. Assumptions/Risks	102
1.1.6. Test schedule	104
1.1.7. Deliverables	105
1.2. Sprint 1	105
1.2.1. Test Cases and Test Logs of Sprint 1	105
1.2.2. Sprint 1 backlog	121
1.2.3. Sprint 1 burndown chart	121
1.3. Sprint 2	123
1.3.1. Test Cases and Test Logs of Sprint 2	123
1.3.2. Sprint 2 backlog	128
1.3.3. Sprint 2 burndown chart	133
1.4. Sprint 3	134
1.4.1. Test Cases and Test Logs of Sprint 3	134
1.4.3. Sprint 3 burndown chart	143
1.5. Test evidence	144
VII.	Agile	156
2.1. Product backlog	156
2.2. Product burndown chart	159
2.3. Team challenges	159
2.4. Minutes of meetings	162
VIII.	Conclusion	164

List of Figures
Figure 1: Functional 1	14
Figure 2: Functional 2	14
Figure 3: Functional 3	15
Figure 4: Functional 4	16
Figure 5: Functional 5	16
Figure 6: Functional 6	17
Figure 7: Functional 7	18
Figure 8: Functional 8	18
Figure 9: Functional 9	19
Figure 10: Functional 10	20
Figure 11: Functional 11.1	20
Figure 12: Functional 11.2	21
Figure 13: Functional 12	22
Figure 14: Functional 13	22
Figure 15: Functional 14	23
Figure 16: ERD of system	24
Figure 17: use case Student of system	26
Figure 18: use case Marketing manager of system	27
Figure 19: use case Marketing coordinator of system	27
Figure 20: use case Admin of system	28
Figure 21: use case Guest of system	29
Figure 22: data security code	30
Figure 23: data validation code	30
Figure 24: fire base authentication database online	31
Figure 25:  fire base real-time database online	31
Figure 26:  fire base storage database online	32
Figure 27: Sitemap	33
Figure 28: Wireframes homepage	34
Figure 29: Wireframes Login page	35
Figure 30: Wireframes Admin Index	36
Figure 31: Wireframes Admin create Student account	37
Figure 32: Wireframes Admin create Marketing Coordinator account	38
Figure 33: Wireframes Admin create Guest account	39
Figure 34: Wireframes Admin create Marketing Manager account	40
Figure 35: Wireframes Admin Edit account	41
Figure 36: Wireframes Admin Index course	42
Figure 37: Wireframes Admin Edit course	43
Figure 38: Wireframes Marketing Manager Index	44
Figure 39: Wireframes Marketing Manager View Course	45
Figure 40: Wireframes Marketing Manager View Submissions	46
Figure 41: Wireframes Marketing Manager View Contributions	47
Figure 42: Wireframes Marketing Manager View Exceptional	48
Figure 43: Wireframes Marketing Coordinator IndexMarketing Coordinator Index	49
Figure 44: Wireframes Marketing Coordinator Mark	50
Figure 45: Wireframes Marketing Coordinator Marking student	51
Figure 46: Wireframes Marketing Coordinator Marking Index chat with student	52
Figure 47: Wireframes Marketing Coordinator Marking chat with student	53
Figure 48: Wireframes Student Index	54
Figure 49: Wireframes Student Submit file	55
Figure 50: Wireframes Student Index chat Marketing Coordinator	56
Figure 51: Wireframes Student chat Marketing Coordinator	57
Figure 52: Wireframes Guest Index	58
Figure 53: Wireframes Guest view submission	59
Figure 54: Interface Home page	60
Figure 55: Interface Login page	60
Figure 56: Interface Admin Index	61
Figure 57:Interface Admin create Admin account	61
Figure 58: Interface Admin create student account	62
Figure 59: Interface Admin create Marketing Coordinator account	62
Figure 60: Interface Admin create Guest account	63
Figure 61: Interface Admin create Marketing Manager account	63
Figure 62: Interface Admin Edit account	64
Figure 63: Interface Admin Index course	65
Figure 64: Interface Admin Edit course	65
Figure 65: Interface Marketing Manager Index	66
Figure 66: Interface Marketing Manager View Courses	66
Figure 67: Interface Marketing Manager View Submissions	67
Figure 68: Interface Marketing Manager View Contributions	67
Figure 69: Interface Marketing Manager View Exceptional	68
Figure 70: Interface Marketing Coordinator Index	69
Figure 71: Interface Marketing Coordinator Mark	69
Figure 72: Interface Marketing Coordinator Marking student	70
Figure 73: Interface Marketing Coordinator Marking Index chat with student	70
Figure 74: Interface Marketing Coordinator Marking chat with student	71
Figure 75: Interface Student Index	71
Figure 76: Interface Student Submit file	72
Figure 77: Interface Student Index chat Marketing Coordinator	72
Figure 78: Interface Student chat Marketing Coordinator	73
Figure 79: Interface Guest Index	73
Figure 80: Interface Guest view submission	74
Figure 81: Flowcharts View exceptional reports	77
Figure 82: Features View exceptional reports	78
Figure 83: Flowcharts View all selected submissions	79
Figure 84: Features View all selected submissions	80
Figure 85: Flowcharts Download submissions by ZIP format	81
Figure 86: Features Download submissions by ZIP format	82
Figure 87: Flowcharts View statistics	83
Figure 88: Flowcharts View submissions from students in specific faculty	84
Figure 89: Features View submissions from students in specific faculty	85
Figure 90: Flowcharts Receive notifications (emails) for new submissions	86
Figure 91: Features Receive notifications (emails) for new submissions	87
Figure 92: Flowcharts Give comments for each submission	88
Figure 93: Feature Give comments for each submission	88
Figure 94: Flowcharts Determine to accept or reject submissions	89
Figure 95: Feature Determine to accept or reject submissions	89
Figure 96: Flowchart Submit article in Word format (1 or more) before first closure date, can edit before final closure date (after first closure date)	90
Figure 97: Feature Submit article in Word format (1 or more) before first closure date, can edit before final closure date (after first closure date)	91
Figure 98: Flowchart Upload images	92
Figure 99: Feature Upload images	92
Figure 100: Flowchart Read comments for own submissions	93
Figure 101: Feature Read comments for own submissions	93
Figure 102: Flowchart Create new accounts	94
Figure 103: Feature Create new accounts	95
Figure 104: Flowchart Set and edit closure date	96
Figure 105: Feature Set and edit closure date	97
Figure 106: Flowchart View selected reports for each faculty	98
Figure 107: Feature View selected reports for each facult	99
Figure 108: Sprint 1 Burndown Chart	122
Figure 109: Sprint 2 Burndown Chart	133
Figure 110: Sprint 3 Burndown Chart	143
Figure 111: Test evidence of the login function	144
Figure 112: Test evidence of the logout function	145
Figure 113: Test evidence of the function to create and edit update time, closing time	145
Figure 114: Test evidence of the function to create account	146
Figure 115: Test evidence of the function to store and preserve all system data	147
Figure 116: Test evidence of the function to submit articles	147
Figure 117: Test evidence of the function to read comments for own submissions	148
Figure 118: Test evidence of the function to update contributions until a final closure date	149
Figure 119: Test evidence of the function to accept the terms and conditions	149
Figure 120: Test evidence of the function to receive email notifications	150
Figure 121: Test evidence of the function to make comments for student's articles	151
Figure 122: Test evidence of the function to view contributions from students in faculty	151
Figure 123: Test evidence of the function to interact with the students in faculty	152
Figure 124: Test evidence of the function to select contributions to publish	152
Figure 125: Test evidence of the function to view all the selected contributions	153
Figure 126: Test evidence of the function to view the exceptional reports	154
Figure 127: Test evidence of the function to download all selected contributions as zip file	154
Figure 128: Test evidence of the function to keep track of faculty data	155
Figure 129: Test evidence of the function to view faculty selected reports	155
Figure 130: Product Burndown Chart	159
List of Tables
Table 1: Requirement	13
Table 2: Physical design	26
Table 3: Team members and Roles	100
Table 4:Risk	103
Table 5: Test schedule	104
Table 6: Sprint 1	117
Table 7: Test case and Test log for student account	120
Table 8: Sprint 1 backlog	121
Table 9: Test Cases and Test Logs of Sprint 2 for admin account and marketing coordinator account	127
Table 10: Sprint backlog 2	132
Table 11: Test Cases and Test Logs of Sprint 3 for admin account and marketing coordinator account	135
Table 12: Test Cases and Test Logs for marketing manager account and guest account	137
Table 13: Sprint 3 backlog	142
Table 14: Product backlog	158
Table 15: Minutes of meetings	164
Cover page
 	Group members:
-	Nguyen Hoang Thuyen, ID: 001181275, Role: Programmer, Information architect, Product owner
-	Pham Ngoc Bao, ID: 001181141, Role: Web designer, Programmer
-	Do Ho Nguyen, ID: 001181241, Role: Tester
-	Nguyen Van Tuan, ID: 001181305, Role: Scrum master, Tester
-	Do The Vinh, ID: 001181111, Role: Database designer, Web designer
-	Ha Ngoc Vi, ID: 001143934, Role: Web designer
 	Repository: https://github.com/Thuyen21/EW
 	Screen Cast: http://www.youtube.com/watch?v=wBGnxqTTZpU
 	Public Site: http://crt.somee.com/
 	Backlog: 
-	https://docs.google.com/spreadsheets/d/1jufthGaESFc8EW44YYNgoAw5PF4Eu8OZur5H6tMhUDY/edit?usp=sharing
 	User account:
-	Admin: admin@gmail.com Password: adminadmin
-	Marketing Manager: TuanMM1@gmail.com Password: TuanMM1@gmail.com
-	Marketing Coordinator: cje.madlife2000@gmail.com Password: cje.madlife2000@gmail.com
-	Student: studentbao@gmail.com Password: studentbao@gmail.com
-	Student2: pnb@gmail.com Password: pnb@gmail.com
-	Guest: TuanGuest1@gmail.com Password: TuanGuest1@gmail.com
I.	Introduction
We formed a group to collaborate on a project. The goal of this project is to create a collection site as well as a place for students to submit papers. The goal was to design a website for the prestigious university. With such a goal in mind, we convene and quickly divide the positions in order to begin project implementation. We need a database designer, an information architect, a programmer, a web designer, a tester, and a scrum specialist before we can spend any money. It is necessary to prepare the necessary knowledge for the project. We must ensure that the website is built to meet the 16 criteria set forth during the website concept and construction process. Divide the implementation phases and implement continuous progress checks to ensure the construction is moving in the right direction, adhering to the requirements, and progressing.
II.	Requirement
In order to build and create websites, we have to adhere to the requirements for which the criteria are given and they must meet the system. Below are the criteria given. From the given criteria, which one has we classified as the Functional Requirement and which one is the Non-functional Request.
 
ID	Type	Reason why I decide it belong to functional or non-functional requirement
1	Functional	Because this requirement belongs to the technical, decentralized and functional part of the system
2	Functional	Because the part's functional decentralization, technical
3	Functional	Because of the requirements and performance of the system requirements, user interaction, description of the function that needs to be performed.
4	Functional	Because of the quality properties of the system. Standards specified by the system
5	Functional	Because it belongs to the functional and technical part of the system
6	Functional	Because it belongs to the functional and technical part of the system
7	Functional	Because belonging to user interaction, capture the behavior to perform the required task
8	Functional	 Because of the technical part, the decentralized function
9	Functional	Because of the user interaction, the request to capture data to request performance
10	Functional	Because it's technical, first use decentralization so that the director can perform his own function. The second is the requirement to submit the correct form
11	Functional	Because it belongs to the functional requirements of the system
12	Functional	Because belonging to the system's functional requirements, capture and statistic data.
13	Functional	Drugs on reviews, quality attributes
14	Non-Functional	Because of the properties and quality, namely the user interface, tailored to the devices
Table 1: Requirement
1.	Functional 1:
It works. In my project I have role Marketing Manager View statistics, view exceptional reports View all selected submissions from every faculty
 
Figure 1: Functional 1
2.	Functional 2:
It works. Each faculty have 1 Marketing Coordinator, and Marketing Coordinator have function mark student, view submission and comment student
 
Figure 2: Functional 2
3.	Functional 3:
It works. Student can submit word files
 
Figure 3: Functional 3
4.	Functional 4:
It works. Student can upload images:
 
Figure 4: Functional 4
5.	Functional 5:
It works. Student can submit before date end and can edit submission before date final
 
Figure 5: Functional 5
6.	Functional 6:
It works. Student must tick in Agree to Terms and Conditions to submit
 
Figure 6: Functional 6
7.	Functional 7:
It works. When their students submit work, the Marketing Coordinator receives mail.
 
Figure 7: Functional 7
8.	Functional 8:
It works, only the Marketing Coordinator can mark, comment and view submission in their faculty
 
Figure 8: Functional 8
9.	Functional 9:
It works. Marketing Coordinator can chat with their students
 
Figure 9: Functional 9
10.	Functional 10:
It works. Marketing Manager can see all of the selected contributions and can download file zip contributions
 
Figure 10: Functional 10
11.	Functional 11:
Admin can edit all the account and all the faculty.
 
Figure 11: Functional 11.1
 
Figure 12: Functional 11.2
 
12.	Functional 12:
Guest can only view selected report of Faculty which admin assign guest in.
 
Figure 13: Functional 12
13.	Functional 13:
Marketing Manager can pick a Faculty to view Statistical analysis
 
Figure 14: Functional 13
14.	Functional 14:
This web can view in all devices
 
Figure 15: Functional 14
1.	Functional 1:
It works. In my project I have role Marketing Manager View statistics, view exceptional reports View all selected submissions from every faculty
 ![image](https://user-images.githubusercontent.com/94780400/152953408-78283153-502b-4c73-ac96-152923a983f5.png)
Figure 1: Functional 1
2.	Functional 2:
It works. Each faculty have 1 Marketing Coordinator, and Marketing Coordinator have function mark student, view submission and comment student
![image](https://user-images.githubusercontent.com/94780400/152953468-b25e1ab8-4ee1-4a07-ad69-a9c4bc5158d8.png)
3.	Functional 3:
It works. Student can submit word files
![image](https://user-images.githubusercontent.com/94780400/152953485-bd4510f0-b1f7-49f7-8136-a2a7fd14ea1c.png)
4.	Functional 4:
It works. Student can upload images:
![image](https://user-images.githubusercontent.com/94780400/152953513-0b742e1c-6eb6-4578-88f4-d94cec6b1bf5.png)
5.	Functional 5:
It works. Student can submit before date end and can edit submission before date final
![image](https://user-images.githubusercontent.com/94780400/152953541-eb920875-a55b-414f-ba2d-9f1e150fc7dd.png)
6.	Functional 6:
It works. Student must tick in Agree to Terms and Conditions to submit
![image](https://user-images.githubusercontent.com/94780400/152953567-6bdbfbbc-7b23-4aa8-a91d-8b8428f91238.png)
7.	Functional 7:
It works. When their students submit work, the Marketing Coordinator receives mail.
![image](https://user-images.githubusercontent.com/94780400/152953600-d671f23a-032b-4780-b112-0ab8dd1632f6.png)
8.	Functional 8:
It works, only the Marketing Coordinator can mark, comment and view submission in their faculty
![image](https://user-images.githubusercontent.com/94780400/152953886-3f7a830c-ddbc-4295-906a-3c29fdddfa1d.png)
9.	Functional 9:
It works. Marketing Coordinator can chat with their students
![image](https://user-images.githubusercontent.com/94780400/152953901-69be60b0-0dc1-4689-b98c-b2dd4950759b.png)
10.	Functional 10:
It works. Marketing Manager can see all of the selected contributions and can download file zip contributions
![image](https://user-images.githubusercontent.com/94780400/152953931-5b240524-b177-4be9-99ef-1f3792fe7044.png)
11.	Functional 11:
Admin can edit all the account and all the faculty.
![image](https://user-images.githubusercontent.com/94780400/152953988-c057f425-db19-4b67-836c-10dcbf6e8895.png)
![image](https://user-images.githubusercontent.com/94780400/152953997-583ac2fe-3f33-4a27-8e10-f26bf2198c44.png)
12.	Functional 12:
Guest can only view selected report of Faculty which admin assign guest in.
![image](https://user-images.githubusercontent.com/94780400/152954029-aa2e7f7c-5ad3-426c-8cc2-849906d292be.png)
13.	Functional 13:
Marketing Manager can pick a Faculty to view Statistical analysis
![image](https://user-images.githubusercontent.com/94780400/152954085-3a0da97d-2fb9-474d-918e-031ada289a81.png)
14.	Functional 14:
This web can view in all devices
![image](https://user-images.githubusercontent.com/94780400/152954107-18404c58-0382-4da5-9dc7-bbad4872217b.png)
III.	Database
1.	Introduction
This report will provide users with an overview of the system and usage purposes. This report covers ERDs, use case diagrams, an introduction to firebase databases used in projects and data security, data validation, followed by understanding the system and clarifying how operation of the system. Analyzing the network journal system of the University of Greenwich, introducing and learning about the use case diagram to help users better understand how the system works and the tasks of each actor, giving advantages and disadvantages and Things to improve in the system
Why choose a firebase database for the project:
•	firebase helps you build and run successful apps
•	Supported by Google and popular with companies and users by convenience
•	Easily use and integrate Firebase with open technology tools like google marketing platform, data studio
•	Trusted used for high-security safety.
![image](https://user-images.githubusercontent.com/94780400/152954139-797fc448-d823-4020-a832-08cbfa1956c2.png)
Figure 16: ERD of system
Collecting user criteria, the database was created into 6 tables, for each table followed standardized rules to minimize duplication. First look at the visible entities that are magazine and user, then we can access the ads and editorial, so there are 4 entities in total. From there I will add the role for the user and post for the ads as it is an important part of the way the system works. In general, a simple ERD will have 6 entities: user, magazine, ads, editorial, role, and post with each of the properties below.
2.	Physical design:
![image](https://user-images.githubusercontent.com/94780400/152954222-a9a5b5a1-7953-4c93-8b52-66166fcde09e.png)
First, for students, it is possible to upload high-quality images, read comments for their submissions, update contributions until the final closing date.
![image](https://user-images.githubusercontent.com/94780400/152954274-1613095d-28ed-4711-adae-6f878e80cd26.png)
-	For the marketing director that can view all selected contributions, special reports can be viewed, all selected contributions can be downloaded as a zip file, track contribution count, plus contributors, and percentage contributions of many faculties.
-	![image](https://user-images.githubusercontent.com/94780400/152954373-bd0f4383-ca4c-479c-b4b0-eb2162992a71.png)
-	The marketing coordinator can log in, log out of accounts on the system, receive email notifications from the system, make comments for students' posts, within 14 days after the system stops accepting new posts, view contributions from students in my faculty, interact with students in my faculty, select contributions to publish.
-	![image](https://user-images.githubusercontent.com/94780400/152954393-77835309-6407-4f3c-865c-97ef81c99780.png)
-	For administrators can maintain all system data, control update time, close time, create new accounts and control login permissions, create approval terms and conditions before students submit their articles.
-	![image](https://user-images.githubusercontent.com/94780400/152954418-28745907-4769-4391-ae11-02bed94da585.png)
-	![image](https://user-images.githubusercontent.com/94780400/152954441-a199dc52-ed27-47ed-949c-842cae7c9c45.png)
Figure 21: use case Guest of system
-	What is data security:
•	Data security is the process of protecting data from unauthorized access and theft throughout its entire life cycle. Similar to the project we deploy to have encrypted information and data. For example, when the user creates an account and logs in the system, the password will be encrypted in is fire base authentication to avoid status steal passwords from users.
![image](https://user-images.githubusercontent.com/94780400/152954485-e0458a61-08dd-4ace-b104-46f4642bb917.png)
-	What is data validation:
•	Data validation is checking the accuracy of the source data before using, importing, or otherwise using the data. To be more precise, data validation is a way of data cleansing. For example, the system developed by this project for users when registering an account to log into the system, when the user enters the password must have enough from 8 to 16 characters including letters and numbers, Registered user account must be @ gmail.com.
![image](https://user-images.githubusercontent.com/94780400/152954511-38c3e6f3-a8c9-42e0-a78e-5a1bc8aaacdd.png)
![image](https://user-images.githubusercontent.com/94780400/152954523-12f01797-9eb1-4d15-9dc9-4c6d1c53f366.png)
![image](https://user-images.githubusercontent.com/94780400/152954538-dc4a72e1-a739-4975-976b-94d66ee66aef.png)
Figure 24: fire base authentication database online
•	The system contains accounts, passwords, including students, guests, admin, and marketing management.
![image](https://user-images.githubusercontent.com/94780400/152954571-dac935ce-d329-46a0-848c-cb3ce2cc35da.png)
![image](https://user-images.githubusercontent.com/94780400/152954585-22c36ff4-b594-4c40-bc05-067c1cff7ec1.png)
Figure 26:  fire base storage database online
A place to store documents submitted by students such as photos, documents, reports in zip format.
IV.	Design
1.	Sitemap
![image](https://user-images.githubusercontent.com/94780400/152954623-8908e744-5c55-41ad-9270-ca98fefa9c62.png)
2.	Wireframes
a.	Home page
![image](https://user-images.githubusercontent.com/94780400/152954644-93b61df2-4b94-44ed-9ae2-ecff95f86648.png)
![image](https://user-images.githubusercontent.com/94780400/152954655-8b3b5477-d5a3-47fd-b4d9-1e4385d2f6d4.png)
![image](https://user-images.githubusercontent.com/94780400/152954690-33748184-ffe7-46de-9301-38dd363f9793.png)
![image](https://user-images.githubusercontent.com/94780400/152954698-5890737c-4238-4085-a42d-9790e00c255f.png)
![image](https://user-images.githubusercontent.com/94780400/152954715-2d81f583-081f-43ff-b6a3-6831cd712bd6.png)
![image](https://user-images.githubusercontent.com/94780400/152954734-dfec0021-48d4-4711-8103-a5aa36d5db07.png)
![image](https://user-images.githubusercontent.com/94780400/152954749-3bb8f98b-bd83-4140-817a-0e5cf69ff004.png)
![image](https://user-images.githubusercontent.com/94780400/152954763-79b5e493-84a0-4b9f-af49-93888b44bd28.png)
![image](https://user-images.githubusercontent.com/94780400/152954771-25620a29-21d5-4ceb-8672-05e1802eaac6.png)
![image](https://user-images.githubusercontent.com/94780400/152954785-b64eec42-58a8-4de0-97e8-b76797139aa9.png)
![image](https://user-images.githubusercontent.com/94780400/152954804-4b5cd945-a654-4c72-a6c8-8f4e310f8865.png)
![image](https://user-images.githubusercontent.com/94780400/152954821-d6efeeb4-cc90-46f4-bd3e-561d62ca2663.png)
![image](https://user-images.githubusercontent.com/94780400/152954832-e0e4db2a-4d41-423f-a380-ea40cd2b55bc.png)
![image](https://user-images.githubusercontent.com/94780400/152954843-8e4497c8-4e5d-4923-ac4d-6d9b376217aa.png)
![image](https://user-images.githubusercontent.com/94780400/152954855-e69c7f59-afb4-49ea-98ce-74c476170ff1.png)
![image](https://user-images.githubusercontent.com/94780400/152954867-1cbb84a4-e4c7-411a-b3d5-5deaa455707b.png)
![image](https://user-images.githubusercontent.com/94780400/152954883-f62c0d0b-a41d-4242-8e39-5aaf0ee6bb14.png)
![image](https://user-images.githubusercontent.com/94780400/152954957-290ccf4b-1a49-4e2c-98f4-727b0a18ca31.png)
![image](https://user-images.githubusercontent.com/94780400/152954977-829266aa-d317-4c74-9894-f7fd6b3b634b.png)
![image](https://user-images.githubusercontent.com/94780400/152954988-8cd25d9a-8bc7-4154-819e-863d56da6bfb.png)
![image](https://user-images.githubusercontent.com/94780400/152955013-9c248efe-8ecc-45db-9dc3-ef44730f9677.png)
3.	Interface
a.	Home page
![image](https://user-images.githubusercontent.com/94780400/152955045-bcf73114-e9da-455c-bba9-9ba2b700f601.png)
![image](https://user-images.githubusercontent.com/94780400/152955035-127f1b2c-cf4b-4cab-8be6-da6eeec0b819.png)
c.	Admin
Admin Index
![image](https://user-images.githubusercontent.com/94780400/152955070-fad4b53b-567f-4368-b96d-ca5b54e09d8e.png)
![image](https://user-images.githubusercontent.com/94780400/152955084-78f17a8a-ad0f-49ef-8315-714969e97738.png)
![image](https://user-images.githubusercontent.com/94780400/152955091-92b48b48-de36-4a47-bf37-dd278fec2788.png)
![image](https://user-images.githubusercontent.com/94780400/152955119-6d7c0633-c201-4427-9938-bae876cf8340.png)
Admin create Guest account
![image](https://user-images.githubusercontent.com/94780400/152955145-03c580f4-a773-43a0-bda2-242ec46ce531.png)
![image](https://user-images.githubusercontent.com/94780400/152955150-40668d38-42c2-4b7f-8a5f-997db3c55ad0.png)
![image](https://user-images.githubusercontent.com/94780400/152955155-ee181794-2864-4477-b0e2-84e0c88dfe2b.png)
![image](https://user-images.githubusercontent.com/94780400/152955168-1245a74b-bd93-46a2-8fe6-c550c178bf65.png)
![image](https://user-images.githubusercontent.com/94780400/152955179-1c57a74c-76f7-44ad-8117-7614c412004d.png)
![image](https://user-images.githubusercontent.com/94780400/152955188-f23a1f9e-330d-4dc8-b7d0-b2b6fff05d8a.png)
![image](https://user-images.githubusercontent.com/94780400/152955196-ef60478c-ab8d-45fc-bc6f-8636b39add83.png)
![image](https://user-images.githubusercontent.com/94780400/152955203-718d48a2-86f7-4471-bbef-aeefc48e593b.png)
![image](https://user-images.githubusercontent.com/94780400/152955313-261dbab0-fe51-4d33-bdad-9440a8483d66.png)
![image](https://user-images.githubusercontent.com/94780400/152955327-69163b7d-ee74-41f6-bf58-88b399df1efe.png)
![image](https://user-images.githubusercontent.com/94780400/152955352-434e3d5e-742a-4ea2-b107-b0953af4418d.png)
V.	Implementation
1.	Techniques
a.	Back-end
Our project is developed based on the ASP.NET MVC 4.8 framework. This is a great framework for building and developing web applications. We see a lot of benefits that this framework brings and think it is very suitable for our project development.
When applying ASP.NET we are provided with a powerful set of Controls based on JavaScript, Html, Bootstrap, C#. Very superior when compared to the Controls provided by some traditional forms on the web.
ASP.NET MVC is very testable. We can run testing while building the functions. This is very suitable for working under the Scrum model with Agile method. 
ASP.NET MVC is divided into 3 separate parts: Model, View, Control, so it shows great benefits in programming and object analysis. Because it is divided into separate parts, for faster web application development, easy to fix if there is a problem without affecting other components of the system. This also makes it easier to maintain
b.	Front-end
We use Bootstrap, combined with Html and CSS to build interfaces for our website. Bootstrap is increasingly used in website design thanks to its advantages. We can quickly create the interface using Bootstrap's built-in components, which can help me eliminate repetitive time when creating Class of CSS, or lines code Html.
The bootstrap platform has been well optimized. In bootstrap has created a library to store that designers can use and customize according to personal purpose. This makes the development of our website much faster because I can choose a suitable template and customize it to have a beautiful and elegant interface right away. What's more, bootstrap is made and used so much that the compatibility with browsers and devices like phones and tablets has been tested many times so I absolutely cannot worry about website creation. Output will not be displayed as desired on different device types.
c.	Database
To deploy our projects, we use the Firebase platform and Firebase available services such as Firebase Authentication, Firebase Realtime Database, and Firebase Storage. Firebase enables the development of fast apps without wasting time, manpower to manage systems, and back-end infrastructure: Firebase includes features such as analytics, databases, activity reporting, and reporting. bug reports so that we can develop and navigate our applications more easily.
Realtime database: This service allows you to store and synchronize data in real time. Applications that use this feature can store and retrieve data, as well as read and write data from the server, in a very short period of time, resulting in high efficiency when in use.
Firebase Authentication: Easily and securely manage users. Firebase Authenticator supports a variety of authentication methods, including email and passwords, as well as third-party providers such as Google or Facebook.
Cloud Storage: Use powerful, simple, and cost-effective object storage to store and share user-generated content such as images, audio, and video.
d.	Hosting
Because we use the ASP.NET MVC framework, selecting a hosting provider that supports this framework to deploy the web application is difficult. Somee is one of the hosts which provided us with the necessities. 
2.	Flowcharts and features 
a.	Marketing Manager
View exceptional reports: It first collects all reports, then determines whether or not they are exceptional, and then prints all exceptional reports.
![image](https://user-images.githubusercontent.com/94780400/152955379-92a2c291-396e-4da5-92be-2aceccafd2f1.png)
![image](https://user-images.githubusercontent.com/94780400/152955392-f085f642-a267-4235-a685-3d07d2921663.png)
![image](https://user-images.githubusercontent.com/94780400/152955404-ec592a59-7a55-43ac-aecf-1a85ed47e81e.png)
![image](https://user-images.githubusercontent.com/94780400/152955415-854b9430-b9c1-4662-b9af-01c3a851583d.png)
•	Download submissions by ZIP format: First, it gathers all of this student's documents, zips them, and then prints a connection to download them.![image](https://user-images.githubusercontent.com/94780400/152955447-f06ba3be-32aa-4ae3-b152-29ced5e5a525.png)
![image](https://user-images.githubusercontent.com/94780400/152955455-49c150f9-c4ae-4d6a-9f86-5e0f56cc4e40.png)
![image](https://user-images.githubusercontent.com/94780400/152955464-36144045-f2f5-4606-80d1-442432c383c7.png)
b.	Marketing Coordinator
View submissions from students in specific faculty: The Marketing Coordinator can only view the submission and cannot edit it. The system searches through all students in the course that the Marketing Coordinator teaches to view and then prints it all.
![image](https://user-images.githubusercontent.com/94780400/152955486-0569a5d2-1062-4538-a32f-b016d4ce718c.png)
![image](https://user-images.githubusercontent.com/94780400/152955634-aeb7b5e0-8683-4f0f-bcd2-7e5ccc5cf270.png)
Receive notifications (emails) for new submissions: After the student submits, the Marketing Coordinator will receive the mall and ask the Marketing Coordinator to comment and mark the submission. ![image](https://user-images.githubusercontent.com/94780400/152955656-a2f8e67d-af13-45f1-a3fa-751dec256a6f.png)
•	Give comments for each submission: Marketing Coordinator can comment submission of student in 14 days after end date. System check date now less tan date end. If not, the Marketing Coordinator may comment; otherwise, the Marketing Coordinator may not comment.![image](https://user-images.githubusercontent.com/94780400/152955710-2d0d2a40-23b0-4a0d-be56-1a6bd2988de3.png)
![image](https://user-images.githubusercontent.com/94780400/152955725-92359ed6-0594-48a3-b3f4-efa8a4e27b46.png)
![image](https://user-images.githubusercontent.com/94780400/152955731-e33427c3-3018-4537-bdfb-9f87e73fac41.png)
c.	Student
Submit article in Word format (1 or more) before first closure date, can edit before final closure date (after first closure date) and edit submissions. System check date now is less than date end, if not student can’t submit, else system checks this student Submit before date end and check date now less than date final. If student had submitted before date end and date now more than date end, system not allow student edit submission. If student had submitted before date end and date now less than date end, system allow student edit submission, system allow student edit submission. If student had not submitted before date end, system not allow student edit submission
![image](https://user-images.githubusercontent.com/94780400/152955755-65a857e9-161a-480e-87bf-e3c9a8fe8f1a.png)
![image](https://user-images.githubusercontent.com/94780400/152955767-7eaa4adc-3285-498c-b4a8-5d7211a6de04.png)
•	Upload images: Students can submit high-quality images. When a student uploads an image, the system retrieves it and saves it to the database.
![image](https://user-images.githubusercontent.com/94780400/152955792-5b05ecf5-0f6c-4faf-8510-d6b028722a8e.png)
•	Read comments for own submissions: Students can read the comments that the Marketing Coordinator has written about them. If the student selects read comment, the system will print the comment.![image](https://user-images.githubusercontent.com/94780400/152955822-a94b7b38-2768-4b8f-889a-264d1b873fab.png)
d.	Admin
Create new accounts: Admin has the ability to create accounts for all roles, including students, guests, marketing coordinators, and marketing managers. Admin enters an account, and the system determines whether it exists or not; if not, the system creates the account; otherwise, the system prints that it exists.
![image](https://user-images.githubusercontent.com/94780400/152955862-175936da-7af5-4e71-a7ad-fad4d7a53da9.png)
![image](https://user-images.githubusercontent.com/94780400/152955882-77cc4d52-97f7-4249-948a-5c667bcd9bae.png)
•	Set and edit closure date: All courses' end dates and final dates can be set/edited by the administrator. Admin input date end date final, If the date final is less than the date end, the date final will be the date end.
![image](https://user-images.githubusercontent.com/94780400/152955913-cb398d34-4969-4cb8-91f5-1d7b9da52cb3.png)
![image](https://user-images.githubusercontent.com/94780400/152955923-87c02216-58fd-47eb-97d0-1bdceff3c160.png)
VI.	Testing
1.1. Test plan
1.1.1. Team members
![image](https://user-images.githubusercontent.com/94780400/152955988-cc2a0023-dd00-41b3-9bab-7c90a7993aa7.png)
1.1.2. Scope
The functions tested in this project are:
General functions:
•	Log in.
•	Log out.
Specific functions:
	For Admin account:
o	Create and edit update time, closing time.
o	Create, edit and delete account.
o	Storing and preserving all system data.
	For Student account:
o	Send articles as word documents.
o	Upload high-quality images.
o	Read comments for own submissions.
o	Update contributions until a final closure date.
o	Accept the terms and conditions that require approval before submitting articles. 
	For Marketing Coordinator account:
o	Receive email notifications from the system whenever the students in faculty publish their articles.
o	Make comments for student's articles within 14 days after the system stops accepting new articles.
o	View contributions from students in faculty.
o	Interact with the students in faculty.
o	Select contributions to publish.
	For Marketing Manager account:
o	View all the selected contributions.
o	View the exceptional reports.
o	Download all selected contributions as zip file.
o	Keep track of the number of contributions, contributors and the percentage of contributions by multiple faculties.
	For Guest account:
o	View faculty selected reports.
1.1.3. Test Approach
Our project uses an agile approach, with iterations daily and after each sprint. Whenever functions or requirements are made for that sprint, they will be delivered and immediately checked by testers. 
Our team also chose manual testing as a method for web application testing and development. More specifically, our manual testing is performed in a sequence of steps: running the web application on the server, testing each function with as many assumptions as possible, writing error reports and send to the coder, check the functions after being fixed, test all the functions passed previously again; if an error occurs, the tester will continue to write the error report, send it to the coder and continue to test until all the functions have been passed. Finally, write test cases, test logs for all cases tested in the previous process. 
1.1.4. Test Environment
The web application, the database and the server to publish web application are required.
	Web application:
•	Back-end: ASP.NET MVC 4.8, JavaScript, C#.
•	Front-end: bootstrap 4, css, html.
	Database: Firebase Authentication, Firebase Realtime Database, Firebase Storage.
	Server: Somee.
1.1.5. Assumptions/Risks
1.1.5.1. Assumptions
1.	Delays in the Sprints may cause the team to increase the working time of the day.
2.	Lack of experience, knowledge in developing and testing the system can make the team spend more time doing and researching.
3.	The lack of manpower may cause some team members to take on more tasks.
4.	Misinterpreting the requirements of the system can cause the team to spend more time and effort on editing, testing, etc.
5.	Having more members or having any member leave the team during project implementation may cause the team to rearrange many things from the beginning.


1.1.5.2. Risks
Below are some of the risks that can be encountered during our team's project implementation.
	Risk	Impact	Trigger	Mitigation Plan
1	Modifications, changes to the system's functionality can make the test cases false and may have to be revised a lot	Medium	The test case deviated too much	Gather human resources, time to discuss system requirements before starting a sprint, and constantly cross-monitor among members during system development
2	Functions become unstable or not function properly as originally achieved, after the successive stages of system development	High	Too much faulty functionality is neglected during development and testing	Perform a rigorous testing process multiple times after each sprint and retest all functionality included in the old sprint when testing new functionality implemented in the new sprint
3	Functions in sprint have execution time deviations that prevent the system from completing on schedule	High	Too many stages are delayed in project development	Continuously monitor the system development process, identify difficulties and obstacles that members face and find ways to overcome them as effectively as possible
![image](https://user-images.githubusercontent.com/94780400/152956152-bcd33cdc-662e-4b2d-b0c2-12935f298e40.png)
1.1.7. Deliverables
The following are the test deliverables: 
1.	Test Plan
2.	Test Case and Test Log
3.	Summary Report
1.2. Sprint 1
1.2.1. Test Cases and Test Logs of Sprint 1
Below is a table showing the test cases and test logs of Sprint 1 which are made to test user account creation and control functionality, exclusively for the Admin account.
Test Case ID	Role	Test Scenario	Test Case	Pre-Conditions	Test Steps	Test Data	Post Conditions	Expected Result	Actual Result	Status
TC_SIGN_UP_001	Admin	Check sign up functionality exclusively for the admin account	Check response on entering Full Name, Email and Password	Requires created and enabled admin account (Active Status = True)	1. Select Log in
2. Login with the enabled admin account
3. Select Admin Index
4. Select Create Admin/Create Student/ Create Marketing Manager/Create Guest 
5. Enter Full Name
6. Enter Email
7. Enter Password
8. Click Create button	Full Name: TuanAdmin
Email: TuanAdmin@gmail.com 
Password: TuanAdmin@gmail.com

Full Name: TuanStudent
Email: TuanStudent@gmail.com 
Password: TuanStudent@gmail.com

Full Name: TuanMM
Email: TuanMM@gmail.com 
Password: TuanMM@gmail.com

Full Name: TuanGuest
Email: TuanGuest@gmail.com 
Password: TuanGuest@gmail.com
The newly created account appears in the account data table on the Admin Index page	- Successfully created a new account with the entered data

-  For the Student and Guest accounts, in addition to the entered data, they will be created and assigned with the name of the default marketing coordinator account	Sign up successful	Pass
TC_SIGN_UP_002	Admin	Check sign up functionality exclusively for the admin account	Check response on entering Full Name, Email, Password and selecting one name from Marketing Coordinator accounts	Requires created and enabled admin account (Active Status = True)	1. Select Log in
2. Login with the enabled admin account
3. Select Admin Index
4. Select Create Student/Create Guest 
5. Enter Full Name
6. Enter Email
7. Enter Password
8. Select one name from the Marketing Coordinator accounts
9. Click Create button	Full Name: TuanStudent2
Email: TuanStudent2@gmail.com 
Password: TuanStudent2@gmail.com
Marketing Coordinator: TuanMC1

Full Name: TuanGuest2
Email: TuanGuest2@gmail.com 
Password: TuanGuest2@gmail.com
Marketing Coordinator: TuanMC1	The newly created account appears in the account data table on the Admin Index page	Successfully created a new account with the entered data, the name selected from Marketing Coordinator accounts
	Sign up successful	Pass
TC_SIGN_UP_003	Admin	Check sign up functionality exclusively for the admin account	Check response on entering Full Name, Course Name, Email and Password	Requires created and enabled admin account (Active Status = True) 	1. Select Log in
2. Login with the enabled admin account
3. Select Admin Index
4. Select Create Marketing Coordinator
5. Enter Full Name
6. Enter Course Name
7. Enter Email
8. Enter Password
9. Click Create button	Full Name: TuanMC1
Course Name: IT
Email: TuanMC1@gmail.com 
Password: TuanMC1@gmail.com
The newly created account appears in the account data table on the Admin Index page	Successfully created a new account with the entered data	Sign up successful	Pass
TC_SIGN_UP_004	Admin	Check sign up functionality exclusively for the admin account	Check response when not entering Full Name, Email and Password	Requires created and enabled admin account (Active Status = True)	1. Select Log in
2. Login with the enabled admin account
3. Select Admin Index
4. Select Create Admin/Create Student/ Create Marketing Coordinator/Create Marketing Manager/Create Guest 
5. Click Create button	Name: 
(Course Name: Filled for Create Marketing Coordinator)
Email: 
Password: 
(Marketing Coordinator: The names of the Marketing Coordinator account available in the system for Create Student and Create Guest)	The program sends a message asking users to enter data for Full Name, Email and Password	Can't create an account without filling out all 3 of these boxes	There are no new accounts with missing data even in 1 of 3 data fields	Pass
TC_SIGN_UP_005	Admin	Check sign up functionality exclusively for the admin account	Check response when not entering Course Name	Requires created and enabled admin account (Active Status = True)	1. Select Log in
2. Login with the enabled admin account
3. Select Admin Index
4. Select Create Marketing Coordinator
5. Enter Full Name
6. Enter Email
7. Enter Password
8. Click Create button	Full Name: TuanMC2
Course Name: 
Email: TuanMC2@gmail.com 
Password: TuanMC2@gmail.com
When the Create button is clicked, the mouse cursor is returned to the Course Name text box	Can't create marketing coordinator account when the Course Name text box is left blank	The create button cannot be used to create a new marketing coordinator account while the Course Name text box is still blank	Pass
TC_SIGN_UP_006	Admin	Check sign up functionality exclusively for the admin account	Check response when don’t have any name from Marketing Coordinator accounts to select	Requires created and enabled admin account (Active Status = True)	1. Select Log in
2. Login with the enabled admin account
3. Select Admin Index
4. Select Create Student/Create Guest
5. Enter Full Name
6. Enter Email
7. Enter Password
8. Click Create button	Full Name: TuanStudent2
Email: TuanStudent2@gmail.com 
Password: TuanStudent2@gmail.com
Marketing Coordinator:	When the Create button is clicked, the mouse cursor is returned to the marketing coordinator account name selection box	Student and guest accounts cannot be created without any marketing coordinator account name in the selection box	The create button cannot be used to create a new student account and guest account while the marketing coordinator account name selection box has no name to choose from	Pass
TC_LOGIN_001	Admin	Check login functionality	Check response when logging in with email and password of the created and enabled admin account	Requires created and enabled admin account (Active Status = True)	1. Select Log in 
2. Login with the enabled admin account	Email: TuanAdmin@gmail.com 
Password: TuanAdmin@gmail.com
The home page of admin accounts appears	Log in successful	Account is logged in successfully	Pass
TC_LOGIN_002	Student	Check login functionality	Check response when logging in with email and password of the created and enabled student account	Requires created and enabled student account (Active Status = True)	1. Select Log in
2. Login with the enabled student account
	Email: TuanStudent@gmail.com
Password: TuanStudent@gmail.com	The home page of student accounts appears	Log in successful	Account is logged in successfully	Pass
TC_LOGIN_003	Marketing Coordinator	Check login functionality	Check response when logging in with email and password of the created and enabled marketing coordinator account	Requires created and enabled marketing coordinator account (Active Status = True)	1. Select Log in
2. Login with the enabled marketing coordinator account	Email: TuanMC1@gmail.com 
Password: TuanMC1@gmail.com	The home page of marketing coordinator accounts appears	Log in successful	Account is logged in successfully	Pass
TC_LOGIN_004	Marketing Manager	Check login functionality	Check response when logging in with email and password of the created and enabled marketing manager account	Requires created and enabled marketing manager account (Active Status = True)	1. Select Log in
2. Login with the enabled marketing manager account	Email: TuanMM@gmail.com
Password: TuanMM@gmail.com	The home page of marketing manager accounts appears	Log in successful	Account is logged in successfully	Pass
TC_LOGIN_005	Guest	Check login functionality	Check response when logging in with email and password of the created and enabled guest account	Requires created and enabled guest account (Active Status = True)	1. Select Log in
2. Login with the enabled guest account	Email: TuanGuest@gmail.com
Password: TuanGuest@gmail.com	The home page of guest accounts appears	Log in successful	Account is logged in successfully	Pass
TC_LOGIN_006	Enabled account	Check login functionality	Check response when logging in with the email entered incorrectly and the password entered correctly	Requires created and enabled account (Active Status = True)
	1. Select Log in
2. Login with any enabled account	Email: Tuan@gmail.com
Password: TuanMC1@gmail.com	The program sends a message that the user has entered an incorrect username or password	Login failed	Fail to login	Pass
TC_LOGIN_007	Enabled account	Check login functionality	Check response when logging in with the email entered correctly and the password entered incorrectly	Requires created and enabled account (Active Status = True)
	1. Select Log in
2. Login with any enabled account	Email: TuanMC1@gmail.com
Password: 123456	The program sends a message that the user has entered an incorrect username or password	Login failed	Fail to login	Pass
TC_LOGIN_008	None	Check login functionality	Check response when logging in without entering Email and Password	None	1. Select Log in
2. Click Sign In button	None	The program sends a message asking users to enter data for Email and Password	Login failed	Fail to login	Pass
TC_LOGIN_009	Unenabled account	Check login functionality	Check response when logging in with an unenabled account	Requires created and unenabled account (Active Status = False)
	1. Select Log in
2. Login with any unenabled account	Email: AAA@gmail.com
Password: AAA@gmail.com	The program sends a message saying that this account has been unenabled	Login failed	Fail to login	Pass
TC_LOG_OUT_001	Enabled account	Check logout functionality	Check response when logging out account	Requires account that successfully logged in	1. Select Log in
2. Login with any enabled account 
3. Select Log out	None	The Login page for account login is displayed	Log out successful	Account is logged out successfully	Pass
TC_EDIT_001	Admin	Check edit functionality exclusively for the admin account	Check response when editing the name of the account	- Requires admin account that successfully logged in

- Requires account which needs to be edited	1. Select Log in
2. Login with the enabled admin account
3. Select Admin Index
4. Select Edit
5. Edit Name
6. Click Save button	Name: TuanMC1
(New Name: TuanMC123)	- The account management page of the admin account that has just made modifications to another account is displayed

- The new name of the newly edited account appears in the account data table containing that account	Successfully edited the name of the account	The name of the account was successfully edited	Pass
TC_EDIT_002	Admin	Check edit functionality exclusively for the admin account	Check response when editing the email of the account	- Requires admin account that successfully logged in

- Requires account which needs to be edited	1. Select Log in
2. Login with the enabled admin account
3. Select Admin Index
4. Select Edit
5. Edit Email
6. Click Save button	Email: TuanMC1@gmail.com
(New Email: TuanMC123@gmail.com)	- The account management page of the admin account that has just made modifications to another account is displayed

- The new email of the newly edited account appears in the account data table containing that account	Successfully edited email of the account	The email of the account was successfully edited	Pass
TC_EDIT_003	Admin	Check edit functionality exclusively for the admin account	Check response when editing the password of the account	- Requires admin account that successfully logged in

- Requires account which needs to be edited	1. Select Log in
2. Login with the enabled admin account
3. Select Admin Index
4. Select Edit
5. Edit Password
6. Click Save button	Password: TuanMC1@gmail.com
(New Password: TuanMC123)	- The account management page of the admin account that has just made modifications to another account is displayed

- The new password of the newly edited account appears in the account data table containing that account	Successfully edited password of the account	The password of the account was successfully edited	Pass
TC_EDIT_004	Admin	Check edit functionality exclusively for the admin account	Check response when editing the active status box of the account	- Requires admin account that successfully logged in

- Require account which needs to be edited	1. Select Log in
2. Login with the enabled admin account
3. Select Admin Index
4. Select Edit
5. Edit active status box
6. Click Save button	Active Status:  (True)
(New Active Status: ☐ (False))
- The account management page of the admin account that has just made modifications to another account is displayed

- The new value of the active status box of the newly edited account appears in the account data table containing that account	Successfully edited the value for the active status box of the account	The value of the active status box of the account was successfully edited	Pass
TC_EDIT_005	Admin	Check edit functionality exclusively for the admin account	Check response when editing account without re-filling for deleted values and leave blank at Full Name, Email and Password	- Requires admin account that successfully logged in

- Require account which needs to be edited	1. Select Log in
2. Login with the enabled admin account
3. Select Admin Index
4. Select Edit
5. Delete Name
6. Delete Email
7. Delete Password
6. Click Save button	Name: 
Email: 
Password: 
Active Status: (selected both True and False) 	The program sends a message asking users to enter data for Name, Email and Password	Edit failed	The account has not changed	Pass
TC_EDIT_006	Admin	Check edit functionality exclusively for the admin account	Check response when editing account with an email already in use by another account in the system	- Requires admin account that successfully logged in

- Require account which needs to be edited	1. Select Log in
2. Login with the enabled admin account
3. Select Admin Index
4. Select Edit
5. Edit Email
6. Click Save button	Email: TuanMC1@gmail.com
(New Email: TuanStudent@gmail.com)	The account management page of the admin account is displayed with the account's email unchanged	Edit failed	The account has not changed	Pass
TC_DELETE_001	Admin	Check delete functionality exclusively for the admin account	Check response when deleting admin, student, guest and marketing manager accounts	- Requires admin account that successfully logged in

- Require account which needs to be deleted	1. Select Log in
2. Login with the enabled admin account
3. Select Admin Index
4. Select Delete Student/Admin/Guest/Marketing Manager account
5. Click Delete button	Name: TuânMM
Email: TuanMM@gmail.com
Password: TuanMM@gmail.com
Role: Marketing Manager
Active Status: True

Name: TuanAdmin
Email: TuanAdmin@gmail.com 
Password: TuanAdmin@gmail.com
Role: Admin
Active Status: True

Name: TuanStudent
Email: TuanStudent@gmail.com 
Password: TuanStudent@gmail.com
Role: Student
Active Status: True

Name: TuanGuest
Email: TuanGuest@gmail.com 
Password: TuanGuest@gmail.com
Role: Guest
Active Status: True	- The account management page of the admin account that has just deleted another account is displayed

- The deleted account disappears from the account data table that contains it	Delete successful	The account has been deleted	Pass
TC_DELETE_002	Admin	Check delete functionality exclusively for the admin account	Check response when deleting the marketing coordinator account without deleting the student accounts and the guest accounts it is in charge of in the faculty	- Requires admin account that successfully logged in

- Require account which needs to be deleted	1. Select Log in
2. Login with the enabled admin account
3. Select Admin Index
4. Select Delete Marketing Coordinator account 
5. Click Delete button	Name: TuanMC1
Email: TuanMC1@gmail.com 
Password: TuanMC1@gmail.com
Role: Marketing Coordinator
Active Status: True	The program sends a notice asking the user to delete the student and guest accounts in that faculty first	Delete failed	The account was not deleted	Pass
TC_DELETE_003	Admin	Check delete functionality exclusively for the admin account	Check response when deleting the marketing coordinator account once the student and guest accounts it is in charge of in the faculty have been deleted	- Requires admin account that successfully logged in

- Require account which needs to be deleted	1. Select Log in
2. Login with the enabled admin account
3. Select Admin Index
4. Select Delete all Student and Guest accounts that the Marketing Coordinator account in charge of
5. Select Delete Marketing Coordinator account 
5. Click Delete button	Name: TuanMC1
Email: TuanMC1@gmail.com 
Password: TuanMC1@gmail.com
Role: Marketing Coordinator
Active Status: True	- The account management page of the admin account that has just deleted other accounts is displayed

- The deleted accounts disappear from the account data table that contains them	Delete successful	All related accounts have been deleted	Pass
Below is a table showing the test case and test log created to test student account functions such as submitting articles as doc files and images, reading comments, updating articles, accepting terms and conditions. condition.
1.2.2. Sprint 1 backlog 
Below is a Sprint 1 backlog with user story related to all the functions of the respective roles mentioned in test cases and test logs of Sprint 1.
Product backlog item	Tasks	Volunteer	Status	Original Estimate	Monday (15/2)	Tuesday (16/2)	Wednesday (17/2)	Thursday (18/2)	Friday (19/2)	Monday (22/2)	Tuesday (23/2)	Wednesday (24/2)	Thursday (25/2)	Friday (26/2)	Sprint review
As a student, I want to be able to post one or more photos and articles so that I can contribute to the school magazine the best products	Create database	Vinh	Done	0	0	0	0	0	0	0	0	0	0	0	0
	Code front-end for submit articles and photos	Bao, Vy	Done	1.5	1.5	1.5	1.5	1.5	1.5	1.5	1.5	1	0	0	0
	Code back-end for submit articles and photos	Thuyen	Done	1.5	1.5	1.5	0	0	0	0	0	0	0	0	0
	Write test case, test log	Nguyen	Done	1	1	1	1	0.5	0.5	0.5	0.5	0.5	0	0	0
As an administrator, I want to be able to create new account and control login permissions so that I can grant permissions to suit the user's role	Create database	Vinh	Done	6	4	3	3	1	1	0	0	0	0	0	0
	Code front-end for create user accounts and authorize them	Bao, Vy	Done	2	2	2	2	2	2	2	2	1	0	0	0
	Code back-end for create user accounts and authorize them	Thuyen	Done	3	3	3	3	2	1	0	0	0	0	0	0
	Write test case, test log	Tuan	Done	4	4	4	4	4	4	4	4	4	2	0	0
Total	19	17	16	14.5	11	10	8	8	6.5	2	0	0
1.2.3. Sprint 1 burndown chart 
The burndown chart below depicts our team's working process during Sprint 1. It is clear that there are significant differences between actual and estimated effort. Most of these differences can be attributed to many subjective factors, such as coding, which takes more time to figure out how to do before actually implementing a function, or the testing process, which also takes a long time to complete before receiving the final results. Because of this, the project's Sprint 1 implementation did not go as smoothly as planned. The graph clearly shows these things, as can be seen in the early stages, because our team spent a lot of time figuring out how to do the functions, testing incomplete functions, and so on, so there isn't much progress on the workflow in the early stages. However, after gaining more knowledge to perform those tasks in the second half of Sprint1, we were able to pick up the pace and meet the Sprint1 deadline.
![image](https://user-images.githubusercontent.com/94780400/152956463-faf15707-be07-40fb-94e5-be67f3c2a123.png)
1.3. Sprint 2
1.3.1. Test Cases and Test Logs of Sprint 2
Below is the table showing the test case and test log of Sprint 2 which are made to test some functions specific to the marketing coordinator account and the admin account. More specifically, the functions such as receiving emails, creating comments, scoring, viewing articles of the marketing coordinator account and the function of controlling the deadline of the faculties of the admin account.
Product backlog item	Tasks	Volunteer	Status	Original Estimate	Monday (1/3)	Tuesday (2/3)	Wednesday (3/3)	Thursday (4/3)	Friday (5/3)	Monday (8/3)	Tuesday (9/3)	Wednesday (10/3)	Thursday (11/3)	Friday (12/3)	Sprint review
As a marketing coordinator, I want to be able to receive email notifications from the system whenever the students in my faculty publish their articles so that I can work with those contributions more conveniently	Edit database and code front-end	Vinh	Done	0.5	0.5	0.5	0.5	0.5	0.5	0.5	0.5	0	0	0	0
	Code front-end for display all submitted articles	Bao, Vy	Done	0	0	0	0	0	0	0	0	0	0	0	0
	Code back-end for display all submitted articles	Thuyen	Done	1	1	1	1	0	0	0	0	0	0	0	0
	Write test case, test log	Tuan	Done	0.5	0.5	0.5	0.5	0.5	0.5	0.5	0.5	0	0	0	0
As an administrator, I want to be able to control the update time, the closing time of some data in the system such as how long new articles are allowed to be posted, the posted articles are allowed to be edited and the end time of the editing of posted articles so that the system works properly as required	Edit database and code front-end	Vinh	Done	0.5	0.5	0.5	0.5	0.5	0.5	0.5	0	0	0	0	0
	Code front-end for control the update time, the closing time of some data in the system	Bao, Vy	Done	1.5	1.5	1.5	1.5	1.5	1.5	1.5	1.5	0.5	0	0	0
	Code back-end for control the update time, the closing time of some data in the system	Thuyen	Done	3	2	1	0	0	0	0	0	0	0	0	0
	Write test case, test log	Tuan	Done	1.5	1.5	1.5	1.5	1.5	1.5	1.5	1.5	1.5	0.5	0	0
As a student, I want to be able to read comments for my own submissions so that I can easily edit the articles accordingly	Edit database and code front-end	Vinh	Done	0.5	0.5	0.5	0.5	0.5	0.5	0.5	0	0	0	0	0
	Code front-end for reading comments for own submissions	Bao, Vy	Done	1	1	1	1	1	1	1	0	0	0	0	0
	Code back-end for reading comments for own submissions	Thuyen	Done	1.5	1.5	1.5	1.5	0	0	0	0	0	0	0	0
	Write test case, test log	Nguyen	Done	0.5	0.5	0.5	0.5	0.5	0.5	0.5	0.5	0.5	0	0	0
As a marketing coordinator, I want to be able to select contributions to publish so that my faculty can contribute the best quality articles to the magazine	Edit database and code front-end	Vinh	Done	0.5	0.5	0.5	0.5	0.5	0.5	0	0	0	0	0	0
	Code front-end for accept or reject student articles	Bao, Vy	Done	0.5	0.5	0.5	0.5	0.5	0.5	0	0	0	0	0	0
	Code back-end for accept or reject student articles	Thuyen	Done	1	1	1	1	1	0	0	0	0	0	0	0
	Write test case, test log	Tuan	Done	0.5	0.5	0.5	0.5	0.5	0.5	0.5	0.5	0	0	0	0
As a student, I want to be able to update my contributions until a final closure date so that I can directly make the necessary changes	Edit database and code front-end	Vinh	Done	0.5	0.5	0.5	0.5	0.5	0	0	0	0	0	0	0
	Code front-end for update contributions until the final closure date	Bao, Vy	Done	0	0	0	0	0	0	0	0	0	0	0	0
	Code back-end for update contributions until the final closure date	Thuyen	Done	1	1	1	1	1	0	0	0	0	0	0	0
	Write test case, test log	Nguyen	Done	1	1	1	1	1	1	1	0	0	0	0	0
As a marketing manager, I want to be able to view all the selected contributions so that I can give the necessary feedback for contributions	Edit database and code front-end	Vinh	Done	1	1	1	1	1	1	1	1	0	0	0	0
	Code front-end for view all selected contributions	Bao, Vy	Done	1.5	1.5	1.5	1.5	1.5	1.5	1.5	0	0	0	0	0
	Code back-end for view all selected contributions	Thuyen	Done	1.5	1.5	1.5	1.5	0.5	0.5	0	0	0	0	0	0
	Write test case, test log	Nguyen	Done	1	1	1	1	1	1	1	1	1	0.5	0	0
As a marketing coordinator, I want to be able to view contributions from students in my faculty so that I can review and evaluate their contributions	Edit database and code front-end	Vinh	Done	1	1	1	1	1	1	1	0	0	0	0	0
	Code front-end for view contributions from students	Bao, Vy	Done	1	1	1	1	1	1	1	1	0	0	0	0
	Code back-end for view contributions from students	Thuyen	Done	1.5	1.5	1.5	1.5	1.5	1.5	0	0	0	0	0	0
	Write test case, test log	Tuan	Done	0.5	0.5	0.5	0.5	0.5	0.5	0.5	0.5	0.5	0	0	0
As a marketing coordinator, I want to be able to make comments for my student's articles so that I can help my students make the necessary updates	Edit database and code front-end	Vinh	Done	0.5	0.5	0.5	0.5	0.5	0.5	0	0	0	0	0	0
	Code front-end for making comments on student articles	Bao, Vy	Done	0.5	0.5	0.5	0.5	0.5	0.5	0	0	0	0	0	0
	Code back-end for making comments on student articles	Thuyen	Done	1	1	1	0	0	0	0	0	0	0	0	0
	Write test case, test log	Tuan	Done	0.5	0.5	0.5	0.5	0.5	0.5	0.5	0.5	0.5	0	0	0
Total	28.5	27.5	26.5	24.5	21	18.5	14.5	9	4.5	1	0	0
1.4.3. Sprint 3 burndown chart
Below is a burndown chart showing the working process of our team during Sprint 3. In Sprint 3, because we gained more experience and knowledge through the process of researching and learning from previous Sprints, so our team went through the work more quickly, sticking to the original estimate. As a result, the first stage of Sprint 3 has progressed faster than the early stages of the previous Sprints. However, there are still certain difficulties when performing some functions such as interaction between marketing coordinator account and student account through messages, monitoring data of faculties, etc. So the mid-stage implementation of Sprint 3 has become slower than originally estimated due to the fact that coding and testing for some functions have to take place many times. However, our team has found a way to improve and overcome the limitations and bugs of the system as much as possible and has caught up with the Sprint 3 deadline. 
![image](https://user-images.githubusercontent.com/94780400/152956784-bf5bbf95-db00-49e4-bb37-f09965cf8f79.png)
1.5. Test evidence
Below is the test evidence used for the functionality contained in our system.
Test evidence for general functions:
•	Log in
Below is an image of the page containing the login function, which can be used by entering the email, password of the user account and clicking the Sign In button.
![image](https://user-images.githubusercontent.com/94780400/152956810-d2a179ae-2aa8-4c28-9ade-a4c5420b4b76.png)
•	Log out
In the upper right corner of the image below is the Log out button that is used to log out of the user account when clicking on it.
![image](https://user-images.githubusercontent.com/94780400/152956841-8309e4eb-2e00-4a93-9b8f-73d26ca84be3.png)
Test evidence for specific functions:
	For Admin account:
o	Create and edit update time, closing time
Below is an image of the Edit Course page with 2 adjustment bars New date End and New date Final. More specifically, the New date End is used to adjust the deadline for submitting new articles of the student account and the comment creation deadline of the marketing coordinator account in a faculty. The New date Final is used to adjust the deadline for submitting edited articles of the student account. After adjusting these bars to the necessary deadlines, the administrator clicks the Save button to be able to successfully create and edit them.
o	Create account
Below is an image of a page used to create user accounts. To successfully perform the function of creating user accounts, the administrator needs to fill in the Full Name, Email and Password for these accounts. In addition, for the student account and guest account, the administrator needs to choose a marketing coordinator account for them to be in charge of their faculty. For marketing coordinator account, when creating it, the administrator needs to fill in the Course name to specify the name of the faculty that the marketing coordinator is in charge of. After filling in the necessary information to create a user account, the administrator clicks the Create button to complete the account creation.
![image](https://user-images.githubusercontent.com/94780400/152956907-5e211e5a-3eb6-402d-80f0-e75e52d5d675.png)
o	Storing and preserving all system data
Below is an image of the View Mark page, used by the admin to keep track of student articles from all faculties. In addition, the administrator can view the student's articles by clicking the View button and from there, the administrator can also download the articles for storing.
VII.	Agile
2.1. Product backlog
As a/an	I want to be able to...	So that...	Priority level	Added in sprint	Story points	Estimate (time)
Student	Send articles as word documents	I can contribute to the school magazine	Must have	1	50	2
	Upload high-quality images	I can increase the persuasion, interactivity and aesthetics of the article	Must have	1	50	2
	Read comments for own submissions	I can easily edit the articles accordingly	Must have	2	50	3.5
	Update contributions until a final closure date	I can directly make the necessary changes	Must have	2	50	2.5
	Accept the terms and conditions that require approval before submitting articles	I can avoid the issues related to the terms and conditions when submitting my submission	Should have	3	30	1.5
Marketing manager	View all the selected contributions	I can give the necessary feedback for contributions	Must have	2	50	5
	View the exceptional reports	I can choose the best articles	Should have	3	40	5
	Download all selected contributions as zip file	I can transfer them out of the system	Should have	3	40	3.5
	Keep track of the number of contributions, contributors and the percentage of contributions by multiple faculties	I can ensure the quality of the school magazine	Must have	3	40	5
Marketing coordinator	Receive email notifications from the system	I can be more convenient in working with contributions	Should have	2	30	2
	Make comments for my student's articles within 14 days after the system stops accepting new articles	I can help my students make the necessary updates	Must have	2	50	2.5
	View contributions from students in my faculty	I can review and evaluate the contributions collected	Must have	2	40	4
	Interact with the students in my faculty	I can make it easy to give suggestions, discuss necessary adjustments with my students	Should have	3	40	4
	Select contributions to publish	I can contribute the best quality articles to the magazine	Must have	2	50	2.5
Administrator	Maintain any system data	I can store and preserve all system data	Must have	3	40	4
	Control update time, closing time	I can control the operation of the system	Must have	2	50	6.5
	Create new account and control login permissions	I can control different user accounts	Must have	1	50	15
Guest	View faculty selected reports	I can keep track of magazine contents	Must have	3	50	5.5
2.2. Product burndown chart
Our product burndown chart, shown below, depicts our team's working process throughout each Sprint. It's clear that there's a big difference between fact and estimate. Because our team's Sprint 1 does not include a large number of tasks, the remaining story points at the end of Sprint 1 are quite large. However, in order to meet the project deadline, our team has decided to significantly increase the number of tasks that must be completed in Sprints 2 and 3 compared to Sprint 1. As a result, the remaining story points dropped more sharply from Sprint 1 onwards and remained consistent with the estimate until the end of the project.
![image](https://user-images.githubusercontent.com/94780400/152957154-9611cf8a-4a15-464d-a4c4-6430436a83e1.png)
Team challenges
During the project's implementation, our team faced a variety of challenges, including:
Difficulty communicating among team members in the early stages of the project, specifically before the start of Sprint 1, when no one knew each other and had never worked together before. It took a long time for our team to get to know each other and feel comfortable enough to work together effectively, so the time spent on the project is significantly reduced before it even begins. However, we have overcome this quite effectively by communicating with each other more actively through Facebook, working together with a strong sense of responsibility, and meeting and chatting on a regular basis when we come to class.
Furthermore, it can be said that the deadline of this project is also a big challenge for our team members, because when the project needs to be started, it is also the time when my country's biggest holiday of the year, the lunar new year, begins, so it was really difficult for everyone to immediately implement this project early. Furthermore, it was during this time that the Covid-19 epidemic in my country became more dangerous, making it difficult to meet and work face to face with each other. However, we have overcome this by accelerating all tasks, getting started on the project as soon as possible, and devoting more time to completing this project on time. 
	One of the challenges is a lack of experience, knowledge, and skills required to complete the project professionally, quickly, and smoothly. More specifically, having to work while learning and supplementing knowledge to meet the needs of the project not only takes more time for the team, but also leaves the project lacking and hazy. However, our team also attempted to learn the necessary knowledge and skills in coding, testing, and so on from a variety of sources. As a result, the project was carried out more effectively, and we gained new and valuable knowledge and experience.
	Other difficulties arose for our team, such as the loss of a team member due to personal reasons, forcing him to leave this project. This has resulted in a significant loss of manpower for our team, as well as a significant increase in the workload that team members must undertake. However, we have overcome this difficulty by sharing the tasks that this member left behind and spending more time assisting each other in completing the various project tasks.
	Other challenges arose for our team, such as the loss of a team member due to personal reasons, which forced him to leave this project. This has resulted in a significant loss of manpower for our team, as well as an increase in the workload that team members must perform. We overcame this difficulty, however, by sharing the tasks that this member left behind and spending more time assisting each other in completing the various project tasks.
	Finally, it is worth noting that misinterpreting project requirements can be a challenge. This necessitates a significant amount of time and effort to correct and supplement the deficiencies, and it can sometimes have an impact on other functions and factors that have been successfully implemented in the project. However, we overcame this obstacle by consulting with our instructor and thoroughly discussing these requirements before implementing them.
Minutes of meetings
Meeting date	Activities take place during the meeting	Participants
Thursday, February 25, 2021	- Describe new functions implemented in Sprint1.
- Describe the interfaces and interactions related to the functions implemented in Sprint1.
- Describes the database implementation and the required data has been successfully created.
- Describe the testing process for the different functions implemented in Sprint1.
- Describe the elements that need to be fixed or improved in Sprint1.
- Discuss the difficulties team members have encountered during Sprint1 and find solutions to overcome them.
- Discuss the project implementation progress and the amount of time allocated to the remaining Sprints.
- Identify the functions that need to be implemented in Sprint2.	- Nguyen Hoang Thuyen
- Pham Ngoc Bao
- Do The Vinh
- Nguyen Van Tuan
- Do Ho Nguyen
- Ha Ngoc Vy
Saturday, March 13, 2021	- Describe new functions implemented in Sprint2 and the old features that have been modified or improved.
- Describe the interfaces and interactions related to the functions implemented in Sprint2 and the modifications or improvements to the old elements.
- Describe the developments and edits made to the database.
- Describe the testing process for the different functions implemented in Sprint2.
- Discuss the adjustments made to the time and progress of the functions, elements in Sprint2.
- Describe the elements that need to be fixed or improved in Sprint2.
- Identify the functions that need to be implemented in Sprint3.	- Nguyen Hoang Thuyen
- Pham Ngoc Bao
- Do The Vinh
- Nguyen Van Tuan
- Do Ho Nguyen
- Ha Ngoc Vy
Saturday, March 27, 2021	- Describe the last remaining new functions, implemented in Sprint3, and old features that have been modified or improved.
- Describe the interfaces and interactions related to the functions implemented in Sprint3 and the modifications or improvements to the old elements.
- Describe the developments and edits made to the database.
- Describe the testing process for the different functions implemented in Sprint3.
- Describe the elements that need to be added, fixed or improved in Sprint3.
- Review and identify all functions, elements that have worked well in the system and those that need to be improved or added to complete the project.
- Discuss all the difficulties experienced during the project implementation to gain more experience when implementing future projects.
- Determine what to do next to announce the results of the team's project implementation.	- Nguyen Hoang Thuyen
- Pham Ngoc Bao
- Do The Vinh
- Nguyen Van Tuan
- Do Ho Nguyen
- Ha Ngoc Vy
VIII.	Conclusion
The process of building our website was completed on time and with all of the required criteria met. The website is stable, loads quickly, and is error-free. The interface is user-friendly and simple to use. We took it very seriously and were disciplined during the implementation process. Make a clear plan for each part, and divide the work in accordance with each individual's capacity. There are short meetings to learn about the situation and the progress of the work. Control the situation and intervene if problems arise. I always write down the content of each meeting and plan for the next phase. The member in charge of designing the database should be well-versed in this area and use appropriate technology. Designers do not work alone or independently; they constantly exchange and receive support from team members, as well as suggestions and upgrades to improve website functionality and design. The examiner will cross-check each other's answers. Examine each function as well as the overall performance of the website. After each test, comprehensive statistical reports are generated. When the implementation and development process is completed. Sit down and go over the website one last time to ensure that it was implemented as planned, completed as required, the system was stable, and no errors occurred. Is it necessary to repair or improve it? That's how we're going to build and finish the website. Working together, dividing work according to each individual's abilities. Hold regular meetings to check on the status of the project. Always be there for one another, share and help one another, and grow together.













 

 

 

