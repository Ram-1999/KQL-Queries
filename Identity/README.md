# Identity KQL Queries

## Sign-in Attempts to Disabled Accounts

**Query File:** [disabled_account_signin.kql](./disabled_account_signin.kql)

This KQL query detects sign-in attempts to disabled accounts in Microsoft Entra (Azure AD).  
It helps identify potential security threats where a disabled user account is being targeted.

### Query Breakdown:
- **Filters logs** for `ResultType == 50057`, which indicates an account is disabled.
- **Summarizes** data by `UserPrincipalName` and `IPAddress`, counting unique applications and total attempts.
- **Applies a threshold** (default: 3) to detect multiple failed attempts.
- **Extracts username and domain** from `UserPrincipalName`.

### Usage:
1. Open Microsoft Sentinel or Log Analytics.
2. Copy and paste the query from `disabled_account_signin.kql`.
3. Adjust the threshold as needed.
4. Analyze the results for unusual activity.


