
### Commands for building

To create a package of your build
```
mvn package
```

To prepare a build and create a new release tag on github
```
mvn release:prepare
```

To perform the actual release and get the source, javadoc and jar-with-dependencies
```
mvn release:perform
```
