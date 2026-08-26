SCENARIO

*This scenario is based on a fictational Company*

Botium Toys is a small U.S. business that develops and sells toys. The
business has a single physical location, which serves as their main
office, a storefront, and warehouse for their products. However, Botium
Toy's online presence has grown, attracting customers in the U.S. and
abroad. As a result, their information technology (IT) department is
under increasing pressure to support their online market worldwide. 

The manager of the IT department has decided that an internal IT audit
needs to be conducted. She\'s worried about maintaining compliance and
business operations as the company grows without a clear plan. She
believes an internal audit can help better secure the company's
infrastructure and help them identify and mitigate potential risks,
threats, or vulnerabilities to critical assets. The manager is also
interested in ensuring that they comply with regulations related to
internally processing and accepting online payments and conducting
business in the European Union (E.U.).   

The IT manager starts by implementing the National Institute of
Standards and Technology Cybersecurity Framework (NIST CSF),
establishing an audit scope and goals, listing assets currently managed
by the IT department, and completing a risk assessment. The goal of the
audit is to provide an overview of the risks and/or fines that the
company might experience due to the current state of their security
posture.

Your task is to review the IT manager's scope, goals, and risk
assessment report. Then, perform an internal audit by completing a
controls and compliance checklist. 

# Botium Toys: Scope, goals, and risk assessment report

## Scope and goals of the audit

**Scope:** The scope is defined as the entire security program at Botium
Toys. This means all assets need to be assessed alongside internal
processes and procedures related to the implementation of controls and
compliance best practices.

**Goals:** Assess existing assets and complete the controls and
compliance checklist to determine which controls and compliance best
practices need to be implemented to improve Botium Toys' security
posture.

## Current assets

Assets managed by the IT Department include:

-   On-premises equipment for in-office business needs

-   Employee equipment: end-user devices (desktops/laptops,
    > smartphones), remote workstations, headsets, cables, keyboards,
    > mice, docking stations, surveillance cameras, etc.

-   Storefront products available for retail sale on site and online;
    > stored in the company's adjoining warehouse

-   Management of systems, software, and services: accounting,
    > telecommunication, database, security, ecommerce, and inventory
    > management

-   Internet access

-   Internal network

-   Data retention and storage

-   Legacy system maintenance: end-of-life systems that require human
    > monitoring

## Risk assessment

### Risk description

Currently, there is inadequate management of assets. Additionally,
Botium Toys does not have all of the proper controls in place and may
not be fully compliant with U.S. and international regulations and
standards.

### Control best practices

The first of the five functions of the NIST CSF is Identify. Botium Toys
will need to dedicate resources to identify assets so they can
appropriately manage them. Additionally, they will need to classify
existing assets and determine the impact of the loss of existing assets,
including systems, on business continuity.

### Risk score

On a scale of 1 to 10, the risk score is 8, which is fairly high. This
is due to a lack of controls and adherence to compliance best practices.

### Additional comments

The potential impact from the loss of an asset is rated as medium,
because the IT department does not know which assets would be at risk.
The risk to assets or fines from governing bodies is high because Botium
Toys does not have all of the necessary controls in place and is not
fully adhering to best practices related to compliance regulations that
keep critical data private/secure. Review the following bullet points
for specific details:

-   Currently, all Botium Toys employees have access to internally
    > stored data and may be able to access cardholder data and
    > customers' PII/SPII.

-   Encryption is not currently used to ensure confidentiality of
    > customers' credit card information that is accepted, processed,
    > transmitted, and stored locally in the company's internal
    > database.

-   Access controls pertaining to least privilege and separation of
    > duties have not been implemented.

-   The IT department has ensured availability and integrated controls
    > to ensure data integrity.

-   The IT department has a firewall that blocks traffic based on an
    > appropriately defined set of security rules.

-   Antivirus software is installed and monitored regularly by the IT
    > department.

-   The IT department has not installed an intrusion detection system
    > (IDS).

-   There are no disaster recovery plans currently in place, and the
    > company does not have backups of critical data.

