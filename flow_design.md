# Flow Designer Configuration

## Trigger
Use a Requested Item record trigger based on the approval state and catalog item.

Example logical condition:
- Approval = Approved
- Catalog Item = Standard Laptop

## Actions
1. Update Requested Item state to Work in Progress.
2. Create Catalog Task.
3. Set short description.
4. Set assignment group to Hardware.
5. Copy relevant catalog variables into task description.
6. Verify task creation.

## Expected Result
Every approved Standard Laptop request should produce one correctly routed fulfillment task.
