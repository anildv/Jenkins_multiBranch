pipeline {
    agent any
stages ('Build'){
steps { 
echo "It is building"
sh "mvn clean compile"
}
}
stage('Test') {
steps {
echo "It is testing"
sh "mvn test"

