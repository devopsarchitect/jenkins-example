pipeline {
    agent any

    stages {
        stage ('Compile Stage') {

            steps {
                echo  ' stage ('Compile Stage')... '
                //withMaven(maven : 'maven_3_5_0') {
                    sh 'mvn clean compile'
                //}
            }
        }

        stage ('Testing Stage') {

            steps {
                echo  ' stage ('Testing Stage')... '
                //withMaven(maven : 'maven_3_5_0') {
                    sh 'mvn test'
               // }
            }
        }


        stage ('Deployment Stage') {
            steps {
                echo  ' stage ('Deployment Stage')... '
               // withMaven(maven : 'maven_3_5_0') {
                   // sh 'mvn deploy'
               // }
            }
        }
    }
}
