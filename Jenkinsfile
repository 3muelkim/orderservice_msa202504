

    pipeline{
        agent any

    stage{
        //각 작업 단위를 스테이지로 나누어서 작성 가능
        stage('Pull Codes from Github'){ // 스테이지 제목 (맘대로 써도 됨)
            steps{
                checkout scm // 젠킨스와 연결된 소스 컨트롤 매니저(git 등)에서 코드를 가지고 옴
            }
            stage('Build Codes by Gradle'){
                steps{
                    script{
                    sh"""
                    echo "Build Stage Start!"
            }
        }
    }

}