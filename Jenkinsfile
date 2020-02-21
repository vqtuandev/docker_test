node('docker') {

    stage 'Checkout'
        checkout scm
    stage 'Build'
        sh "docker build -t simple_nodejs ."
    stage 'Pusblish UT Reports'
        sh "docker-compose up -d"
}
