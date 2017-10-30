*To Build*
 - oc new-build https://github.com/brandoncox/custom-docker --context-dir=jdk --strategy=docker
*To Deploy*
 - oc new-app --image-stream=custom-docker
