# devoxx-java
Some demos about quarqus and maybe some other java spring samples - nothing more

## Build native quarqus image
    ./mvnw package -Pnative -Dquarkus.native.container-runtime=docker

    OR

    export JAVA_HOME=$GRAALVM_HOME
    mvn clean package  -Dquarkus.package.type=native


