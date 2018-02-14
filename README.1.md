# Send email using Node.js

1. **Make sure you have the prerequisites**
   Our library requires Node.js version 0.10, 0.12, or 4.

2. **Create an API key**
    This allows your application to authenticate to our API and send mail. You can enable or disable additional permissions on the API keys page.

3. **Create an environment variable**
    Update your development environment with your SENDGRID_API_KEY. Run the following in your shell:
    `echo "export SENDGRID_API_KEY='YOUR_API_KEY'" > sendgrid.env`
   `echo "sendgrid.env" >> .gitignore`
   `source ./sendgrid.env`

4. **Install the package**
    The following recommended installation requires npm. If you are unfamiliar with npm, see the npm docs. Npm comes installed with Node.js since node version 0.8.x, therefore you likely already have it: