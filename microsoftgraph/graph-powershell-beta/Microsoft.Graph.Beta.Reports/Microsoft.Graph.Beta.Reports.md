---
Module Name: Microsoft.Graph.Beta.Reports
Module Guid: bd62468d-3a11-44d5-b88d-2a8e1a71a343
Download Help Link: https://learn.microsoft.com/powershell/module/microsoft.graph.beta.reports
Help Version: 1.0.0.0
Locale: en-US
---

# Microsoft.Graph.Beta.Reports Module
## Description
Microsoft Graph PowerShell Cmdlets

## Microsoft.Graph.Beta.Reports Cmdlets
### [Confirm-MgBetaAuditLogSignInCompromised](Confirm-MgBetaAuditLogSignInCompromised.md)
Allow admins to mark an event in the Azure AD sign in logs as risky.
Events marked as risky by an admin are immediately flagged as high risk in Azure AD Identity Protection, overriding previous risk states.
Admins can confirm that events flagged as risky by Azure AD Identity Protection are in fact risky.
For details about investigating Identity Protection risks, see How to investigate risk.

### [Confirm-MgBetaAuditLogSignInSafe](Confirm-MgBetaAuditLogSignInSafe.md)
Allow admins to mark an event in Azure AD sign in logs as safe.
Admins can either mark the events flagged as risky by Azure AD Identity Protection as safe, or they can mark unflagged events as safe.
For details about investigating Identity Protection risks, see How to investigate risk.

### [Get-MgBetaAdminReportSetting](Get-MgBetaAdminReportSetting.md)
Get the tenant-level settings for Microsoft 365 reports.

### [Get-MgBetaAuditLogCustomSecurityAttributeAudit](Get-MgBetaAuditLogCustomSecurityAttributeAudit.md)
Get customSecurityAttributeAudits from auditLogs

### [Get-MgBetaAuditLogCustomSecurityAttributeAuditCount](Get-MgBetaAuditLogCustomSecurityAttributeAuditCount.md)
Get the number of the resource

### [Get-MgBetaAuditLogDirectoryAudit](Get-MgBetaAuditLogDirectoryAudit.md)
Get a specific Azure Active Directory audit log item.
This includes an audit log item generated by various services within Azure Active Directory like user, application, device and group management, privileged identity management (PIM), access reviews, terms of use, identity protection, password management (self-service and admin password resets), self-service group management, and so on.

### [Get-MgBetaAuditLogDirectoryAuditCount](Get-MgBetaAuditLogDirectoryAuditCount.md)
Get the number of the resource

### [Get-MgBetaAuditLogDirectoryProvisioning](Get-MgBetaAuditLogDirectoryProvisioning.md)
Get directoryProvisioning from auditLogs

### [Get-MgBetaAuditLogDirectoryProvisioningCount](Get-MgBetaAuditLogDirectoryProvisioningCount.md)
Get the number of the resource

### [Get-MgBetaAuditLogProvisioning](Get-MgBetaAuditLogProvisioning.md)
Get provisioning from auditLogs

### [Get-MgBetaAuditLogProvisioningCount](Get-MgBetaAuditLogProvisioningCount.md)
Get the number of the resource

### [Get-MgBetaAuditLogSignIn](Get-MgBetaAuditLogSignIn.md)
Get a signIn object that contains a specific user sign-in event for your tenant.
This includes sign-ins where a user is asked to enter a username or password, and session tokens.

### [Get-MgBetaAuditLogSignInCount](Get-MgBetaAuditLogSignInCount.md)
Get the number of the resource

### [Get-MgBetaDeviceManagementReport](Get-MgBetaDeviceManagementReport.md)
Reports singleton

### [Get-MgBetaDeviceManagementReportCachedReportConfiguration](Get-MgBetaDeviceManagementReportCachedReportConfiguration.md)
Entity representing the configuration of a cached report

### [Get-MgBetaDeviceManagementReportCachedReportConfigurationCount](Get-MgBetaDeviceManagementReportCachedReportConfigurationCount.md)
Get the number of the resource

### [Get-MgBetaDeviceManagementReportExportJob](Get-MgBetaDeviceManagementReportExportJob.md)
Entity representing a job to export a report

