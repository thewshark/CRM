# ManageSoft CRM

The ManageSoft CRM is designed so you can manage all your company aspects, accounts, projects, processes, interventions, etc...

- All configurations come from our licensing server thru an encrypted connection so no security breaches happen.
- All bus reporting is made thru the Microsoft APP Center for better reporting.
- Available for Windows (UWP), Android and iOS.


## CRM General Modules

- MyAccount
- Agenda
- Projects
- Documents
- Immobilized
- Tickets
- Products
- Projects
- Archive


## CRM Administrator Exclusive Modules

- Accounts
- Applications
- Licenses
- Devices
- Logs
- Notifications
- Parameters
- Files


## Application Global Functions

| Global Action | Description | Error Address|
| ------ | ------ | ------ |
|CRM_GAS_api_create_provisory_account|Creates a provisory account on the CRM. It will be created with the inactive status so it can be confirmed by the administrator.|1000|
|CRM_GAS_api_exec_http_request|Executes an HTTP request to the API.|1000|
|CRM_GAS_api_get_account_id|Gets the account id so it can be used thru all the application.|1000|
|CRM_GAS_api_get_database_profile_parameters|Gets the parameters from a specified profile.||
|CRM_GAS_api_get_mis_profile_parameters|Gets the parameters from a specified profile.||
|CRM_GAS_api_register_device|Register the device on the platform.||
|CRM_GAS_api_reset_account_password|Resets the account password using a defined password by the application||
|CRM_GAS_api_send_email|Sends an email to a given email.||
|CRM_GAS_api_verify_application_ip_banned|Verifies if an application id/ip is banned.||
|CRM_GAS_api_verify_if_email_exists|Verifies if a given email exists.||
|CRM_GAS_api_verify_if_username_exists|Verifies if a given username exists.||
|CRM_GAS_api_verify_license_credentials|Verifies a given license credentials.||
|CRM_GAS_api_verify_license_expire_date|Verifies the expire date from a given license.||
|CRM_GAS_api_verify_license_expire_in_days|Verifies how many days are yet available on a license.||
|CRM_GAS_api_verify_login_credentials|Verifies a given login credentials.||
|CRM_GAS_api_verify_recover_password_data|Verifies if a given account information is valid for a password reset.||
|CRM_GAS_appplication_load|Loads all the initial parameters from the application.||
|CRM_GAS_decrypt|Decrypts a given value.||
|CRM_GAS_encrypt|Encrypts a given value.||
|CRM_GAS_generate_json_from_temp_table|Generates a JSON from the temp table.||
|CRM_GAS_load_database_profile|Loads a database profile.||
|CRM_GAS_load_mis_profile|Loads a MIS profile||
|CRM_GAS_log_event|Logs an event.||
|CRM_GAS_test_internet_access|Tests if the application as internet access.||



> Note: `--capt-add=SYS-ADMIN` is required for PDF rendering.