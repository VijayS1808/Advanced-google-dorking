# 🚨 Google Dorks for Bug Bounty 🚨

Level up your #BugBounty hunting with these essential Google Dorks for Web App Security & Pentesting! 💻🔍

🔹 PHP Extension w/ Parameters

🔹 API Endpoints

🔹 Juicy Extensions

🔹 SQLi / XSS / RCE Prone Params

🔹 File Upload Endpoints

🔹 Sensitive Docs & More!

Check out the full list & start exploiting Google Dorks like a pro! 👇

👉 [VeryLazyTechDork](https://verylazytech.github.io/index.html)

[![image](https://github.com/user-attachments/assets/4865ee71-ebb3-46fa-b5f9-73d7d74c374d)](https://verylazytech.github.io/index.html)


[![My Shop](https://img.shields.io/badge/My%20Shop-verylazytech-%23FFDD00?style=flat&logo=buy-me-a-coffee&logoColor=yellow)](https://buymeacoffee.com/verylazytech/extras)
[![Medium](https://img.shields.io/badge/Medium-%40verylazytech-%231572B6?style=flat&logo=medium&logoColor=white)](https://medium.com/@verylazytech)
[![Github](https://img.shields.io/badge/Github-verylazytech-%23181717?style=flat&logo=github&logoColor=white)](https://github.com/verylazytech)
[![Buy Me A Coffee](https://img.shields.io/badge/Buy%20Me%20A%20Coffee-verylazytech-%23FFDD00?style=flat&logo=buy-me-a-coffee&logoColor=yellow)](https://buymeacoffee.com/verylazytech)
[![My GitBook](https://img.shields.io/badge/My%20GitBook-VeryLazyTech-%23FFDD00?style=flat&logo=gitbook&logoColor=white)](https://www.verylazytech.com)
[![X](https://img.shields.io/twitter/url?url=https%3A%2F%2Fx.com%2Fverylazytech)](https://x.com/verylazytech)
---

### Join Slack Channels

```
ext:pdf "invite" "join.slack" site:"example.com"
```
### Broad domain search w/ negative search

```
site:"example.com" -www -shop -share -ir -mfa
```

### PHP extension w/ parameters

```
site:"example.com" ext:php inurl:?
```

### API Endpoints

```
site:"example[.]com" inurl:api | site:*/rest | site:*/v1 | site:*/v2 | site:*/v3
```

### Juicy Extensions

```
site:"example[.]com" ext:log | ext:txt | ext:conf | ext:cnf | ext:ini | ext:env | ext:sh | ext:bak | ext:backup | ext:swp | ext:old | ext:~ | ext:git | ext:svn | ext:htpasswd | ext:htaccess | ext:json
```

### High % inurl keywords

```
inurl:conf | inurl:env | inurl:cgi | inurl:bin | inurl:etc | inurl:root | inurl:sql | inurl:backup | inurl:admin | inurl:php site:"example[.]com"
```

### Server Errors

```
inurl:"error" | intitle:"exception" | intitle:"failure" | intitle:"server at" | inurl:exception | "database error" | "SQL syntax" | "undefined index" | "unhandled exception" | "stack trace" site:"example[.]com"
```

### XSS prone parameters

```
inurl:q= | inurl:s= | inurl:search= | inurl:query= | inurl:keyword= | inurl:lang= inurl:& site:"example.com"
```

### Open Redirect prone parameters

```
inurl:url= | inurl:return= | inurl:next= | inurl:redirect= | inurl:redir= | inurl:ret= | inurl:r2= | inurl:page= inurl:& inurl:http site:"example.com"
```

### SQLi Prone Parameters

```
inurl:id= | inurl:pid= | inurl:category= | inurl:cat= | inurl:action= | inurl:sid= | inurl:dir= inurl:& site:"example.com"
```

### SSRF Prone Parameters

```
inurl:http | inurl:url= | inurl:path= | inurl:dest= | inurl:html= | inurl:data= | inurl:domain=  | inurl:page= inurl:& site:"example.com"
```

### LFI Prone Parameters

```
inurl:include | inurl:dir | inurl:detail= | inurl:file= | inurl:folder= | inurl:inc= | inurl:locate= | inurl:doc= | inurl:conf= inurl:& site:"example.com"
```

### RCE Prone Parameters

```
inurl:cmd | inurl:exec= | inurl:query= | inurl:code= | inurl:do= | inurl:run= | inurl:read=  | inurl:ping= inurl:& site:"example.com"
```

### File upload endpoints

```
site:"example.com" ”choose file”
```

### API Docs

```
inurl:apidocs | inurl:api-docs | inurl:swagger | inurl:api-explorer site:"example[.]com"
```

### Login Pages

```
inurl:login | inurl:signin | intitle:login | intitle:signin | inurl:secure site:"example[.]com"
```

### Test Environments

```
inurl:test | inurl:env | inurl:dev | inurl:staging | inurl:sandbox | inurl:debug | inurl:temp | inurl:internal | inurl:demo site:"example.com"
```

### Sensitive Documents

```
site:"example.com" ext:txt | ext:pdf | ext:xml | ext:xls | ext:xlsx | ext:ppt | ext:pptx | ext:doc | ext:docx
intext:“confidential” | intext:“Not for Public Release” | intext:”internal use only” | intext:“do not distribute”
```

### Sensitive Parameters

```
inurl:email= | inurl:phone= | inurl:password= | inurl:secret= inurl:& site:"example[.]com"
```

### Adobe Experience Manager (AEM)

```
inurl:/content/usergenerated | inurl:/content/dam | inurl:/jcr:content | inurl:/libs/granite | inurl:/etc/clientlibs | inurl:/content/geometrixx | inurl:/bin/wcm | inurl:/crx/de site:"example[.]com"
```

### Disclosed XSS and Open Redirects

```
site:openbugbounty.org inurl:reports intext:"example.com"
```

### Google Groups

```
site:groups.google.com "example.com"
```

### Code Leaks

```
site:pastebin.com "example.com"
```

```
site:jsfiddle.net "example.com"
```

```
site:codebeautify.org "example.com"
```

```
site:codepen.io "example.com"
```

### Cloud Storage

```
site:s3.amazonaws.com "example.com"
```

```
site:blob.core.windows.net "example.com"
```

```
site:googleapis.com "example.com"
```

```
site:drive.google.com "example.com"
```

```
site:dev.azure.com "example[.]com"
```

```
site:onedrive.live.com "example[.]com"
```

```
site:digitaloceanspaces.com "example[.]com"
```

```
site:sharepoint.com "example[.]com"
```

```
site:s3-external-1.amazonaws.com "example[.]com"
```

```
site:s3.dualstack.us-east-1.amazonaws.com "example[.]com"
```

```
site:dropbox.com/s "example[.]com"
```

```
site:box.com/s "example[.]com"
```

```
site:docs.google.com inurl:"/d/" "example[.]com"
```

### JFrog Artifactory

```
site:jfrog.io "example[.]com"
```

### Firebase

```
site:firebaseio.com "example[.]com"
```

