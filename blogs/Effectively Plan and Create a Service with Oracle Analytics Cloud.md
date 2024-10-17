# Effectively Plan and Create a Service with Oracle Analytics Cloud
 June 1, 2021 | 4 minute read 
 
 Shounak Ganguly

 With your Oracle Analytics Cloud subscription, you get access to a full set of capabilities to explore and perform collaborative analytics for you, your workgroup, and your enterprise, all managed by Oracle. Before you embark on creating your first Oracle Analytics Cloud service, take a moment to familiarize yourself with some of the settings and deployment options that you’ll be asked to select during the setup process.

You’ll find that the setup will go more smoothly if you ask yourself these questions and decide what you need before you start.

- What should I name my service?
- Do I need to create one or more compartments?
- Which feature set do I need?
- What sizing options are available to me?
- Do I need a public or private endpoint?
## Watch the video!
If you don’t do anything else, watch this video on the Oracle Learning YouTube channel:

Video: [Create a Service with Oracle Analytics Cloud](https://www.youtube.com/watch?v=xSzXHRTAJ8o)

This short video takes you through the steps and provides information to help you make the best choices about compartments, which feature set to use, sizing options, network access, and explains how to choose a suitable name for your service. 

Because everyone works and learns differently, it can be helpful to watch a quick video that shows a process in action.
## Bookmark the step-by-step documentation
Step-by-step information that describes how to create a service is available on Oracle Help Center:

Documentation: [Create Services with Oracle Analytics Cloud](https://docs.oracle.com/en/cloud/paas/analytics-cloud/acoci/create-services.html)

If you don’t want to read this now, bookmark the page in case you get stuck or need it later.
## Plan your service
The [Create a Service with Oracle Analytics Cloud](https://www.youtube.com/watch?v=xSzXHRTAJ8o) video focuses on how to create your service on Oracle Cloud Infrastructure (Gen 2) and highlights the various choices you have to make. We explain the main decision points here too:

|Create Option |Considerations |Change Later |More Information |
|---|---|:---:|---|
|Region|If multiple regions are available to you, you must decide where you want to create your service.|No| [Where Do You Want to Deploy Your Service?](https://docs.oracle.com/en/cloud/paas/analytics-cloud/acoci/create-services.html#GUID-ED3EC816-55C3-4D26-923B-52324555F950)|
|Compartment|Before you create your service, Oracle recommends that you set up the compartment where you want the instance to belong.|Yes|[Create a Compartment](https://docs.oracle.com/en/cloud/paas/analytics-cloud/acoci/create-services.html#GUID-C89E7903-A463-43A0-921B-16E1E60C2CAF)|
|Name|The name you give your service is displayed in the default URL for your service. For example, if you use the name "myanalytics", the URL will look something like this: <https://myanalytics-ia.analytics.ocp.oraclecloud.com/ui>. You can’t change this name later, but you can configure a vanity URL if you wish.|No|[What Name Do You Want for Your Service?](https://docs.oracle.com/en/cloud/paas/analytics-cloud/acoci/create-services.html#GUID-C6195E0C-E147-4184-BF67-3A06C9701672)|
|Feature Set|Oracle Analytics Cloud offers two feature sets: <ul><li> **Self-Service Analytics:** Creates a service that offers data visualization.</li><li>**Enterprise Analytics:** Creates a service that offers enterprise modeling, reporting, and data visualization.</li></ul> |No|[Which Feature Set Do You Need?](https://docs.oracle.com/en/cloud/paas/analytics-cloud/acoci/create-services.html#GUID-C956B196-48AC-4B22-9D8B-97B8D587ACE0)|
|Licensing|Oracle Analytics Cloud offers two licensing options:<ul><li>**License Included:** Select if you subscribe to an Oracle Cloud license for Oracle Analytics Cloud.</li><li>**Bring Your Own License (BYOL):** Select to use your Oracle Middleware on-premise license with Oracle Analytics Cloud and be charged the Bring Your Own License (BYOL) rate.</li></ul>|Yes|[Create a Service using the Console](https://docs.oracle.com/en/cloud/paas/analytics-cloud/acoci/create-services.html#GUID-689AC9D0-7AF4-4DD7-AC45-27DCEECFE19F)|
|Size|You can size your service in two different ways. You must select the capacity type that matches your subscription, that is, either *OCPU per hour* or *User per month*.<ul><li>**OCPUs** - For production services, select the number of OCPUs you want to deploy (between 2 and 52). If you want to set up a trial service, you can select 1 OCPU. </li><li>**Number of Users** - The number of users you expect to use this service.  You can split your capacity over multiple services. For example, if you subscribe to 100 users per month, you might create a test service for 10 users and a production service with the remaining 90 users.</li></ul>|Yes|[What Sizing Options Are Available to You?](https://docs.oracle.com/en/cloud/paas/analytics-cloud/acoci/create-services.html#GUID-7D6DB4EE-8DD5-44C5-9B6E-9FA847463A5F)|
|Network Access: Public or Private|You can specify how you want users to access Oracle Analytics Cloud.<ul><li>**Public:** This option deploys Oracle Analytics Cloud with a public internet accessible endpoint.</li><li>**Private:** The Private option deploys Oracle Analytics Cloud with a private endpoint. Before you configure this option, you must set up the Oracle Cloud Infrastructure VCN that you plan to use with a subnet for Oracle Analytics Cloud. </li></ul> You can configure access control rules for a public endpoint or change the VCN and subnet for a private endpoint later, if required. However, you can't change your network access selection from public to private (or private to public).|No|[Do You Need a Public or Private Endpoint?](https://docs.oracle.com/en/cloud/paas/analytics-cloud/acoci/create-services.html#GUID-707046B2-B244-4485-9DA7-1F834D1506F1)|

## Get more information
Because you want to get the most from your Oracle Analytics Cloud subscription and create your service to suit your specific needs, you can consult a wealth of information on Oracle Help Center. For information that specifically relates to planning and creating a service, see [Administering Oracle Analytics Cloud on Oracle Cloud Infrastructure (Gen 2)](https://docs.oracle.com/en/cloud/paas/analytics-cloud/acoci/get-started.html#GUID-0762E6D3-3F42-46D0-B6ED-8D5CE8D16F5A).

If you still have questions after reviewing the video and documentation, contact [Oracle Support](https://www.oracle.com/support/contact.html) to help clear any doubts before you get started or to fix any issues you encounter while creating your service.

We hope the video, documentation, and support resources help you to get Oracle Analytics Cloud up and running!