### [Get-MgBetaDeviceManagementReportExportJobCount](Get-MgBetaDeviceManagementReportExportJobCount.md)
Get the number of the resource

### [Get-MgBetaReportAppCredentialSignInActivity](Get-MgBetaReportAppCredentialSignInActivity.md)
Get an appCredentialSignInActivity object that contains recent activity of an application credential.

### [Get-MgBetaReportAppCredentialSignInActivityCount](Get-MgBetaReportAppCredentialSignInActivityCount.md)
Get the number of the resource

### [Get-MgBetaReportApplicationSignInDetailedSummary](Get-MgBetaReportApplicationSignInDetailedSummary.md)
Retrieve the properties and relationships of an applicationSignInDetailedSummary object.

### [Get-MgBetaReportApplicationSignInDetailedSummaryCount](Get-MgBetaReportApplicationSignInDetailedSummaryCount.md)
Get the number of the resource

### [Get-MgBetaReportAttackSimulationRepeatOffender](Get-MgBetaReportAttackSimulationRepeatOffender.md)
Invoke function getAttackSimulationRepeatOffenders

### [Get-MgBetaReportAttackSimulationTrainingUserCoverage](Get-MgBetaReportAttackSimulationTrainingUserCoverage.md)
Invoke function getAttackSimulationTrainingUserCoverage

### [Get-MgBetaReportAttackSimulationUserCoverage](Get-MgBetaReportAttackSimulationUserCoverage.md)
Invoke function getAttackSimulationSimulationUserCoverage

### [Get-MgBetaReportAuthenticationMethod](Get-MgBetaReportAuthenticationMethod.md)
Container for navigation properties for Azure AD authentication methods resources.

### [Get-MgBetaReportAuthenticationMethodUserRegistrationDetail](Get-MgBetaReportAuthenticationMethodUserRegistrationDetail.md)
Read the properties and relationships of a userRegistrationDetails object.

### [Get-MgBetaReportAuthenticationMethodUserRegistrationDetailCount](Get-MgBetaReportAuthenticationMethodUserRegistrationDetailCount.md)
Get the number of the resource

### [Get-MgBetaReportAzureAdApplicationSignInSummary](Get-MgBetaReportAzureAdApplicationSignInSummary.md)
Invoke function getAzureADApplicationSignInSummary

### [Get-MgBetaReportBrowserDistributionUserCount](Get-MgBetaReportBrowserDistributionUserCount.md)
Invoke function getBrowserDistributionUserCounts

### [Get-MgBetaReportBrowserUserCount](Get-MgBetaReportBrowserUserCount.md)
Invoke function getBrowserUserCounts

### [Get-MgBetaReportBrowserUserDetail](Get-MgBetaReportBrowserUserDetail.md)
Invoke function getBrowserUserDetail

### [Get-MgBetaReportCredentialUsageSummary](Get-MgBetaReportCredentialUsageSummary.md)
Invoke function getCredentialUsageSummary

### [Get-MgBetaReportCredentialUserRegistrationCount](Get-MgBetaReportCredentialUserRegistrationCount.md)
Report the current state of how many users in your organization are registered for self-service password reset and multi-factor authentication (MFA) capabilities.

### [Get-MgBetaReportCredentialUserRegistrationDetail](Get-MgBetaReportCredentialUserRegistrationDetail.md)
Details of the usage of self-service password reset and multi-factor authentication (MFA) for all registered users.

### [Get-MgBetaReportCredentialUserRegistrationDetailCount](Get-MgBetaReportCredentialUserRegistrationDetailCount.md)
Get the number of the resource

### [Get-MgBetaReportDailyPrintUsage](Get-MgBetaReportDailyPrintUsage.md)
Get dailyPrintUsage from reports

### [Get-MgBetaReportDailyPrintUsageByPrinter](Get-MgBetaReportDailyPrintUsageByPrinter.md)
Retrieve a printer's usage summary for a particular time period.
For descriptions of each of the endpoints, see printUsageByPrinter.

### [Get-MgBetaReportDailyPrintUsageByPrinterCount](Get-MgBetaReportDailyPrintUsageByPrinterCount.md)
Get the number of the resource

### [Get-MgBetaReportDailyPrintUsageByUser](Get-MgBetaReportDailyPrintUsageByUser.md)
Retrieve a user's usage summary for a particular time period.
See the printUsageByUser documentation for descriptions of each of the endpoints.

