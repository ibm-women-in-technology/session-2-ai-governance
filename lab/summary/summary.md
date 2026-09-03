# Summary

Congratulations on completing this long lab! You covered the entire *Use Case Request* workflow from start to finish, including all the child objects with their respective workflow.

<img src="./assets/image_089.png">

Along the way, you have seen how the different elements of a workflow can be used to codify an organization’s governance processes and policies:

|  |  |
| --- | --- |
| Workflow properties | * (De-)activate workflows. * Implement how the workflow starts. * Implement the rules that describe when a workflow applies, for example to limit the workflow to instances of an object with a specific status value.   + This can help break up a large process into smaller workflows.   + This can help differentiate between objects with different characteristics (e.g., high-risk vs low-risk use cases, or ML vs. gen AI assets) |
| Action properties | * Define the label that will be visible under the Action button. * Send notification emails to users that are assignees or subscribers. * Implement conditional routing through a workflow. * Implementation validation rules on data entry (with appropriate warning messages). * Implement automated operations to:   + Set fields such as *Status* or *Completion Date*.   + Create new child objects such as a *Questionnaire, Review* or *Model Group.*   + Run questionnaire response actions. |
| Stage properties | * Set a due date for a task. * Assign a task to the right person or role. * Send notification emails for workflow end stages. * Implement automated operations on workflow end stages. |

In conjunction with the workflow, the questionnaire templates also play a role in codifying an organization’s governance processes and policies:

1. Define conditional routing through the questionnaire
1. Define response actions to
    + Set fields such as the *EU AI Risk Category* field.
    + Create or copy new child objects such as Risks.

Lastly, there is an interplay between workflows and Views. This topic was out of scope for this lab.
