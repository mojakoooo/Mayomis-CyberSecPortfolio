Scenario

You are a newly hired cybersecurity analyst for an e-commerce company. The company stores information on a remote database server, since many of the employees work remotely from locations all around the world. Employees of the company regularly query, or request, data from the server to find potential customers. The database has been open to the public since the company's launch three years ago. As a cybersecurity professional, you recognize that keeping the database server open to the public is a serious vulnerability.

You are tasked with completing a vulnerability assessment of the situation to communicate the potential risks to decision makers at the company. You must create a written report that explains how the vulnerable server is a risk to business operations and how it can be secured.

Vulnerability Assessment Report
October 23, 2026

System Description
The server hardware consists of a powerful CPU processor and 128GB of memory. It runs on the latest version of Linux operating system and hosts a MySQL database management system. It is configured with a stable network connection using IPv4 addresses and interacts with other servers on the network. Security measures include SSL/TLS encrypted connections.
Scope
The scope of this vulnerability assessment relates to the current access controls of the system. The assessment will cover a period of three months, from October 23, 2026 to January 2027. NIST SP 800-30 Rev. 3 is used to guide the risk analysis of the information system.
Purpose
Consider the following questions to help you write:
●How is the database server valuable to the business?
●Why is it important for the business to secure the data on the server?
●How might the server impact the business if it were disabled?
Risk Assessment

Threat source	Threat event	Likelihood	Severity	Risk
Hacker	Obtain sensitive information via exfiltration.	3	3	9
Employee	Disrupt critical operations and/or sell sensitive information	2	3	6
Customer	Alter/ Delete Criticall Informataions	1	3	3
Risk Interpretation
Hacker with unauthorized access posses the highest risk, with a risk score of 9. Since the database is publicly accessible attackers can easily hack and attempt to exploit the server.
Employee related risk have a risk score of 6 simply because employees have legitimate access to the company’s resources and could potentially misuse their privileges.
Customer related risk has a score of 3 with the lowest level of risk. This should still be addressed through appropriate access controls because unauthorized modification or deletion of information could still affect business operations.
Approach
The risks were evaluated and selected based from the database server’s public exposure  and its importance to daily operation and sensitivity of the information stored on it. Having a publicly accessible database presents an increased opportunity to external hackers wanting to gain unauthorized access, steal critical information and/or disrupt daily operations.
Likelihood scores on the likeliness each threat source is successful in exploiting the identified vulnerabilities. Hackers were assigned with a higher likelihood of exploiting the vulnerabilities since the server is publicly accessible from the internet. While lower likelihood scores were assigned to both employee and customers because they are less likely to have the same level of access or opportunity compared to a hacker.
Severity scores were based on the potential impact to the confidentiality, integrity, and availability to the company. A severity score of 3 is assigned to threats that could result in significant data loss, unauthorized disclosure, or disruption of critical business operations
Overall risk score was calculated by multiplying the likelihood by severity. This assessment is limited since we are only basing it on the information provided about the database and does not include a full vulnerability scan, penetration testing, source-code review, and/or a detailed review of all the existing security configurations(firewalls, IDS/IPS,.etc).

Remediation Strategy
The most important recommendation is to remove direct public access to the database server. The database should only be accessible to authorized employees and applications that require it.

The following controls should be implemented:

1.Restrict network access: Configure the firewall rules to prevent any direct public access to the MySQL database. Connections should only be allowed from approved applications, servers, VPNs, or trusted IP addresses.

2.Use a VPN or secure access gateway: Since most of the company’s employees work remotely it should be mandaroty that they connect to the database through a company-approved VPN or secure access solution in order to access internal database resources.

3.Implement strong authentication: Password policy and multi-factor authentication (MFA) should be implemented for employees.

4.Implement least privilege: Employees should only  be able to modify what is necessary in order for them to perform their jobs efficiently while limiting administrative privileges to authorized personnel. only

5.Encrypt sensitive information: SSL/TLS need to still be implemented for data transmitted between clients and the database. All sensitive information stored in the database should also be protected perform network segmentation just in case a threat actor would enter the company netwrok it would be harder for them to access sensitive data.

6.Keep systems updated: Regular update to the Linux operating system, MySQL database, and  all the other software to address known security vulnerabilities.

7.Enable monitoring and logging: Database access, authentication attempts, unusual queries, and other suspicious activity should be monitored and logged. Logs needs to be reviewed regularly to identify possible unauthorized access.

8.Perform regular backups: Critical database information needs to have a secure and tested backups so that data can be restored if it is deleted, corrupted, or affected by a security incident.

9.Conduct regular vulnerability assessments: Regularly perform periodic vulnerability scans and security assessments to help identify new weaknesses and verify that all security controls remain effective.

Overall Improvement

By implementing these controls it will significantly reduce the database server's exposure to external threats. Restricting public access, enforcing least privilege, monitoring activity and maintaining secure backups will help protect the confidentiality, integrity, and availability of the company's data. These improvements will reduce the likelihood of data breaches and service disruptions while supporting the company's remote-work requirements.
