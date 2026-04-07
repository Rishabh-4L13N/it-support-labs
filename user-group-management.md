# User & Group Management Lab (Active Directory)

## Objective
To create and manage users, organizational units (OUs), and security groups in Active Directory, and apply basic access control.

## Lab Setup
- Windows Server 2022 (Domain Controller)
- Domain: lab.local
- Tools: Active Directory Users and Computers (ADUC)

## Steps Performed

### 1. Created Organizational Units (OUs)
- IT
- HR

### 2. Created Users
- john (IT)
- support1 (IT)
- emily (HR)

### 3. Moved Users into OUs
- IT → john, support1
- HR → emily

### 4. Created Security Groups
- IT Support (inside IT OU)
- HR Team (inside HR OU)

### 5. Added Users to Groups
- john, support1 → IT Support
- emily → HR Team

### 6. Created Shared Folders
- C:\IT-shared
- C:\HR-shared

### 7. Configured Permissions

#### IT Folder:
- IT Support → Full Control

#### HR Folder:
- HR Team → Full Control

### 8. Testing
- Logged in as different users
- Verified:
  - IT users can access IT folder
  - HR users can access HR folder
  - Access restrictions working correctly

## Outcome
Successfully implemented user management, group-based access control, and folder permissions using Active Directory.

## Skills Demonstrated
- Active Directory (ADUC)
- User & Group Management
- Organizational Units (OU)
- NTFS Permissions
- Access Control
- Troubleshooting login & permission issues
