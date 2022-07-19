# Contribution Guide

### Intro

Unlike most contribtion guides this one is not about THIS repo! It's about how you can contribute in general to the Backbase Open Source Community.

Our goal at backbase is allow everyone to share and benefit plus accelerate from our community of engineers. You can read more about our principles and culture of inner sourcing at our [engineering blog] (https://engineering.backbase.com/principles/). That's about how we work within Backbase, but these principles translate to how as much as posible we would like to share openly and use our Backbase Github as the one place you can find open source code.

### Topics

* Repos Naming conventions and standards
* Support and Licence agreements
* Governanace and maitainance
* Contacts


## Repos Naming conventions and standards

We have many repo's that indend to solve a vast varety of problems from solutions like our own internal tools like the **engineering blog** to customer facing acceleration like **stream services**. As such understanding at a glance what repo is for can be very use if we have a convenion.

### Community Product Extentions

Are repo that are to be reused across multiple projects to accellerate the customer but are not offically supported by Backbase. It is possible this extentions will be adopted in to offical support in the future and thus made compliant with Backbase standards. But as a community edition any customer is free to take as is or customise to fit thier needs. Often extention work with API's of the Engagment Banking platofrm and as such are compatible with certain version. These extensions can be of various pouposes some of which we categories:

* Community Connector?? - <fintech-name>-commnity-connector e.g. **twillio-commnity-connector**
* Community Journey?? -  <journey-name>-community-journey e.g. **share-payment-qr-code-community-journey**
* Community Integration?? - <integration-name>-community-integrtion e.g. **mambu-core-community-integrtion**
  
In some cases you may consider you product extention to be regional, this is not the case with open source. Regional markets will change and vendors will expand. What is only applicable to on part of the world at the time of building will change. As such do not specific in the naming an defniition of being local to one area. Part of our ecosystem my wish to build more flexibility into a capability so that is it will become universal.
  
### Open Source Projects

Are tools, samples and demos that are often intially built by Backbase R&D or Customer Success but can also be on project. They are they not an extention to the platform but would be used in projects often as a technology or accelerator to solve a problem and improve the developer experaince. Such repos are often not bound to a single version of thier Engaement Banking Platform and have an independant Semver version to the EBP. Some examples:

* Tools - stream-services, backbase-openapi-tools, bb-fuel, backbase-services-toolkit, generator-springboot, variants
* Examples and samples - Golden Samples App, Golden Sample Servive, documentation-code-samples, WhatsNewJourney, arrangement-behaviour-extension, payments-batch-integration-sample, access-control-service-extension, positive-pay-extension
* Demos, POC's and trainings - backbase-plaid-poc, bb-k8s-operator, twilio-integration-service, mx-integration-transactions, mambu-integration-service, saltedge-integration-service, fiserv-integration-bill-pay

When naming of these open source projects it is recommended to include the following as a suffix: **tool**, **poc**, **demo**, **sample**, **training**
  
### Open Source Product
  
Watch this space, we're looking into how we can share parts of our offical product to a wider community.
  
## Support and Licence agreements
  
### Support  
If you are using a Community product extention or an Open Source Project all these projects are not part of Backbase's offical supported licence agreement and support from Backbase will be on a good will basis or can be arranged as part of a project.
  
Open Source Product must follow the normal support channels if you require support to follow the SLA commitments. Opening issues via github or making pull requests is not part of an SLA.

### Licence agreements
  
Community product extention or an Open Source Projects should contain a standard open source backbase licenece any repo missing this should be assumed to be using the same agreement. Exmample of such licence: https://github.com/Backbase/stream-services/blob/master/LICENSE.txt
  
Not repo should contain MIT licences of any other types.

Open Source Product will be licenced with a diferent agreement.



