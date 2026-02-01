# AWS EC2 & EBS Snapshot Demo

## Objective
Launch EC2 instances (Linux and Windows), attach a 5 GB EBS volume, take a snapshot, and create a new volume from the snapshot.

## Tech Stack
- AWS EC2
- AWS EBS

## Steps Performed
1. Launched Amazon Linux EC2 instance
2. Launched Windows EC2 instance
3. Created 5 GB EBS volume
4. Attached volume to Linux and Windows
5. Formatted and mounted volume on Linux
6. Initialized disk on Windows
7. Created EBS snapshot
8. Created new volume from snapshot

## Verification
- Linux: `df -h`
- Windows: Disk Management

## Author
Ashok Kumar

