pipeline {
 agent any
 stages {
 stage('build') {
 steps {
 sh 'javac -d . src/*.java'
 sh 'echo Main-Class: Rectangulator > MANIFEST.MF'
 sh 'java Rectangulator 10 20'
 }
 stage('run') {
 steps {
 sh 'java  Rectangular 7 9'
 }
 }
 }
 }
}
