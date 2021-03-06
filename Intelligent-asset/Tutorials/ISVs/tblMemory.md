---
title: in.tblMemory - UI Input Schema
description: Input Schema of Table in.tblMemory, shows the data points and types included on this table.
---
# in.tblMemory - Input Schema Table

Physical/Virtual Memory per Device.​

| Name          | Data Type     | Mandatory | Key                   | Comment                                 |
|---------------|---------------|-----------|-----------------------|-----------------------------------------|
| DataSourceId  | varchar(​​32)   | Y         |                       | Unique ID of the source of this record. |
| SrcDeviceId   | nvarchar(128) | Y         | FK > tblDevices.SrcId | Device this RAM is installed in.        |
| DeviceLocator | nvarchar(256) | Y         |                       | Win32_PhysicalMemory.DeviceLocator      |
| CapacityMB    | bigint        |           |                       |                                         |
| DataWidth     | int           |           |                       |                                         |