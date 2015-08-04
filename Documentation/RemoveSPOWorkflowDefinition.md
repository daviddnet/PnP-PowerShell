#Remove-SPOWorkflowDefinition
*Topic automatically generated on: 2015-08-04*

Removes a workflow definition
##Syntax
```powershell
Remove-SPOWorkflowDefinition [-Web [<WebPipeBind>]] -Identity [<WorkflowDefinitionPipeBind>]
```
&nbsp;

##Parameters
Parameter|Type|Required|Description
---------|----|--------|-----------
Identity|WorkflowDefinitionPipeBind|True|The subscription to remove
Web|WebPipeBind|False|The web to apply the command to. Omit this parameter to use the current web.