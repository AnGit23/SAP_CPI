# SAP_CPI
Cloud Platform Integration



# What is Integration?

Integration is the process of connecting two or more systems to share data and work together. The main purpose is to reduce manual effort and errors.

## The Problem

Organizations use multiple systems (HR, Finance, Warehouse, Sales, etc.) that don't speak the same language — some use CSV, XML, or JSON.

<img width="725" height="470" alt="image" src="https://github.com/user-attachments/assets/762eab99-d759-479a-ad86-1650ab04b99a" />

## How CPI Solves It

CPI acts as a middleware — a translator and traffic controller combined. It receives data from one system, transforms it, and sends it to another securely, in the right format, at the right time.

<img width="1709" height="94" alt="image" src="https://github.com/user-attachments/assets/52ace0b9-4a66-4485-83d3-dd6396ef0232" />

> No installation or maintenance needed — accessed via web browser.

You can integrate data between SAP-to-SAP and SAP-to-non-SAP systems.

<img width="855" height="631" alt="image" src="https://github.com/user-attachments/assets/08df161c-40f8-4ff5-ac20-fc545ba8dac9" />

<img width="496" height="516" alt="image" src="https://github.com/user-attachments/assets/1be4d839-3998-4e5f-a811-9bdc360eb380" />

## Real-World Example: SuccessFactors → ADP

**Scenario:** A company uses SuccessFactors (HR) and ADP (Payroll, non-SAP). When a new employee joins or a salary changes, ADP must be updated.

**Without CPI:** Manual updates — slow and error-prone at scale (thousands of employees).

**With CPI:** An integration flow reads data from SuccessFactors, transforms it, and sends it to ADP automatically.

<img width="1135" height="203" alt="image" src="https://github.com/user-attachments/assets/3c36a3f5-46d8-4d4f-8642-108fcf378149" />




What is integration?
Integration is the process of connecting 2 or more system to share the data and to work togwther.
the main purpose of integration is to reduce the manual effort.

<img width="725" height="470" alt="image" src="https://github.com/user-attachments/assets/762eab99-d759-479a-ad86-1650ab04b99a" />

Every organization uses multiple systems. like HR,FI, warehouse, sales etc.  these systems do not speak same language.some works with csv, xml, json.
how will you exchange data between different system. 

it's a middle ware which receives data from one system, translate and send to another system securely. Think of it as a tranlsator and tranffic control combined. It make sure the fdata get to where it supposed to go at right format and at right time.

<img width="1709" height="94" alt="image" src="https://github.com/user-attachments/assets/52ace0b9-4a66-4485-83d3-dd6396ef0232" />


HOW TO INSTALL CPI

no need to install or maint it.
we can integration this with the help of web browser.


You can integrate dta abetween SAP system and SAP and non sap systems.
<img width="855" height="631" alt="image" src="https://github.com/user-attachments/assets/08df161c-40f8-4ff5-ac20-fc545ba8dac9" />




<img width="496" height="516" alt="image" src="https://github.com/user-attachments/assets/1be4d839-3998-4e5f-a811-9bdc360eb380" />



REAL WORLD EXAMPLE
SUPPOSE your company uses Success factors for HR oeprations and ADP(non SAP system) for payroll operations.
when a anew employee joins or salary hcnage for an existing employee, needs to be updated in ADP system.
one way to  do this update manually. what we have 1000s of employess, it will take lot of time and data errors.

with CPI we can build integration flows, reads data from succsfactors, transform the data, send it to ADP securely. Manual effort and errors resolved.

<img width="1135" height="203" alt="image" src="https://github.com/user-attachments/assets/3c36a3f5-46d8-4d4f-8642-108fcf378149" />


WHAT IS BTP INTEGRATION SUITE AND CLOUD INTEGRATION


BTP is the main cloud platform of SAP.
4 pillars and integration is one of them. Integration  suite is a set of cloud based tools used for integration.
It's a service offered by BTP.
cloud integration is a tool inside integrfation suite.

<img width="1502" height="745" alt="image" src="https://github.com/user-attachments/assets/37f13344-9f4a-4029-9667-c630fdea9ca0" />


3. SAP BTP Free Trail Account Creation | Activating Integration Suite and SAP CPI


