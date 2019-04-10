# Milestone Utilities

This package consists of two invocable Apex methods that can be used either in Process Builder or the Flow Builder to assist with entitlement and milestone management from a declarative standpoint.

## AssignCaseEntitlement

A case's EntitlementID can be set in Process Builder using a hard-coded ID, but these will not survive a Trialforce or other type of org-to-org copy. **AssignCaseEntitlement** will allow you to set an entitlement to a case by its name.

I have included a sample process called **Sample Case Creation Process with Entitlement Assignment** but it's very easy to add the action to existing processes:

![Add Action to Process](/images/Entitlement_Process_Builder.png)

*Note:* This can also be invoked from a Flow in Flow Builder.


## CompleteCaseMilestone

There is no way to declaratively complete a case milestone using a process or flow in Salesforce. **CompleteCaseMilestone** will allow you to do so. It's often nice to be able to show the case milestone Lightning component automatically updating when a case Status is changed in a demo, for example.

**CompleteCaseMilestone** can be included in a process in much the same way as demonstrated above, so let's try a flow this time:

![Add Apex Action to Canvas](/images/Apex_Action.png)
![Input Values](/images/Input_Values.png)
![Output Values](/images/Output_Values.png)


## How to Deploy to Your Org

Simply click the button below and log into your org when requested:

<a href="https://githubsfdeploy.herokuapp.com">
  <img alt="Deploy to Salesforce"
       src="https://raw.githubusercontent.com/afawcett/githubsfdeploy/master/src/main/webapp/resources/img/deploy.png">
</a>