# InformationSecurity_task4

## x Summary OWASP

### A01:2021 - Broken Access Control

- Access control is about making sure people can only see or do what their role allows
- When it’s broken, users can trick the system (e.g., by changing a URL or token) to get into areas they shouldn’t
- This can lead to stolen data, misuse of accounts, or even full admin control
- The fix is simple in theory: always block by default and carefully check every request before granting access

### A05:2021 – Security Misconfiguration

- Many systems stay on unsafe defaults (e.g., admin/admin, open ports)
- Debug tools or detailed error messages often leak info in production
- Misconfigured cloud storage or servers can expose huge amounts of data
- Prevention as my solution: automate configs, remove unused features, enforce least privilege

### A06:2021 – Vulnerable and Outdated Components

- Apps rely on many libraries and frameworks, if outdated, they become easy targets
- Hackers exploit known bugs in old components to break in
- Risk grows when teams don’t track or patch what they us
- Fix as my solution: keep an inventory, scan regularly, and update fast

### A03:2021 – Injection

- Injection is basically when user input sneaks into commands (like SQL or system commands)
- Happens if input isn’t checked or apps build queries by string-concatenation
- Common types are: SQL, NoSQL, OS command
- Fix as my solution: use parameterized queries, validate input, and escape special characters

### Munroe: xkcd 327: Exploits of a Mom

- Title is “Fully Vaccinated” 
- Person thinks being vaccinated = free pass to visit anyone
- CDC meant “safe with friends/family,” not strangers’ houses
- Joke: vaccine protects from COVID, not from social rules

## a) Goat

<img width="786" height="226" alt="image" src="https://github.com/user-attachments/assets/c545dafb-9bf9-4b6a-a42e-739389d1bab7" />

Not able to install openjdk 17, so I went with 21
<img width="803" height="135" alt="image" src="https://github.com/user-attachments/assets/5ef90485-5e2b-4f01-860f-3f40918136b2" />

Firewall installed and enabled
<img width="638" height="156" alt="image" src="https://github.com/user-attachments/assets/daf99cc6-636d-4345-9ac1-c86c4ef3ef09" />

I have no package for wget, so I need to install it first
<img width="803" height="346" alt="image" src="https://github.com/user-attachments/assets/fb5221d6-6617-49b4-8d43-0de95799fcfb" />

After that, I can install Goat
<img width="815" height="131" alt="image" src="https://github.com/user-attachments/assets/68f4a345-d657-4d59-ac5d-c3de07b216fd" />

Now it is installed
<img width="802" height="255" alt="image" src="https://github.com/user-attachments/assets/45b2fa71-f187-4a3c-ab6c-edb8d415c0c4" />

With this URL we can access it
<img width="939" height="653" alt="image" src="https://github.com/user-attachments/assets/d97e8730-57c0-4336-afc2-c060207927dc" />

## b) F12

So I created an account and did the first task here
<img width="1146" height="718" alt="image" src="https://github.com/user-attachments/assets/f2d12057-5919-4d22-be47-9280052e06a8" />

Here it basically says that the elements can be manipulated, the styling for example (Page 2)
<img width="790" height="243" alt="image" src="https://github.com/user-attachments/assets/c6112d9f-c5a9-4df2-9ae7-2014488578bf" />

Then we have here the console (Page 3)
<img width="1141" height="519" alt="image" src="https://github.com/user-attachments/assets/b8194d26-9586-4c5d-a05b-c598d677e66a" />

After that we actuall use it (Page 4)
<img width="1136" height="93" alt="image" src="https://github.com/user-attachments/assets/259c9d91-741f-4c1c-84bc-056aa196dd35" />

Later we have have a look on the sources
<img width="1141" height="250" alt="image" src="https://github.com/user-attachments/assets/73207019-9229-42b1-bb98-a1bba14b9700" />

And lastly we click on a request and try to guess the right number
<img width="1149" height="418" alt="image" src="https://github.com/user-attachments/assets/03dc0e15-234e-4f06-a160-9ec3fd33a59f" />

## c) Update

Seems already updated
<img width="367" height="49" alt="image" src="https://github.com/user-attachments/assets/02a7ce67-1141-46ae-aa54-31f34c2ab5f0" />

## d) SQL Zoo

### 0 SELECT basis

<img width="1195" height="481" alt="image" src="https://github.com/user-attachments/assets/6af9948a-159c-4e01-9083-a6183af51ad8" />

<img width="1209" height="563" alt="image" src="https://github.com/user-attachments/assets/2858b1d7-1cfd-4668-94f3-4004bc38cc33" />

<img width="1202" height="543" alt="image" src="https://github.com/user-attachments/assets/83eda4d9-ca21-4f86-bd18-35f36adb6d2d" />

### Select from world

<img width="1212" height="490" alt="image" src="https://github.com/user-attachments/assets/8c5d6c9b-67d8-4cab-b9ef-09a837de760f" />

<img width="1199" height="459" alt="image" src="https://github.com/user-attachments/assets/9b8e4604-1fff-4cd4-b2f8-381dd57e2d93" />

<img width="1203" height="456" alt="image" src="https://github.com/user-attachments/assets/f0846932-cdb7-4240-845d-02dd0802d25c" />

<img width="1017" height="340" alt="image" src="https://github.com/user-attachments/assets/b7bba02b-573a-444d-8ae7-e6eb15bf5435" />

<img width="1206" height="452" alt="image" src="https://github.com/user-attachments/assets/e0d629d7-14ed-49a1-844a-730062bf62ce" />

<img width="1204" height="462" alt="image" src="https://github.com/user-attachments/assets/2d153b7e-f380-4844-ae57-f2f21c8a0242" />

<img width="1200" height="488" alt="image" src="https://github.com/user-attachments/assets/8e6e90f4-5833-44d9-a503-9f3f2aa99c6a" />

<img width="1188" height="626" alt="image" src="https://github.com/user-attachments/assets/5986187f-05b7-4ac9-865d-28026162df89" />

<img width="1181" height="585" alt="image" src="https://github.com/user-attachments/assets/16989350-e5d9-45d6-b7df-25e3ba9c7e81" />

<img width="1201" height="530" alt="image" src="https://github.com/user-attachments/assets/21545e92-534e-4c21-9e56-49d623619d4f" />

I just realized I only had to do the first 2...
Nevermind!

### e) Portswigger













