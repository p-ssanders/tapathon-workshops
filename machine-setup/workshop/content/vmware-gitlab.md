Confirm you have access to VMware's GitLab instance, as we'll be using that for source control.

Browse to [https://gitlab.eng.vmware.com/](https://gitlab.eng.vmware.com/)

If you can't login, let us know.

Once you log in, ensure you have an [SSH key setup](https://gitlab.eng.vmware.com/-/profile/keys) that you can use to interact with repositories.

If you don't have one setup, follow [the instructions](https://gitlab.eng.vmware.com/help/user/ssh.md#generate-an-ssh-key-pair) to create one. We recommend adding your key to `~/.ssh/` and naming it "vmware-gitlab" to distinguish it from others that may already exist.

You might have to add an entry to your `~/.ssh/config` file:

    ```
    IdentityFile ~/.ssh/vmware-gitlab
    ```