### [Get-MgBetaReportDailyPrintUsageByUserCount](Get-MgBetaReportDailyPrintUsageByUserCount.md)
Get the number of the resource

### [Get-MgBetaReportDailyPrintUsageCount](Get-MgBetaReportDailyPrintUsageCount.md)
Get the number of the resource

### [Get-MgBetaReportDailyPrintUsageSummaryByPrinter](Get-MgBetaReportDailyPrintUsageSummaryByPrinter.md)
Get dailyPrintUsageSummariesByPrinter from reports

### [Get-MgBetaReportDailyPrintUsageSummaryByPrinterCount](Get-MgBetaReportDailyPrintUsageSummaryByPrinterCount.md)
Get the number of the resource

### [Get-MgBetaReportDailyPrintUsageSummaryByUser](Get-MgBetaReportDailyPrintUsageSummaryByUser.md)
Get dailyPrintUsageSummariesByUser from reports

### [Get-MgBetaReportDailyPrintUsageSummaryByUserCount](Get-MgBetaReportDailyPrintUsageSummaryByUserCount.md)
Get the number of the resource

### [Get-MgBetaReportDeviceConfigurationDeviceActivity](Get-MgBetaReportDeviceConfigurationDeviceActivity.md)
Metadata for the device configuration device activity report

### [Get-MgBetaReportDeviceConfigurationUserActivity](Get-MgBetaReportDeviceConfigurationUserActivity.md)
Metadata for the device configuration user activity report

### [Get-MgBetaReportEmailActivityCount](Get-MgBetaReportEmailActivityCount.md)
Invoke function getEmailActivityCounts

### [Get-MgBetaReportEmailActivityUserCount](Get-MgBetaReportEmailActivityUserCount.md)
Invoke function getEmailActivityUserCounts

### [Get-MgBetaReportEmailActivityUserDetail](Get-MgBetaReportEmailActivityUserDetail.md)
Invoke function getEmailActivityUserDetail

### [Get-MgBetaReportEmailAppUsageAppUserCount](Get-MgBetaReportEmailAppUsageAppUserCount.md)
Invoke function getEmailAppUsageAppsUserCounts

### [Get-MgBetaReportEmailAppUsageUserCount](Get-MgBetaReportEmailAppUsageUserCount.md)
Invoke function getEmailAppUsageUserCounts

### [Get-MgBetaReportEmailAppUsageUserDetail](Get-MgBetaReportEmailAppUsageUserDetail.md)
Invoke function getEmailAppUsageUserDetail

### [Get-MgBetaReportEmailAppUsageVersionUserCount](Get-MgBetaReportEmailAppUsageVersionUserCount.md)
Invoke function getEmailAppUsageVersionsUserCounts

### [Get-MgBetaReportFormUserActivityCount](Get-MgBetaReportFormUserActivityCount.md)
Invoke function getFormsUserActivityCounts

### [Get-MgBetaReportFormUserActivityUserCount](Get-MgBetaReportFormUserActivityUserCount.md)
Invoke function getFormsUserActivityUserCounts

### [Get-MgBetaReportFormUserActivityUserDetail](Get-MgBetaReportFormUserActivityUserDetail.md)
Invoke function getFormsUserActivityUserDetail

### [Get-MgBetaReportGroupArchivedPrintJob](Get-MgBetaReportGroupArchivedPrintJob.md)
Invoke function getGroupArchivedPrintJobs

### [Get-MgBetaReportM365AppPlatformUserCount](Get-MgBetaReportM365AppPlatformUserCount.md)
Invoke function getM365AppPlatformUserCounts

### [Get-MgBetaReportM365AppUserCount](Get-MgBetaReportM365AppUserCount.md)
Invoke function getM365AppUserCounts

### [Get-MgBetaReportM365AppUserDetail](Get-MgBetaReportM365AppUserDetail.md)
Invoke function getM365AppUserDetail

### [Get-MgBetaReportMailboxUsageDetail](Get-MgBetaReportMailboxUsageDetail.md)
Invoke function getMailboxUsageDetail

### [Get-MgBetaReportMailboxUsageMailboxCount](Get-MgBetaReportMailboxUsageMailboxCount.md)
Invoke function getMailboxUsageMailboxCounts

