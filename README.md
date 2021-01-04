首云Open API目录
=================

   * [首云公开API文档](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#%E9%A6%96%E4%BA%91%E5%85%AC%E5%BC%80api%E6%96%87%E6%A1%A3)
     * [认证方式](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#认证方式)
       * [1.公共请求参数](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#1公共请求参数)
       * [2.签名机制](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#2签名机制)
         * [步骤一：构造规范化请求字符串](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#步骤一构造规范化请求字符串)
         * [步骤二：构造签名字符串](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#步骤二构造签名字符串)
       * [3.获取签名代码](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#2获取签名代码)
     * [访问地址](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#访问地址)
     * [实例相关](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#实例相关)
       * [1.CreateInstance](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#1createinstance)
       * [2.DeleteInstance](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#2deleteinstance)
       * [3.StopInstance](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#3stopinstance)
       * [4.RebootInstance](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#4rebootinstance)
       * [5.ModifyInstanceChargeType](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#5modifyinstancechargetype)
       * [6.ModifyInstanceSpec](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#6modifyinstancespec)
       * [7.CreateDisk](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#7createdisk)
       * [8.ResizeDisk](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#8resizedisk)
       * [9.DeleteDisk](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#9deletedisk)
       * [11.DescribeInstances](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#11describeinstances)
       * [12.ConnectNetworkInterface](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#12connectnetworkinterface)
       * [13.DisconnectNetworkInterface](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#13disconnectnetworkinterface)
       * [14.ModifyIpAddress](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#14modifyipaddress)
       * [15.DescribeInstanceMonitor](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#15describeinstancemonitor)
       * [16.StartInstance](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#16startinstance)
       * [17.ModifyInstanceName](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#17modifyinstancename)
       * [18.DescribeTags](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#18describetags)
       * [19.CreateTag](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#19createtag)
       * [20.DeleteTag](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#20deletetag)
       * [21.AddInstancesTags](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#21addinstancestags)
       * [22.DeleteInstancesTags](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#22deleteinstancestags)
       * [23.DescribeInstanceType](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#23DescribeInstanceType)
       * [24.DescribePublicIp](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#24DescribePublicIp)
       * [25.DescribePrivateIp](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#25DescribePrivateIp)
       * [26.ResetInstancesPassword](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#26ResetInstancesPassword)
       * [27.CreateInstanceHtmlConsoleURL](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#27CreateInstanceHtmlConsoleURL)
       * [28.ExtendSystemDisk](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#28ExtendSystemDisk)
       * [29.DescribeInstancePrice](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#29DescribeInstancePrice)
       * [30.StopInstances](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#30StopInstances)
       * [31.StartInstances](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#31StartInstances)
       * [32.RebootInstances](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#32RebootInstances)
       * [33.BatchAddNetworkInterfaces](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#33BatchAddNetworkInterfaces)
       * [34.BatchDeleteNetworkInterfaces](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#34BatchDeleteNetworkInterfaces)

     * [安全组相关](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#安全组相关)
       * [1.CreateSecurityGroup](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#1createsecuritygroup)
       * [2.DeleteSecurityGroup](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#2deletesecuritygroup)
       * [3.ForceDeleteSecurityGroup](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#3forcedeletesecuritygroup)
       * [4.DescribeSecurityGroupAttribute](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#4describesecuritygroupattribute)
       * [5.ModifySecurityGroupAttribute](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#5modifysecuritygroupattribute)
       * [6.DescribeSecurityGroups](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#6describesecuritygroups)
       * [7.AddSecurityGroupRule](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#7addsecuritygrouprule)
       * [8.RemoveSecurityGroupRule](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#8removesecuritygrouprule)
       * [9.ModifySecurityGroupRule](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#9modifysecuritygrouprule)
       * [10.JoinSecurityGroup](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#10joinsecuritygroup)
       * [11.LeaveSecurityGroup](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#11leavesecuritygroup)
       * [12.ModifySecurityGroupRulePriority](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#12modifysecuritygrouprulepriority)
     * [模板相关](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#模板相关)
       * [1.CreateTemplate](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#1createtemplate)
       * [2.DeleteTemplate](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#2deletetemplate)
       * [3.SyncTemplate](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#3synctemplate)
       * [4.DescribeTemplateInfo](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#4describetemplateinfo)
     * [虚拟数据中心相关](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#虚拟数据中心相关)
       * [1.DescribeVdc](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#1describevdc)
       * [2.CreateVdc](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#2createvdc)
       * [3.DeleteVdc](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#3deletevdc)
       * [4.CreatePublicNetwork](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#4createpublicnetwork)
       * [5.CreatePrivateNetwork](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#5createprivatenetwork)
       * [6.ModifyPublicNetwork](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#6modifypublicnetwork)
       * [7.AddPublicIp](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#7addpublicip)
       * [8.DeletePublicIp](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#8deletepublicip)
       * [9.DeletePublicNetwork](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#9deletepublicnetwork)
       * [10.DeletePrivateNetwork](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#10deleteprivatenetwork)
       * [11.RenewPublicNetwork](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#11renewpublicnetwork)
       * [12.DescribeBandwidthTraffic](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#12describebandwidthtraffic)
       * [13.DescribeGPN](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#13describegpn)
       * [14.AddAccessPoint](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#14addaccesspoint)
       * [15.DeleteAccessPoint](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#15deleteaccesspoint)
       * [16.DescribeAccessInfo](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#16describeaccessinfo)
       * [17.CreateGPN](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#17creategpn)
       * [18.DeleteGPN](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#18deletegpn)
       * [19.ModifyVdcName](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#19modifyvdcname)
     * [裸金属相关](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#裸金属相关)
       * [1.DescribeBmsGoods](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#1describebmsgoods)
       * [2.DescribeBmsGoodsPrice](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#2describebmsgoodsprice)
       * [3.DescribeBmsImage](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#3describebmsimage)
       * [4.CreateBmsInstance](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#4createbmsinstance)
       * [5.DescribeBms](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#5describebms)
       * [6.DescribeBmsDetail](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#6describebmsdetail)
       * [7.OperateBmsPower](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#7operatebmspower)
       * [8.ReinstallBms](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#8ReinstallBms)
       * [9.DescribeBmsVNC](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#9describebmsvnc)
       * [10.ModifyBmsOrder](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#10modifybmsorder) 
     * [裸金属云盘相关](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#裸金属云盘相关)
       * [1.CreateDisk](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#1createDisk)
       * [2.AttachDisk](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#2attachDisk)
       * [3.DetachDisk](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#3detachDisk)
       * [4.DeleteDisk](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#4deleteDisk)
       * [5.DescribeDisks](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#5describeDisks)
       * [6.DescribeDiskUsage](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#6describeDiskUsage)
       * [7.DescribePoolUsage](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#7describePoolUsage)
       * [8.ChangeIops](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#8changeIops)
       * [9.ChangeBandwidth](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#9changeBandwidth)
       * [10.ExpansionSize](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#10expansionSize) 
       * [11.CreateSnapshot](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#11createSnapshot) 
       * [12.CloneSnapshot](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#12cloneSnapshot) 
       * [13.DeleteSnapshot](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#13deleteSnapshot) 
       * [14.RollbackSnapshot](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#14rollbackSnapshot) 
       * [15.DescribeGoodsId](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#15describeGoodsId) 
     * [账单相关](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#账单相关)
       * [1.DescribeBill](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#1describebill)
       * [2.DescribeBillInfo](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#2describebillinfo)
     * [冷云计量相关](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#冷云计量相关)
       * [1.GetMetering](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#1GetMetering)
     * [MySQL相关](https://github.com/capitalonline/openapi/blob/master/MySQL%E6%A6%82%E8%A7%88.md)
       * [1.DescribeRegions](https://github.com/capitalonline/openapi/blob/master/MySQL%E6%A6%82%E8%A7%88.md#1describeregions) 
       * [2.DescribeAvailableDBConfig](https://github.com/capitalonline/openapi/blob/master/MySQL%E6%A6%82%E8%A7%88.md#2describeavailabledbconfig) 
       * [3.CreateDBInstance](https://github.com/capitalonline/openapi/blob/master/MySQL%E6%A6%82%E8%A7%88.md#3createdbinstance) 
       * [4.DescribeDBInstances](https://github.com/capitalonline/openapi/blob/master/MySQL%E6%A6%82%E8%A7%88.md#4describedbinstances)
       * [5.CreatePrivilegedAccount](https://github.com/capitalonline/openapi/blob/master/MySQL%E6%A6%82%E8%A7%88.md#5createprivilegedaccount)
       * [6.DescribeModifiableDBSpec](https://github.com/capitalonline/openapi/blob/master/MySQL%E6%A6%82%E8%A7%88.md#6describemodifiabledbspec) 
       * [7.ModifyDBInstanceSpec](https://github.com/capitalonline/openapi/blob/master/MySQL%E6%A6%82%E8%A7%88.md#7modifydbinstancespec) 
       * [8.DeleteDBInstance](https://github.com/capitalonline/openapi/blob/master/MySQL%E6%A6%82%E8%A7%88.md#8deletedbinstance)
       * [9.DescribeAvailableReadOnlyConfig](https://github.com/capitalonline/openapi/blob/master/MySQL%E6%A6%82%E8%A7%88.md#9describeavailablereadonlyconfig) 
       * [10.CreateReadOnlyDBInstance](https://github.com/capitalonline/openapi/blob/master/MySQL%E6%A6%82%E8%A7%88.md#10createreadonlydbinstance)
       * [11.CreateBackup](https://github.com/capitalonline/openapi/blob/master/MySQL%E6%A6%82%E8%A7%88.md#11createbackup)
       * [12.DescribeBackups](https://github.com/capitalonline/openapi/blob/master/MySQL%E6%A6%82%E8%A7%88.md#12describebackups)
       * [13.DeleteBackup](https://github.com/capitalonline/openapi/blob/master/MySQL%E6%A6%82%E8%A7%88.md#13deletebackup)
       * [14.DownloadBackup](https://github.com/capitalonline/openapi/blob/master/MySQL%E6%A6%82%E8%A7%88.md#14downloadbackup)
       * [15.StartBatchRollback](https://github.com/capitalonline/openapi/blob/master/MySQL%E6%A6%82%E8%A7%88.md#15startbatchrollback)
       * [16.DescribeRollbackRangeTime](https://github.com/capitalonline/openapi/blob/master/MySQL%E6%A6%82%E8%A7%88.md#16describerollbackrangetime)
       * [17.StartBatchRollbackToTemporaryDBInstance](https://github.com/capitalonline/openapi/blob/master/MySQL%E6%A6%82%E8%A7%88.md#17startbatchrollbacktotemporarydbinstance)
       * [18.DescribeTemporaryDBInstances](https://github.com/capitalonline/openapi/blob/master/MySQL%E6%A6%82%E8%A7%88.md#18describetemporarydbinstances)
       * [19.RegularizeTemporaryDBInstances](https://github.com/capitalonline/openapi/blob/master/MySQL%E6%A6%82%E8%A7%88.md#19regularizetemporarydbinstances)
       * [20.DeleteTemporaryDBInstances](https://github.com/capitalonline/openapi/blob/master/MySQL%E6%A6%82%E8%A7%88.md#20deletetemporarydbinstances)
     * [Redis相关](https://github.com/capitalonline/openapi/blob/master/Redis%E6%A6%82%E8%A7%88.md)
       * [1.DescribeRegins](https://github.com/capitalonline/openapi/blob/master/Redis%E6%A6%82%E8%A7%88.md#1describeregins)
       * [2.DescribeAvailableDBConfig](https://github.com/capitalonline/openapi/blob/master/Redis%E6%A6%82%E8%A7%88.md#2describeavailabledbconfig)
       * [3.CreateDBInstance](https://github.com/capitalonline/openapi/blob/master/Redis%E6%A6%82%E8%A7%88.md#3createdbinstance) 
       * [4.DescribeDBInstances](https://github.com/capitalonline/openapi/blob/master/Redis%E6%A6%82%E8%A7%88.md#4describedbinstances)
       * [5.DeleteDBInstance](https://github.com/capitalonline/openapi/blob/master/Redis%E6%A6%82%E8%A7%88.md#5deletedbinstance)
       * [6.DescribeBackups](https://github.com/capitalonline/openapi/blob/master/Redis%E6%A6%82%E8%A7%88.md#6describebackups)
       * [7.DownloadBackup](https://github.com/capitalonline/openapi/blob/master/Redis%E6%A6%82%E8%A7%88.md#7downloadbackup)
       * [8.CreateBackup](https://github.com/capitalonline/openapi/blob/master/Redis%E6%A6%82%E8%A7%88.md#8createbackup)
       * [9.DeleteBackup](https://github.com/capitalonline/openapi/blob/master/Redis%E6%A6%82%E8%A7%88.md#9deletebackup)
      * [MongoDB相关](https://github.com/capitalonline/openapi/blob/master/MongoDB%E6%A6%82%E8%A7%88.md)
        * [1.DescribeZones](https://github.com/capitalonline/openapi/blob/master/MongoDB%E6%A6%82%E8%A7%88.md#1describezones)
        * [2.DescribeSpecInfo](https://github.com/capitalonline/openapi/blob/master/MongoDB%E6%A6%82%E8%A7%88.md#2describespecinfo)
        * [3.CreateDBInstance](https://github.com/capitalonline/openapi/blob/master/MongoDB%E6%A6%82%E8%A7%88.md#3createdbinstance)
        * [4.DescribeDBInstances](https://github.com/capitalonline/openapi/blob/master/MongoDB%E6%A6%82%E8%A7%88.md#4describedbinstances)
        * [5.DeleteDBInstance](https://github.com/capitalonline/openapi/blob/master/MongoDB%E6%A6%82%E8%A7%88.md#5deletedbinstance)
      * [新版MongoDB相关](https://github.com/capitalonline/openapi/blob/master/%E6%96%B0%E7%89%88MongoDB%E6%A6%82%E8%A7%88.md)
        * [1.DescribeZones](https://github.com/capitalonline/openapi/blob/master/%E6%96%B0%E7%89%88MongoDB%E6%A6%82%E8%A7%88.md#1describezones)
        * [2.DescribeSpecInfo](https://github.com/capitalonline/openapi/blob/master/%E6%96%B0%E7%89%88MongoDB%E6%A6%82%E8%A7%88.md#2describespecinfo)
        * [3.CreateDBInstance](https://github.com/capitalonline/openapi/blob/master/%E6%96%B0%E7%89%88MongoDB%E6%A6%82%E8%A7%88.md#3createdbinstance)
        * [4.DescribeDBInstances](https://github.com/capitalonline/openapi/blob/master/%E6%96%B0%E7%89%88MongoDB%E6%A6%82%E8%A7%88.md#4describedbinstances)
        * [5.DeleteDBInstance](https://github.com/capitalonline/openapi/blob/master/%E6%96%B0%E7%89%88MongoDB%E6%A6%82%E8%A7%88.md#5deletedbinstance)
      * [HaProxy相关](https://github.com/capitalonline/openapi/blob/master/%E8%B4%9F%E8%BD%BD%E5%9D%87%E8%A1%A1%E6%A6%82%E8%A7%88.md#9describecacertificate)
        * [1.DescribeZones](https://github.com/capitalonline/openapi/blob/master/%E8%B4%9F%E8%BD%BD%E5%9D%87%E8%A1%A1%E6%A6%82%E8%A7%88.md#9describecacertificate#1describezones)
        * [2.DescribeLoadBalancersSpec](https://github.com/capitalonline/openapi/blob/master/%E8%B4%9F%E8%BD%BD%E5%9D%87%E8%A1%A1%E6%A6%82%E8%A7%88.md#9describecacertificate#2describeloadbalancersspec)
        * [3.CreateLoadBalancer](https://github.com/capitalonline/openapi/blob/master/%E8%B4%9F%E8%BD%BD%E5%9D%87%E8%A1%A1%E6%A6%82%E8%A7%88.md#9describecacertificate#3createloadbalancer)
        * [4.DescribeLoadBalancers](https://github.com/capitalonline/openapi/blob/master/%E8%B4%9F%E8%BD%BD%E5%9D%87%E8%A1%A1%E6%A6%82%E8%A7%88.md#9describecacertificate#4describeloadbalancers)
        * [5.DescribeLoadBalancersModifySpec](https://github.com/capitalonline/openapi/blob/master/%E8%B4%9F%E8%BD%BD%E5%9D%87%E8%A1%A1%E6%A6%82%E8%A7%88.md#9describecacertificate#5describeloadbalancersmodifyspec)
        * [6.ModifyLoadBalancerInstanceSpec](https://github.com/capitalonline/openapi/blob/master/%E8%B4%9F%E8%BD%BD%E5%9D%87%E8%A1%A1%E6%A6%82%E8%A7%88.md#9describecacertificate#6modifyloadbalancerinstancespec)
        * [7.DeleteloadBalancer](https://github.com/capitalonline/openapi/blob/master/%E8%B4%9F%E8%BD%BD%E5%9D%87%E8%A1%A1%E6%A6%82%E8%A7%88.md#9describecacertificate#7deleteloadbalancer)
        * [8.DescribeCACertificates](https://github.com/capitalonline/openapi/blob/master/%E8%B4%9F%E8%BD%BD%E5%9D%87%E8%A1%A1%E6%A6%82%E8%A7%88.md#9describecacertificate#8describecacertificates)
        * [9.DescribeCACertificate](https://github.com/capitalonline/openapi/blob/master/%E8%B4%9F%E8%BD%BD%E5%9D%87%E8%A1%A1%E6%A6%82%E8%A7%88.md#9describecacertificate#9describecacertificate)
        * [10.DeleteCACertificate](https://github.com/capitalonline/openapi/blob/master/%E8%B4%9F%E8%BD%BD%E5%9D%87%E8%A1%A1%E6%A6%82%E8%A7%88.md#9describecacertificate#10deletecacertificate)
        * [11.UploadCACertificate](https://github.com/capitalonline/openapi/blob/master/%E8%B4%9F%E8%BD%BD%E5%9D%87%E8%A1%A1%E6%A6%82%E8%A7%88.md#9describecacertificate#11uploadcacertificate)
        * [12.DescribeLoadBalancerStrategys](https://github.com/capitalonline/openapi/blob/master/%E8%B4%9F%E8%BD%BD%E5%9D%87%E8%A1%A1%E6%A6%82%E8%A7%88.md#9describecacertificate#describeloadbalancerstrategys)
        * [13.ModifyLoadBalancerStrategys](https://github.com/capitalonline/openapi/blob/master/%E8%B4%9F%E8%BD%BD%E5%9D%87%E8%A1%A1%E6%A6%82%E8%A7%88.md#9describecacertificate#modifyloadbalancerstrategys)
     * [其他公共接口](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#其他公共接口)
       * [1.DescribeAvailableResource](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#1describeavailableresource)
       * [2.DescribeTask](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#2describetask)
     * [附件一](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#附件一)
           * [可用区名称](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#可用区名称)
     * [附件二](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#附件二)
           * [主机类型](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#主机类型)
     * [附件三](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#附件三)
           * [带宽类型](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#带宽类型)
     * [附件四](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#附件四)
           * [公共模板](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#公共模板)
     * [示例](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#示例)
       * [1.获取请求url](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#1获取请求url)
       * [2.获取虚拟数据中心公网信息](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#2获取虚拟数据中心公网信息)
       * [3.获取机器信息](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#3获取机器信息)
       * [4.创建云主机实例](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#4创建云主机实例)
       * [5.修改公网带宽](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#5修改公网带宽)
       * [6.修改云主机实例计费类型](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#6修改云主机实例计费类型)
       * [7.获取任务状态](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#7获取任务状态)
       * [8.定制模板](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#8定制模板)
