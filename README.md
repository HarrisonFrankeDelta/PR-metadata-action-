# PR-metadata-action-
Adds pull request file changes as a comment to a newly opened PR 

##Testing GitHub actions
Test Test: this is where the change happened

```mermaid
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
        int number
    }
 ```
