pipeline{
agent any 
stages{
stage('Build my app'){
  when{
  expression{
    BRANCH_NAME='master'
  }
  }
steps{
echo 'building the app'
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
