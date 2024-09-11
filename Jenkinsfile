pipeline{
  agent any 
  stages{
   stage('working with conditions'){
    steps{
    script{
        a=10 
        b=20
        if (a > b) {
            println "a is greater then b value is ${a}"
        }
        else {
            println "b is greater then a value is ${b}"
        }
        for (i=1;i<=10;i++){
            println "my value of i is ${i}"
        }
        lisl=[20,30,40,50]
        for(element in lisl){
            println "my element values is ${element}"
        }
        k=1
        while (k <=0) {
            println "k value is ${k}"
            k=k+1
        }
        File file = new File("/tmp/testdata.txt")
          for(line in file.readLines()){
            println "your lines is ${line}"
           }     
       }
     }
    }
   }
  }

