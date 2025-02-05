# MS-Azure-AZ-900

- Basuc level MS certification

# Cloud service
- Iaas ( Computer, Storage, Networking) - VM - pay/sec - Multiple hardware -v network as free
- Paas ( Middleware , dev tool, sql server.. load balancer..) - Azure app service - run code
- Saas (MS office , drive )
#### others
- On premise
- Serverless (low power hardware) - no option to change hardware
  - Container apps
  - kubernetes
  - SQL DB
    

# cloud type
- public
- private
- hybrid

# pricing
- https://azure.microsoft.com/en-in/pricing/calculator/

# Capital Expenses vs Operational expenses

# Benefit
 - High availability (low down time,)
   - planed outages (Update, migration, replacement)
   - unplaned outages( hardware failure,power,cyber attack, software bug)
 - Scalability
   -  Adding or Removing resources as need (Traffic)
   -  Vertical Scaling ( add cpu memory)
   -  Horizondal scaling ( add seperate server)
 - Elasticity
   - How quickly and easily do scaling
 - Reliability
   - Ability of system recover from failures
     - hardware Failure , Network Interruptions , power failures , Large-scale region
 - Predictability
    - Ability to forecast and control the performanvce and behavior of system and cost
 - Security
    - use industry standard (ISO)
    - Microsoft security response center
    - Role based access
    - Up to date
    - Encryption by default
 - Governance
    - Auditing and reporting
    - Azure policy and blueprint
    - Guides and best practice
  - Managability
    - Templates
    - Scaling
    - Web portal
    - PowerShell
      
# Core Architecture components
  - Region (based on usage and high speed connection) 60+ region
  - Sovereign azure (not connect to public cloud , need subscription ,diff standard)
  - Zone ( seperate center in each region with high speed network)
  - Resource (Resources < Resources grp < subscription < Management grp)
     - resource - are hardware , software
     - resource group - Logical group of resources (create delete all resource at time )
     - Subsription - billing unit
     - Management group - multiple subsription for single administration

# compute service
 - Types
    - Virtual machines - laas 
    - VM scale set - top of vm - scale up / scale down with load balancer
    - App services -app in cloud - paas
    - Azure Container Instance  - single instance , quickest way to deploy a container
    - Azure kubernetes service
    - Azure virtual desktop - v desktop run in cloud
    - Azure Function - small pieces od code run in cloud - 1million execution / month as free for 1st month by serverless model
  - Availability set
    - fault isolation - separete power , network switch for update one at a time
# network service
  - Virtual network as laas
  - it be a IPV4 or IPV 6 but is can't access outside of azure because is private
  - all VN is divided as more subnets
  - the one vm had atleast one subnet
  - peering
    - connect to subnet together
    - communication between vm using subnet on different network is blocked so use peering
  - DNS
    - can use domain name for ip but it internally use only
  - VPN
    - inside azure can install vpn gateway
  - Express Route
     - private connection from isp to Azure endpoint for high speed comminication
  - Networking Option in Azure
     - Public access from all network
     - Public access from selectged VN and IP address
     - use private access

# Demo
- create VM with OS , download RDS file connection tap to open the VM
- create App service with runtime stack py3.8 or .net 8 and also os , copy the default url . (na manul installtion needed automatic from git rep)








    
