## Local Storage

The localStorage **object** stores data with no expiration date. The data will not be deleted when the browser is closed, and will be available the next day, week, or year.

### Syntax

**SAVING** data to localStorage:
```javaScript
  localStorage.setItem("key", "value");
```

**READING** data from localStorage:
```javaScript
  var name = localStorage.getItem("key");
```

**REMOVING** data from localStorage:
```javaScript
  localStorage.removeItem("key");
```
