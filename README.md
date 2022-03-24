# ctUniverse
Comtech Universe, Index Repository of Products, Compute Solutions, and Compute Resources
## Comtech's Enterprise Solution
- Comtech Products are tracked by Comtech's Enterprise Resource Planning/Configuration Management (ERP/CM) system
  - Products contain Compute Solutions
  - Product repositories in GitHub are linked to ERP/CM system by Part Number (P/N)
  - Engineering Change Orders (ECOs) which modify P/N in ERP/CM are linked to Pull Requests in GitHub by commit hash number.
- Compute Solutions are also tracked in Comtech's ERP/CM system
  - Compute Solutions contain source code
  - Platform build machines create production binary files from source code
  - Product repositories are linked to ERP/CM system by P/N
  - ECOs to modify P/N in ERP/CM are linked to Pull Requests in GitHub by commit hash number.
- Compute Resources are not tracked in ERP/CM systems
  - Compute Resources are reusable Intellectual Property (IP) developers can modify and test without restriction
  - When a Compute Resource passes developer testing, it is deployed as a compute solution
  - When a Compute Solution passes official testing, it is deployed to a product