### [Get-MgBetaReportMailboxUsageQuotaStatusMailboxCount](Get-MgBetaReportMailboxUsageQuotaStatusMailboxCount.md)
Invoke function getMailboxUsageQuotaStatusMailboxCounts

### [Get-MgBetaReportMailboxUsageStorage](Get-MgBetaReportMailboxUsageStorage.md)
Invoke function getMailboxUsageStorage

### [Get-MgBetaReportManagedDeviceEnrollmentAbandonmentDetail](Get-MgBetaReportManagedDeviceEnrollmentAbandonmentDetail.md)
Metadata for Enrollment abandonment details report

### [Get-MgBetaReportManagedDeviceEnrollmentAbandonmentSummary](Get-MgBetaReportManagedDeviceEnrollmentAbandonmentSummary.md)
Metadata for Enrollment abandonment summary report

### [Get-MgBetaReportManagedDeviceEnrollmentFailureDetail](Get-MgBetaReportManagedDeviceEnrollmentFailureDetail.md)
Invoke function managedDeviceEnrollmentFailureDetails

### [Get-MgBetaReportManagedDeviceEnrollmentFailureTrend](Get-MgBetaReportManagedDeviceEnrollmentFailureTrend.md)
Metadata for the enrollment failure trends report

### [Get-MgBetaReportManagedDeviceEnrollmentTopFailure](Get-MgBetaReportManagedDeviceEnrollmentTopFailure.md)
Invoke function managedDeviceEnrollmentTopFailures

### [Get-MgBetaReportMonthlyPrintUsageByPrinter](Get-MgBetaReportMonthlyPrintUsageByPrinter.md)
Retrieve a list of monthly print usage summaries, grouped by printer.

### [Get-MgBetaReportMonthlyPrintUsageByPrinterCount](Get-MgBetaReportMonthlyPrintUsageByPrinterCount.md)
Get the number of the resource

### [Get-MgBetaReportMonthlyPrintUsageByUser](Get-MgBetaReportMonthlyPrintUsageByUser.md)
Retrieve a list of monthly print usage summaries, grouped by user.

### [Get-MgBetaReportMonthlyPrintUsageByUserCount](Get-MgBetaReportMonthlyPrintUsageByUserCount.md)
Get the number of the resource

### [Get-MgBetaReportMonthlyPrintUsageSummaryByPrinter](Get-MgBetaReportMonthlyPrintUsageSummaryByPrinter.md)
Get monthlyPrintUsageSummariesByPrinter from reports

### [Get-MgBetaReportMonthlyPrintUsageSummaryByPrinterCount](Get-MgBetaReportMonthlyPrintUsageSummaryByPrinterCount.md)
Get the number of the resource

### [Get-MgBetaReportMonthlyPrintUsageSummaryByUser](Get-MgBetaReportMonthlyPrintUsageSummaryByUser.md)
Get monthlyPrintUsageSummariesByUser from reports

### [Get-MgBetaReportMonthlyPrintUsageSummaryByUserCount](Get-MgBetaReportMonthlyPrintUsageSummaryByUserCount.md)
Get the number of the resource

### [Get-MgBetaReportOffice365ActivationCount](Get-MgBetaReportOffice365ActivationCount.md)
Invoke function getOffice365ActivationCounts

### [Get-MgBetaReportOffice365ActivationUserCount](Get-MgBetaReportOffice365ActivationUserCount.md)
Invoke function getOffice365ActivationsUserCounts

### [Get-MgBetaReportOffice365ActivationUserDetail](Get-MgBetaReportOffice365ActivationUserDetail.md)
Invoke function getOffice365ActivationsUserDetail

### [Get-MgBetaReportOffice365ActiveUserCount](Get-MgBetaReportOffice365ActiveUserCount.md)
Invoke function getOffice365ActiveUserCounts

### [Get-MgBetaReportOffice365ActiveUserDetail](Get-MgBetaReportOffice365ActiveUserDetail.md)
Invoke function getOffice365ActiveUserDetail

### [Get-MgBetaReportOffice365GroupActivityCount](Get-MgBetaReportOffice365GroupActivityCount.md)
Invoke function getOffice365GroupsActivityCounts

