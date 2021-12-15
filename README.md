# upgrade-log4j to 2.0.16 on your Nuxeo server
This marketplace package can be installed on Nuxeo 10.10 or LTS2021 (just relax the constraint).
It brings nothing else, just replaces the existing log4j jars in your $Nuxeo/lib with the ones in 2.0.16

To build:
```
mvn package
```

To install

```
./nuxeoctl mp-install $YOUR_PATH_HERE/upgrade-log4j/upgrade-log4j-package/target/upgrade-log4j-package-1.0-SNAPSHOT.zip
```
