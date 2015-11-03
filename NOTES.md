service instance

ServiceInstance { rootFolder: { attributes: { type: 'Folder' }, '$value': 'group-d1' },
  propertyCollector: 
   { attributes: { type: 'PropertyCollector' },
     '$value': 'propertyCollector' },
  viewManager: { attributes: { type: 'ViewManager' }, '$value': 'ViewManager' },
  about: 
   { name: 'VMware vCenter Server',
     fullName: 'VMware vCenter Server 5.5.0 build-2646482',
     vendor: 'VMware, Inc.',
     version: '5.5.0',
     build: '2646482',
     localeVersion: 'INTL',
     localeBuild: '000',
     osType: 'linux-x64',
     productLineId: 'vpx',
     apiType: 'VirtualCenter',
     apiVersion: '5.5',
     instanceUuid: '4450E39B-C4EF-49F9-88F0-09621645B85C',
     licenseProductName: 'VMware VirtualCenter Server',
     licenseProductVersion: '5.0' },
  setting: 
   { attributes: { type: 'OptionManager' },
     '$value': 'VpxSettings' },
  userDirectory: 
   { attributes: { type: 'UserDirectory' },
     '$value': 'UserDirectory' },
  sessionManager: 
   { attributes: { type: 'SessionManager' },
     '$value': 'SessionManager' },
  authorizationManager: 
   { attributes: { type: 'AuthorizationManager' },
     '$value': 'AuthorizationManager' },
  serviceManager: 
   { attributes: { type: 'ServiceManager' },
     '$value': 'ServiceMgr' },
  perfManager: 
   { attributes: { type: 'PerformanceManager' },
     '$value': 'PerfMgr' },
  scheduledTaskManager: 
   { attributes: { type: 'ScheduledTaskManager' },
     '$value': 'ScheduledTaskManager' },
  alarmManager: 
   { attributes: { type: 'AlarmManager' },
     '$value': 'AlarmManager' },
  eventManager: 
   { attributes: { type: 'EventManager' },
     '$value': 'EventManager' },
  taskManager: { attributes: { type: 'TaskManager' }, '$value': 'TaskManager' },
  extensionManager: 
   { attributes: { type: 'ExtensionManager' },
     '$value': 'ExtensionManager' },
  customizationSpecManager: 
   { attributes: { type: 'CustomizationSpecManager' },
     '$value': 'CustomizationSpecManager' },
  customFieldsManager: 
   { attributes: { type: 'CustomFieldsManager' },
     '$value': 'CustomFieldsManager' },
  diagnosticManager: 
   { attributes: { type: 'DiagnosticManager' },
     '$value': 'DiagMgr' },
  licenseManager: 
   { attributes: { type: 'LicenseManager' },
     '$value': 'LicenseManager' },
  searchIndex: { attributes: { type: 'SearchIndex' }, '$value': 'SearchIndex' },
  fileManager: { attributes: { type: 'FileManager' }, '$value': 'FileManager' },
  datastoreNamespaceManager: 
   { attributes: { type: 'DatastoreNamespaceManager' },
     '$value': 'DatastoreNamespaceManager' },
  virtualDiskManager: 
   { attributes: { type: 'VirtualDiskManager' },
     '$value': 'virtualDiskManager' },
  snmpSystem: 
   { attributes: { type: 'HostSnmpSystem' },
     '$value': 'SnmpSystem' },
  vmProvisioningChecker: 
   { attributes: { type: 'VirtualMachineProvisioningChecker' },
     '$value': 'ProvChecker' },
  vmCompatibilityChecker: 
   { attributes: { type: 'VirtualMachineCompatibilityChecker' },
     '$value': 'CompatChecker' },
  ovfManager: { attributes: { type: 'OvfManager' }, '$value': 'OvfManager' },
  ipPoolManager: 
   { attributes: { type: 'IpPoolManager' },
     '$value': 'IpPoolManager' },
  dvSwitchManager: 
   { attributes: { type: 'DistributedVirtualSwitchManager' },
     '$value': 'DVSManager' },
  hostProfileManager: 
   { attributes: { type: 'HostProfileManager' },
     '$value': 'HostProfileManager' },
  clusterProfileManager: 
   { attributes: { type: 'ClusterProfileManager' },
     '$value': 'ClusterProfileManager' },
  complianceManager: 
   { attributes: { type: 'ProfileComplianceManager' },
     '$value': 'MoComplianceManager' },
  localizationManager: 
   { attributes: { type: 'LocalizationManager' },
     '$value': 'LocalizationManager' },
  storageResourceManager: 
   { attributes: { type: 'StorageResourceManager' },
     '$value': 'StorageResourceManager' },
  guestOperationsManager: 
   { attributes: { type: 'GuestOperationsManager' },
     '$value': 'guestOperationsManager' } }



