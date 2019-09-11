node{
        stage ("Checkout")
        {
            checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[url: 'https://github.com/Rasmita2018/First_test.git']]])
        }
    
        stage ( "Build")
        {
            echo "demo Build"
        }
         
}
        
    
