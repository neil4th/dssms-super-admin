# DSSMS Super Admin - WinUI 3 Application

## Project Overview

The DSSMS Super Admin is a powerful Windows application built with **WinUI 3**. It allows administrators to manage users, access roles, and monitor various system activities.

This application leverages modern UI elements, real-time updates, and offers a responsive design to ensure a smooth user experience.

---

## Features

- **User Management:** Add, update, and remove users.
- **Real-time Notifications:** Receive notifications for system updates.
- **Role Management:** Assign and manage roles for users.
- **Data Visualization:** Integrated data charts to track system metrics (coming soon).
- **Dashboard:** Centralized view of system stats and user activity.

---

## Screenshots

- **Dashboard**

  ![Dashboard](https://utfs.io/f/kjLlKkAq2owL1lN8IzcCqaE2HIThJAl9uPmboiNdVtSGx4Ls)

---

## Design

The DSSMS Super Admin application follows the **MVVM (Model-View-ViewModel)** pattern to separate concerns and ensure maintainability. The UI is designed to be responsive and uses the latest **WinUI 3** features, including:

- **NavigationView** for sidebar navigation
- **ListView** for displaying dynamic data
- **TextBlock** and **Button** controls for interactive UI components
- **Grid** layouts to arrange components seamlessly

---

## Installation Instructions

Follow the steps below to install DSSMS Super Admin using the `.msix` package:

### 1. Download the `.msix` Package

- Go to the **Releases** section of the repository.
- Download the **.msix** file from the **latest release**.

  [Download DSSMS Super Admin v1.0.0 MSIX](https://github.com/neil4th/dssms-super-admin/releases/download/v1.0.0/DSSMS.SuperAdmin_v1.0.0.msix)

### 2. Install the `.msix` Package

#### For Windows 10/11 Users:
1. **Double-click** on the `.msix` file you downloaded.
2. You may be prompted to confirm that you trust the app. If so, click **Install**.
3. Wait for the installation process to complete. Once done, the application will be available in the **Start Menu**.

#### For IT Administrators (Installing via PowerShell):
If you need to deploy the app via PowerShell or remotely, use the following command:

```powershell
Add-AppxPackage -Path "path-to-your-dssms-super-admin.msix"
