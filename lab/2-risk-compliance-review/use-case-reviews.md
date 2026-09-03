# Use case reviews

## Complete the stakeholder reviews

1. First of all, note that there are two Review objects, one for each Stakeholder Departments that you set in the early steps of this Lab. Both are in an “Awaiting Approval” status. <img src="./assets/image_071.png">
1. Each Stakeholder Review that is created is a child object of the use case. The *Stakeholder Review* object is subject to a workflow of its own, separate from the Use Case Request workflow. <img src="./assets/image_072.png">
1. From the *Use Case Approvals* section, open the **Review for the Information Security** department. <img src="./assets/image_073.png">
1. Expand the *workflow information* panel to see that
    + This Stakeholder Review is in the *Awaiting Approval* lifecycle stage.
    + It is **not assigned** to anybody yet. <img src="./assets/image_074.png">
1. Depending on a customer’s setup, this could be automatically assigned to a person or a role, but that’s not set in the out-of-the-box configuration.
1. As the use case owner, you can assign this to someone. For simplicity, assign yourself. In the *Reviewer* field, select **yourself**, then **Save** the information. <img src="./assets/image_075.png">
1. You are now the assignee, and the workflow’s Action button is enabled. <img src="./assets/image_076.png">
1. On this task view, you can access the *Use Case* (1) and both of its *assessments* (2) for more information. If there were any *documents* attached to the use case, you would see those as well (3) to help with your review. <img src="./assets/image_077.png">
1. Let’s assume you have done all of that, and are happy with the information provided and want to approve the Use Case.
1. In the *Reviewer Comment* field, enter a **comment** that states your approval, then **Save** the information. <img src="./assets/image_078.png">
1. You have now completed all three fields under the *Key Items* list
1. Click on the **Action** button, then select **Approve Use Case**. <img src="./assets/image_079.png">
1. On the *Confirmation* screen, select **Continue and close tab**. <img src="./assets/image_080.png">
1. You should get a message like this: <img src="./assets/image_081.png">
1. This wasn’t immediately obvious in the UI anywhere, but there is a built-in check that the *Risk Rating* field has been set.
1. Change the *Risk Rating* field to **Low**, then **Save** the information. <img src="./assets/image_082.png">
1. Click on the **Action** button again, then select **Approve Use Case**.
1. On the *Confirmation* screen, select **Continue and close tab**.
1. Back on your Use Case screen, for this first Stakeholder Review the Approval Status is now set to
  “Approved”, and the *Approval Date* field is set to today’s date. <img src="./assets/image_083.png">
1. Like before, you have again seen various automated actions and checks on this Stakeholder Review. And like before, there is a workflow that drives this. Let’s see where this happens.
1. Complete the **second Stakeholder Review** in the same way as the first one.
    + Don’t forget to set the risk rating

## Continue the use case request workflow

1. With all Stakeholder Reviews done, click on the **Action** button, then select **Approve for development**. <img src="./assets/image_084.png">
1. On the *Confirmation* screen, select **Continue**. <img src="./assets/image_085.png">
1. Back on the *Use Case* screen, the *Status* field is now set to “Approved for Development”. <img src="./assets/image_086.png">
1. That completes the *Use Case Request* workflow.
1. If you are completing this Lab on a shared environment, please follow the steps in the next chapter to remove your use case.
1. After that, read the summary chapter.