### [Get-MgBetaReportOffice365GroupActivityDetail](Get-MgBetaReportOffice365GroupActivityDetail.md)
Invoke function getOffice365GroupsActivityDetail

### [Get-MgBetaReportOffice365GroupActivityFileCount](Get-MgBetaReportOffice365GroupActivityFileCount.md)
Invoke function getOffice365GroupsActivityFileCounts

### [Get-MgBetaReportOffice365GroupActivityGroupCount](Get-MgBetaReportOffice365GroupActivityGroupCount.md)
Invoke function getOffice365GroupsActivityGroupCounts

### [Get-MgBetaReportOffice365GroupActivityStorage](Get-MgBetaReportOffice365GroupActivityStorage.md)
Invoke function getOffice365GroupsActivityStorage

### [Get-MgBetaReportOffice365ServiceUserCount](Get-MgBetaReportOffice365ServiceUserCount.md)
Invoke function getOffice365ServicesUserCounts

### [Get-MgBetaReportOneDriveActivityFileCount](Get-MgBetaReportOneDriveActivityFileCount.md)
Invoke function getOneDriveActivityFileCounts

### [Get-MgBetaReportOneDriveActivityUserCount](Get-MgBetaReportOneDriveActivityUserCount.md)
Invoke function getOneDriveActivityUserCounts

### [Get-MgBetaReportOneDriveActivityUserDetail](Get-MgBetaReportOneDriveActivityUserDetail.md)
Invoke function getOneDriveActivityUserDetail

### [Get-MgBetaReportOneDriveUsageAccountCount](Get-MgBetaReportOneDriveUsageAccountCount.md)
Invoke function getOneDriveUsageAccountCounts

### [Get-MgBetaReportOneDriveUsageAccountDetail](Get-MgBetaReportOneDriveUsageAccountDetail.md)
Invoke function getOneDriveUsageAccountDetail

### [Get-MgBetaReportOneDriveUsageFileCount](Get-MgBetaReportOneDriveUsageFileCount.md)
Invoke function getOneDriveUsageFileCounts

### [Get-MgBetaReportOneDriveUsageStorage](Get-MgBetaReportOneDriveUsageStorage.md)
Invoke function getOneDriveUsageStorage

### [Get-MgBetaReportPrinterArchivedPrintJob](Get-MgBetaReportPrinterArchivedPrintJob.md)
Invoke function getPrinterArchivedPrintJobs

### [Get-MgBetaReportRelyingPartyDetailedSummary](Get-MgBetaReportRelyingPartyDetailedSummary.md)
Invoke function getRelyingPartyDetailedSummary

### [Get-MgBetaReportSecurity](Get-MgBetaReportSecurity.md)
Provides the ability to launch a realistic simulated phishing attack that organizations can learn from.

### [Get-MgBetaReportSecurityAttackSimulationRepeatOffender](Get-MgBetaReportSecurityAttackSimulationRepeatOffender.md)
Invoke function getAttackSimulationRepeatOffenders

### [Get-MgBetaReportSecurityAttackSimulationTrainingUserCoverage](Get-MgBetaReportSecurityAttackSimulationTrainingUserCoverage.md)
Invoke function getAttackSimulationTrainingUserCoverage

### [Get-MgBetaReportSecurityAttackSimulationUserCoverage](Get-MgBetaReportSecurityAttackSimulationUserCoverage.md)
Invoke function getAttackSimulationSimulationUserCoverage

### [Get-MgBetaReportServicePrincipalSignInActivity](Get-MgBetaReportServicePrincipalSignInActivity.md)
Get a servicePrincipalSignInActivity object that contains sign-in activity information for a service principal in an Azure Active Directory tenant.
You can use a service principal as a client or resource.
A service principal supports delegated or app-only authentication context.

### [Get-MgBetaReportServicePrincipalSignInActivityCount](Get-MgBetaReportServicePrincipalSignInActivityCount.md)
Get the number of the resource

### [Get-MgBetaReportSharePointActivityFileCount](Get-MgBetaReportSharePointActivityFileCount.md)
Invoke function getSharePointActivityFileCounts

### [Get-MgBetaReportSharePointActivityPage](Get-MgBetaReportSharePointActivityPage.md)
Invoke function getSharePointActivityPages

