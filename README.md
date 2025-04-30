# Nginx - CI Pipeline
## Steps :-
## **1. Create a instance :-**
![1](https://github.com/sudhajobs0107/nginx-github_actions_ci/blob/main/images/1.png)

## **2. Code send from local to github command are :-**
```
git init
git remote add origin https://github.com/sudhajobs0107/nginx-pipeline.git
git add .
git commit -m "first commit"
git push -u origin master
```
## **3. Make file .github/workflows/aws.yml for pipeline.**
## **4. Add AWS credentials as a secret in github.**
## **5. Connect instance to local(powershell) through ssh :-**
```
ssh -i "key" ubuntu@hostname
```
## **6. Run command :-**
```
sudo apt update && sudo apt upgrade -y
 sudo apt install nginx -y
```
## **7. And we automate our application using GitHub Actions**
![2](https://github.com/sudhajobs0107/nginx-github_actions_ci/blob/main/images/2.png)
![3](https://github.com/sudhajobs0107/nginx-github_actions_ci/blob/main/images/3.png)



# Our Nginx - CI Pipeline Project is completed :smile:.

