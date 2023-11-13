//original jenkinsfile
@Library('my-shared-library') _
pipeline{

    agent any

    stages{
        stage('Git Checkout'){

            steps{
                script{
                    git branch: 'main', url: 'https://github.com/asingh824/https---github.com-asingh824-singh1_java_app.git'
                }
                //gitCheckout(
                   // branch: "main",
                  //  url: "https://github.com/asingh824/https---github.com-asingh824-singh1_java_app.git"
                    //git branch: 'main', url: 'https://github.com/asingh824/https---github.com-asingh824-singh1_java_app.git'
                //)
            }
        }
/*
        stage('Unit Test maven'){

            steps{
                script{

                    mvnTest()

                }
            }
        }   */
        }
    }