-   The IT department has established a plan to notify E.U. customers
    > within 72 hours if there is a security breach. Additionally,
    > privacy policies, procedures, and processes have been developed
    > and are enforced among IT department members/other employees, to
    > properly document and maintain data.

-   Although a password policy exists, its requirements are nominal and
    > not in line with current minimum password complexity requirements
    > (e.g., at least eight characters, a combination of letters and at
    > least one number; special characters).

-   There is no centralized password management system that enforces the
    > password policy's minimum requirements, which sometimes affects
    > productivity when employees/vendors submit a ticket to the IT
    > department to recover or reset a password.

-   While legacy systems are monitored and maintained, there is no
    > regular schedule in place for these tasks and intervention methods
    > are unclear.

-   The store's physical location, which includes Botium Toys' main
    > offices, store front, and warehouse of products, has sufficient
    > locks, up-to-date closed-circuit television (CCTV) surveillance,
    > as well as functioning fire detection and prevention systems.

# Control categories

## Control categories

Controls within cybersecurity are grouped into three main categories:

-   Administrative/Managerial controls

-   Technical controls

-   Physical/Operational controls

**Administrative/Managerial controls** address the human component of
cybersecurity. These controls include policies and procedures that
define how an organization manages data and clearly defines employee
responsibilities, including their role in protecting the organization.
While administrative controls are typically policy based, the
enforcement of those policies may require the use of technical or
physical controls.

**Technical controls** consist of solutions such as firewalls, intrusion
detection systems (IDS), intrusion prevention systems (IPS), antivirus
(AV) products, encryption, etc. Technical controls can be used in a
number of ways to meet organizational goals and objectives.

**Physical/Operational controls** include door locks, cabinet locks,
surveillance cameras, badge readers, etc. They are used to limit
physical access to physical assets by unauthorized personnel.

## Control types

Control types include, but are not limited to:

1.  Preventative

2.  Corrective

3.  Detective

4.  Deterrent

These controls work together to provide defense in depth and protect
assets. **Preventative controls** are designed to prevent an incident
from occurring in the first place. **Corrective controls** are used to
restore an asset after an incident. **Detective controls** are
implemented to determine whether an incident has occurred or is in
progress. **Deterrent controls** are designed to discourage attacks.

Review the following charts for specific details about each type of
control and its purpose.

**Administrative/Managerial Controls**

  ----------------------- ----------------------- -----------------------
  **Control Name**        **Control Type**        **Control Purpose**

  Least Privilege         Preventative            Reduce risk and
                                                  overall impact
                                                  of malicious insider or
                                                  compromised accounts

  Disaster recovery plans Corrective              Provide business
                                                  continuity

  Password policies       Preventative            Reduce likelihood of
                                                  account compromise
                                                  through brute force or
                                                  dictionary attack
                                                  techniques

  Access control policies Preventative            Bolster confidentiality
                                                  and integrity by
                                                  defining which groups
                                                  can access or modify
                                                  data

  Account management      Preventative            Managing account
  policies                                        lifecycle, reducing
                                                  attack surface, and
                                                  limiting overall
                                                  impact from
                                                  disgruntled former
                                                  employees and default
                                                  account usage

  Separation of duties    Preventative            Reduce risk and
                                                  overall impact
                                                  of malicious insider or
                                                  compromised accounts
  ----------------------- ----------------------- -----------------------

**Technical Controls**

  ----------------------- ----------------------- -----------------------
  **Control Name**        **Control Type**        **Control Purpose**

  Firewall                Preventative            To filter unwanted or
                                                  malicious traffic from
                                                  entering the network

  IDS/IPS                 Detective               To detect and prevent
                                                  anomalous traffic that
                                                  matches a signature or
                                                  rule

  Encryption              Deterrent               Provide confidentiality
                                                  to sensitive
                                                  information

  Backups                 Corrective              Restore/recover from an
                                                  event

  Password management     Preventative            Reduce password fatigue

  Antivirus (AV) software Corrective              Detect and quarantine
                                                  known threats

  Manual monitoring,      Preventative            Necessary to identify
  maintenance, and                                and manage threats,
  intervention                                    risks, or
                                                  vulnerabilities to
                                                  out-of-date systems
  ----------------------- ----------------------- -----------------------

