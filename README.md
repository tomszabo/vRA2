# vRA2
New vRA template repo.  These blueprints MUST work.

Starting a new repo for known good templates.  Please notify of any issues found.

Template list:
- Multi-Cloud-Simple - A cloud agnostic template that deploys an Ubuntu18 image to GCP or vSphere based on inputs.  Can be adapted to deploy to other providers, image types, etc.
- Ubuntu16 - A vSphere based template that deploys an Ubuntu16 image and creates a user named 'tom2' and uses a private key for authentication.  Note you need a working Ubuntu16 image with cloud init and a private key.  The username and password inputs are not being used.
