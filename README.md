# System-Design
1. Scalling:
  - Vertical Scalling: Getting bigger server
  - Horizontal Scalling: Increasing server count.
2. Backup:
  - Cold Standby: Periodic data backup, when one down, manually turn on other one.
  - Warm Standby: Instant backup. Backing up data instantly in backup DB. When one down, change the hit-point.
  - Hot Standby: Write data in both DB. When onw down, no need to do anything, autometically that path will be inactive.

  
