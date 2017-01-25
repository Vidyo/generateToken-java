# generateToken-java

To build, run:

    ./gradlew clean build
    
This will build *generateToken.jar* in directory build/libs
    
Generate tokens using your appID and developer key from vidyo.io:

    java -jar generateToken.jar --key=rUlaMASgt1Byi4Kp3sKYDeQzo --appID=ApplicationID --userName=user1 --vCardFile=vcard-example.xml --expiresInSecs=10000
