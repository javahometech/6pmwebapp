pipeline{
    agent any
    parameters {
        string defaultValue: 'master', description: 'Choose the branch to build and deploy', name: 'branchName', trim: false
    }
    stages{
        stage('SCM Checkout'){
            steps{
                git branch: "${params['branchName']}",
                    url: 'https://github.com/javahometech/6pmwebapp'
            }
        }
    }
}