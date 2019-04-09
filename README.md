# Milestone Utilities

This package consists of two invocable Apex methods that can be used either in Process Builder or the Flow Builder to assist with entitlement and milestone management from a declarative standpoint.

## AssignCaseEntitlement

A case's EntitlementID can be set in Process Builder using a hard-coded ID, but these will not survive a Trialforce. **AssignCaseEntitlement** will allow you to set an entitlement to a case by its name.

I have included a sample process called **Sample Case Creation Process with Entitlement Assignment** but it's very easy to add the action to existing flows:

![Add Action to Process](/images/Entitlement_Process_Builder.png)


## How to Deploy to Your Org

Simply click the button below and log into your org when requested:

<a href="https://githubsfdeploy.herokuapp.com">
  <img alt="Deploy to Salesforce"
       src="https://raw.githubusercontent.com/afawcett/githubsfdeploy/master/src/main/webapp/resources/img/deploy.png">
</a>