node{
    stage("Checkout"){
        checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: 'GitHub', url: 'https://github.com/Ranjith02/multi-mod.git']]])
}
stage("Build"){
    echo "date"
}
}
