# Spiceworks-AD-Ticketing
# Active Directory & Spiceworks Helpdesk Lab

## Project Overview

This project demonstrates a hands-on IT Helpdesk L1 practice environment using Windows Server 2022, Active Directory, Windows 11, and Spiceworks.

The objective is to practice common IT support activities, including user account management, group management, account troubleshooting, and helpdesk ticket handling.

## Lab Environment

| Component | Details |
|---|---|
| Virtualization | VMware Workstation 17 |
| Server OS | Windows Server 2022 |
| Client OS | Windows 11 |
| Domain | `pardhu.local` |
| Directory Service | Active Directory Domain Services |
| Ticketing Tool | Spiceworks |

## Active Directory Configuration

Created and configured a Windows Server 2022 domain environment.

- Set up the Active Directory domain: `pardhu.local`
- Created user accounts for different departments.
- Created security and distribution groups.
- Added users to their respective groups.
- Configured domain user account properties.
- Connected a Windows 11 client to the domain.

### Department Groups

| Group | Group Type |
|---|---|
| IT-Group | Security |
| HR-Group | Distribution |
| Finance Group | Security |

### User Accounts

**IT Department**
- Sai Teja
- Salma Shaik
- Siva Ram

**HR Department**
- Vinay Kumar
- Veera Teja

**Finance Department**
- Vasu Dev
- Vijay Babu

## Spiceworks User Management

Added the Active Directory lab users to the Spiceworks User Management section under the organization `practice`.

The following users were added:

| User | Email |
|---|---|
| Sai Teja | saiteja@pardhu.com |
| Salma Shaik | salmashaik@pardhu.com |
| Siva Ram | sivaram@pardhu.com |
| Vasu Dev | vasudev@pardhu.com |
| Veera Teja | veerateja@pardhu.com |
| Vijay Babu | vijaybabu@pardhu.com |
| Vinay Kumar | vinaykumar@pardhu.com |

## Helpdesk Ticket Practice

Created practice tickets in Spiceworks to simulate real-world IT support requests.

The ticket scenarios include:

1. Create a new IT employee account.
2. Disable an employee account.
3. Unlock a locked Active Directory account.
4. Reset a user's password.
5. Add a user to an Active Directory group.
6. Remove a user from an Active Directory group.


## Practical Tasks Performed

- Disabled the Sai Teja Active Directory account.
- Configured the domain account lockout policy.
- Set the account lockout threshold to 5 attempts.
- Set the lockout duration to 15 minutes.
- Set the observation window to 15 minutes.
- Practiced unlocking a user account and resetting its password.
- Added users to Spiceworks User Management.

## Skills Practiced

- Windows Server 2022 administration
- Active Directory user management
- Security and distribution group management
- Account enable and disable operations
- Password reset and account unlock
- Account lockout policy configuration
- Windows 11 domain joining
- Spiceworks User Management
- Helpdesk ticket creation and resolution documentation

## Project Objective

To gain practical experience with common L1 IT Support and Service Desk activities by building a virtual Windows domain environment and simulating user support requests through a ticketing system.

---

**Tools Used:** VMware Workstation 17 | Windows Server 2022 | Windows 11 | Active Directory | Spiceworks
