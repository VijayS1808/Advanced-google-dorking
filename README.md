# 🥇 Google Dorks for Bug Bounty 🥇

Level up your #BugBounty hunting with these essential Google Dorks for Web App Security & Pentesting! 💻🔍

🔹 PHP Extension w/ Parameters

🔹 API Endpoints

🔹 Juicy Extensions

🔹 SQLi / XSS / RCE Prone Params

🔹 File Upload Endpoints

🔹 Sensitive Docs & More!

💠💠💠💠💠💠💠 Check out the full list & start exploiting Google Dorks like a pro! 👇💠💠💠💠💠💠💠💠

### 💠Join Slack Channels💠

```
ext:pdf "invite" "join.slack" site:"example.com"
```
### 💠Broad domain search w/ negative search💠

```
site:"example.com" -www -shop -share -ir -mfa
```

### 💠PHP extension w/ parameters💠

```
site:"example.com" ext:php inurl:?
```

### 💠API Endpoints💠


```
site:"example[.]com" inurl:api | inurl:rest | inurl:v1 | inurl:v2 | inurl:v3 | inurl:v4 | inurl:graphql | inurl:service
```

```
site:"example[.]com" inurl:data | inurl:endpoint | inurl:action | inurl:json | inurl:swagger | inurl:auth | inurl:login | inurl:oauth | inurl:user)
```
```
site:"example[.]com" inurl:profile | inurl:session | inurl:token | inurl:key | inurl:config | inurl:admin | inurl:dashboard | inurl:status | inurl:monitor
```
```
site:"example[.]com" inurl:"/settings" | inurl:"/upload" | inurl:"/download" | inurl:"/search" | inurl:"/metrics" | inurl:"/events" | inurl:"/webhook" | inurl:"/notifications"
```
```
site:"example[.]com" inurl:"/report" | inurl:"/logs" | inurl:"/trace" | inurl:"/actions" | inurl:"/queue" | inurl:"/tasks" | inurl:"/subscriptions" | inurl:"/websocket" | inurl:"/batch"
```
```
site:"example[.]com" inurl:"/rpc" | inurl:"/call" | inurl:"/file" | inurl:"/static" | inurl:"/api-docs" | inurl:"/health" | inurl:"/register" | inurl:"/reset" | inurl:"/confirm"
```
```

site:"example[.]com" site:*/verify | site:*/verify-email | site:*/sms

```

### 💠Juicy Extensions💠
```
site:"example[.]com" ext:log | ext:txt | ext:conf | ext:cnf | ext:ini | ext:env | ext:sh 
```
```
site:"example[.]com" ext:bak | ext:backup | ext:swp | ext:old | ext:~ | ext:git | ext:svn | ext:htpasswd 
```
```
site:"example[.]com" ext:htaccess | ext:json | ext:xml | ext:yml | ext:csv | ext:sql | ext:db | ext:tar 
```
```
site:"example[.]com" ext:gz | ext:bz2 | ext:7z | ext:zip | ext:rar | ext:log1 | ext:out | ext:tmp 
```
```
site:"example[.]com" ext:swo | ext:diff | ext:patch | ext:md5 | ext:sha1 | ext:crt | ext:key | ext:pem 
```
```
site:"example[.]com" ext:cert | ext:jsp | ext:php | ext:asp | ext:aspx | ext:bak1 | ext:swp1 | ext:temp 
```
```
site:"example[.]com" ext:backup1 | ext:dump | ext:log~ | ext:passwd | ext:pswd | ext:tar.gz | ext:config 
```
```
site:"example[.]com" ext:inc | ext:sqlite | ext:sqlite3 | ext:db3 | ext:bak~ | ext:orig | ext:old~ 
```
```
site:"example[.]com" ext:access | ext:secret | ext:credentials | ext:env.backup | ext:env.old | ext:env~ | ext:lock
```
### 💠High % inurl keywords💠