**Physical/Operational Controls**

  ----------------------- ------------------------ -----------------------
  **Control Name**        **Control Type**         **Control Purpose**

  Time-controlled safe    Deterrent                Reduce attack surface
                                                   and
                                                   impact from
                                                   physical threats

  Adequate lighting       Deterrent                Deter threats by
                                                   limiting "hiding"
                                                   places

  Closed-circuit          Preventative/Detective   Closed circuit
  television (CCTV)                                television is both a
                                                   preventative and
                                                   detective control
                                                   because it's presence
                                                   can reduce risk of
                                                   certain types of events
                                                   from occurring, and can
                                                   be used after an event
                                                   to inform on event
                                                   conditions

  Locking cabinets (for   Preventative             Bolster integrity by
  network gear)                                    preventing unauthorized
                                                   personnel and other
                                                   individuals from
                                                   physically accessing or
                                                   modifying network
                                                   infrastructure gear

  Signage indicating      Deterrent                Deter certain types of
  alarm service provider                           threats by making the
                                                   likelihood of a
                                                   successful attack seem
                                                   low

  Locks                   Deterrent/Preventative   Bolster integrity by
                                                   deterring and
                                                   preventing unauthorized
                                                   personnel, individuals
                                                   from physically
                                                   accessing assets

  Fire detection and      Detective/Preventative   Detect fire in physical
  prevention (fire alarm,                          location and prevent
  sprinkler system, etc.)                          damage to physical
                                                   assets such as
                                                   inventory, servers,
                                                   etc.
  ----------------------- ------------------------ -----------------------

# Controls and compliance checklist

To complete the controls assessment checklist, refer to the information
provided in the [scope, goals, and risk assessment report]{.underline}.
For more details about each control, including the type and purpose,
refer to the [control categories]{.underline} document.

Then, select "yes" or "no" to answer the question: *Does Botium Toys
currently have this control in place?*

**Controls assessment checklist**

+-----+------+--------------------------------------------------------+
| *   | **   | **Control**                                            |
| *Ye | No** |                                                        |
| s** |      |                                                        |
+-----+------+--------------------------------------------------------+
| -   | ❌   | Least Privilege                                        |
|     |      |                                                        |
+-----+------+--------------------------------------------------------+
|     | ❌   | Disaster recovery plans                                |
+-----+------+--------------------------------------------------------+
|     | ❌   | Password policies                                      |
+-----+------+--------------------------------------------------------+
|     | ❌   | Separation of duties                                   |
+-----+------+--------------------------------------------------------+
| ✅  |      | Firewall                                               |
+-----+------+--------------------------------------------------------+
|     | ❌   | Intrusion detection system (IDS)                       |
+-----+------+--------------------------------------------------------+
|     | ❌   | Backups                                                |
+-----+------+--------------------------------------------------------+
| ✅  |      | Antivirus software                                     |
+-----+------+--------------------------------------------------------+
|     | ❌   | Manual monitoring, maintenance, and intervention for   |
|     |      | legacy systems                                         |
+-----+------+--------------------------------------------------------+
|     | ❌   | Encryption                                             |
+-----+------+--------------------------------------------------------+
|     | ❌   | Password management system                             |
+-----+------+--------------------------------------------------------+
| ✅  |      | Locks (offices, storefront, warehouse)                 |
+-----+------+--------------------------------------------------------+
| ✅  |      | Closed-circuit television (CCTV) surveillance          |
+-----+------+--------------------------------------------------------+
| ✅  |      | Fire detection/prevention (fire alarm, sprinkler       |
|     |      | system, etc.)                                          |
+-----+------+--------------------------------------------------------+

**Control summary**

*Implemented*

  ---------------------- ---------------------------------------------------------
  Firewall               The IT department has a firewall configured to detect and
                         block traffic according to security rules.

  Anti Virus Software    Antivirus software is installed and regularly monitored.

  Locks                  The physical location has sufficient locks installed.

  CCTV                   The location has up to date Closed-circuit television
                         surveillance.

  Fire                   There are functioning fire detection and prevention
  Detection/preventive   systems in place.
  ---------------------- ---------------------------------------------------------

