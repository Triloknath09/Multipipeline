node('master')
{
    stage('Continuous Download')
        {
    git 'https://github.com/Triloknath09/Multipipeline.git'
        }
    stage('Continuous Build')
        {
    sh label: '', script: 'mvn package'
        }
   
}

