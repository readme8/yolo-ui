# yolo-ui
auto produce the ui by ai 
yolo
A file watcher with web based user interface, so you can see the status of your build (and error output, if any) instantly.



Usage example:

$ yolo -i *.go -c 'go build' -a localhost:8080
It's silent by default. You can enable internal logging by;

$ LOG=* yolo ...
Install
$ go get github.com/azer/yolo
Todo
 Check if a matching make command if -c isn't provided.
 Read filenames from another file. So we could do yolo -f index.html and get live updates when dependencies change.
 Escape characters
 Output the name of changed file
 Split JS to another endpoint so it can be included by other pages
 How could it be used for viewing web pages / apps ?
 How could output be processed ?
