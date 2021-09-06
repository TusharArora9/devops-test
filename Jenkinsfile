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
sh "touch {1..10}.txt"
}
}
}
}
