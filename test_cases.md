# Test Cases

| ID | Scenario | Expected Result |
|---|---|---|
| TC01 | Submit valid laptop request | Request created |
| TC02 | Submit without justification | Validation prevents submission |
| TC03 | Manager rejects request | No fulfillment task created |
| TC04 | Manager approves request | Flow executes |
| TC05 | Approved request | Catalog Task created |
| TC06 | Task creation | Assignment group = Hardware |
| TC07 | Multiple requests | Each request remains traceable |