### [Get-MgBetaReportSharePointActivityUserCount](Get-MgBetaReportSharePointActivityUserCount.md)
Invoke function getSharePointActivityUserCounts

### [Get-MgBetaReportSharePointActivityUserDetail](Get-MgBetaReportSharePointActivityUserDetail.md)
Invoke function getSharePointActivityUserDetail

### [Get-MgBetaReportSharePointSiteUsageDetail](Get-MgBetaReportSharePointSiteUsageDetail.md)
Invoke function getSharePointSiteUsageDetail

### [Get-MgBetaReportSharePointSiteUsageFileCount](Get-MgBetaReportSharePointSiteUsageFileCount.md)
Invoke function getSharePointSiteUsageFileCounts

### [Get-MgBetaReportSharePointSiteUsagePage](Get-MgBetaReportSharePointSiteUsagePage.md)
Invoke function getSharePointSiteUsagePages

### [Get-MgBetaReportSharePointSiteUsageSiteCount](Get-MgBetaReportSharePointSiteUsageSiteCount.md)
Invoke function getSharePointSiteUsageSiteCounts

### [Get-MgBetaReportSharePointSiteUsageStorage](Get-MgBetaReportSharePointSiteUsageStorage.md)
Invoke function getSharePointSiteUsageStorage

### [Get-MgBetaReportSkypeForBusinessActivityCount](Get-MgBetaReportSkypeForBusinessActivityCount.md)
Invoke function getSkypeForBusinessActivityCounts

### [Get-MgBetaReportSkypeForBusinessActivityUserCount](Get-MgBetaReportSkypeForBusinessActivityUserCount.md)
Invoke function getSkypeForBusinessActivityUserCounts

### [Get-MgBetaReportSkypeForBusinessActivityUserDetail](Get-MgBetaReportSkypeForBusinessActivityUserDetail.md)
Invoke function getSkypeForBusinessActivityUserDetail

### [Get-MgBetaReportSkypeForBusinessDeviceUsageDistributionUserCount](Get-MgBetaReportSkypeForBusinessDeviceUsageDistributionUserCount.md)
Invoke function getSkypeForBusinessDeviceUsageDistributionUserCounts

### [Get-MgBetaReportSkypeForBusinessDeviceUsageUserCount](Get-MgBetaReportSkypeForBusinessDeviceUsageUserCount.md)
Invoke function getSkypeForBusinessDeviceUsageUserCounts

### [Get-MgBetaReportSkypeForBusinessDeviceUsageUserDetail](Get-MgBetaReportSkypeForBusinessDeviceUsageUserDetail.md)
Invoke function getSkypeForBusinessDeviceUsageUserDetail

### [Get-MgBetaReportSkypeForBusinessOrganizerActivityCount](Get-MgBetaReportSkypeForBusinessOrganizerActivityCount.md)
Invoke function getSkypeForBusinessOrganizerActivityCounts

### [Get-MgBetaReportSkypeForBusinessOrganizerActivityMinuteCount](Get-MgBetaReportSkypeForBusinessOrganizerActivityMinuteCount.md)
Invoke function getSkypeForBusinessOrganizerActivityMinuteCounts

### [Get-MgBetaReportSkypeForBusinessOrganizerActivityUserCount](Get-MgBetaReportSkypeForBusinessOrganizerActivityUserCount.md)
Invoke function getSkypeForBusinessOrganizerActivityUserCounts

### [Get-MgBetaReportSkypeForBusinessParticipantActivityCount](Get-MgBetaReportSkypeForBusinessParticipantActivityCount.md)
Invoke function getSkypeForBusinessParticipantActivityCounts

### [Get-MgBetaReportSkypeForBusinessParticipantActivityMinuteCount](Get-MgBetaReportSkypeForBusinessParticipantActivityMinuteCount.md)
Invoke function getSkypeForBusinessParticipantActivityMinuteCounts

### [Get-MgBetaReportSkypeForBusinessParticipantActivityUserCount](Get-MgBetaReportSkypeForBusinessParticipantActivityUserCount.md)
Invoke function getSkypeForBusinessParticipantActivityUserCounts

### [Get-MgBetaReportSkypeForBusinessPeerToPeerActivityCount](Get-MgBetaReportSkypeForBusinessPeerToPeerActivityCount.md)
Invoke function getSkypeForBusinessPeerToPeerActivityCounts