we need to start a trial account
<img width="984" height="574" alt="image" src="https://github.com/user-attachments/assets/ad8dbe4a-58ef-4c93-ab17-8a8d270ae357" />


You can search in Service-> instances ans subscriptions


<img width="1110" height="425" alt="image" src="https://github.com/user-attachments/assets/e3df7e81-b700-4d4e-b077-3d0af79f5d98" />

To be able to access the integraton suite we need proper oermissions.
Security-> user-> select our user-> click on Role collection and assign Role collection -> search for 'Integration Provisioner'.

<img width="1165" height="357" alt="image" src="https://github.com/user-attachments/assets/7cbe5122-d41e-4ae1-b8b6-d0dbe15e257f" />




This role will help you to access basic functionalites of integration suite.

<img width="1114" height="305" alt="image" src="https://github.com/user-attachments/assets/7b0f039e-0a0a-4dc5-8cee-13fc90f6c285" />

Go back to Instances and subscription again and launch integration suite.



NOTE: In case of any error, clear your browser cache and login to SAP BTP and try access it again.



To be able to access SAP CPI, you need to add some capabilities:

<img width="882" height="544" alt="image" src="https://github.com/user-attachments/assets/c122de65-7dfe-4165-a362-e82ba1a7a908" />


For the time being, select only Business Integration Scenarios and activate. (it can take up to 10 min)



We can add few more roles for the user.

<img width="1109" height="457" alt="image" src="https://github.com/user-attachments/assets/57b26644-5de8-437f-9105-345db4be0ecf" />


<img width="1073" height="527" alt="image" src="https://github.com/user-attachments/assets/37a68c75-3b3b-4266-8429-24377b3b0b03" />


After these steps, clear the cache and login again to Integration Suite.


If you're able to see below section on left hand panel, the integration suite is activated successfully.

<img width="988" height="537" alt="image" src="https://github.com/user-attachments/assets/d5ba6cca-ba8b-460d-a385-fb14f19e36dc" />


4. Navigating Through SAP CPI | What are packages and artifacts

# SAP CPI — Key Sections Overview

## Discover (Pre-Built Integrations)

SAP provides a library of ready-made integrations called **packages**. Each package is a collection of artifacts such as integration flows, value mappings, and script collections.

These standard packages can be copied and configured for customer-specific requirements — for example, adding credentials or endpoint URLs.

<img width="1182" height="324" alt="image" src="https://github.com/user-attachments/assets/2798563f-a7bc-4223-ba4d-a233c28334a2" />

## Design

This is where integrations are built and managed. It has two areas:

- **Standard Integrations** — pre-built packages provided by SAP
- **Customer Integrations** — custom integrations developed by the project team

<img width="1137" height="538" alt="image" src="https://github.com/user-attachments/assets/3ca1c3dc-35be-460f-9ead-08685e2dca1e" />

<img width="1194" height="379" alt="image" src="https://github.com/user-attachments/assets/40c87c52-63bc-4072-ae5f-40050b7d238c" />

### Integration Flow Canvas

Each integration flow has:
- **Canvas** — the white workspace where the flow is designed
- **Palette components** — the building blocks (boxes) that represent steps
- **Arrows** — show the direction of data flow

<img width="1203" height="390" alt="image" src="https://github.com/user-attachments/assets/11357f87-ed03-4fb8-aa43-f8e5628445a2" />

## Monitor

Used to track the status of integration flows — view error messages, execution logs, and processing details.

<img width="1021" height="391" alt="image" src="https://github.com/user-attachments/assets/f12ae716-0141-4cd1-b373-5191177d45de" />

## Manage Security

A centralized place to store and manage sensitive data:
- User credentials
- Certificates
- PGP keys
- Connectivity tests

<img width="1085" height="394" alt="image" src="https://github.com/user-attachments/assets/c2313412-7e1b-49f4-9142-a94e3438d15c" />

## Manage Stores

Provides temporary storage within CPI for intermediate data handling during integration processing.

## Inspect

Displays memory usage across integration flows. CPI follows a **Pay-As-You-Go** pricing model — customers are billed based on actual usage.

<img width="1082" height="422" alt="image" src="https://github.com/user-attachments/assets/60e78e05-111f-4d86-b5bf-d0eae2a749b9" />