methods

{ DestroyPropertyFilter: [Function],
  CreateFilter: [Function],
  RetrieveProperties: [Function],
  CheckForUpdates: [Function],
  WaitForUpdates: [Function],
  CancelWaitForUpdates: [Function],
  WaitForUpdatesEx: [Function],
  RetrievePropertiesEx: [Function],
  ContinueRetrievePropertiesEx: [Function],
  CancelRetrievePropertiesEx: [Function],
  CreatePropertyCollector: [Function],
  DestroyPropertyCollector: [Function],
  AddAuthorizationRole: [Function],
  RemoveAuthorizationRole: [Function],
  UpdateAuthorizationRole: [Function],
  MergePermissions: [Function],
  RetrieveRolePermissions: [Function],
  RetrieveEntityPermissions: [Function],
  RetrieveAllPermissions: [Function],
  SetEntityPermissions: [Function],
  ResetEntityPermissions: [Function],
  RemoveEntityPermission: [Function],
  HasPrivilegeOnEntity: [Function],
  HasPrivilegeOnEntities: [Function],
  ReconfigureCluster_Task: [Function],
  ApplyRecommendation: [Function],
  CancelRecommendation: [Function],
  RecommendHostsForVm: [Function],
  AddHost_Task: [Function],
  MoveInto_Task: [Function],
  MoveHostInto_Task: [Function],
  RefreshRecommendation: [Function],
  RetrieveDasAdvancedRuntimeInfo: [Function],
  ClusterEnterMaintenanceMode: [Function],
  ReconfigureComputeResource_Task: [Function],
  AddCustomFieldDef: [Function],
  RemoveCustomFieldDef: [Function],
  RenameCustomFieldDef: [Function],
  SetField: [Function],
  DoesCustomizationSpecExist: [Function],
  GetCustomizationSpec: [Function],
  CreateCustomizationSpec: [Function],
  OverwriteCustomizationSpec: [Function],
  DeleteCustomizationSpec: [Function],
  DuplicateCustomizationSpec: [Function],
  RenameCustomizationSpec: [Function],
  CustomizationSpecItemToXml: [Function],
  XmlToCustomizationSpecItem: [Function],
  CheckCustomizationResources: [Function],
  QueryConnectionInfo: [Function],
  PowerOnMultiVM_Task: [Function],
  queryDatacenterConfigOptionDescriptor: [Function],
  ReconfigureDatacenter_Task: [Function],
  RefreshDatastore: [Function],
  RefreshDatastoreStorageInfo: [Function],
  UpdateVirtualMachineFiles_Task: [Function],
  RenameDatastore: [Function],
  DestroyDatastore: [Function],
  DatastoreEnterMaintenanceMode: [Function],
  DatastoreExitMaintenanceMode_Task: [Function],
  CreateDirectory: [Function],
  DeleteDirectory: [Function],
  QueryDescriptions: [Function],
  BrowseDiagnosticLog: [Function],
  GenerateLogBundles_Task: [Function],
  FetchDVPortKeys: [Function],
  FetchDVPorts: [Function],
  QueryUsedVlanIdInDvs: [Function],
  ReconfigureDvs_Task: [Function],
  PerformDvsProductSpecOperation_Task: [Function],
  MergeDvs_Task: [Function],
  AddDVPortgroup_Task: [Function],
  MoveDVPort_Task: [Function],
  UpdateDvsCapability: [Function],
  ReconfigureDVPort_Task: [Function],
  RefreshDVPortState: [Function],
  RectifyDvsHost_Task: [Function],
  UpdateNetworkResourcePool: [Function],
  AddNetworkResourcePool: [Function],
  RemoveNetworkResourcePool: [Function],
  EnableNetworkResourceManagement: [Function],
  DVSRollback_Task: [Function],
  CreateDVPortgroup_Task: [Function],
  UpdateDVSHealthCheckConfig_Task: [Function],
  LookupDvPortGroup: [Function],
  QueryConfigOptionDescriptor: [Function],
  QueryConfigOption: [Function],
  QueryConfigTarget: [Function],
  QueryTargetCapabilities: [Function],
  setCustomValue: [Function],
  UnregisterExtension: [Function],
  FindExtension: [Function],
  RegisterExtension: [Function],
  UpdateExtension: [Function],
  GetPublicKey: [Function],
  SetPublicKey: [Function],
  SetExtensionCertificate: [Function],
  QueryManagedBy: [Function],
  QueryExtensionIpAllocationUsage: [Function],
  MoveDatastoreFile_Task: [Function],
  CopyDatastoreFile_Task: [Function],
  DeleteDatastoreFile_Task: [Function],
  MakeDirectory: [Function],
  ChangeOwner: [Function],
  CreateFolder: [Function],
  MoveIntoFolder_Task: [Function],
  CreateVM_Task: [Function],
  RegisterVM_Task: [Function],
  CreateCluster: [Function],
  CreateClusterEx: [Function],
  AddStandaloneHost_Task: [Function],
  CreateDatacenter: [Function],
  UnregisterAndDestroy_Task: [Function],
  CreateDVS_Task: [Function],
  CreateStoragePod: [Function],
  SetCollectorPageSize: [Function],
  RewindCollector: [Function],
  ResetCollector: [Function],
  DestroyCollector: [Function],
  QueryTpmAttestationReport: [Function],
  QueryHostConnectionInfo: [Function],
  UpdateSystemResources: [Function],
  UpdateSystemSwapConfiguration: [Function],
  ReconnectHost_Task: [Function],
  DisconnectHost_Task: [Function],
  EnterMaintenanceMode_Task: [Function],
  ExitMaintenanceMode_Task: [Function],
  RebootHost_Task: [Function],
  ShutdownHost_Task: [Function],
  PowerDownHostToStandBy_Task: [Function],
  PowerUpHostFromStandBy_Task: [Function],
  QueryMemoryOverhead: [Function],
  QueryMemoryOverheadEx: [Function],
  ReconfigureHostForDAS_Task: [Function],
  UpdateFlags: [Function],
  EnterLockdownMode: [Function],
  ExitLockdownMode: [Function],
  AcquireCimServicesTicket: [Function],
  UpdateIpmi: [Function],
  RetrieveHardwareUptime: [Function],
  HttpNfcLeaseGetManifest: [Function],
  HttpNfcLeaseComplete: [Function],
  HttpNfcLeaseAbort: [Function],
  HttpNfcLeaseProgress: [Function],
  QueryIpPools: [Function],
  CreateIpPool: [Function],
  UpdateIpPool: [Function],
  DestroyIpPool: [Function],
  AllocateIpv4Address: [Function],
  AllocateIpv6Address: [Function],
  ReleaseIpAllocation: [Function],
  QueryIPAllocations: [Function],
  UpdateAssignedLicense: [Function],
  RemoveAssignedLicense: [Function],
  QueryAssignedLicenses: [Function],
  QuerySupportedFeatures: [Function],
  QueryLicenseSourceAvailability: [Function],
  QueryLicenseUsage: [Function],
  SetLicenseEdition: [Function],
  CheckLicenseFeature: [Function],
  EnableFeature: [Function],
  DisableFeature: [Function],
  ConfigureLicenseSource: [Function],
  UpdateLicense: [Function],
  AddLicense: [Function],
  RemoveLicense: [Function],
  DecodeLicense: [Function],
  UpdateLicenseLabel: [Function],
  RemoveLicenseLabel: [Function],
  Reload: [Function],
  Rename_Task: [Function],
  Destroy_Task: [Function],
  DestroyNetwork: [Function],
  ValidateHost: [Function],
  ParseDescriptor: [Function],
  CreateImportSpec: [Function],
  CreateDescriptor: [Function],
  QueryPerfProviderSummary: [Function],
  QueryAvailablePerfMetric: [Function],
  QueryPerfCounter: [Function],
  QueryPerfCounterByLevel: [Function],
  QueryPerf: [Function],
  QueryPerfComposite: [Function],
  CreatePerfInterval: [Function],
  RemovePerfInterval: [Function],
  UpdatePerfInterval: [Function],
  UpdateCounterLevelMapping: [Function],
  ResetCounterLevelMapping: [Function],
  EstimateDatabaseSize: [Function],
  UpdateConfig: [Function],
  MoveIntoResourcePool: [Function],
  UpdateChildResourceConfiguration: [Function],
  CreateResourcePool: [Function],
  DestroyChildren: [Function],
  CreateVApp: [Function],
  CreateChildVM_Task: [Function],
  RegisterChildVM_Task: [Function],
  ImportVApp: [Function],
  QueryResourceConfigOption: [Function],
  RefreshRuntime: [Function],
  FindByUuid: [Function],
  FindByDatastorePath: [Function],
  FindByDnsName: [Function],
  FindByIp: [Function],
  FindByInventoryPath: [Function],
  FindChild: [Function],
  FindAllByUuid: [Function],
  FindAllByDnsName: [Function],
  FindAllByIp: [Function],
  CurrentTime: [Function],
  RetrieveServiceContent: [Function],
  ValidateMigration: [Function],
  QueryVMotionCompatibility: [Function],
  RetrieveProductComponents: [Function],
  QueryServiceList: [Function],
  UpdateServiceMessage: [Function],
  LoginByToken: [Function],
  Login: [Function],
  LoginBySSPI: [Function],
  Logout: [Function],
  AcquireLocalTicket: [Function],
  AcquireGenericServiceTicket: [Function],
  TerminateSession: [Function],
  SetLocale: [Function],
  LoginExtensionBySubjectName: [Function],
  LoginExtensionByCertificate: [Function],
  ImpersonateUser: [Function],
  SessionIsActive: [Function],
  AcquireCloneTicket: [Function],
  CloneSession: [Function],
  ExecuteSimpleCommand: [Function],
  ConfigureDatastoreIORM_Task: [Function],
  QueryIORMConfigOption: [Function],
  QueryDatastorePerformanceSummary: [Function],
  ApplyStorageDrsRecommendationToPod_Task: [Function],
  ApplyStorageDrsRecommendation_Task: [Function],
  CancelStorageDrsRecommendation: [Function],
  RefreshStorageDrsRecommendation: [Function],
  ConfigureStorageDrsForPod_Task: [Function],
  RecommendDatastores: [Function],
  CancelTask: [Function],
  UpdateProgress: [Function],
  SetTaskState: [Function],
  SetTaskDescription: [Function],
  ReadNextTasks: [Function],
  ReadPreviousTasks: [Function],
  CreateCollectorForTasks: [Function],
  CreateTask: [Function],
  RetrieveUserGroups: [Function],
  UpdateVAppConfig: [Function],
  UpdateLinkedChildren: [Function],
  CloneVApp_Task: [Function],
  ExportVApp: [Function],
  PowerOnVApp_Task: [Function],
  PowerOffVApp_Task: [Function],
  SuspendVApp_Task: [Function],
  unregisterVApp_Task: [Function],
  CreateVirtualDisk_Task: [Function],
  DeleteVirtualDisk_Task: [Function],
  MoveVirtualDisk_Task: [Function],
  CopyVirtualDisk_Task: [Function],
  ExtendVirtualDisk_Task: [Function],
  QueryVirtualDiskFragmentation: [Function],
  DefragmentVirtualDisk_Task: [Function],
  ShrinkVirtualDisk_Task: [Function],
  InflateVirtualDisk_Task: [Function],
  EagerZeroVirtualDisk_Task: [Function],
  ZeroFillVirtualDisk_Task: [Function],
  SetVirtualDiskUuid: [Function],
  QueryVirtualDiskUuid: [Function],
  QueryVirtualDiskGeometry: [Function],
  RefreshStorageInfo: [Function],
  CreateSnapshot_Task: [Function],
  RevertToCurrentSnapshot_Task: [Function],
  RemoveAllSnapshots_Task: [Function],
  ConsolidateVMDisks_Task: [Function],
  EstimateStorageForConsolidateSnapshots_Task: [Function],
  ReconfigVM_Task: [Function],
  UpgradeVM_Task: [Function],
  ExtractOvfEnvironment: [Function],
  PowerOnVM_Task: [Function],
  PowerOffVM_Task: [Function],
  SuspendVM_Task: [Function],
  ResetVM_Task: [Function],
  ShutdownGuest: [Function],
  RebootGuest: [Function],
  StandbyGuest: [Function],
  AnswerVM: [Function],
  CustomizeVM_Task: [Function],
  CheckCustomizationSpec: [Function],
  MigrateVM_Task: [Function],
  RelocateVM_Task: [Function],
  CloneVM_Task: [Function],
  ExportVm: [Function],
  MarkAsTemplate: [Function],
  MarkAsVirtualMachine: [Function],
  UnregisterVM: [Function],
  ResetGuestInformation: [Function],
  MountToolsInstaller: [Function],
  UnmountToolsInstaller: [Function],
  UpgradeTools_Task: [Function],
  AcquireMksTicket: [Function],
  AcquireTicket: [Function],
  SetScreenResolution: [Function],
  DefragmentAllDisks: [Function],
  CreateSecondaryVM_Task: [Function],
  TurnOffFaultToleranceForVM_Task: [Function],
  MakePrimaryVM_Task: [Function],
  TerminateFaultTolerantVM_Task: [Function],
  DisableSecondaryVM_Task: [Function],
  EnableSecondaryVM_Task: [Function],
  SetDisplayTopology: [Function],
  StartRecording_Task: [Function],
  StopRecording_Task: [Function],
  StartReplaying_Task: [Function],
  StopReplaying_Task: [Function],
  PromoteDisks_Task: [Function],
  CreateScreenshot_Task: [Function],
  QueryChangedDiskAreas: [Function],
  QueryUnownedFiles: [Function],
  reloadVirtualMachineFromPath_Task: [Function],
  QueryFaultToleranceCompatibility: [Function],
  TerminateVM: [Function],
  RemoveAlarm: [Function],
  ReconfigureAlarm: [Function],
  CreateAlarm: [Function],
  GetAlarm: [Function],
  AreAlarmActionsEnabled: [Function],
  EnableAlarmActions: [Function],
  GetAlarmState: [Function],
  AcknowledgeAlarm: [Function],
  ReconfigureDVPortgroup_Task: [Function],
  DVPortgroupRollback_Task: [Function],
  QueryAvailableDvsSpec: [Function],
  QueryCompatibleHostForNewDvs: [Function],
  QueryCompatibleHostForExistingDvs: [Function],
  QueryDvsCompatibleHostSpec: [Function],
  QueryDvsFeatureCapability: [Function],
  QueryDvsByUuid: [Function],
  QueryDvsConfigTarget: [Function],
  QueryDvsCheckCompatibility: [Function],
  RectifyDvsOnHost_Task: [Function],
  DVSManagerExportEntity_Task: [Function],
  DVSManagerImportEntity_Task: [Function],
  DVSManagerLookupDvPortGroup: [Function],
  UpdateDVSLacpGroupConfig_Task: [Function],
  ReadNextEvents: [Function],
  ReadPreviousEvents: [Function],
  RetrieveArgumentDescription: [Function],
  CreateCollectorForEvents: [Function],
  LogUserEvent: [Function],
  QueryEvents: [Function],
  PostEvent: [Function],
  JoinDomain_Task: [Function],
  JoinDomainWithCAM_Task: [Function],
  ImportCertificateForCAM_Task: [Function],
  LeaveCurrentDomain_Task: [Function],
  ReconfigureAutostart: [Function],
  AutoStartPowerOn: [Function],
  AutoStartPowerOff: [Function],
  QueryBootDevices: [Function],
  UpdateBootDevice: [Function],
  ConfigureHostCache_Task: [Function],
  EnableHyperThreading: [Function],
  DisableHyperThreading: [Function],
  SearchDatastore_Task: [Function],
  SearchDatastoreSubFolders_Task: [Function],
  DeleteFile: [Function],
  UpdateLocalSwapDatastore: [Function],
  QueryAvailableDisksForVmfs: [Function],
  QueryVmfsDatastoreCreateOptions: [Function],
  CreateVmfsDatastore: [Function],
  QueryVmfsDatastoreExtendOptions: [Function],
  QueryVmfsDatastoreExpandOptions: [Function],
  ExtendVmfsDatastore: [Function],
  ExpandVmfsDatastore: [Function],
  CreateNasDatastore: [Function],
  CreateLocalDatastore: [Function],
  RemoveDatastore: [Function],
  RemoveDatastoreEx_Task: [Function],
  ConfigureDatastorePrincipal: [Function],
  QueryUnresolvedVmfsVolumes: [Function],
  ResignatureUnresolvedVmfsVolume_Task: [Function],
  UpdateDateTimeConfig: [Function],
  QueryAvailableTimeZones: [Function],
  QueryDateTime: [Function],
  UpdateDateTime: [Function],
  RefreshDateTimeSystem: [Function],
  QueryAvailablePartition: [Function],
  SelectActivePartition: [Function],
  QueryPartitionCreateOptions: [Function],
  QueryPartitionCreateDesc: [Function],
  CreateDiagnosticPartition: [Function],
  EsxAgentHostManagerUpdateConfig: [Function],
  UpdateDefaultPolicy: [Function],
  EnableRuleset: [Function],
  DisableRuleset: [Function],
  UpdateRuleset: [Function],
  RefreshFirewall: [Function],
  ResetFirmwareToFactoryDefaults: [Function],
  BackupFirmwareConfiguration: [Function],
  QueryFirmwareConfigUploadURL: [Function],
  RestoreFirmwareConfiguration: [Function],
  RefreshGraphicsManager: [Function],
  IsSharedGraphicsActive: [Function],
  RefreshHealthStatusSystem: [Function],
  ResetSystemHealthInfo: [Function],
  HostImageConfigGetAcceptance: [Function],
  HostImageConfigGetProfile: [Function],
  UpdateHostImageAcceptanceLevel: [Function],
  QueryVnicStatus: [Function],
  QueryPnicStatus: [Function],
  QueryBoundVnics: [Function],
  QueryCandidateNics: [Function],
  BindVnic: [Function],
  UnbindVnic: [Function],
  QueryMigrationDependencies: [Function],
  QueryModules: [Function],
  UpdateModuleOptionString: [Function],
  QueryConfiguredModuleOptionString: [Function],
  CreateUser: [Function],
  UpdateUser: [Function],
  CreateGroup: [Function],
  RemoveUser: [Function],
  RemoveGroup: [Function],
  AssignUserToGroup: [Function],
  UnassignUserFromGroup: [Function],
  ReconfigureServiceConsoleReservation: [Function],
  ReconfigureVirtualMachineReservation: [Function],
  UpdateNetworkConfig: [Function],
  UpdateDnsConfig: [Function],
  UpdateIpRouteConfig: [Function],
  UpdateConsoleIpRouteConfig: [Function],
  UpdateIpRouteTableConfig: [Function],
  AddVirtualSwitch: [Function],
  RemoveVirtualSwitch: [Function],
  UpdateVirtualSwitch: [Function],
  AddPortGroup: [Function],
  RemovePortGroup: [Function],
  UpdatePortGroup: [Function],
  UpdatePhysicalNicLinkSpeed: [Function],
  QueryNetworkHint: [Function],
  AddVirtualNic: [Function],
  RemoveVirtualNic: [Function],
  UpdateVirtualNic: [Function],
  AddServiceConsoleVirtualNic: [Function],
  RemoveServiceConsoleVirtualNic: [Function],
  UpdateServiceConsoleVirtualNic: [Function],
  RestartServiceConsoleVirtualNic: [Function],
  RefreshNetworkSystem: [Function],
  CheckHostPatch_Task: [Function],
  ScanHostPatch_Task: [Function],
  ScanHostPatchV2_Task: [Function],
  StageHostPatch_Task: [Function],
  InstallHostPatch_Task: [Function],
  InstallHostPatchV2_Task: [Function],
  UninstallHostPatch_Task: [Function],
  QueryHostPatch_Task: [Function],
  Refresh: [Function],
  UpdatePassthruConfig: [Function],
  ConfigurePowerPolicy: [Function],
  UpdateServicePolicy: [Function],
  StartService: [Function],
  StopService: [Function],
  RestartService: [Function],
  UninstallService: [Function],
  RefreshServices: [Function],
  ReconfigureSnmpAgent: [Function],
  SendTestNotification: [Function],
  RetrieveDiskPartitionInfo: [Function],
  ComputeDiskPartitionInfo: [Function],
  ComputeDiskPartitionInfoForResize: [Function],
  UpdateDiskPartitions: [Function],
  FormatVmfs: [Function],
  MountVmfsVolume: [Function],
  UnmountVmfsVolume: [Function],
  MountVmfsVolumeEx_Task: [Function],
  UnmountVmfsVolumeEx_Task: [Function],
  DeleteVmfsVolumeState: [Function],
  RescanVmfs: [Function],
  AttachVmfsExtent: [Function],
  ExpandVmfsExtent: [Function],
  UpgradeVmfs: [Function],
  UpgradeVmLayout: [Function],
  QueryUnresolvedVmfsVolume: [Function],
  ResolveMultipleUnresolvedVmfsVolumes: [Function],
  ResolveMultipleUnresolvedVmfsVolumesEx_Task: [Function],
  UnmountForceMountedVmfsVolume: [Function],
  RescanHba: [Function],
  RescanAllHba: [Function],
  UpdateSoftwareInternetScsiEnabled: [Function],
  UpdateInternetScsiDiscoveryProperties: [Function],
  UpdateInternetScsiAuthenticationProperties: [Function],
  UpdateInternetScsiDigestProperties: [Function],
  UpdateInternetScsiAdvancedOptions: [Function],
  UpdateInternetScsiIPProperties: [Function],
  UpdateInternetScsiName: [Function],
  UpdateInternetScsiAlias: [Function],
  AddInternetScsiSendTargets: [Function],
  RemoveInternetScsiSendTargets: [Function],
  AddInternetScsiStaticTargets: [Function],
  RemoveInternetScsiStaticTargets: [Function],
  EnableMultipathPath: [Function],
  DisableMultipathPath: [Function],
  SetMultipathLunPolicy: [Function],
  QueryPathSelectionPolicyOptions: [Function],
  QueryStorageArrayTypePolicyOptions: [Function],
  UpdateScsiLunDisplayName: [Function],
  DetachScsiLun: [Function],
  DetachScsiLunEx_Task: [Function],
  DeleteScsiLunState: [Function],
  AttachScsiLun: [Function],
  AttachScsiLunEx_Task: [Function],
  RefreshStorageSystem: [Function],
  DiscoverFcoeHbas: [Function],
  MarkForRemoval: [Function],
  FormatVffs: [Function],
  ExtendVffs: [Function],
  DestroyVffs: [Function],
  MountVffsVolume: [Function],
  UnmountVffsVolume: [Function],
  DeleteVffsVolumeState: [Function],
  RescanVffs: [Function],
  QueryAvailableSsds: [Function],
  ConfigureVFlashResourceEx_Task: [Function],
  HostConfigureVFlashResource: [Function],
  HostRemoveVFlashResource: [Function],
  HostConfigVFlashCache: [Function],
  HostGetVFlashModuleDefaultConfig: [Function],
  UpdateIpConfig: [Function],
  SelectVnic: [Function],
  DeselectVnic: [Function],
  QueryNetConfig: [Function],
  SelectVnicForNicType: [Function],
  DeselectVnicForNicType: [Function],
  QueryCmmds: [Function],
  QueryPhysicalVsanDisks: [Function],
  QueryVsanObjects: [Function],
  QueryObjectsOnPhysicalVsanDisk: [Function],
  QueryDisksForVsan: [Function],
  AddDisks_Task: [Function],
  InitializeDisks_Task: [Function],
  RemoveDisk_Task: [Function],
  RemoveDiskMapping_Task: [Function],
  UpdateVsan_Task: [Function],
  QueryHostStatus: [Function],
  QueryOptions: [Function],
  UpdateOptions: [Function],
  CheckCompliance_Task: [Function],
  QueryComplianceStatus: [Function],
  ClearComplianceStatus: [Function],
  QueryExpressionMetadata: [Function],
  RetrieveDescription: [Function],
  DestroyProfile: [Function],
  AssociateProfile: [Function],
  DissociateProfile: [Function],
  CheckProfileCompliance_Task: [Function],
  ExportProfile: [Function],
  CreateProfile: [Function],
  QueryPolicyMetadata: [Function],
  FindAssociatedProfile: [Function],
  UpdateClusterProfile: [Function],
  UpdateReferenceHost: [Function],
  UpdateHostProfile: [Function],
  ExecuteHostProfile: [Function],
  ApplyHostConfig_Task: [Function],
  GenerateConfigTaskList: [Function],
  GenerateHostProfileTaskList_Task: [Function],
  QueryHostProfileMetadata: [Function],
  QueryProfileStructure: [Function],
  CreateDefaultProfile: [Function],
  UpdateAnswerFile_Task: [Function],
  RetrieveAnswerFile: [Function],
  RetrieveAnswerFileForProfile: [Function],
  ExportAnswerFile_Task: [Function],
  CheckAnswerFileStatus_Task: [Function],
  QueryAnswerFileStatus: [Function],
  RemoveScheduledTask: [Function],
  ReconfigureScheduledTask: [Function],
  RunScheduledTask: [Function],
  CreateScheduledTask: [Function],
  RetrieveEntityScheduledTask: [Function],
  CreateObjectScheduledTask: [Function],
  RetrieveObjectScheduledTask: [Function],
  OpenInventoryViewFolder: [Function],
  CloseInventoryViewFolder: [Function],
  ModifyListView: [Function],
  ResetListView: [Function],
  ResetListViewFromView: [Function],
  DestroyView: [Function],
  CreateInventoryView: [Function],
  CreateContainerView: [Function],
  CreateListView: [Function],
  CreateListViewFromView: [Function],
  RevertToSnapshot_Task: [Function],
  RemoveSnapshot_Task: [Function],
  RenameSnapshot: [Function],
  ExportSnapshot: [Function],
  CheckCompatibility_Task: [Function],
  QueryVMotionCompatibilityEx_Task: [Function],
  CheckMigrate_Task: [Function],
  CheckRelocate_Task: [Function],
  ValidateCredentialsInGuest: [Function],
  AcquireCredentialsInGuest: [Function],
  ReleaseCredentialsInGuest: [Function],
  MakeDirectoryInGuest: [Function],
  DeleteFileInGuest: [Function],
  DeleteDirectoryInGuest: [Function],
  MoveDirectoryInGuest: [Function],
  MoveFileInGuest: [Function],
  CreateTemporaryFileInGuest: [Function],
  CreateTemporaryDirectoryInGuest: [Function],
  ListFilesInGuest: [Function],
  ChangeFileAttributesInGuest: [Function],
  InitiateFileTransferFromGuest: [Function],
  InitiateFileTransferToGuest: [Function],
  StartProgramInGuest: [Function],
  ListProcessesInGuest: [Function],
  TerminateProcessInGuest: [Function],
  ReadEnvironmentVariableInGuest: [Function] }