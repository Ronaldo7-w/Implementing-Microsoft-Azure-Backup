# Implementing Microsoft Azure Backup

## Objective

Deployed Azure Recovery Service Vault and configured automated backup policies for a Windows Virtual Machine. Implemented weekly, monthly and yearly backup schedules to ensure data redundancy and compliance. 


## Skills Learned

- Creating a Recovery Services Vault on Azure to store the backup.
- Configuring weekly, monthly and yearly backup policies to govern the backup.
- Creating a Windows 11 Virtual Machine on Azure.
- Performing backup on Windows Virtual Machine.

## Azure services Used

- Azure Resource Group
- Azure Recovery Services Vault.
- Used Microsoft Virtual Machine.

## Step 1

Create a Resource Group (azure_backup) and a Recovery Service Vault on Azure to store the backup.

<img width="1918" height="1078" alt="Screenshot 2025-11-18 093031" src="https://github.com/user-attachments/assets/dd92cefd-422f-44be-a545-d84bf8e78cf4" />

## Step 2

Configure an hourly and a weekly, monthly and year backup policies to govern the backup (vaultpolicy and vaultpolicy02).

<img width="1916" height="1074" alt="Screenshot 2025-11-18 094228" src="https://github.com/user-attachments/assets/3994f35d-639c-4122-a002-0b768b63cfae" />

<img width="1914" height="1074" alt="Screenshot 2025-11-18 094737" src="https://github.com/user-attachments/assets/c5a50a1a-76a0-488a-bb00-05e1f47d2e54" />

<img width="1919" height="1079" alt="Screenshot 2025-11-18 095512" src="https://github.com/user-attachments/assets/af5bd4a1-dee0-47cf-99b3-dac6950140db" />


## Step 3 

Create a Windows Virtual Machine on Azure so that I can apply the backup policy (vaultpolicy02).

<img width="1919" height="1079" alt="Screenshot 2025-11-18 101148" src="https://github.com/user-attachments/assets/7ae93f40-822e-4c3a-8e74-fecd2b41da79" />


## Step 4

Applying the backup policy to the Windows Virtual Machine.

<img width="1919" height="1079" alt="Screenshot 2025-11-18 101742" src="https://github.com/user-attachments/assets/da0de0f0-577c-4b22-87bf-f04c4bc17f41" />

<img width="1919" height="1079" alt="Screenshot 2025-11-18 102223" src="https://github.com/user-attachments/assets/3dad48d0-ac47-48f1-8ee6-22b5867dc70b" />

<img width="1919" height="1079" alt="Screenshot 2025-11-18 102759" src="https://github.com/user-attachments/assets/af4d763e-4972-4c68-ba13-145a95101f63" />

