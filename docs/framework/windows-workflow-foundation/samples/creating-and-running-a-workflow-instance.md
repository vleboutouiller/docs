---
description: "Learn more about: Creating and Running a Workflow Instance"
title: "Creating and Running a Workflow Instance"
ms.date: "03/30/2017"
ms.assetid: 19d27f47-0491-4569-8f53-51bc1d940e80
---
# Creating and Running a Workflow Instance

This sample shows how to run a workflow instance. It shows how to execute it synchronously and asynchronously.

## Demonstrates

<xref:System.Activities.WorkflowInvoker>, <xref:System.Activities.WorkflowApplication>.

## Discussion

The first part of the sample uses <xref:System.Activities.WorkflowInvoker.Invoke%2A>. This is the most basic way to execute a workflow. Workflows executed with <xref:System.Activities.WorkflowInvoker.Invoke%2A> are executed synchronously.

The second part of the sample uses the <xref:System.Activities.WorkflowApplication> class. <xref:System.Activities.WorkflowApplication> enables you to have more control over each instance, including the ability to interact with the running workflow and to run the workflow asynchronously.

> [!IMPORTANT]
> The samples may already be installed on your machine. Check for the following (default) directory before continuing.
>
> `<InstallDrive>:\WF_WCF_Samples`
>
> If this directory does not exist, go to [Windows Communication Foundation (WCF) and Windows Workflow Foundation (WF) Samples for .NET Framework 4](https://www.microsoft.com/download/details.aspx?id=21459) to download all Windows Communication Foundation (WCF) and [!INCLUDE[wf1](../../../../includes/wf1-md.md)] samples. This sample is located in the following directory.
>
> `<InstallDrive>:\WF_WCF_Samples\WF\Basic\Execution\CreatingWorkflowInstances`

## See also

- [Using WorkflowInvoker and WorkflowApplication](../using-workflowinvoker-and-workflowapplication.md)
