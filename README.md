# TestRepo
Created Date field Survey Date on Contact Object.
Created Language Field on Contact Object, value must be entered like "en", "de"
Created Visualforce Email Template"SendSurveyWithDiffLangauage" in order to use in batch class.
Email template will be language specific.
Custom Label created: 1. Survey_Greeting, where translation in German language provided.
                      2. Survey_Body, where translation in German language provided.
In template merge field has been used inorder to get the value like contact Id.
Created "SendSurveys_Batch" to pull all the contact whose Langauage__c field is not blank and Survey date before now and not null
Created "SendSurveysBatch_SCH"  to schedule the batch on business need.                           
