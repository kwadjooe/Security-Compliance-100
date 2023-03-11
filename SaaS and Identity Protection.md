# SaaS - Identity - Access  

## Protecting Saas with Defender for Cloud Apps  
    - The best solution for protection SaaS apps is Defender for Cloud Apps
     - This is the recommendation from the Microsoft Cybersecurity Architecture Reference MCRA  
     - This is also the ideal solution to address Shadow IT  

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

