This is an example program showing how to use the native MySQL connections from Google App Engine to Google Cloud SQL.

## Deploying

1. edit the 'application: your-app-id' from app.yaml to point to an app you control. Optionally, edit the 'version: 1' to create the desired version.

2. edit the `unix_socket` from `app.py` and `app_mysql.py` to point to a Cloud SQL instance that is associated with the app you used at step 1.

3. Upload the app: `appcfg.py update .`

## Contributing changes

* See [CONTRIB.md](CONTRIB.md)


## Licensing

* See [LICENSE](LICENSE)
