node {
    stage 'Clone the project'
    git 'https://github.com/feysal07/Spring-Boot-Sample-Project.git'

    dir('spring-jenkins-pipeline') {
        stage("Compilation and Analysis") {
            parallel 'Compilation': {
                sh "./mvnw clean install -DskipTests"
            }
    }
}