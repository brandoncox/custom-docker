*To Build*
 - oc new-build https://github.com/brandoncox/custom-docker --context-dir=jdk --strategy=docker --name=jdk
 
*To Deploy*
 - oc new-app --image-stream=jdk
 
*To Run*
 - oc rsh {pod}
 - cd /app
 - javac Test.java
 - java Test
