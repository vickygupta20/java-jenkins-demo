pipeline {

agent any

tools {

maven 'Maven'

}

stages {

stage('Build') {

steps {

bat 'mvn clean compile'

}

}

stage('Test') {

steps {

sh 'mvn test'


}

}

}

}