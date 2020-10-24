pipeline{
agent any
stages 
{
stage('Build') 
{
steps{
echo "Building the Project.........."
sh 'touch build-stage.txt'
sh 'ls'
}
}
stage('Test') 
{
steps{
echo "Testing the Project.........."
}
}
stage('Deploy') 
{
steps{
echo "Deploying the Project.........."
  sh 'touch deploy-stage.txt'
}
}
}
