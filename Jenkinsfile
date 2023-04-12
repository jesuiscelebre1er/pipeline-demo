pipeline {
    agent any

    stages {
        stage('clone'{
            steps {
                sh 'git clone https://github.com/jesuiscelebre1er/pipeline-demo.git'
                sh 'mv pipeline-demo /var/jenkens_home/workspace pipeline-demo /var/jenkens_home/pipeline-test'
            }
           
        }

//         stage('Build') {
//             steps {
//                 sh './mvnw clean package'
//             }
//         }

//         stage('Test') {
//             steps {
//                 sh './mvnw test'
//             }
//         }


    }
}
