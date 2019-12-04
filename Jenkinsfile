pipeline{
    agent any
    stages{
        stage('Parallel Demo'){
            parallel(
              task1: {
                echo "This is task1"
              },
              task2: {
                echo "This is task2"
              }
            )
        }
    }
}