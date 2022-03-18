# beam-go
* check the go version using:**go version**
* after creating hello.go file and after custommizing : **go run hello.go** 
* Use the following command to obtain the apache beam go sdk: **go get -u github.com/apache/beam/sdks/v2/go/pkg/beam**
* Install the wordcount example with the following command: **go install github.com/apache/beam/sdks/v2/go/examples/wordcount**
* Make a wordcount. **Go to the file and paste the code from the wordcount example.**[sample](http://github.com/apache/beam/sdks/v2/go/examples/wordcount)
* Use the command to run the wordcount example:**wordcount --input sample.txt --output telluri_counts**
* If you get an error, run the following command and then rerun step 6: **go get github.com/apache/beam/sdks/v2/go/pkg/beam/io/filesystem/gcs@v2.37.0**
