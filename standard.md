# X. Identification
# 1. Prevention
## 1.1 Governance
### 1.1.1 Inventory of Assets
* There shall exist an established process for building and maintaining an inventory of assets.
* There shall exist an inventory of all information assets.
* The inventory should included dependencies between assets.
* The inventory should be as updated as possible.
* The inventory should be built automatically in a way that an operator would be able to validate what systems were in the inventory and what systems weren't in order to identify rogue assets.
* It should be possible to know the number of instances of one element in our organization.
* It should be possible to know the technical owner of each asset.
* It should be possible to know the owner of each asset.

### 1.1.2 Risk Management
* There shall exist an established risk management process. There shall exist at least one risk assessment done.

### 1.1.3 Vulnerability Management
* There shall exist an established vulnerability management process.
* All systems should be built in a way that could be updated or patched without impacting in a significant way to the business.
* The vulnerability management process should specify time windows where systems could be unpatched. There should not exist any system not patched outside these time windows.

### 1.1.4 Pentesting and Red Teaming
* The security of all the systems shall be tested (e.g pentesting, red team).

### 1.1.5 Patching
* There shall exist an established patching process.
* The patching process should guarantee that business is not going to be affected negatively patching or that negative affection is contained.

### 1.1.6 Security Audits
### 1.1.7 Backups
* There shall exist a backup process.
* The backup process should guarantee that the backups are available, protected and that are going to work as expected when it were necessary.
* The backups should be seggregated, tested and protected in a way that if a malicious user gains total control over the systems and networks, it won't be able to damage the backups (e.g. storing them seggregated and offline).

### 1.1.8 Indicators of Compromise Management
* There shall exist an established process to discover and update the indicators of compromise of each security solution (e.g. antivirus or firewall signatures, endpoint detection and response patterns, etc.)

## 1.2 Authentication and Authorization
* There shall exist an established policy for authentication and authorization.
* Systems in the perimeter should be protected with multifactor authentication or an equivalent security control.
* Every user, program or process should have access only to what it needs.
* For every sensitive action, it should be possible to know who did it and when.

## 1.3 Endpoint Security
* There shall be controls that prevent the execution of malicious software (e.g. antivirus).
* The number of files that could be executed only by double clicking should be reduced to the minimum necessary (e.g. .js, .hta).
* There exist techniques (e.g. macros) that allow that document files, like Word or Excel, were able to execute commands that may be malicious. There should exist security controls to reduce this possibility to the minimum necessary by the business:
  * Completely disable macros.
  * Disable macros in one type of document and not in the other.
  * Disable the possibility that a macro downloads a binary from the Internet.
  * Disable the possibility that a macro launches the execution of a binary.
  * Detect any of the behaviours above.
* Data at rest should be encrypted.

## 1.4 Server Security
* There shall be controls that prevent the execution of non authorized software.

## 1.5 Network Devices Security
## 1.6 Mobile Security
## 1.7 Application Security
* There shall exist an established process for the secure software development (could be called the SSDL process).
* The SSDL process should include dynamic analysis, static analysis and open source component analysis.

## 1.8 Physical Security
There shall be controls that prevent the access to areas where there are accessible critical hardware.

## 1.9 Awareness and Training
* Any member of the organization that use any information system should recive at least a basic cybersecurity training.
* If the organization has developers, they should receive and advanced training on secure development.
* Each member of the organization should receive a cybersecurity training aligned with its role and responsibilities.

# 2. Detection
## 2.1 Logging
* There shall exist an established logging policy.
* All logs should be centralized.
* Patterns should be search in the logs and alarms raised for security relevant issues.

# 3. Response
## 3.1 Incident response
* There shall exist an established process for incident response.

# 4. Recovery
## 4.1 Disaster recovery
* There shall exist an established process for disaster recovery.

# 5. Compliance
* There shall exist a process for the compliance of laws, regulations, standards and contractual obligations.
* There should exist a documented list of all the laws, regulations, standards and contractual obligations that the organization must comply with.