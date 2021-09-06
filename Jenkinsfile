pipeline{
agent {label 'node2'}
stages{
stage("make directory devops"){
steps{
sh "mkdir /test/devops"
}
}
stage("file creation"){
steps{
sh "touch /test/devops/{1..10}.txt"
}
}
}
}