```
site:"example[.]com" inurl:conf | inurl:env | inurl:cgi | inurl:bin | inurl:etc | inurl:root | inurl:sql | inurl:backup | inurl:admin | inurl:php | inurl:config | inurl:db | inurl:logs | inurl:wp-content | inurl:private | inurl:inc | inurl:uploads | inurl:data | inurl:server | inurl:secure | inurl:auth | inurl:login | inurl:dev | inurl:debug | inurl:staging | inurl:test | inurl:temp | inurl:core | inurl:install | inurl:readme | inurl:.env | inurl:.git | inurl:.svn | inurl:.bak | inurl:.tar | inurl:.zip | inurl:adminpanel | inurl:dashboard | inurl:config.php | inurl:settings | inurl:resources | inurl:static | inurl:api | inurl:config.json | inurl:.htaccess | inurl:.gitignore | inurl:composer.json | inurl:docker-compose.yml | inurl:uploads | inurl:tmp | inurl:assets | inurl:scripts | inurl:middleware | inurl:management | inurl:.npmrc | inurl:node_modules | inurl:debug.log | inurl:trace | inurl:version | inurl:custom | inurl:monitor | inurl:session | inurl:cache | inurl:backup.zip | inurl:dump.sql | inurl:archive | inurl:archives | inurl:binlog | inurl:email | inurl:messages | inurl:logs.txt | inurl:config.yaml | inurl:cron | inurl:ssl | inurl:secrets | inurl:protected | inurl:key | inurl:privatekey | inurl:publickey | inurl:db_backup | inurl:admin_area | inurl:panel | inurl:settings.xml | inurl:config.xml | inurl:.rnd | inurl:*.bak | inurl:.pem | inurl:.key | inurl:.pfx | inurl:db_restore | inurl:api_keys | inurl:.bashrc 
```

### 💠Server Errors💠

```
site:"example[.]com" inurl:"error" | intitle:"exception" | intitle:"failure" | intitle:"server at" | inurl:exception | "database error" | "SQL syntax" | "undefined index" | "unhandled exception" | "stack trace" | "500 Internal Server Error" | "503 Service Unavailable" | "404 Not Found" | "Bad Gateway" | "Gateway Timeout" | "request failed" | "server down" | "service error" | "server overload" | "service unavailable" | "connection timeout" | "database connection error" | "fatal error" | "application error" | "system error" | "configuration error" | "403 Forbidden" | "501 Not Implemented" | "502 Bad Gateway" | "408 Request Timeout" | "504 Gateway Timeout" | "403 Forbidden" | "database unresponsive" | "invalid query" 

```

### 💠XSS prone parameters💠

```
site:"example[.]com" inurl:q= | inurl:s= | inurl:search= | inurl:query= | inurl:keyword= | inurl:lang= | inurl:& | inurl:page= | inurl:term= | inurl:cat= | inurl:ref= | inurl:tag= | inurl:show= | inurl:id= | inurl:product= | inurl:article= | inurl:post= | inurl:count= | inurl:type= | inurl:category= | inurl:filter= | inurl:author= | inurl:date= | inurl:count= | inurl:entry= | inurl:sort= | inurl:order= | inurl:view= | inurl:searchterm= | inurl:querystring= | inurl:results= | inurl:subcategory= | inurl:filename= | inurl:file= | inurl:categoryid= | inurl:langcode= | inurl:price= | inurl:page_id= | inurl:limit= | inurl:slug= | inurl:status= | inurl:uid= | inurl:session= | inurl:locale= | inurl:page_num= 

```

### 💠Open Redirect prone parameters💠

```
site:"example[.]com" inurl:url= | inurl:return= | inurl:next= | inurl:redirect= | inurl:redir= | inurl:ret= | inurl:r2= | inurl:page= | inurl:destination= | inurl:go= | inurl:forward= | inurl:uri= | inurl:goto= | inurl:link= | inurl:target= | inurl:path= | inurl:href= | inurl:jump= | inurl:back= | inurl:loc= | inurl:out= | inurl:redirto= | inurl:refto= | inurl:continue= | inurl:from= | inurl:to= | inurl:action= | inurl:nextpage= | inurl:url_redirect= | inurl:load= | inurl:redirecturl= | inurl:dest= | inurl:destinationurl= | inurl:forwardto= | inurl:continue_to= | inurl:goto_url= | inurl:locate= | inurl:go_url= | inurl:jump_url= inurl:& inurl:http 
```

### 💠SQLi Prone Parameters💠

```
site:"example[.]com" inurl:id= | inurl:pid= | inurl:category= | inurl:cat= | inurl:action= | inurl:sid= | inurl:dir= | inurl:& | inurl:page= | inurl:article= | inurl:search= | inurl:userid= | inurl:username= | inurl:product= | inurl:order= | inurl:post= | inurl:newsid= | inurl:bookid= | inurl:section= | inurl:flag= | inurl:view= | inurl:catid= | inurl:empid= | inurl:query= | inurl:lang= 
```

### 💠SSRF Prone Parameters💠

