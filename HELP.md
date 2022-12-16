# Getting Started

### Reference Documentation
For further reference, please consider the following sections:

* [Official Apache Maven documentation](https://maven.apache.org/guides/index.html)
* [Spring Boot Maven Plugin Reference Guide](https://docs.spring.io/spring-boot/docs/2.7.6/maven-plugin/reference/html/)
* [Create an OCI image](https://docs.spring.io/spring-boot/docs/2.7.6/maven-plugin/reference/html/#build-image)



### Spring boot IDE Setup
 https://www.youtube.com/watch?v=TQx-A1GxVOg&list=PLLUFZCmqicc-ESKvg3XZE-7yX5o_0PPED&index=1
 
### PostMan

http://localhost:8080/rest/decision-definition/key/Decision_1do3pdq/evaluate

```
HTTP POST ( RAW / JSON ) 
{
    "variables" :{
        "inputcellvariable": {"value": 0 , "type" : "integer"}
    }
}
```