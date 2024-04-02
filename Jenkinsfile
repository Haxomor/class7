node("denis_class"){
    stage("clone"){
        git branch: 'main', url: 'https://github.com/Haxomor/class7.git'

    }
    stage("execute"){
        sh "ls -l"
        sh "/usr/bin/python3 Jenkinsfile"
    }
}
