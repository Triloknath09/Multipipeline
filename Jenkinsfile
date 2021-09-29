node('master')
{
    stage('Continuous Download_loans')
        {
    git 'https://github.com/Triloknath09/Multipipeline.git'
        }
    stage('Continuous Build_loans')
        {
    sh label: '', script: 'mvn package'
        }
   
}

