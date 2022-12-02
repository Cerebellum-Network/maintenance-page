# Maintenance

This is a Cere maintenance page which can be setup and enabled for any UI application.

## Add an application to Github actions

1. Create  an `<app>-<env>.yaml` workflow file separatelly for each environment.
2. In the `<app>-<env>.yaml` write your team name to show it on the maintenance page.
3. Add app secrets `<APP>_S3_BUCKET_NAME_DEV`, `<APP>_CF_DISTRIBUTION_ID_DEV` for this repository.  
3. Create, approve and merge a PR into `dev-cere` branch.

## Enable maintenance mode

1. Run your application workflow in [GitHub Actions](https://github.com/Cerebellum-Network/maintenance-page/actions).

## Disable maintenance mode

1. Re-deploy your original application.