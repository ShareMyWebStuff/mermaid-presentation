## Entity Diagrams

Entity diagrams show the entities in a system and the relationships between the entities. It shows the attributes of each entity and the relationships between the entities.

The colouring of entity diagrams currently has issues.

```mermaid
%%{
  init: {
    'theme': 'dark',
  }
}%%
erDiagram
    CUSTOMER ||--o{ ORDER : places
    CUSTOMER {
        string name
        string custNumber
        string sector
    }
    ORDER ||--|{ LINE-ITEM : contains
    ORDER {
        int orderNumber
        string deliveryAddress
    }
    LINE-ITEM {
        string productCode
        int quantity
        float pricePerUnit
    }
```
