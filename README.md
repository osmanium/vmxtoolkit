vmxtoolkit
==========

vmxtoolkit is the Powershell extension to VMware Workstation
vmxtoolkit is community-driven
vmxtoolkit is the Base for labbuildr, the automated lab building environment for vmware workstation on windows
you get support for labbuildr on http://labbuildr.com and https://community.emc.com/blogs/bottk/2014/06/16/announcement-labbuildr-released

simply follow @hyperv_guy on twitter for updates
Installation  
===========
 
Simply extract the toolkit into a folder where your VM´s reside.
Per Default, vmxtoolkit searches from that path
Otherwise, specifythe path to your vm when doing a get-vmx

current exposed commands
===========  
```Powershell
 PS E:\GitHub> Get-Command -Module vmxtoolkit

CommandType     Name                                               ModuleName
-----------     ----                                               ----------
Function        Add-VMXScsiDisk                                    vmxtoolkit
Function        Connect-VMXNetworkAdapter                          vmxtoolkit
Function        convert-VMXdos2unix                                vmxtoolkit
Function        Copy-VMXDirHost2Guest                              vmxtoolkit
Function        copy-VMXfile2guest                                 vmxtoolkit
Function        Disconnect-VMXNetworkAdapter                       vmxtoolkit
Function        Get-VMwareVersion                                  vmxtoolkit
Function        Get-VMX                                            vmxtoolkit
Function        Get-VMXActivationPreference                        vmxtoolkit
Function        Get-VMXAnnotation                                  vmxtoolkit
Function        Get-VMXConfig                                      vmxtoolkit
Function        Get-VMXConfigVersion                               vmxtoolkit
Function        Get-VMXDisplayName                                 vmxtoolkit
Function        Get-VMXGuestOS                                     vmxtoolkit
Function        Get-VMXHWVersion                                   vmxtoolkit
Function        Get-VMXIdeDisk                                     vmxtoolkit
Function        Get-VMXInfo                                        vmxtoolkit
Function        Get-VMXIPAddress                                   vmxtoolkit
Function        Get-VMXmemory                                      vmxtoolkit
Function        Get-VMXNetwork                                     vmxtoolkit
Function        Get-VMXNetworkAdapter                              vmxtoolkit
Function        Get-VMXNetworkAddress                              vmxtoolkit
Function        Get-VMXNetworkConnection                           vmxtoolkit
Function        Get-VMXProcessesInGuest                            vmxtoolkit
Function        Get-VMXProcessor                                   vmxtoolkit
Function        Get-VMXRun                                         vmxtoolkit
Function        Get-VMXscenario                                    vmxtoolkit
Function        Get-VMXScsiController                              vmxtoolkit
Function        Get-VMXScsiDisk                                    vmxtoolkit
Function        Get-VMXSnapshot                                    vmxtoolkit
Function        Get-VMXSnapshotconfig                              vmxtoolkit
Function        Get-VMXTemplate                                    vmxtoolkit
Function        Get-VMXToolsState                                  vmxtoolkit
Function        Get-VMXUUID                                        vmxtoolkit
Function        Get-yesnoabort                                     vmxtoolkit
Function        Invoke-VMXBash                                     vmxtoolkit
Function        Invoke-VMXexpect                                   vmxtoolkit
Function        Invoke-VMXPowerShell                               vmxtoolkit
Function        New-VMXClone                                       vmxtoolkit
Function        New-VMXGuestPath                                   vmxtoolkit
Function        New-VMXLinkedClone                                 vmxtoolkit
Function        New-VMXScsiDisk                                    vmxtoolkit
Function        New-VMXSnapshot                                    vmxtoolkit
Function        Optimize-VMXDisk                                   vmxtoolkit
Function        remove-vmx                                         vmxtoolkit
Function        Remove-VMXserial                                   vmxtoolkit
Function        Remove-VMXSnapshot                                 vmxtoolkit
Function        Repair-VMXDisk                                     vmxtoolkit
Function        Resize-VMXDiskfile                                 vmxtoolkit
Function        Restore-VMXSnapshot                                vmxtoolkit
Function        Search-VMXPattern                                  vmxtoolkit
Function        Set-VMXActivationPreference                        vmxtoolkit
Function        Set-VMXAnnotation                                  vmxtoolkit
Function        Set-VMXDisconnectIDE                               vmxtoolkit
Function        Set-VMXDisplayName                                 vmxtoolkit
Function        Set-VMXLinuxDNS                                    vmxtoolkit
Function        Set-VMXLinuxNetwork                                vmxtoolkit
Function        Set-VMXMainMemory                                  vmxtoolkit
Function        Set-VMXmemory                                      vmxtoolkit
Function        Set-VMXNetworkAdapter                              vmxtoolkit
Function        Set-VMXprocessor                                   vmxtoolkit
Function        Set-VMXscenario                                    vmxtoolkit
Function        Set-VMXserialPipe                                  vmxtoolkit
Function        Set-VMXSharedFolder                                vmxtoolkit
Function        Set-VMXSharedFolderState                           vmxtoolkit
Function        Set-VMXSize                                        vmxtoolkit
Function        Set-VMXTemplate                                    vmxtoolkit
Function        Set-VMXToolsReminder                               vmxtoolkit
Function        Set-VMXVnet                                        vmxtoolkit
Function        Start-VMX                                          vmxtoolkit
Function        Stop-VMX                                           vmxtoolkit
Function        Suspend-VMX                                        vmxtoolkit
``` 
Help
==========
while commands are self explaining, there is an online help available get-help [command] -online
Contributing
==========
Please contribute in any way to the project. Specifically, normalizing differnet image sizes, locations, and intance types would be easy adds to enhance the usefulness of the project.

Licensing
==========
Licensed under the Apache License, Version 2.0 (the “License”); you may not use this file except in compliance with the License. You may obtain a copy of the License at http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an “AS IS” BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.

Support
==========
Please file bugs and issues at the Github issues page. The code and documentation are released with no warranties or SLAs and are intended to be supported through a community driven process.
