pipeline {
    agent any
    environment{
        CONN = 'marcin@172.17.0.1'
        TOMCAT_HOME = '/home/marcin/tools/apache-tomcat-8.5.23'
        ENV_URL = 'https://github.com/chaminda/product-dummy'
        INITIALIZE_URL = 'http://172.17.0.1:8080/RestDemo-0.0.1-SNAPSHOT/demo'
    }
    tools {
        maven 'mvn3.5'
        jdk 'JDK1.8'
    }
    stages{
        stage ('Initialize') {
            steps {
                sh '''
                    echo "PATH = ${PATH}"
                    echo "M2_HOME = ${M2_HOME}"
                '''
            }

        }

        
    }
}
