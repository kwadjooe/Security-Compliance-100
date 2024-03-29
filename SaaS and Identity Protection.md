# Secuirty is huge and require a clear vision with a set of incremental daily progress toward that vision  

## SaaS - Identity - Access  
[Defender for Cloud Step-by-step walkthrough](https://mslearn.cloudguides.com/en-us/guides/Protect%20your%20multi-cloud%20environment%20with%20Microsoft%20Defender%20for%20Cloud)
## Protecting Saas with Defender for Cloud Apps  
Microsoft Defender for Cloud is a cloud-native application protection platform (CNAPP) with a set of security measures and practices designed to protect cloud-based applications from various cyber threats and vulnerabilities. Defender for Cloud combines the capabilities of:

 * A development security operations (DevSecOps) solution that unifies security management at the code level across multicloud and multiple-pipeline environments  
 * A cloud security posture management (CSPM) solution that surfaces actions that you can take to prevent breaches  
 * A cloud workload protection platform (CWPP) with specific protections for servers, containers, storage, databases, and other workloads  
 - The best solution for protection SaaS apps is Defender for Cloud Apps
 - This is the recommendation from the Microsoft Cybersecurity Architecture Reference MCRA  
 - This is also the ideal solution to address Shadow IT  

![enter image description here](https://learn.microsoft.com/en-us/azure/defender-for-cloud/media/defender-for-cloud-introduction/defender-for-cloud-pillars.png) 

## Secure cloud applications
Defender for Cloud helps you to incorporate good security practices early during the software development process, or DevSecOps. You can protect your code management environments and your code pipelines, and get insights into your development environment security posture from a single location. Defender for Cloud currently includes Defender for DevOps.

Today’s applications require security awareness at the code, infrastructure, and runtime levels to make sure that deployed applications are hardened against attacks.  

### Code Pipeline Insights  
  Empowers security teams with the ability to protect applications and resources from code to cloud across multi-pipeline environments, including GitHub and Azure DevOps. Findings from Defender for DevOps, such as IaC misconfigurations and exposed secrets, can then be correlated with other contextual cloud security insights to prioritize remediation in code  

## Protecting Identities 

- We can leverage solution such as  
    
    - Conditional Access Policies to provide a central policy control for data and Application 
    by enforcing condition put in place based on :
        - Account authentication  
        - Network Location  
        - Device Health and compliance as well as various risk factors  
   
   - PasswordLess and Mutli Factor Authentication (MFA)  
        - Azure MFA help safeguard access to Applications and Data using strong authentication and comes in various flavours  
           - simple button Push using the microsoft Authenticator App  
           - Phone call, Text messages ... 

## Protecting Identity with Azure Active Directory (AAD)

    - Leverage tools such as 
        - Azure AD Privileged Identity Management (PIM)  
            - Manage Control and Monitor Privileged Access using Approval workflows which also allow to provide Just-in-Time (JIT) Access  
        
        - Identity Governance  
            - Balance Security with Productivity and ensure the right people have the right Access (RBAC)  
        
        - Identity Protection  
            - Provide a consolidated view into risky event and potentials vulnerabilities affecting the Organization identities  


### Defender for Identity  

    - Protect Identities on-prem or in the Cloud  

        - how is this done ?

    Event log are sent to Defender for Identity which Analyse the log looking for 
        - Compromised identities  
        - Advance Threat  
        - Malicious inside Users Actions  ...  

    Then Alert and Flags are generated to help investigate further and correct this issues   

