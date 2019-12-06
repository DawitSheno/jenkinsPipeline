# jenkinsPipeline
pipeline
agent any
stages
{
stage('Build')
{
steps{
echo " Building the Project..."
}
}
stage('Test')
{
steps{
echo" Testing the Project"
}
}
stage('Deploy')
{
steps{
echo "Deploying the project "
}
}
stage('Realease')
{
steps{
echo" Realeasing the project "
}
}
}
}
