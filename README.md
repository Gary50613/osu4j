# osu!4J
The osu API client written in Java

***

### Example

```java
OsuClient client = new OsuClient("API_TOKEN");
try {
        User user = client.getUser("Gary50613");
        System.out.println(user.name);
} catch (IOException | InvalidTokenException | NotFoundException e) {
    e.printStackTrace();
}
```

### Install
replace `VERSION` with current version [![version][]]

```xml
<dependency>
    <groupId>tw.kane</groupId>
    <artifactId>osu4j</artifactId>
    <version>VERSION</version>
</dependency>
```

### Support
- [Discord](https://discord.gg/ct2ufag)