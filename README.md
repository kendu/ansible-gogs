# Gogs ansible role
Gogs ansible role installs and configures  [gogs](https://gogs.io/)

## Gogs

### Mandatory variables

* gogs_username - system user gogs should run under
* gogs_home - gogs user home directory
* gogs_database_name - database with this name is created if it doesn't exist
* gogs_database_user - database user with this name is created if it doesn't exist
* gogs_database_password_file - File with the mysql user password
* gogs_database_host
* gogs_title - Gogs site title
* gogs_url - Url under which gogs will be available(without schema)
* gogs_port - port on which gogs service wil run locally
* gogs_ssl_cert - ssl certificate path
* gogs_ssl_key - ssl key path

### Optional variables

* gogs_github_oauth - boolean ("true"/"false") should github oauth be used
* gogs_google_oauth  - boolean ("true"/"false") should google oauth be used
* gogs_github_oauth_client_id
* gogs_github_oauth_client_secret
* gogs_google_oauth_client_id
* gogs_google_oauth_client_secret
