Flow Chart TD
```mermaid
flowchart TD
A[["@"order = Order.new]] --> B
B[["@"order.save]] --> C{return value}
C{return value} -->|true| D[[OrderItem.new]]
```

