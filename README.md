Scambi Selvaggi di Carte da Nerd

To launch it, run:

`mvn -U -e gwt:codeserver -pl stockwatcher-client -am`

to execute the codeserver (just keep that running).

Then you can use

`mvn -U jetty:run -pl stockwatcher-server -am -Denv=dev`

to run the application in developer mode (the URL is `http://localhost:8080/`). 

