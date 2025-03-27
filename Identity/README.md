# Identity Threat Hunting Queries  

This folder contains KQL queries designed to assist in identity-based threat hunting and incident investigations. Each query focuses on detecting suspicious activity related to authentication and user access.  

## Queries  

### 1. **Sign-in Attempts to Disabled Accounts**  
- **Purpose**: Detects repeated sign-in attempts to disabled accounts in Microsoft Entra ID (Azure AD).  
- **Usage**: Identifies potential security threats where a disabled user account is being targeted.  
- **File**: [disabled_account_signin.kql](./disabled_account_signin.kql)  
