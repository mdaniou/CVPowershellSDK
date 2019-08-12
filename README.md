CVPowershellSDK
===============
CVPowershellSDK is a Windows Powershell package for Commvault software.

CVPowershellSDK uses the Commvault REST API to perform operations on a CommCell via the WebConsole.

Requirements
------------
- Windows Powershell version 5.1 or above
- Commvault Software v11 SP16 or later release with WebConsole installed

Installation
------------
After downloading, launch a Powershell session with Administrator privileges and execute:
- PS > Install-CVModules.ps1

Usage
-----
Login to Commcell:
- PS > Connect-CVServer
- For information on any Commvault Powershell command, run Get-Help [command] 
- For detailed examples on any Commvault Powershell command, run Get-Help [command] -Examples

Sample Package Function Table
-----------------------------
- Function: Get-CVClient                                       in Module: Commvault.CommCell
- Function: Get-CVClientGroup                                  in Module: Commvault.CommCell
- Function: Get-CVVersionInfo                                  in Module: Commvault.CommCell
- Function: Get-CVAlert                                        in Module: Commvault.CommCell
- Function: Get-CVSubclient                                    in Module: Commvault.CommCell
- Function: Set-CVClient                                       in Module: Commvault.CommCell
- Function: Add-CVClient                                       in Module: Commvault.CommCell
- Function: Set-CVClientGroup                                  in Module: Commvault.CommCell
- Function: Backup-CVClientFileSystem                          in Module: Commvault.FileSystem
- Function: Restore-CVClientFileSystem                         in Module: Commvault.FileSystem
- Function: Select-CVClientFileSystem                          in Module: Commvault.FileSystem
- Function: Search-CVClientFileSystem                          in Module: Commvault.FileSystem
- Function: Get-CVSLAReport                                    in Module: Commvault.JobManager
- Function: Get-CVJobDetail                                    in Module: Commvault.JobManager
- Function: Stop-CVJob                                         in Module: Commvault.JobManager
- Function: Suspend-CVJob                                      in Module: Commvault.JobManager
- Function: Send-CVLogFile                                     in Module: Commvault.JobManager
- Function: Update-CVMissedSLA                                 in Module: Commvault.JobManager
- Function: Resume-CVJob                                       in Module: Commvault.JobManager
- Function: Get-CVJob                                          in Module: Commvault.JobManager
- Function: Backup-CVDisasterRecovery                          in Module: Commvault.JobManager
- Function: Backup-CVSubclient                                 in Module: Commvault.JobManager
- Function: Get-CVStoragePolicy                                in Module: Commvault.Policies
- Function: Enable-CVSchedulePolicy                            in Module: Commvault.Policies
- Function: Get-CVSchedulePolicy                               in Module: Commvault.Policies
- Function: Disable-CVSchedulePolicy                           in Module: Commvault.Policies
- Function: Connect-CVServer                                   in Module: Commvault.RESTSession
- Function: Submit-CVRESTRequest                               in Module: Commvault.RESTSession
- Function: Get-CVRESTHeader                                   in Module: Commvault.RESTSession
- Function: Get-CVCommCellGlobals                              in Module: Commvault.RESTSession
- Function: Get-CVSessionDetail                                in Module: Commvault.RESTSession
- Function: Backup-CVSQLDatabase                               in Module: Commvault.SQLServer
- Function: Restore-CVSQLDatabase                              in Module: Commvault.SQLServer
- Function: Backup-CVSQLInstance                               in Module: Commvault.SQLServer
- Function: Mount-CVSQLDatabase                                in Module: Commvault.SQLServer
- Function: Get-CVSQLCloneDetail                               in Module: Commvault.SQLServer
- Function: Backup-CVSQLSubclient                              in Module: Commvault.SQLServer
- Function: Export-CVSQLDatabaseRTD                            in Module: Commvault.SQLServer
- Function: Get-CVSQLDatabase                                  in Module: Commvault.SQLServer
- Function: Get-CVSQLClientDetail                              in Module: Commvault.SQLServer
- Function: Get-CVSQLClone                                     in Module: Commvault.SQLServer
- Function: Get-CVSQLDatabaseBackupHistory                     in Module: Commvault.SQLServer
- Function: Get-CVSQLInstanceBackupHistory                     in Module: Commvault.SQLServer
- Function: Get-CVSQLInstanceDetail                            in Module: Commvault.SQLServer
- Function: Get-CVSQLDatabaseDetail                            in Module: Commvault.SQLServer
- Function: Get-CVSQLInstance                                  in Module: Commvault.SQLServer
- Function: Get-CVDiskSpace                                    in Module: Commvault.StorageResources
- Function: Get-CVSubclientMediaAgent                          in Module: Commvault.StorageResources
- Function: Get-CVLibrary                                      in Module: Commvault.StorageResources
- Function: Get-CVMediaAgent                                   in Module: Commvault.StorageResources
- Function: Get-CVVirtualMachine                               in Module: Commvault.VirtualServer
- Function: Add-CVVirtualMachine                               in Module: Commvault.VirtualServer
- Function: Dismount-CVVirtualMachine                          in Module: Commvault.VirtualServer
- Function: Restore-CVVirtualMachine                           in Module: Commvault.VirtualServer
- Function: Mount-CVVirtualMachine                             in Module: Commvault.VirtualServer
- Function: Remove-CVVirtualMachine                            in Module: Commvault.VirtualServer
- Function: Restore-CVVirtualMachineOutofPlace                 in Module: Commvault.VirtualServer
- Function: Get-CVVirtualMachineActiveMounts                   in Module: Commvault.VirtualServer
- Function: Backup-CVVirtualMachine                            in Module: Commvault.VirtualServer
- Function: Get-CVVirtualMachineBackupTime                     in Module: Commvault.VirtualServer

Uninstallation
--------------
Launch a Powershell session with Administrator privileges and execute:
PS > Uninstall-CVModules.ps1

Contributions
=============
Contributions are welcome; please do a pull request against the 'dev' branch.