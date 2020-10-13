Hi There! Here is a complete documentation of this application

### What is it?
- This is a tool that allows you to add CSV files and compare them against the database to find out who were the people that might have gotten into contact with this person.
- This tool focuses on comparing 3 main groups of people with the suspects. They are the Confirmed Cases (CC), Close Contacts (Close) and People At The Public (PTAP).
- This is a one time use tool. This means that once you exit the page, the data will be cleared.

<img align="right" height="250" alt="" src="https://i.imgur.com/VNFSV1c.gif" />

### Languages and Tools Used
<code><img height="30" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/react/react.png" alt="ReactJs"></code>
<code><img height="30" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/postgresql/postgresql.png" alt="Postgres"></code>
<code><img height="30" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/java/java.png" alt="Java"></code>
<code><img height="30" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/spring-boot/spring-boot.png" alt="Spring Boot"></code>
<code><img height="30" src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/7b/Tomcat-logo.svg/1200px-Tomcat-logo.svg.png" alt="Apache Tomcat"></code>
<code><img height="30" src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/d5/CSS3_logo_and_wordmark.svg/1200px-CSS3_logo_and_wordmark.svg.png" alt="CSS"></code>

### Features
- CSV importing
- Easy to use map to show the path of the suspects (can be filtered for easier viewing)
- On intersection of paths, it is easy to check if the suspects have come into contact with each other using the gantt chart
- Sections will only appear if there are items for users to use. (For example, if there is no data is shown in the table section, no visuals will appear)
- Easy visualisation of person's routes in the profile page
- Allows user to go in depth (+ 1 layer) to view intersection of person (CC, Close, PTAP) with other people

### Contributers
[![TP](https://img.shields.io/badge/-Temasek%20Polytechnic-0e76a8?style=flat-square&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAA4AAAAOCAMAAAAolt3jAAAABGdBTUEAALGPC/xhBQAAAAFzUkdCAK7OHOkAAABdUExURe0bJOtMUvbPz/Ovse4eJ%200RGusuNu4WH////%20wMFuyLjOkABv3//%20olLuo4QOtbYfbc3Pz5%20elDSfz09PO/vvO4uPvw8Pvq6upUWfClpe1tcPOdn/TExegdJfXCweRi15IAAAHCelRYdFJhdyBwcm9maWxlIHR5cGUgaWNjAAA4jaVT2a3cMAz8VxUpgeIplWNLMpD%20Gwh1eb2L9xC8hIBhe8RjPByH36WEXz1UNEAPzKBFSasRMA1IqzZjQ0E2RgRJkuVAAKuXH3tS7PfoF/vrGTQqGRlwFBDgAv8Ql08Nq%20uISlhvZj%20M8MP8U1nFSOegCGnClIJ/GBgazwNe%20dzMXCHYeF54ZOebXI6FH6sAS3A5h4zzoL4K3vDGN25P/Eob743YNzOpIiyxEbzggeMLf8vnGw%20dqqFOKqj7gH0RxUQ/Rd%20LKW6dJiLrPJawH9wgDoobxaUBxj7F3dSNI353kfqQrhnW9d565R74ubVvJhK%20BrI30GsNovlsff3m3Q3XFGejaU0uM7kz6mxVVrGufFlXZ5pvRvcv8IjuWPgwrHtIieiZGKHwMRtJo6sH4Vyr5XM0qskGfh447vWYn0p1rL1A5k3gTSO98vALpdZmQf6SKXKeW77SaHzq2cJXiYqHjASbjo6pNgONbpP4SNvWQPUYjC48bIogozLScvgh598a7Prwvw12ffhs8Ob09wZwUB2FwjaWwaWMvJzz3BquCXBJCX8AEDoaxXGJJX0AAAAJcEhZcwAAAAEAAAABAE8lxNYAAACASURBVAjXZY7ZCsMwDATlQ1Zsy3dCkl7//5m140IL3QfBsFoYgL8QaNA9HzLOEvZMtFsW8agpUQeNjpldGwf7P4kia2V57CWMHtrLGz694tjnFJp8ClZeshkt5YXPnfOyjq1G8dhSkau6SgBEa/jucVI3osjK6q9nuAn69bZT8Q0R4QUJZ46JMAAAAABJRU5ErkJggg==&logoColor=white)](https://www.tp.edu.sg/)
[![CSIT](https://img.shields.io/badge/CSIT-3b5998?style=flat-square&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAA4AAAAOCAMAAAAolt3jAAAABGdBTUEAALGPC/xhBQAAAAFzUkdCAK7OHOkAAABvUExURcKmnN/W0Ofh3P///%20bb2P///9vQyceXhem4qKN%20b%20Pb1dXKwdDDutjNxdPHvvbx7%20Td1/39/M7AttzUzPDAr/vz8Ni1qt%20woMqupOzl4vz6%20e/Etu/r6NOnl72RgtiypLSTh/Pe1sObjdy%20s6%20Pg3FT05EAAAAKdFJOU/7////9///%20/v5SGmKXAAAAjElEQVQI102O2w7CMAxD3YoGSHrZ2q7buosY8P/fSMUDzFHkHFmRDPPTilpRv2ffNuzbCCInxCTaDGPOSKQS65lWM%20R8Q7QUxbWwpdsVSSlS3s3t9zkB5KNL3nvXh8c0QXWs2rCuYS8F1ooVH6X561iwstaaO5KOD7Pg32pY%20nLCUCpOWB/v%20wnN7C4f1vYJF8xTHO4AAAAASUVORK5CYII=&logoColor=white)](https://www.csit.gov.sg/)
