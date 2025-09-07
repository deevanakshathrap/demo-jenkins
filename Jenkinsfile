pipeline
 agent any
 stages
   stages('version'){
    steps{
	  bat'"c:\\windows\\system32\\cmd.exe"/c python --version'
	  }
   }
   stage('done'){
    steps {
	  bat'"c:\\windows\\system32\\cmd.exe" /c python demo.py 
	  }
  }
  }
 }