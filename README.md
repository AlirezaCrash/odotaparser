1. run it with "java -jar stats-0.1.0.jar" . it starts a server itself at localhost:5600
2. send a curl request with :  "  curl -X POST --data-binary "@{path_to_the_replay}\\{replay_name}.dem" http://localhost:5600/parse " 
   (if you need the output in a text file add -o output.txt at the end of the command)
