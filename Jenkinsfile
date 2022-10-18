pipeline{
  agent{
      label "built-in"

}

   stages{
    stage(deploy on tomcat){
      steps{
         sh"copy -r gameoflife.war /mnt/server/apache-tomcat-9.0.68/webapps"
}
}
}
}
 
