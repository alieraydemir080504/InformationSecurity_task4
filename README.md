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