```
site:"example[.]com" inurl:http | inurl:url= | inurl:path= | inurl:dest= | inurl:html= | inurl:data= | inurl:domain= | inurl:page= | inurl:target= | inurl:ref= | inurl:server= | inurl:forward= | inurl:location= | inurl:target_url= | inurl:callback= | inurl:proxy= | inurl:request= | inurl:forward_to= | inurl:service= | inurl:fetch= | inurl:uri= | inurl:endpoint= | inurl:address= | inurl:host= | inurl:urlpath= | inurl:redir= | inurl:link= | inurl:shell= | inurl:destination= | inurl:url_redirect= | inurl:connect= | inurl:outbound= | inurl:internal= | inurl:call= | inurl:res= | inurl:fetch_url= | inurl:request_url= | inurl:netloc= | inurl:route= | inurl:linkto= | inurl:req= | inurl:get= | inurl:forwarded= | inurl:forward_url= | inurl:source= | inurl:urlencode= | inurl:params= | inurl:referrer= | inurl:response= | inurl:callback_url= | inurl:load= | inurl:fetchdata= | inurl:responsebody= | inurl:out= | inurl:deliver= | inurl:host_header= 
```

### 💠LFI Prone Parameters💠

```
site:"example[.]com" inurl:include | inurl:dir | inurl:detail= | inurl:file= | inurl:folder= | inurl:inc= | inurl:locate= | inurl:doc= | inurl:conf= | inurl:page= | inurl:section= | inurl:config= | inurl:lib= | inurl:template= | inurl:template_id= | inurl:script= | inurl:component= | inurl:data= | inurl:files= | inurl:load= | inurl:module= | inurl:source= | inurl:view= 
```

### 💠RCE Prone Parameters💠

```
site:"example[.]com" inurl:cmd | inurl:exec= | inurl:query= | inurl:code= | inurl:do= | inurl:run= | inurl:read= | inurl:ping= | inurl:system= | inurl:shell= | inurl:command= | inurl:eval= | inurl:cmdshell= | inurl:execute= | inurl:action= | inurl:script= | inurl:action=run | inurl:input= | inurl:output= | inurl:query_string= | inurl:file= | inurl:evalfile= | inurl:get= | inurl:set= | inurl:runfile= | inurl:include= | inurl:upload= | inurl:download= | inurl:invoke= | inurl:execfile= | inurl:fetch= | inurl:outputfile= | inurl:open= | inurl:save= | inurl:process= | inurl:runcommand= | inurl:execurl= | inurl:attach= | inurl:cmd_exec= | inurl:shell_exec= | inurl:evalcmd= | inurl:run_query= | inurl:exec_query= | inurl:systemcall= | inurl:shellcommand= | inurl:doscript= | inurl:execfunction= | inurl:run_script= | inurl:execute_command= | inurl:eval_exec= | inurl:commandexec= | inurl:process_exec= | inurl:call_shell= | inurl:do_exec= | inurl:commandinput= | inurl:run_input= | inurl:execute_input= | inurl:run_action= | inurl:eval_input= 
```

### 💠File upload endpoints💠

```
site:"example.com" ”choose file”
```

### 💠API Docs💠

```
site:"example[.]com" inurl:apidocs | inurl:api-docs | inurl:swagger | inurl:api-explorer | inurl:docs/api | inurl:v1/api | inurl:developers | inurl:openapi | inurl:api-reference | inurl:api/v1 | inurl:rest-api | inurl:json-api | inurl:developer-guide | inurl:api-guide | inurl:resources/api | inurl:api/tutorial | inurl:dev/api | inurl:api-docs | inurl:api/v2 | inurl:postman | inurl:api-platform | inurl:api-management | inurl:api-console 
```

### 💠Login Pages💠

