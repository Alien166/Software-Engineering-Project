
# Use case modeling

## Use case description

### Use Case: Generate Invoice

| Use Case Name  | Generate Invoice                                                                    |
|----------------|--------------------------------------------------------------------------------------|
| Function       | Generate invoice                                                                    |
| Description    | This use case involves authorized users (physicians, administrators, and billing clerks) generating invoices for clinic services within the Clinic Management System, ensuring accurate financial tracking and providing reports for accounting purposes. |
| Input          | - User's login credentials.<br>- Selection of clinic services for the invoice.<br>- Patient information and service details. |
| Output         | - Confirmation message indicating successful invoice generation.<br>- Stored invoice for financial tracking. |
| Action         | 1. The user logs into the system.<br>2. They navigate to the "Generate Invoice" section, choosing clinic services and inputting relevant details.<br>3. The system calculates the total cost based on the selected services.<br>4. The user confirms and generates the invoice, which the system stores for financial tracking. |
| Pre-condition  | The user (physician, administrator, or billing clerk) is logged into the Clinic Management System. |
| Post-condition | An invoice is successfully generated and stored in the system for financial tracking. |
