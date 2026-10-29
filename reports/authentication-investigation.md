# Microsoft Entra ID — Security Investigation Report

**Organization:** TJ Tech Solutions (Simulated Company)  
**Platform:** Microsoft Entra ID  
**Investigation Type:** Authentication Log Analysis  
**Date:** October 28, 2026  
**User Investigated:** Alex Carter

## 1. Objective

The purpose of this investigation was to analyze authentication activity in Microsoft Entra ID and evaluate the effectiveness of identity security controls, including multifactor authentication (MFA).

## 2. Lab Environment

The simulated company environment included:

- Six employee accounts across IT, HR, and Finance.
- Three departmental security groups.
- Role-Based Access Control (RBAC).
- Helpdesk Administrator permissions assigned to Alex Carter.
- Microsoft Entra security defaults enabled.
- Microsoft Authenticator configured for MFA.

## 3. Investigation Process

1. Accessed Microsoft Entra ID sign-in logs.
2. Filtered authentication events for Alex Carter.
3. Identified successful and failed sign-in attempts.
4. Reviewed authentication information for the successful sign-in.
5. Verified that MFA requirements were satisfied.
6. Compared the available authentication results.

## 4. Investigation Findings

| Security Event | Result |
|---|---|
| Successful sign-in | Confirmed |
| Failed sign-in | Confirmed |
| MFA verification | Successful |
| Successful sign-in IP | Not recorded |
| Failed sign-in IP | Not recorded |
| Failed sign-in reason | Not yet determined |

## 5. Security Analysis

The successful authentication event demonstrated that Alex Carter could access the Microsoft environment after satisfying MFA requirements.

A failed authentication event was also observed. However, the exact cause could not be determined because the failure reason and error code were not recorded.

The failed attempt may have resulted from incorrect credentials, an authentication challenge, or another access issue.

No evidence currently establishes that the failed attempt was malicious.

## 6. Security Recommendations

- Maintain MFA protections for administrative accounts.
- Apply the principle of least privilege.
- Monitor failed authentication events.
- Investigate repeated failures and unfamiliar source IP addresses.
- Review administrative audit logs for unexpected changes.
- Document authentication errors for future investigations.

## 7. Conclusion

This investigation demonstrated foundational cloud security monitoring skills using Microsoft Entra ID.

The lab provided hands-on experience with identity management, role-based access control, multifactor authentication, and authentication log analysis.

**Final Assessment:** Successful MFA authentication was verified. The failed sign-in remains unclassified pending additional evidence.
