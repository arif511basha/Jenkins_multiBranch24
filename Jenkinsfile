node('master')
{
    stage('Continuous Download')
        {
    git 'https://github.com/sunildevops77/maven.git'
        }
    stage('Continuous Build')
        {
    sh label: '', script: 'mvn package'
        }
     stage('Continuous testing')
        {
    echo "testing"
        }
    }
