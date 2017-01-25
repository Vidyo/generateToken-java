# generateToken-java

To build, run:

    ./gradlew clean build
    
This will build *generateToken.jar* in directory build/libs
    
Generate tokens using your appID and devevloper key from vidyo.io:

    java -jar generateToken.jar --key=rUlaMASgt1Byi4Kp3sKYDeQzo --appID=ApplicationID --userName=user1 --vCardFile=vcard-example.xml --expiresInSecs=10000

    java -jar ./build/libs/generateToken.jar --key=rUlaMASgt1Byi4Kp3sKYDeQzo --appID=ApplicationID --userName=user1 --vCardFile=vcard-example.xml --expiresInSecs=10000
    Setting key           :  rUlaMASgt1Byi4Kp3sKYDeQzo
    Setting appID         :  ApplicationID
    Setting userName      :  user1
    Setting vCardFile     :  vcard-example.xml
    Setting expiresInSecs :  10000
    Generating Token...
    cHJvdmlzaW9uAHVzZXIxQEFwcGxpY2F0aW9uSUQANjM2NTI2MDI3ODUAAGQzMDkxMjA5NjFmMGYxMjFkM2FlZjQxMzJkNmRiNTdkMTA5MDU0MGU4ZWZmNjYxMzlhOTUyMzJiODA0MGViOWU5MjI3OTQ3N2MwYWUzODQ3Y2NiYmJiYTNhZDc5OTdkOA==