*Not Implemented*

  -------------- ---------------------------------------------------------
  Least          All employees have access to internally stored data.
  Privilage      

  Disaster       There are no disaster recovery plans in place.
  recovery plans 

  Password       There is a password policy in place but its requirements
  policies       are too weak and does not meet the stated minimum
                 complexity requirement.

  Separation of  Separation of duties has not been implemented.
  duties         

  Intrution      There is no IDS installed.
  detection      
  system         

  Backups        The company does not have a backup of critical company
                 data.

  Manual         Although legacy systems are monitored there is no regular
  Monitoring,    schedule and intervention methods are unclear.
  maintenance    
  and            
  intervention   
  for legacy     
  systems        

  Encryption     Customer credit card information are not encrypted when
                 stored.

  Password       There is no centralized password management system in
  management     place.
  system         
  -------------- ---------------------------------------------------------

**Compliance checklist**

[Payment Card Industry Data Security Standard (PCI DSS)]{.underline}

+------+------+--------------------------------------------------------+
| **Y  | **   | **Best practice**                                      |
| es** | No** |                                                        |
+------+------+--------------------------------------------------------+
| -    | ❌   | Only authorized users have access to customers' credit |
|      |      | card information.                                      |
+------+------+--------------------------------------------------------+
|      | ❌   | Credit card information is stored, accepted,           |
|      |      | processed, and transmitted internally, in a secure     |
|      |      | environment.                                           |
+------+------+--------------------------------------------------------+
|      | ❌   | Implement data encryption procedures to better secure  |
|      |      | credit card transaction touchpoints and data.          |
|      |      | []{.mark}                                              |
+------+------+--------------------------------------------------------+
|      | ❌   | Adopt secure password management policies.             |
+------+------+--------------------------------------------------------+

**Compliance Summary**

*Not Implemented*

  ------------------------------- ---------------------------------------
  Only authorized users have      All employees have access to internally
  access to customers' credit     stored data and have ability to access
  card information.               cardholder data.

  Credit card information is      Credit card information is stored
  stored, accepted, processed,    internally without any encryption.
  and transmitted internally, in  
  a secure environment.           

  Implement data encryption       Encryption is not currently used for
  procedures to better secure     customers credit card information.
  credit card transaction         
  touchpoints and data. []{.mark} 

  Adopt secure password           The password policy has weak
  management policies.            requirements and no centralized
                                  password management system is in place.
  ------------------------------- ---------------------------------------

[General Data Protection Regulation (GDPR)]{.underline}

+-----+------+--------------------------------------------------------+
| *   | **   | **Best practice**                                      |
| *Ye | No** |                                                        |
| s** |      |                                                        |
+-----+------+--------------------------------------------------------+
| -   | ❌   | E.U. customers' data is kept private/secured.          |
|     |      |                                                        |
+-----+------+--------------------------------------------------------+
| ✅  |      | There is a plan in place to notify E.U. customers      |
|     |      | within 72 hours if their data is compromised/there is  |
|     |      | a breach.                                              |
+-----+------+--------------------------------------------------------+
|     | ❌   | Ensure data is properly classified and inventoried.    |
+-----+------+--------------------------------------------------------+
| ✅  |      | Enforce privacy policies, procedures, and processes to |
|     |      | properly document and maintain data.                   |
+-----+------+--------------------------------------------------------+

General Data Proctection Summary

*Implemented*

  ----------------------------------- -----------------------------------
  There is a plan in place to notify  The company has a plan established
  E.U. customers within 72 hours if   to notify E.U. customers within 72
  their data is compromised/there is  hours.
  a breach.                           

  Enforce privacy policies,           Company privacy policies,
  procedures, and processes to        procedures and processed are
  properly document and maintain      developed and enforced
  data.                               
  ----------------------------------- -----------------------------------

*Not Implemented*

  ----------------------------------- -----------------------------------
  E.U. customers' data is kept        All employees have access to
  private/secured.                    internally stored data and the
                                      company doesn\'t have all necessary
                                      controls to protect critical
                                      company data.

  Ensure data is properly classified  The risk assessment states that the
  and inventoried.                    asset management is inadequate and
                                      assets need to be identified and
                                      classified.
  ----------------------------------- -----------------------------------

