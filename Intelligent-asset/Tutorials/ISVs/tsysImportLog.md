---
title: in.tsysImportLog - UI Input Schema
description: Input Schema of Table in.tsysImportLog, shows the data points and types included on this table.
---
# in.tsysImportLog - Input Schema Table

Import process results. Read-only.

| Name   | Data Type   | Mandatory | Key | Comment                                                                                                             |
|--------|-------------|-----------|-----|---------------------------------------------------------------------------------------------------------------------|
| ID     | int         | Y         |     | Unique ID.                                                                                                          |
| Start  | datetime    | Y         |     | Date and time this Import started.                                                                                  |
| End    | datetime​​    |           |     | Date and time this Import ended.                                                                                    |
| Status | varchar(16) |           |     | Possible Values:<br/>"Failed" - the import process failed and was rolled back.<br/>"Finished"- The import process succeeded. |