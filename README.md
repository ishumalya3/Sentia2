# Sentia Project#
# Project Description is a formally written declaration of the dummy project and its idea and context to explain the goals and objectives to be reached, the business need and problem to be addressed, potentials pitfalls and challenges, approaches and execution methods, reusibility ,robust, time consumption #
# Cloud computing service created by Microsoft for building, testing, deploying, and managing applications and services through Microsoft-managed data centers. Service can be paid on its usage. Its cost eefective , manageable, application supported 
# Microsoft azure link -https://portal.azure.com/#home
# Registered - login - ishaisha3786@gmail.com
# Password  - *************
# Subscription -pay - as-you - go 
# Created the follwing features #
# Resusable 
# Robust
# Flexible
# Every subscription has diffent features as per the cost .
# Resource Group 
# Paid subscription #
# Strage Account
# Location - Central US always 
# Data lake Storage Gen 1
# Key Vault
# Scret and key identfier
# Roles and user
# Virtual Netowrk - network - for the inbound rule and outbound rule setup to access via load balancer 
# Virtual Network Gateway
# Subnets
# Public Ip address, can be newly created , old old can be used if not associated 
# App Service
# Web App
# App Service Plan 
# Load Balancer 
# Virtual Machine can be created many in the same zone, different zone.
# Along with VM more components are created like disc , size, security,NSG for the inbound rule , outbund rule setup
# Network Security Gatway
# Dashbaord to see the deployment result 
# Three ways 1. Azure Portal  2. Powershell 3. Azure CLI
# ********** All resources and application are created through Azure Portal ********* 
# Tool features are advance and resuseable to access the resources deployed & manage the apps in a quick and easier way
# Flexibility ,Agility ,Compliance, Storage, Security ,Analytics Support,Unified Delivery Plan #
# Account can be free for 1 month on trail basis, subscribed & paid as on usage monthly , annually . 

***********ARM creating Data Lake Storage Gen1 Account **************************
# DLSGen1 capabilities dedicated to big data analytics
# Encrypted data
# Account is encrypted using keys managed by your  ********Key Vault ********
# Azure Data Lake Storage Gen1 makes use of the virtual network service endpoint security claims in the access token made data lake very scecure to specific group user - Ishamalya3786@gmail.com, given Read, write, execute access
# By access can make it secrue to user - data explorer
# secured store for secrets. Securely stored keys, password and other secrets

# **********ARM creating Virtual network*************************
# A reusuable resources ,own network in the cloud
# It can be newly created, subnet can be updated . 
# Upgrade the subscription for the more scecurity purpose.
# Many virtual VM can be connected 
# Virtual Network gateway created

# ***************Load Balancer on VMs************
# Load balancer to balance the load over the access of the web apps.
# Created Remote desktops. Seeting done to access the Remote desktops
# Create an Azure Load Balancer
# Front end IP , Backend pool where VMs are associated , health probe ,balancing rule to se the port 
# On remote desk top -- dashbaord to do the IIS installation , set the inbound rule .
# Create Load Balancer resources
# Create virtual machines and install IIS server
# Network security group NSG- Set the inbound rule - TCP, Port 80 , set the priorty to 100 (lower the priorty higher the weight )
# View Load Balancer in action how the Inbound rule manages the Web app server on Remote desktop
# Keeping the virtual machine , start , stop, restart
# Capture to make the duplicate of the virtual machine , reusable feature .
# Run the 52.230.228.111 (LB04PublicIP) to test the web papplication is running on hitting the url the web page will open - "Ishu Web page."
# If stop the VM then hitting the 52.230.228.111 (LB04PublicIP) the web app will not run or show no error
# Can create the secured site by HTTPS .

# ************************* Tags to resources ***************************************
# Created virtual machine under name and value .
# its kind of index to find any resources easily under name and tags.
# Tags can be changed.










