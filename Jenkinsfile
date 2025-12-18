pipeline{
agent any 
environment{
New_version=1.1
}
stages{
stage('Build my app'){
when{
expression{
env.BRANCH_NAME=='main'
}
}
steps{
echo 'building the app'
echo "the version of the app is ${New_version}"
}
}
stage('Testing the app'){
steps{
echo 'Testing the app'
}
}
stage('Deployed the app'){
steps{
echo 'Deploying the app '
}
}
}
}
