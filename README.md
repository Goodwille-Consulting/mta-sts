Feel free to clone for implementing Google Workspace MTA-STS policies.

You'll need to add your own domain as a custom domain in your repository settings...

    First add a CNAME record for 'mta-sts.yourdomain.com' at your DNS provider, pointing to 'YOURGITHUBUSERNAME.github.io'

    Then go to your Repository Settings (not personal account settings) in GitHub.

    If it isn't already, enable GitHub pages for the Master Branch/Root.

    Add your custom domain ('mta-sts.yourdomain.com'), save it and tick the 'Enforce HTTPS' box.

(You might need to wait a few minutes for the Let's Encrypt certificate to be set up properly)

Then edit the mta-sts.txt file in /.well-known/ to your liking!
