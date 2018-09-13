--- 

title: Platinum~Pro Public API (20.2) 

language_tabs: 
   - shell 

toc_footers: 
   - <a href='#'>Sign Up for a Developer Key</a> 
   - <a href='https://github.com/lavkumarv'>Documentation Powered by lav</a> 

includes: 
   - errors 

search: true 

--- 

# Introduction 

**Version:** 20.2 

# /BORROWINGS
## ***GET*** 

**Summary:** Find Borrowing

### HTTP Request 
`***GET*** /Borrowings` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /BORROWINGS/{BORROWING_ID}
## ***GET*** 

**Summary:** Find Borrowing Summary

### HTTP Request 
`***GET*** /Borrowings/{borrowing_id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| borrowing_id | path |  | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 404 | Not Found |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /FINANCE/BANKACCOUNTS
## ***GET*** 

**Summary:** Find Bank Account

### HTTP Request 
`***GET*** /Finance/BankAccounts` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /FINANCE/BANKACCOUNTS/{BANKACCOUNT_ID}
## ***GET*** 

**Summary:** Find Bank Account Summary

### HTTP Request 
`***GET*** /Finance/BankAccounts/{bankaccount_id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| bankaccount_id | path |  | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 404 | Not Found |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /FUNCTIONS/BATCHES
## ***GET*** 

**Summary:** Batches

### HTTP Request 
`***GET*** /Functions/Batches` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /FUNCTIONS/BULKTAXCODES
## ***GET*** 

**Summary:** Bulk Tax Codes

### HTTP Request 
`***GET*** /Functions/BulkTaxCodes` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /FUNCTIONS/SCHEDULEDTASKS
## ***GET*** 

**Summary:** Scheduled Tasks

### HTTP Request 
`***GET*** /Functions/ScheduledTasks` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /FUNCTIONS/FEEDS/BANKBALANCE
## ***GET*** 

**Summary:** Bank Balance Feeds

### HTTP Request 
`***GET*** /Functions/Feeds/BankBalance` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /FUNCTIONS/BATCHES/{BATCHE_ID}
## ***GET*** 

**Summary:** Batches Summary

### HTTP Request 
`***GET*** /Functions/Batches/{batche_id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| batche_id | path |  | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 404 | Not Found |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /FUNCTIONS/FEEDS/BANKTRANSACTION
## ***GET*** 

**Summary:** Bank Transaction Feeds

### HTTP Request 
`***GET*** /Functions/Feeds/BankTransaction` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /FUNCTIONS/BULKTAXCODES/{BULKTAXCODE_ID}
## ***GET*** 

**Summary:** Bulk Tax Codes Summary

### HTTP Request 
`***GET*** /Functions/BulkTaxCodes/{bulktaxcode_id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| bulktaxcode_id | path |  | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 404 | Not Found |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /FUNCTIONS/SCHEDULEDTASKS/{SCHEDULEDTASK_ID}
## ***GET*** 

**Summary:** Scheduled Tasks Summary

### HTTP Request 
`***GET*** /Functions/ScheduledTasks/{scheduledtask_id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| scheduledtask_id | path |  | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 404 | Not Found |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /FUNCTIONS/FEEDS/BANKBALANCE/{BANKBALANCE_ID}
## ***GET*** 

**Summary:** Bank Balance Feeds Summary

### HTTP Request 
`***GET*** /Functions/Feeds/BankBalance/{bankbalance_id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| bankbalance_id | path |  | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 404 | Not Found |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /FUNCTIONS/FEEDS/BANKTRANSACTION/{BANKTRANSACTION_ID}
## ***GET*** 

**Summary:** Bank Transaction Feeds Summary

### HTTP Request 
`***GET*** /Functions/Feeds/BankTransaction/{banktransaction_id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| banktransaction_id | path |  | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 404 | Not Found |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /FUNDMANAGEMENT/INVESTMENTITEMS
## ***GET*** 

**Summary:** Find Investment Item

### HTTP Request 
`***GET*** /FundManagement/InvestmentItems` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /FUNDMANAGEMENT/INVESTMENTITEMS/{INVESTMENTITEM_ID}
## ***GET*** 

**Summary:** Find Investment Item Summary

### HTTP Request 
`***GET*** /FundManagement/InvestmentItems/{investmentitem_id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| investmentitem_id | path |  | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 404 | Not Found |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /GROUPS
## ***GET*** 

**Summary:** Find Group

### HTTP Request 
`***GET*** /Groups` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /GROUPS/{GROUP_ID}
## ***GET*** 

**Summary:** Find Group Summary

### HTTP Request 
`***GET*** /Groups/{group_id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| group_id | path |  | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 404 | Not Found |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /LOANS
## ***GET*** 

**Summary:** Find Loan

### HTTP Request 
`***GET*** /Loans` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /LOANS/{LOAN_ID}
## ***GET*** 

**Summary:** Find Loan Summary

### HTTP Request 
`***GET*** /Loans/{loan_id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| loan_id | path |  | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 404 | Not Found |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /MEMBERS
## ***GET*** 

**Summary:** Find Member

### HTTP Request 
`***GET*** /Members` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /MEMBERS/{MEMBER_ID}
## ***GET*** 

**Summary:** Find Member Summary

### HTTP Request 
`***GET*** /Members/{member_id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| member_id | path |  | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 404 | Not Found |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /MEMBERS/{MEMBER_ID}/LOANS
## ***GET*** 

**Summary:** Loans

### HTTP Request 
`***GET*** /Members/{member_id}/Loans` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| member_id | path |  | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /MEMBERS/{MEMBER_ID}/PLANS
## ***GET*** 

**Summary:** Plans

### HTTP Request 
`***GET*** /Members/{member_id}/Plans` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| member_id | path |  | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /MEMBERS/{MEMBER_ID}/CLAIMS
## ***GET*** 

**Summary:** Claim Masters

### HTTP Request 
`***GET*** /Members/{member_id}/Claims` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| member_id | path |  | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /MEMBERS/{MEMBER_ID}/GROUPS
## ***GET*** 

**Summary:** Groups

### HTTP Request 
`***GET*** /Members/{member_id}/Groups` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| member_id | path |  | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /MEMBERS/{MEMBER_ID}/ADVISERS
## ***GET*** 

**Summary:** Advisers

### HTTP Request 
`***GET*** /Members/{member_id}/Advisers` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| member_id | path |  | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /MEMBERS/{MEMBER_ID}/EARNINGS
## ***GET*** 

**Summary:** Earnings

### HTTP Request 
`***GET*** /Members/{member_id}/Earnings` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| member_id | path |  | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /MEMBERS/{MEMBER_ID}/HOLDINGS
## ***GET*** 

**Summary:** View Current Holdings

### HTTP Request 
`***GET*** /Members/{member_id}/Holdings` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| member_id | path |  | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /MEMBERS/{MEMBER_ID}/EMPLOYERS
## ***GET*** 

**Summary:** Employment

### HTTP Request 
`***GET*** /Members/{member_id}/Employers` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| member_id | path |  | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 404 | Not Found |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /MEMBERS/{MEMBER_ID}/AFTRECORDS
## ***GET*** 

**Summary:** Accounting For Tax Records

### HTTP Request 
`***GET*** /Members/{member_id}/AFTRecords` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| member_id | path |  | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /MEMBERS/{MEMBER_ID}/BORROWINGS
## ***GET*** 

**Summary:** Borrowings

### HTTP Request 
`***GET*** /Members/{member_id}/Borrowings` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| member_id | path |  | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /MEMBERS/{MEMBER_ID}/PROPERTIES
## ***GET*** 

**Summary:** Properties

### HTTP Request 
`***GET*** /Members/{member_id}/Properties` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| member_id | path |  | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /MEMBERS/{MEMBER_ID}/EVENTREPORTS
## ***GET*** 

**Summary:** Event Reports

### HTTP Request 
`***GET*** /Members/{member_id}/EventReports` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| member_id | path |  | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /MEMBERS/{MEMBER_ID}/TRANSFERS/IN
## ***GET*** 

**Summary:** Transfers In

### HTTP Request 
`***GET*** /Members/{member_id}/Transfers/In` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| member_id | path |  | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 404 | Not Found |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /MEMBERS/{MEMBER_ID}/DOCUMENTATION
## ***GET*** 

**Summary:** Documentation

### HTTP Request 
`***GET*** /Members/{member_id}/Documentation` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| member_id | path |  | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /MEMBERS/{MEMBER_ID}/WORKLOG/TASKS
## ***GET*** 

**Summary:** Worklog

### HTTP Request 
`***GET*** /Members/{member_id}/Worklog/Tasks` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| member_id | path |  | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /MEMBERS/{MEMBER_ID}/HMRCPROTECTIONS
## ***GET*** 

**Summary:** HMRC Protections

### HTTP Request 
`***GET*** /Members/{member_id}/HMRCProtections` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| member_id | path |  | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /MEMBERS/{MEMBER_ID}/LOANS/{LOAN_ID}
## ***GET*** 

**Summary:** Loans Summary

### HTTP Request 
`***GET*** /Members/{member_id}/Loans/{loan_id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| loan_id | path |  | Yes | integer |
| member_id | path |  | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 404 | Not Found |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /MEMBERS/{MEMBER_ID}/PLANS/{PLAN_ID}
## ***GET*** 

**Summary:** Plans Summary

### HTTP Request 
`***GET*** /Members/{member_id}/Plans/{plan_id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| plan_id | path |  | Yes | integer |
| member_id | path |  | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 404 | Not Found |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /MEMBERS/{MEMBER_ID}/INVOICE/INVOICES
## ***GET*** 

**Summary:** Invoices

### HTTP Request 
`***GET*** /Members/{member_id}/Invoice/Invoices` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| member_id | path |  | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /MEMBERS/{MEMBER_ID}/CLAIMS/{CLAIM_ID}
## ***GET*** 

**Summary:** Claim Masters Summary

### HTTP Request 
`***GET*** /Members/{member_id}/Claims/{claim_id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| claim_id | path |  | Yes | integer |
| member_id | path |  | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 404 | Not Found |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /MEMBERS/{MEMBER_ID}/GROUPS/{GROUP_ID}
## ***GET*** 

**Summary:** Groups Summary

### HTTP Request 
`***GET*** /Members/{member_id}/Groups/{group_id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| group_id | path |  | Yes | integer |
| member_id | path |  | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 404 | Not Found |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /MEMBERS/{MEMBER_ID}/INVOICE/LINEITEMS
## ***GET*** 

**Summary:** Line Items

### HTTP Request 
`***GET*** /Members/{member_id}/Invoice/LineItems` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| member_id | path |  | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /MEMBERS/{MEMBER_ID}/TRANSFERS/OVERSEAS
## ***GET*** 

**Summary:** Overseas Transfers

### HTTP Request 
`***GET*** /Members/{member_id}/Transfers/Overseas` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| member_id | path |  | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /MEMBERS/{MEMBER_ID}/TRANSFERS/IN/{IN_ID}
## ***GET*** 

**Summary:** Transfer In Master Records Summary

### HTTP Request 
`***GET*** /Members/{member_id}/Transfers/In/{in_id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| in_id | path |  | Yes | integer |
| member_id | path |  | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 404 | Not Found |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /MEMBERS/{MEMBER_ID}/ADVISERS/{ADVISER_ID}
## ***GET*** 

**Summary:** Advisers Summary

### HTTP Request 
`***GET*** /Members/{member_id}/Advisers/{adviser_id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| adviser_id | path |  | Yes | integer |
| member_id | path |  | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 404 | Not Found |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /MEMBERS/{MEMBER_ID}/BENEFIT/OTHER/DETAILS
## ***GET*** 

**Summary:** Other Benefit Details

### HTTP Request 
`***GET*** /Members/{member_id}/Benefit/Other/Details` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| member_id | path |  | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /MEMBERS/{MEMBER_ID}/EARNINGS/{EARNING_ID}
## ***GET*** 

**Summary:** Earnings Summary

### HTTP Request 
`***GET*** /Members/{member_id}/Earnings/{earning_id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| earning_id | path |  | Yes | integer |
| member_id | path |  | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 404 | Not Found |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /MEMBERS/{MEMBER_ID}/HOLDINGS/{HOLDING_ID}
## ***GET*** 

**Summary:** View Current Holdings Summary

### HTTP Request 
`***GET*** /Members/{member_id}/Holdings/{holding_id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| holding_id | path |  | Yes | integer |
| member_id | path |  | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 404 | Not Found |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /MEMBERS/{MEMBER_ID}/REGULARPAYMENTPROFILES
## ***GET*** 

**Summary:** Regular Payment Profiles

### HTTP Request 
`***GET*** /Members/{member_id}/RegularPaymentProfiles` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| member_id | path |  | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /MEMBERS/{MEMBER_ID}/EMPLOYERS/{EMPLOYER_ID}
## ***GET*** 

**Summary:** Employers Summary

### HTTP Request 
`***GET*** /Members/{member_id}/Employers/{employer_id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| employer_id | path |  | Yes | integer |
| member_id | path |  | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 404 | Not Found |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /MEMBERS/{MEMBER_ID}/WORKLOG/TASKS/{TASK_ID}
## ***GET*** 

**Summary:** Worklog Summary

### HTTP Request 
`***GET*** /Members/{member_id}/Worklog/Tasks/{task_id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| task_id | path |  | Yes | integer |
| member_id | path |  | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 404 | Not Found |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /MEMBERS/{MEMBER_ID}/PROPERTIES/{PROPERTY_ID}
## ***GET*** 

**Summary:** Properties Summary

### HTTP Request 
`***GET*** /Members/{member_id}/Properties/{property_id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| property_id | path |  | Yes | integer |
| member_id | path |  | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 404 | Not Found |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /MEMBERS/{MEMBER_ID}/AFTRECORDS/{AFTRECORD_ID}
## ***GET*** 

**Summary:** Accounting For Tax Records Summary

### HTTP Request 
`***GET*** /Members/{member_id}/AFTRecords/{aftrecord_id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| aftrecord_id | path |  | Yes | integer |
| member_id | path |  | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 404 | Not Found |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /MEMBERS/{MEMBER_ID}/BORROWINGS/{BORROWING_ID}
## ***GET*** 

**Summary:** Borrowings Summary

### HTTP Request 
`***GET*** /Members/{member_id}/Borrowings/{borrowing_id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| borrowing_id | path |  | Yes | integer |
| member_id | path |  | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 404 | Not Found |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /MEMBERS/{MEMBER_ID}/INVESTMENT/TYPE/2/PORTFOLIOS
## ***GET*** 

**Summary:** IP Type 2 Portfolios

### HTTP Request 
`***GET*** /Members/{member_id}/Investment/Type/2/Portfolios` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| member_id | path |  | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /MEMBERS/{MEMBER_ID}/INVESTMENT/TYPE/3/PORTFOLIOS
## ***GET*** 

**Summary:** IP Type 3 Portfolios

### HTTP Request 
`***GET*** /Members/{member_id}/Investment/Type/3/Portfolios` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| member_id | path |  | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /MEMBERS/{MEMBER_ID}/PENSIONLIFEASSURANCEPOLICIES
## ***GET*** 

**Summary:** Pension Life Assurance

### HTTP Request 
`***GET*** /Members/{member_id}/PensionLifeAssurancePolicies` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| member_id | path |  | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /MEMBERS/{MEMBER_ID}/EVENTREPORTS/{EVENTREPORT_ID}
## ***GET*** 

**Summary:** Event Reports Summary

### HTTP Request 
`***GET*** /Members/{member_id}/EventReports/{eventreport_id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| eventreport_id | path |  | Yes | integer |
| member_id | path |  | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 404 | Not Found |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /MEMBERS/{MEMBER_ID}/INVESTMENT/TYPE/1/INVESTMENTS
## ***GET*** 

**Summary:** IP Type 1 Investments

### HTTP Request 
`***GET*** /Members/{member_id}/Investment/Type/1/Investments` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| member_id | path |  | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /MEMBERS/{MEMBER_ID}/INVOICE/INVOICES/{INVOICE_ID}
## ***GET*** 

**Summary:** Invoices Summary

### HTTP Request 
`***GET*** /Members/{member_id}/Invoice/Invoices/{invoice_id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| invoice_id | path |  | Yes | integer |
| member_id | path |  | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 404 | Not Found |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /MEMBERS/{MEMBER_ID}/CONTRIBUTIONS/{CONTRIBUTION_ID}
## ***GET*** 

**Summary:** Contributions Summary

### HTTP Request 
`***GET*** /Members/{member_id}/Contributions/{contribution_id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| contribution_id | path |  | Yes | integer |
| member_id | path |  | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 404 | Not Found |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /MEMBERS/{MEMBER_ID}/INVOICE/LINEITEMS/{LINEITEM_ID}
## ***GET*** 

**Summary:** Line Items Summary

### HTTP Request 
`***GET*** /Members/{member_id}/Invoice/LineItems/{lineitem_id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| lineitem_id | path |  | Yes | integer |
| member_id | path |  | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 404 | Not Found |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /MEMBERS/{MEMBER_ID}/TRANSFERS/OVERSEAS/{OVERSEA_ID}
## ***GET*** 

**Summary:** Overseas Transfers Summary

### HTTP Request 
`***GET*** /Members/{member_id}/Transfers/Overseas/{oversea_id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| oversea_id | path |  | Yes | integer |
| member_id | path |  | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 404 | Not Found |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /MEMBERS/{MEMBER_ID}/BENEFICIARY/ACTUAL/BENEFICIARIES
## ***GET*** 

**Summary:** Actual Beneficiaries

### HTTP Request 
`***GET*** /Members/{member_id}/Beneficiary/Actual/Beneficiaries` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| member_id | path |  | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /MEMBERS/{MEMBER_ID}/DOCUMENTATION/{DOCUMENTATION_ID}
## ***GET*** 

**Summary:** Documentation Summary

### HTTP Request 
`***GET*** /Members/{member_id}/Documentation/{documentation_id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| documentation_id | path |  | Yes | integer |
| member_id | path |  | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 404 | Not Found |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /MEMBERS/{MEMBER_ID}/BENEFIT/OTHER/DETAILS/{DETAIL_ID}
## ***GET*** 

**Summary:** Other Benefit Details Summary

### HTTP Request 
`***GET*** /Members/{member_id}/Benefit/Other/Details/{detail_id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| detail_id | path |  | Yes | integer |
| member_id | path |  | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 404 | Not Found |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /MEMBERS/{MEMBER_ID}/BENEFICIARY/NOMINATED/BENEFICIARIES
## ***GET*** 

**Summary:** Nominated Beneficiaries

### HTTP Request 
`***GET*** /Members/{member_id}/Beneficiary/Nominated/Beneficiaries` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| member_id | path |  | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /MEMBERS/{MEMBER_ID}/HMRCPROTECTIONS/{HMRCPROTECTION_ID}
## ***GET*** 

**Summary:** HMRC Protections Summary

### HTTP Request 
`***GET*** /Members/{member_id}/HMRCProtections/{hmrcprotection_id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| hmrcprotection_id | path |  | Yes | integer |
| member_id | path |  | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 404 | Not Found |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /MEMBERS/{MEMBER_ID}/INVESTMENT/TYPE/2/PORTFOLIOS/{PORTFOLIO_ID}
## ***GET*** 

**Summary:** IP Type 2 Portfolios Summary

### HTTP Request 
`***GET*** /Members/{member_id}/Investment/Type/2/Portfolios/{portfolio_id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| portfolio_id | path |  | Yes | integer |
| member_id | path |  | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 404 | Not Found |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /MEMBERS/{MEMBER_ID}/INVESTMENT/TYPE/3/PORTFOLIOS/{PORTFOLIO_ID}
## ***GET*** 

**Summary:** IP Type 3 Portfolios Summary

### HTTP Request 
`***GET*** /Members/{member_id}/Investment/Type/3/Portfolios/{portfolio_id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| portfolio_id | path |  | Yes | integer |
| member_id | path |  | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 404 | Not Found |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /MEMBERS/{MEMBER_ID}/INVESTMENT/TYPE/1/INVESTMENTS/{INVESTMENT_ID}
## ***GET*** 

**Summary:** IP Type 1 Investments Summary

### HTTP Request 
`***GET*** /Members/{member_id}/Investment/Type/1/Investments/{investment_id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| investment_id | path |  | Yes | integer |
| member_id | path |  | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 404 | Not Found |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /MEMBERS/{MEMBER_ID}/BENEFICIARY/ACTUAL/BENEFICIARIES/{BENEFICIARY_ID}
## ***GET*** 

**Summary:** Actual Beneficiaries Summary

### HTTP Request 
`***GET*** /Members/{member_id}/Beneficiary/Actual/Beneficiaries/{beneficiary_id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| beneficiary_id | path |  | Yes | integer |
| member_id | path |  | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 404 | Not Found |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /MEMBERS/{MEMBER_ID}/REGULARPAYMENTPROFILES/{REGULARPAYMENTPROFILE_ID}
## ***GET*** 

**Summary:** Regular Payment Profiles Summary

### HTTP Request 
`***GET*** /Members/{member_id}/RegularPaymentProfiles/{regularpaymentprofile_id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| regularpaymentprofile_id | path |  | Yes | integer |
| member_id | path |  | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 404 | Not Found |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /MEMBERS/{MEMBER_ID}/BENEFICIARY/NOMINATED/BENEFICIARIES/{BENEFICIARY_ID}
## ***GET*** 

**Summary:** Nominated Beneficiaries Summary

### HTTP Request 
`***GET*** /Members/{member_id}/Beneficiary/Nominated/Beneficiaries/{beneficiary_id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| beneficiary_id | path |  | Yes | integer |
| member_id | path |  | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 404 | Not Found |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /MEMBERS/{MEMBER_ID}/PENSIONLIFEASSURANCEPOLICIES/{PENSIONLIFEASSURANCEPOLICY_ID}
## ***GET*** 

**Summary:** Pension Life Assurance Summary

### HTTP Request 
`***GET*** /Members/{member_id}/PensionLifeAssurancePolicies/{pensionlifeassurancepolicy_id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| pensionlifeassurancepolicy_id | path |  | Yes | integer |
| member_id | path |  | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 404 | Not Found |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /PROPERTY
## ***GET*** 

**Summary:** Find Property

### HTTP Request 
`***GET*** /Property` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /PROPERTY/{PROPERTY_ID}
## ***GET*** 

**Summary:** Find Property Summary

### HTTP Request 
`***GET*** /Property/{property_id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| property_id | path |  | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 404 | Not Found |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /RELATIONSHIPMANAGEMENT/ROLES
## ***GET*** 

**Summary:** Find Roles

### HTTP Request 
`***GET*** /RelationshipManagement/Roles` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /RELATIONSHIPMANAGEMENT/BRANCHES
## ***GET*** 

**Summary:** Find Branch

### HTTP Request 
`***GET*** /RelationshipManagement/Branches` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /RELATIONSHIPMANAGEMENT/ORGANISATIONS
## ***GET*** 

**Summary:** Find Role Holder

### HTTP Request 
`***GET*** /RelationshipManagement/Organisations` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /RELATIONSHIPMANAGEMENT/ROLES/{ROLE_ID}
## ***GET*** 

**Summary:** Find Roles Summary

### HTTP Request 
`***GET*** /RelationshipManagement/Roles/{role_id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| role_id | path |  | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 404 | Not Found |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /RELATIONSHIPMANAGEMENT/BRANCHES/{BRANCHE_ID}
## ***GET*** 

**Summary:** Find Branch Summary

### HTTP Request 
`***GET*** /RelationshipManagement/Branches/{branche_id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| branche_id | path |  | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 404 | Not Found |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /RELATIONSHIPMANAGEMENT/ORGANISATIONS/{ORGANISATION_ID}
## ***GET*** 

**Summary:** Find Role Holder Summary

### HTTP Request 
`***GET*** /RelationshipManagement/Organisations/{organisation_id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| organisation_id | path |  | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 404 | Not Found |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /REPORTING/REPORTS/PSR
## ***GET*** 

**Summary:** Pension Scheme Return (PSR)

### HTTP Request 
`***GET*** /Reporting/Reports/PSR` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /REPORTING/GOVTGATEWAY/DPS
## ***GET*** 

**Summary:** Find Data Provisioning Service (DPS)

### HTTP Request 
`***GET*** /Reporting/GovtGateway/DPS` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /REPORTING/GOVTGATEWAY/EPS
## ***GET*** 

**Summary:** Find Employer Payment Summary (EPS)

### HTTP Request 
`***GET*** /Reporting/GovtGateway/EPS` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /REPORTING/GOVTGATEWAY/EYU
## ***GET*** 

**Summary:** Find Earlier Year Update (EYU)

### HTTP Request 
`***GET*** /Reporting/GovtGateway/EYU` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /REPORTING/REPORTS/PSR/{PSR_ID}
## ***GET*** 

**Summary:** Pension Scheme Return (PSR) Summary

### HTTP Request 
`***GET*** /Reporting/Reports/PSR/{psr_id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| psr_id | path |  | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 404 | Not Found |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /REPORTING/GOVTGATEWAY/DPS/{DP_ID}
## ***GET*** 

**Summary:** Find Data Provisioning Service (DPS) Summary

### HTTP Request 
`***GET*** /Reporting/GovtGateway/DPS/{dp_id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| dp_id | path |  | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 404 | Not Found |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /REPORTING/GOVTGATEWAY/EPS/{EP_ID}
## ***GET*** 

**Summary:** Find Employer Payment Summary (EPS) Summary

### HTTP Request 
`***GET*** /Reporting/GovtGateway/EPS/{ep_id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| ep_id | path |  | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 404 | Not Found |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /REPORTING/GOVTGATEWAY/FPS/PAYROLL
## ***GET*** 

**Summary:** Find Full Payment Submission (FPS)

### HTTP Request 
`***GET*** /Reporting/GovtGateway/FPS/Payroll` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /REPORTING/GOVTGATEWAY/EYU/{EYU_ID}
## ***GET*** 

**Summary:** Find Earlier Year Update (EYU) Summary

### HTTP Request 
`***GET*** /Reporting/GovtGateway/EYU/{eyu_id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| eyu_id | path |  | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 404 | Not Found |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /REPORTING/GOVTGATEWAY/FPS/PAYROLL/{PAYROLL_ID}
## ***GET*** 

**Summary:** Find Full Payment Submission (FPS) Summary

### HTTP Request 
`***GET*** /Reporting/GovtGateway/FPS/Payroll/{payroll_id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| payroll_id | path |  | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 404 | Not Found |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /SCHEMES
## ***GET*** 

**Summary:** Find Scheme

### HTTP Request 
`***GET*** /Schemes` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /SCHEMES/BRANDS
## ***GET*** 

**Summary:** Find Brand

### HTTP Request 
`***GET*** /Schemes/Brands` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /SCHEMES/{SCHEME_ID}
## ***GET*** 

**Summary:** Find Scheme Summary

### HTTP Request 
`***GET*** /Schemes/{scheme_id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| scheme_id | path |  | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 404 | Not Found |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /SCHEMES/BRANDS/{BRAND_ID}
## ***GET*** 

**Summary:** Find Brand Summary

### HTTP Request 
`***GET*** /Schemes/Brands/{brand_id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| brand_id | path |  | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 404 | Not Found |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /WORKLOG/TASKS
## ***GET*** 

**Summary:** Find Worklog

### HTTP Request 
`***GET*** /Worklog/Tasks` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

# /WORKLOG/TASKS/{TASK_ID}
## ***GET*** 

**Summary:** Find Worklog Summary

### HTTP Request 
`***GET*** /Worklog/Tasks/{task_id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| task_id | path |  | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 400 | Bad Request |
| 401 | User is not authenticated with the provider |
| 403 | User is not authorised to use this end-point |
| 404 | Not Found |
| 405 | Method Not Allowed |
| 500 | Internal Server Error |

<!-- Converted with the swagger-to-slate https://github.com/lavkumarv/swagger-to-slate -->
