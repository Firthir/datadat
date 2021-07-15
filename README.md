### Step 1:  
```mkdir projectTitle```
### Step 2:  
```npm init  ```
### Step 3:  
```npm install --save json-server ``` 
### Step 4:  
Create a new file & name it ```db.json```
Put the JSON data you want to retrieve into that file.
### Step 5:  
In package.json replace the existing value of key name: “scripts” to:
```
"scripts": {
    "json:server": "json-server --watch db.json"
},
```
### Step 6:  
```npm run json:server```
### Step 7:  
Host for FREE. For that, you need to create a new repository in GitHub and Pushed the local repo to remote GitHub.  
After you pushed the local repo to origin master. Open the URL:   
https://my-json-server.typicode.com/```your-github-username```/```your-repo-name```  
My URL: https://my-json-server.typicode.com/Firthir/datadat  