# Validando parametros para un accesso de usuario
Parametros para validar un Emai, Usuario y patrones para password.

###Emial
```java
String EMAIL = "[a-zA-Z0-9\\+\\._%\\-\\+]{1,256}" +
        "@" +
        "[a-zA-Z0-9][a-zA-Z0-9\\-]{0,64}" +
        "(" +
        "\\." +
        "[a-zA-Z0-9][a-zA-Z0-9\\-]{1,25}" +
        ")+";
```

###Usuario
```java
String USERNAME = "^([-_A-Za-z0-9])*$";
```

###Usuario
```java
String PASSWORD = "^([A-Za-z0-9_.,&%€@#~])*$";
```