[System and Organizations Controls (SOC type 1, SOC type 2)]{.underline}

+------+------+--------------------------------------------------------+
| **Y  | **   | **Best practice**                                      |
| es** | No** |                                                        |
+------+------+--------------------------------------------------------+
| -    | ❌   | User access policies are established.                  |
+------+------+--------------------------------------------------------+
|      | ❌   | Sensitive data (PII/SPII) is confidential/private.     |
+------+------+--------------------------------------------------------+
| ✅   |      | Data integrity ensures the data is consistent,         |
|      |      | complete, accurate, and has been validated.            |
+------+------+--------------------------------------------------------+
| ✅   |      | Data is available to individuals authorized to access  |
|      |      | it.                                                    |
+------+------+--------------------------------------------------------+

System and Organized Controls Summary

*Implemented*

  ----------------------------------- -----------------------------------
  Data integrity ensures the data is  Company IT department has
  consistent, complete, accurate, and implemented controls to ensure data
  has been validated.                 integrity.

  Data is available to individuals    Company IT department ensures data
  authorized to access it.            availability
  ----------------------------------- -----------------------------------

*Not implemented*

  ----------------------------------- -----------------------------------
  User access policies are            Least privilege and separation of
  established.                        duties are not implemented and
                                      access controls are inadequate

  Sensitive data (PII/SPII) is        Employees have access to internally
  confidential/private.               stored data and have ability to
                                      access PII/SPII
  ----------------------------------- -----------------------------------

**Recommendations (optional):**

Based on the current risk assessment Botium Toys should prioritize the
implementation of controls needed to protect sensitive customer
information, reduce unauthorized access and improve business continuity.

-   Implement least privilege

    Company should restrict access to internal data based on employee's
    job responsibilities. All employees should only have the access to
    information and systems required to perform their duties. This will
    greatly reduce the risk of unauthorized access to critical company
    data.

```{=html}
<!-- -->
```
-   Implement separation of duties

    The company needs to separate critical responsibilities among it's
    employees. This would greatly reduce the risk of fraud, errors and
    malicious activities by ensuring that a single employee does not
    have excessive control over sensitive processes.

```{=html}
<!-- -->
```
-   Strengten password policies

    The company need to implement a stronger password requirements,
    including a required minimum length, combination of letters, numbers
    and special characters as specified in the risk assessment. This
    requirements needs to be consistently enforced

```{=html}
<!-- -->
```
-   Implement centralized password management system

    The company should have a centralized password management system to
    enforce password requirements for all employees and make account
    recovery and resets more efficient.

```{=html}
<!-- -->
```
-   Encypt sensitive company data

    Customers critical information needs to be encrypted this is
    important since the company accepts, processes, transmits and stores
    credit card information internally.

```{=html}
<!-- -->
```
-   Implement regular backups and disaster recovery

    The company should have regular backup of data and a disaster
    recovery plan established. This controls in place will help the
    company recover from security incidents, system failures or other
    events that could disrupt the business operations.

```{=html}
<!-- -->
```
-   Implement an intrusion detection system

    The company should have an intrusion detection system in place in
    order to monitor and detect suspicious or anomalous network activity
    strengthening the company's ability to identify potential security
    incidents.

```{=html}
<!-- -->
```
-   Establish a scheduled monitoring maintenance for legacy systems

    The company IT department should establish a regular schedule for
    monitoring and maintaining legacy systems. There should also be
    clear intervention procedures documented so that outdated systems
    can be managed consistently.

-   Improve company asset management and classification

    The company should identify, inventory and classify its assets and
    determine which systems and data are most critical so that security
    resources can be allocated appropriately.

-   Prioritize PCI DSS and GDPR compliance

    Since the company processes customer payment information and
    conducts business in the E.U. controls related to PCI DSS and GPDR
    needs to be prioritized. In particular, the company access
    restrictions, encryption, data classification, privacy controls and
    breach notification procedures should be maintained and improved
    accordingly.
