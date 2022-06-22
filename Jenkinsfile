pipeline {
agent any
stages {
stage ('Build') {
steps {
echo "This is building"
sh "mvn clean compile"
}
}
stage ('Test') {
steps {
echo "This is testing"
sh "mvn test"
}
}
stage ('package') {
steps {
echo "this is packaging"
sh "mvn -B -DskipTests package"
}
}
}
}
