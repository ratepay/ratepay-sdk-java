# Ratepay GmbH - Java SDK (Software Development Kit) for Ratepay Payments API v2
============================================

|Module | Ratepay Java SDK
|------|----------
|Versions | [click here](https://github.com/ratepay/ratepay-sdk-java/tree/gh-pages/com/ratepay/sdk)
|Link | http://www.ratepay.com
|Mail | integration@ratepay.com
|Documentation | [click here](https://docs.ratepay.com/docs/developer/sdk/introduction)|
|Legal Disclaimer   | [click here](https://docs.ratepay.com/docs/legal/a_legal_requirements_for_the_integration/introduction)|


## Usage instructions

### Using Maven

In your Maven project, add the following dependency to your `pom.xml`:

```xml
<dependency>
    <groupId>com.ratepay.sdk</groupId>
    <artifactId>ratepay-sdk-core</artifactId>
    <version>1.12.0</version>
</dependency>
```

Also, you will need to add the Ratepay Maven repository to your `pom.xml`:

```xml
<repositories>
    <repository>
        <id>ratepay</id>
        <name>Ratepay Maven Repository</name>
        <url>https://ratepay.github.io/ratepay-sdk-java</url>
    </repository>
</repositories>
```

### Using Gradle

In your Gradle project, add the following dependency to your `build.gradle`:

```groovy
dependencies {
    implementation 'com.ratepay.sdk:ratepay-sdk-core:1.12.0'
}
```

Also, you will need to add the Ratepay Maven repository to your `build.gradle`:

```groovy
repositories {
    maven {     
        url 'https://ratepay.github.io/ratepay-sdk-java'
    }
}   
```