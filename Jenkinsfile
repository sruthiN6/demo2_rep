pipeline
{
agent any 
stages
{
stage('clone')
{
steps{
git 'https://github.com/sruthiN6/demo2_rep.git'
}
}
stages(build')
{
steps{
sh'javac hello.java'
}
}
stage('run')
{
steps{
sh 'java hello'
}
}
}
}
