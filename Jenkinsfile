node {
    stage('Clone'){
        git 'https://github.com/joelrajao/hello.git'
    }
    stage('Build'){
       sh label:'', script: 'cd src/main/java/org/example && javac Main.java'
    }
    stage('Run'){
        sh label:'', script: 'cd src/main/java/org/example && java -classpath ../../ org.example.Main'
    }
}