# Kafka squeezecnn API

# Kafka architecture

# Doc

This basic kafka program acts as both a producer and a consumer in order to send and receive an image.
The command line parameters are 
* -type : Can either be "producer" or "consumer", depending on the usage
* -brokers : default is localhost:9092
* -file : The filePath of the image to send
* -groupid : if the program is acting as a consumer, this option is required
