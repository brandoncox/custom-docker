*To Build*
 - oc new-build https://github.com/brandoncox/custom-docker --context-dir=python/v2 --strategy=docker --name=pythonv2
 
*To Deploy*
 - oc new-app --image-stream=pythonv2

*To Demo*
 - oc rsh {pod}
 - cd /app       
 - python print_version.py
