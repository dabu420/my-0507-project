properties([pipelineTriggers([pollSCM('* * * * *')])])
node {
    stage("clone"){
        git branch: 'main', url: 'https://github.com/dabu420/my-0507-project.git'
    }
    stage("show files"){
        sh "ls -ltr"
    }
}
