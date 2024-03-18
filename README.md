# jenkins_test
jenkins 測試

使用 tag 部署
branch: tag
tag: v1.0.1



### docker安裝
    docker pull jenkins/jenkins
    
    docker run -p 8080:8080 --name=jenkins -d jenkins/jenkins