### [Get-MgBetaReportSkypeForBusinessPeerToPeerActivityMinuteCount](Get-MgBetaReportSkypeForBusinessPeerToPeerActivityMinuteCount.md)
Invoke function getSkypeForBusinessPeerToPeerActivityMinuteCounts

### [Get-MgBetaReportSkypeForBusinessPeerToPeerActivityUserCount](Get-MgBetaReportSkypeForBusinessPeerToPeerActivityUserCount.md)
Invoke function getSkypeForBusinessPeerToPeerActivityUserCounts

### [Get-MgBetaReportSla](Get-MgBetaReportSla.md)
A placeholder to allow for the desired URL path for SLA.

### [Get-MgBetaReportSlaAzureAdAuthentication](Get-MgBetaReportSlaAzureAdAuthentication.md)
Read the properties and relationships of an azureADAuthentication object to find the level of Azure AD authentication availability for your tenant.
The Azure AD Service Level Agreement (SLA) commits to at least 99.99% authentication availability, as described in Azure Active Directory SLA performance.
This object provides you with your tenant's actual performance against this commitment.

### [Get-MgBetaReportTeamActivityCount](Get-MgBetaReportTeamActivityCount.md)
Invoke function getTeamsTeamActivityCounts

### [Get-MgBetaReportTeamActivityDetail](Get-MgBetaReportTeamActivityDetail.md)
Invoke function getTeamsTeamActivityDetail

### [Get-MgBetaReportTeamActivityDistributionCount](Get-MgBetaReportTeamActivityDistributionCount.md)
Invoke function getTeamsTeamActivityDistributionCounts

### [Get-MgBetaReportTeamCount](Get-MgBetaReportTeamCount.md)
Invoke function getTeamsTeamCounts

### [Get-MgBetaReportTeamDeviceUsageDistributionTotalUserCount](Get-MgBetaReportTeamDeviceUsageDistributionTotalUserCount.md)
Invoke function getTeamsDeviceUsageDistributionTotalUserCounts

### [Get-MgBetaReportTeamDeviceUsageDistributionUserCount](Get-MgBetaReportTeamDeviceUsageDistributionUserCount.md)
Invoke function getTeamsDeviceUsageDistributionUserCounts

### [Get-MgBetaReportTeamDeviceUsageTotalUserCount](Get-MgBetaReportTeamDeviceUsageTotalUserCount.md)
Invoke function getTeamsDeviceUsageTotalUserCounts

### [Get-MgBetaReportTeamDeviceUsageUserCount](Get-MgBetaReportTeamDeviceUsageUserCount.md)
Invoke function getTeamsDeviceUsageUserCounts

### [Get-MgBetaReportTeamDeviceUsageUserDetail](Get-MgBetaReportTeamDeviceUsageUserDetail.md)
Invoke function getTeamsDeviceUsageUserDetail

### [Get-MgBetaReportTeamUserActivityCount](Get-MgBetaReportTeamUserActivityCount.md)
Invoke function getTeamsUserActivityCounts

### [Get-MgBetaReportTeamUserActivityDistributionTotalUserCount](Get-MgBetaReportTeamUserActivityDistributionTotalUserCount.md)
Invoke function getTeamsUserActivityDistributionTotalUserCounts

### [Get-MgBetaReportTeamUserActivityDistributionUserCount](Get-MgBetaReportTeamUserActivityDistributionUserCount.md)
Invoke function getTeamsUserActivityDistributionUserCounts

### [Get-MgBetaReportTeamUserActivityTotalCount](Get-MgBetaReportTeamUserActivityTotalCount.md)
Invoke function getTeamsUserActivityTotalCounts

### [Get-MgBetaReportTeamUserActivityTotalDistributionCount](Get-MgBetaReportTeamUserActivityTotalDistributionCount.md)
Invoke function getTeamsUserActivityTotalDistributionCounts

### [Get-MgBetaReportTeamUserActivityTotalUserCount](Get-MgBetaReportTeamUserActivityTotalUserCount.md)
Invoke function getTeamsUserActivityTotalUserCounts

