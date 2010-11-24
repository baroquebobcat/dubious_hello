A Dubious Hello.
=================

Instructions
-------------

#Install Dubious(don't forget the JRuby-ness)

    gem install dubious

#Generate App Skeleton

    dubious new dubious-hello
    cd dubious-hello

#Generate A Controller

    dubious generate controller hello

#Add Index Method

    #app/controllers/hello_controller.mirah
    def index
      "hello"
    end

#Run the Dev Server

    rake server

#Check It Out Locally

    http://localhost:8080/hello

