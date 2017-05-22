# corenlp-docker
Dockerfile for Stanford CoreNLP Server
---------

This Dockerfile builds the [Stanford CoreNLP Server](http://stanfordnlp.github.io/CoreNLP/corenlp-server.html)
and exposes the endpoint on port 9000. Requests are made as covered in the documentation.

Latest version is [CoreNLP 3.7.0](http://nlp.stanford.edu/software/stanford-corenlp-full-2016-10-31.zip)

Docker images whose tags end with "-sr" also include the [shift reduce constituency parser](https://nlp.stanford.edu/software/srparser.shtml)
which is used as the default parser.

This version of the image includes a server properties file that uses the beam
search version of the shift reduce parser by default.
