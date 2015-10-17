# ValidateFX
A Java Bean Validation (JSR 303) plugin that adds the support for the JavaFX property API

By adding this class a plugin for the JSR 303 will be added that allows the validation of JavaFX Properties:

```java
public class MyModel {

    @NotNull
    private StringProperty name;

}
```
