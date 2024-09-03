<h1><b>Interactive Pharmacy Management System</b></h1>

<h2>Content</h2>

<h2>Requirement</h2>
<pre>
        1. .NET SDK
        2. Microsoft SQL Server 2019
        3. Visual Studio
</pre>

<h2> Description <h2>

## Role-Based Access Control

The Pharmacy Management System implements role-based access control, ensuring that users have access to the functionalities relevant to their role. There are two primary roles within the system:

### Pharmacist
Pharmacists have access to the following features:
- **Dashboard**: Access a summary of daily activities, including inventory status, recent sales, and alerts for low stock or expiring medicines.
- **Manage Medicines**:
  - **Add Medicine**: Enter new medicines into the system, including details like name, batch number, expiration date, and quantity.
  - **View and Modify Medicines**: Search for medicines in the inventory, update their details, or modify stock levels.
- **Sell Medicines**: Process customer orders, generate invoices, and update inventory in real-time.
- **Log Out**: Securely log out of the system.

### Administrator
Administrators have access to the following features:
- **Dashboard**: Access an overview of system activity, user management, and critical notifications.
- **User Management**:
  - **Add User**: Create new users in the system, assigning them roles and setting their credentials.
  - **View and Modify Users**: Manage existing users, update their details, change roles, or deactivate accounts.
- **Update Personal Profile**: Modify personal information, such as contact details and password.
- **Log Out**: Securely log out of the system.


