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