### [Get-MgBetaReportTeamUserActivityUserCount](Get-MgBetaReportTeamUserActivityUserCount.md)
Invoke function getTeamsUserActivityUserCounts

### [Get-MgBetaReportTeamUserActivityUserDetail](Get-MgBetaReportTeamUserActivityUserDetail.md)
Invoke function getTeamsUserActivityUserDetail

### [Get-MgBetaReportUserArchivedPrintJob](Get-MgBetaReportUserArchivedPrintJob.md)
Invoke function getUserArchivedPrintJobs

### [Get-MgBetaReportUserCredentialUsageDetail](Get-MgBetaReportUserCredentialUsageDetail.md)
Represents the self-service password reset (SSPR) usage for a given tenant.

### [Get-MgBetaReportUserCredentialUsageDetailCount](Get-MgBetaReportUserCredentialUsageDetailCount.md)
Get the number of the resource

### [Get-MgBetaReportYammerActivityCount](Get-MgBetaReportYammerActivityCount.md)
Invoke function getYammerActivityCounts

### [Get-MgBetaReportYammerActivityUserCount](Get-MgBetaReportYammerActivityUserCount.md)
Invoke function getYammerActivityUserCounts

### [Get-MgBetaReportYammerActivityUserDetail](Get-MgBetaReportYammerActivityUserDetail.md)
Invoke function getYammerActivityUserDetail

### [Get-MgBetaReportYammerDeviceUsageDistributionUserCount](Get-MgBetaReportYammerDeviceUsageDistributionUserCount.md)
Invoke function getYammerDeviceUsageDistributionUserCounts

### [Get-MgBetaReportYammerDeviceUsageUserCount](Get-MgBetaReportYammerDeviceUsageUserCount.md)
Invoke function getYammerDeviceUsageUserCounts

### [Get-MgBetaReportYammerDeviceUsageUserDetail](Get-MgBetaReportYammerDeviceUsageUserDetail.md)
Invoke function getYammerDeviceUsageUserDetail

### [Get-MgBetaReportYammerGroupActivityCount](Get-MgBetaReportYammerGroupActivityCount.md)
Invoke function getYammerGroupsActivityCounts

### [Get-MgBetaReportYammerGroupActivityDetail](Get-MgBetaReportYammerGroupActivityDetail.md)
Invoke function getYammerGroupsActivityDetail

### [Get-MgBetaReportYammerGroupActivityGroupCount](Get-MgBetaReportYammerGroupActivityGroupCount.md)
Invoke function getYammerGroupsActivityGroupCounts

### [Invoke-MgBetaGraphReportAuthenticationMethod](Invoke-MgBetaGraphReportAuthenticationMethod.md)
Invoke function usersRegisteredByFeature

### [New-MgBetaReportAuthenticationMethodUserRegistrationDetail](New-MgBetaReportAuthenticationMethodUserRegistrationDetail.md)
Create new navigation property to userRegistrationDetails for reports

### [Remove-MgBetaAdminReportSetting](Remove-MgBetaAdminReportSetting.md)
Delete navigation property reportSettings for admin

### [Remove-MgBetaDeviceManagementReport](Remove-MgBetaDeviceManagementReport.md)
Delete navigation property reports for deviceManagement

### [Remove-MgBetaReportAuthenticationMethodUserRegistrationDetail](Remove-MgBetaReportAuthenticationMethodUserRegistrationDetail.md)
Delete navigation property userRegistrationDetails for reports

### [Remove-MgBetaReportSlaAzureAdAuthentication](Remove-MgBetaReportSlaAzureAdAuthentication.md)
Delete navigation property azureADAuthentication for reports

### [Update-MgBetaAdminReportSetting](Update-MgBetaAdminReportSetting.md)
Update tenant-level settings for Microsoft 365 reports.

### [Update-MgBetaDeviceManagementReport](Update-MgBetaDeviceManagementReport.md)
Update the navigation property reports in deviceManagement

### [Update-MgBetaReportAuthenticationMethodUserRegistrationDetail](Update-MgBetaReportAuthenticationMethodUserRegistrationDetail.md)
Update the navigation property userRegistrationDetails in reports

### [Update-MgBetaReportSlaAzureAdAuthentication](Update-MgBetaReportSlaAzureAdAuthentication.md)
Update the navigation property azureADAuthentication in reports