```
site:"example[.]com" inurl:login | inurl:signin | inurl:auth | inurl:authentication | inurl:secure | inurl:account | inurl:user | inurl:member | inurl:loginpage | inurl:loginform | inurl:access | inurl:entry | inurl:panel | inurl:admin | inurl:portal | inurl:dashboard | inurl:console | inurl:adminlogin | inurl:management | inurl:signup | inurl:register | inurl:create-account | inurl:join | inurl:subscription | inurl:signupform | inurl:signup-page | inurl:signupform.php | inurl:registerform | inurl:registration | inurl:signup.html | inurl:signup.aspx | inurl:register.php | inurl:register.html | inurl:register.aspx | inurl:sign_in | inurl:sign_up | inurl:reset | inurl:forgot | inurl:recovery | inurl:loginform.php | inurl:signinform.php | inurl:forgot-password | inurl:change-password | inurl:user-recovery | inurl:account-recovery | inurl:recover | inurl:create-account-page | inurl:signup-process | inurl:register-now | inurl:new-account | inurl:signupform-new | inurl:signup-confirmation | inurl:sign-up-form | inurl:signup-link | inurl:activation | inurl:verify-account | inurl:confirm-email | inurl:welcome | inurl:activate-account | inurl:verify-registration | inurl:welcome-email | inurl:confirm-registration | inurl:account-verification | intitle:login | intitle:signin | intitle:auth | intitle:authentication | intitle:secure | intitle:account | intitle:user | intitle:member | intitle:loginpage | intitle:loginform | intitle:access | intitle:entry | intitle:admin | intitle:panel | intitle:portal | intitle:dashboard | intitle:console | intitle:adminlogin | intitle:management | intitle:signup | intitle:register | intitle:create-account | intitle:join | intitle:subscription | intitle:register-now | intitle:signup-form | intitle:activation | intitle:verify-account | intitle:confirm-email | site:"example[.]com" | site:"*.example[.]com" | inurl:login.aspx? | inurl:signin.aspx? | inurl:auth.php? | inurl:login.html? | inurl:signup.php? | inurl:register.php? | inurl:login-reset | inurl:forgot-password | inurl:change-password | inurl:login-reset | inurl:user-login | inurl:sign-in.php | inurl:loginform.html | inurl:admin-portal | inurl:signup? | inurl:register? | inurl:create-account? | inurl:register-form? | inurl:register-page? | inurl:signup-process? | inurl:signup-confirmation? | inurl:signup-form.php | inurl:account-verification? | inurl:email-confirmation? | inurl:account-activation? | inurl:activate-account? | inurl:verify-registration? | inurl:welcome-email? | inurl:confirm-registration?
```

### 💠Test Environments💠

```
site:"example[.]com" inurl:test | inurl:env | inurl:dev | inurl:staging | inurl:sandbox | inurl:debug | inurl:temp | inurl:internal | inurl:demo | inurl:qa | inurl:preprod | inurl:local | inurl:beta | inurl:devops | inurl:backup | inurl:mirror | inurl:acceptance | inurl:development | inurl:testing | inurl:ci | inurl:uat | inurl:prototype | inurl:experimental | inurl:training | inurl:validation | inurl:scratch | inurl:review | inurl:integration | inurl:build 
```

### 💠Sensitive Documents💠

```
site:"example.com" ext:txt | ext:pdf | ext:xml | ext:xls | ext:xlsx | ext:ppt | ext:pptx | ext:doc | ext:docx
intext:"confidential" | intext:"Not for Public Release" | intext:"internal use only" | intext:"do not distribute" | intext:"proprietary" | intext:"restricted" | intext:"private" | intext:"sensitive" | intext:"for authorized eyes only" | intext:"classified"

```

### 💠Sensitive Parameters💠

```
site:"example[.]com" inurl:email= | inurl:phone= | inurl:password= | inurl:secret= | inurl:token= | inurl:apikey= | inurl:auth= | inurl:username= | inurl:creditcard= | inurl:ssn= | inurl:dob= | inurl:cvv= | inurl:pin= | inurl:access_token= | inurl:refresh_token= | inurl:security_code= | inurl:client_secret= | inurl:session_id= | inurl:invoice_id= | inurl:order_id= 
```

### 💠Adobe Experience Manager (AEM)💠

```
site:"example[.]com" inurl:/content/usergenerated | inurl:/content/dam | inurl:/jcr:content | inurl:/libs/granite | inurl:/etc/clientlibs | inurl:/content/geometrixx | inurl:/bin/wcm | inurl:/crx/de | inurl:/content/sites | inurl:/libs/cq/core | inurl:/content/experience | inurl:/bin/querybuilder | inurl:/content/environments | inurl:/etc/designs | inurl:/content/websites 

```

### 💠Disclosed XSS and Open Redirects💠

```
site:openbugbounty.org inurl:reports intext:"example.com"
```

###💠 Google Groups💠

```
site:groups.google.com "example.com"
```

### 💠Code Leaks💠

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

### 💠Cloud Storage💠

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

### 💠JFrog Artifactory💠

```
site:jfrog.io "example[.]com"
```

### 💠Firebase💠

```
site:firebaseio.com "example[.]com"
```


