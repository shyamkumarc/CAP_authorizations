# SAP CAP Nodejs Authorisation example
All credits to : https://github.com/jowavp/SAP-CAPM-Nodejs-Authorisation-example

Only minor corrections in Package.json of SRV and root folders : this was to accomodate the node and  CDS version  dependancy errors while building the app locally (in case of CDS) and while deploying(in case of node) .

The blog for this code can be found in : https://blogs.sap.com/2019/10/24/test-your-cap-nodejs-applications-with-authentication-locally/

And note that the blog doesnt speak of adding the roles specific to this app  to a role collection and  assigning it to a user , which is covered pretty clear in 
the CAP official documentation  : https://cap.cloud.sap/docs/node.js/authentication#jwt (section : Set Up the Roles for the Application )
