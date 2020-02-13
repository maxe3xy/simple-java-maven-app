pipeline {
    agent any
    stages {
        stage('package') {
            steps {
                sh 'mvn -B -DskipTests clean package'
            }
        stage('Build') {
            steps {
                sh 'mvn -B -DskipTests clean package'
            }
        stage('Deploy_pre') {
            steps {
                sh 'mvn -B -DskipTests clean package'
            }
        stage('Deploy') {
            steps {
                sh 'mvn -B -DskipTests clean package'
            }	
        stage('Deploy_post') { 
            steps {
                sh 'mvn -B -DskipTests clean package' 
            }
        }
    }
}
