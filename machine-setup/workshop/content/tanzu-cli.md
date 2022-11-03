Now that you're logged into the VMware Tanzu Network, search for TAP, and navigate to the product page.

Select the version specified by your facilitators from the drop-down. At time of writing, the most recent GA version is 1.3.0.

Follow the [product documentation](https://docs.vmware.com/en/VMware-Tanzu-Application-Platform/1.3/tap/GUID-install-tanzu-cli.html#cli-and-plugin) to install the CLI.

The `login` plugin is not installed by default, so install it:

    ```
    tanzu plugin install login
    ```

Validate the `login` plugin is installed by running `tanzu plugin list`.