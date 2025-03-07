<!-- loio09dd313bf6644250a14f8f38c3d644c0 -->

# Create the Kyma Environment Instance

Set up a Kubernetes cluster with project "Kyma" and use it to build applications and extensions to your SAP and third-party solutions.



<a name="loio09dd313bf6644250a14f8f38c3d644c0__prereq_drc_4yb_zrb"/>

## Prerequisites

Your subaccount has entitlements for Kyma runtime configured. For more information, read [Managing Entitlements and Quotas Using the Cockpit](managing-entitlements-and-quotas-using-the-cockpit-c824874.md).



<a name="loio09dd313bf6644250a14f8f38c3d644c0__context_er4_224_5pb"/>

## Context

To set up the Kyma environment on your subaccount, you must create an instance of it. You can easily create it from Service Marketplace, following the same wizard steps as for SAP services and applications. You can configure the instance by selecting the region in which you want to create the cluster and the number of virtual machines to run on it.

> ### Note:  
> The legacy method to set up a Kubernetes cluster is to select *Enable Kyma* in the *Kyma Environment* section of your subaccount overview. However, this way offers fewer configuration options, so we recommend the Service Marketplace.



<a name="loio09dd313bf6644250a14f8f38c3d644c0__steps_dbj_w15_frb"/>

## Procedure

1.  In SAP BTP cockpit, navigate to your subaccount.

2.  Go to *Services* \> *Service Marketplace* and select *Kyma Environment*.

3.  Select *Create* either from actions in the upper-right corner of the tile or from the tile overview page, to which you get by clicking on the tile.

4.  Change the instance name or keep the default name.

    You see the default plan assigned to your account. The default plan and its specification can differ depending on your global account type.

5.  To move to the plan configuration view, choose *Next*.

6.  In the *Parameters* view, specify the required details. You can also configure your instance parameters by changing its region and the maximum or the minimum number of virtual machines to be created for it. You can also configure a custom identity provider.

7.  Confirm changes by selecting *Create*.




<a name="loio09dd313bf6644250a14f8f38c3d644c0__result_ghx_pcv_dlb"/>

## Results

You have created a Kyma environment instance.

> ### Tip:  
> For users who like to work in a terminal or want to automate operations using scripts, there's an alternative to the SAP BTP cockpit: You can create the Kyma environment with the SAP BTP command line interface \(btp CLI\).
> 
> To learn more, read [Creating SAP BTP, Kyma runtime via the SAP BTP cli](https://blogs.sap.com/2022/02/24/creating-sap-btp-kyma-runtime-via-the-sap-btp-cli/).



<a name="loio09dd313bf6644250a14f8f38c3d644c0__postreq_jdw_z24_5pb"/>

## Next Steps

To get the link to Kyma Dashboard, navigate to the overview of the instance under *Instances and Subscriptions*.

To manage access to the Kyma environment and Kyma Dashboard, assign roles as needed.

**Related Information**  


[Available Plans in the Kyma Environment](available-plans-in-the-kyma-environment-befe01d.md "Depending on your global account type, you have access to a different plan that specifies the cluster parameters for the Kyma environment.")

[Configure a Custom Identity Provider for Kyma](../60-security/configure-a-custom-identity-provider-for-kyma-67bcc6e.md "Enable the Kyma environment with a custom identity provider.")

[Assign Roles in the Kyma Environment](assign-roles-in-the-kyma-environment-148ae38.md "Kyma uses roles to manage access within the cluster, which give the assigned users the permissions suitable for their purposes.")

[Account Administration Using the SAP BTP Command Line Interface \(btp CLI\)](account-administration-using-the-sap-btp-command-line-interface-btp-cli-7c6df2d.md "Use the SAP BTP command line interface (btp CLI) for all account administration tasks, such as creating or updating subaccounts, authorization management, and working with service brokers and platforms. It is an alternative to the SAP BTP cockpit for all users who like to work in a terminal or want to automate operations using scripts.")

[Creating SAP BTP, Kyma runtime via the SAP BTP cli](https://blogs.sap.com/2022/02/24/creating-sap-btp-kyma-runtime-via-the-sap-btp-cli/)

