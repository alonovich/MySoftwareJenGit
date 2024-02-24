properties([pipelineTriggers([pollSCM('*/30 * * * *')])])
node {
    stage("clone") {
        git branch: 'master', url: 'https://github.com/alonovich/MySoftwareJenGit.git'
    }
    stage("show files"){
        sh "ls -l"
    }
}
