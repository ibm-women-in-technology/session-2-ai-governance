## Create a new use case

1. In *Governance Console*, open the **main menu**, then select **Inventory &rarr; Use Cases**. <img src="./assets/image_012.png">
1. Click **“Create New”**

    On the *Use Cases* grid view, click on the **New** button. <img src="./assets/image_013.png">

1. On the *New Use Case* screen, notice the right-hand panel that guides the user through what needs to happen here.
    + **Expand and read** the guidance text
    + Under *All Key Items*, mandatory fields are marked with a red asterisk (\*). The other fields are recommended but not mandatory. <img src="./assets/image_014.png">
1. Fill in the screen as follows:
    + *Name* = “AskMeAnything”+ your initials
    + *Owner* = your username
    + *Purpose* = “General purpose AI assistant for all of our employees”
    + *Description* = “AI chatbot with Q&A, summarization and RAG capabilities”
    + *Use Case Type* = AI
1. In the *Business Entities* section of the screen, on the *Primary Business Entity* tab, Click on the **Add** button. <img src="./assets/image_015.png">
    + From the list of business entities, find and select “**High Oaks Bank**” and click **Done**. <img src="./assets/image_016.png">
    + This selection determines the accountability of this use case – which department or business unit is responsible for this AI system?
1. Back on the *New Use Case* screen, click on **Save**. <img src="./assets/image_017.png">
1. Note the following fields have appeared on your use case:
    + Status = “Proposed”
    + Workflow stage = “Use Case Data Gathering (Data gathering)”
    + Due date = 5 days from now
    + Owner = you <img src="./assets/image_018.png">
    + Where does that come from? Those are all defined in the workflow. It’s outside of the scope of this session to dive deep into that.
    + If the *Third Party Link* field is not yet set, **refresh** the screen to allow the Factsheet link to be populated automatically. You don’t need this link in this lab, but if you move ahead too quickly, you might get an error message in the next chapter of this lab. <img src="./assets/image_018a.png">

## Further use case data gathering

1. Go back to the **tab with your use case**.
1. Add your use case to your favorites so you can find it quickly. Click on the **star** next to the use case name. <img src="./assets/image_019.png">
1. In the *right-hand panel*, you can see some new recommended fields. Let’s fill those in (you can click on the name of the field in the guidance panel to jump to that field on the UI):
    + *Stakeholder departments* = Information Security, AI Committee
    + *Technical owner* = your username
    + *Risk level* – leave this field blank for now, we’ll come back to it later <img src="./assets/image_019a.png">
1. **Save** your use case. <img src="./assets/image_020.png">
    + If you get an error “The object has been recently updated by another user”, refresh the screen and enter the information again
    <img alt="A close-up of a message  AI-generated content may be incorrect." src="./assets/image_021.png">
    + This is caused by the automated action to populate your use case with the Factsheets link. If you did the refresh action earlier in this lab, you would have already avoided this message, but in demos you might be moving quicker than the tool 😉
1. Click on the **Action** button, then click on **Send for risk and applicability scoring**. <img src="./assets/image_022.png">
1. On the confirmation screen, click on **Continue**. <img src="./assets/image_023.png">
1. Once again, the workflow has taken certain actions. Note the following on your use case:
    + *Status* has changed to “Risk and Applicability Scoping”.
    + *Workflow stage* has changed to “Risk Identification and Applicability ”.
    + The *Data Gathering Completion Date* field has been set to today’s date.
    + The use case is *assigned to you* in this stage of the workflow.
    + A new *Risk* section has been added to the use case view, with an assessment questionnaire.
    + A new *Regulatory Information* section has been added to the use case view, with an assessment questionnaire.
1. Before we continue with our use case, let’s first have a quick look at the automated audit trail.

## Audit logging

1. Click on the **Activity** tab. <img src="./assets/image_024.png">
1. Here, the software automatically captures an audit trail for your use case.
1. At the top you will see your most recent changes such as the changes to the *Status*, *Data Gathering Completion Date* and *Workflow Stage* fields. <img src="./assets/image_025.png">
1. All of these entries are automatically logged with the name of the user and a date/timestamp.
    + This data is immutable, it is not changed or deleted. Even if the user in question is no longer active (for example because they switched roles, or left the organization), their activities will still be visible here for audit purposes.
1. Over time, this audit trail can get quite long, so you have the ability to filter this list. Open the **Filter** side bar. <img src="./assets/image_026.png">
1. Here, I can filter by date, user, or specific types of changes.
1. Select the **Workflow** filter. <img src="./assets/image_027.png">
1. As a result, I now only see the workflow transitions that this use case has gone through.
    + Right now, we have just started the onboarding process, so you only see two workflow transitions here. Throughout this lab, feel free to come back to this tab to see what is captured here along the way.

## Regulatory applicability assessment

1. Go back to the **Task** on with your use case.
1. In the *Regulatory Information* section of your use case, notice that the EU AI Risk Category is set to “Not Determined”. <img src="./assets/image_028.png">
1. Each assessment that is created is a child object of the use case. The Questionnaire Assessment object is subject to a workflow of its own, separate from the Use Case Request workflow. <img src="./assets/image_029.png">
1. To help us categorize our use case, click on the questionnaire assessment called **Applicability Assessment (AskMeAnything ABC)** to open it.
1. The questionnaire consists of a few sections. The first section is *Scope and Prohibited AI Systems* (1).
1. The first part of that consists of 3 questions, of which none have been answered yet (the question counter (2) shows 0 / 3 completed). <img src="./assets/image_030.png">
    + **Read the questions and fill in the answers**. Use the information from the Business context paragraph of this document if you need clues about the appropriate answers. Ask your course leader to clarify anything that is unclear.
1. If you answered the first three questions correctly, the questionnaire determines that your AI system is *in scope of the AI Act*, and a set of additional questions appear. <img src="./assets/image_031.png">
    + **Read the questions and fill in the answers**. Use the information from the Business context paragraph of this document if you need clues about the appropriate answers. Ask your course leader to clarify anything that is unclear.
1. If you answered these next 6 questions correctly, the questionnaire determines that your AI system is *not Prohibited*, a new questionnaire section called “Category Assessment” appears in left hand panel.
1. Click on that **section name**. <img src="./assets/image_032.png">
    + **Read the questions and fill in the answers**. Use the information from the Business context paragraph of this document if you need clues about the appropriate answers. Ask your course leader to clarify anything that is unclear.
1. After completing all the questions, you will get a final notice that your use case may be subject to *transparency requirements* in the AI Act, and you are asked to contact the compliance department. Click the “I confirm” button. <img src="./assets/image_033.png">
1. If your outcome is different, you probably have answered some questions differently. That’s OK for this exercise, no need to go back and change anything.
1. In total, you have answered 23 questions. <img src="./assets/image_033a.png">
1. The questionnaire with your answers is periodically auto saved. If the *Save draft* button is not greyed out, **click on that button** to make sure your final answers have been saved. <img src="./assets/image_033b.png">
1. You have now completed and saved the applicability assessment. Click on the **Action** button, then select **Submit and Close**. (as expected from the Action properties you just saw). <img src="./assets/image_034.png">
1. On the confirmation screen, click **Submit and close tab**. <img src="./assets/image_035.png">
1. Go back to the **tab with your use case**.
1. In the *Regulatory Information* section, notice that the *EU AI Risk Category* field is now set to “Limited”. <img src="./assets/image_036.png">
1. Where does that come from? The questionnaire template contains decision logic that sets this field, based on the answers you’ve given.
1. In graphical form: <img src="./assets/image_037.png">
1. Next, you will go through the same process with the Risk identification assessment.

## Risk identification

This chapter is similar in structure to the previous one. The instructions are a little more compact since you are doing this for the second time now. Refer back to the previous chapter if you need a memory jog.

1. Go back to the **tab with your use case**.
1. In the *Risk* section of your use case, click on the questionnaire assessment called **AI Risk Identification (AskMeAnything ABC)** to open it.
1. Fill in the risk identification questionnaire. Use the information from the Business context and [Create a new use case](#_Create_a_new) paragraphs of this document if you need clues about the appropriate answers. Ask your course leader to clarify anything that is unclear.
1. As you work through the questionnaire, notice that
    + You can be asked to provide a comment on a question
    + You can be prompted to answer additional questions
1. In the questionnaire I created when writing this content, I have answered 31 questions (you might have a different number based on the answers you’ve given). <img src="./assets/image_038.png">
1. The questionnaire with your answers is periodically auto saved. If the *Save draft* button is not greyed out, **click on that button** to make sure your final answers have been saved. <img src="./assets/image_038a.png">
1. You have now completed and saved the risk identification. Click on the **Action** button, then select **Submit and Close**. <img src="./assets/image_039.png">
1. On the confirmation screen, click **Submit and close tab**. <img src="./assets/image_040.png">
1. Now that we have described our use case in detail, the next step is to *assess* the risks that have been identified from your answers.

## Continue the Use Case Request workflow

1. Go back to the **tab with your use case**.
1. Click on the **Action** button, then click on **Submit for Risk Assessment**. <img src="./assets/image_041.png">
1. On the *confirmation screen*, click **Continue**. <img alt="A screenshot of a computer  AI-generated content may be incorrect." src="./assets/image_042.png">
1. In the *Risk* section of your use case, notice that a number of risks are added to your use case (the exact number of risks and which ones, depends on how you answered the questionnaire). <img src="./assets/image_043.png">

## Risk assessment

1. In the *Risk* section, for the *table of Risks*, click on the **Launch Grid page** icon to display the list of risks in a separate tab. <img src="./assets/image_044.png">
1. Click the **name** of the first risk in your list to open it. <img src="./assets/image_045.png">
1. Read the **description** of the risk. <img src="./assets/image_046.png">
1. Notice that
    + The *Inherent Risk* and *Residual Risk* fields are both set to “Not determined”
    + The *Status* field is set to “Awaiting Assessment” (as per the Response action)
    + In the *Risk Categorization* section, the *Domain* field is set to “AI / Model governance”.
      - This field is set on the Risk object in the library. When the Risk is copied to your use case, it maintains that categorization. <img src="./assets/image_047.png">
1. From the **Action** button, select **Start Model Risk Assessment**. <img src="./assets/image_048.png">
1. On the *confirmation screen*, click **Continue**. <img src="./assets/image_049.png">
1. You have now initiated the assessment workflow, you are the owner of this Risk object, and the Risk is placed in the *Confirm Assignment* workflow state. <img src="./assets/image_050.png">
1. We will work through this activity in its entirety first, and then have a look at the workflow that drives this.
1. Read the instruction in the right-hand panel.
    + You are asked to confirm that you are the owner, or re-assign the Risk to someone else. You will continue as the owner yourself. <img src="./assets/image_050a.png">
1. Open the **Action** button, but do not select any of the options yet. <img src="./assets/image_051.png">
1. Notice that you have two options:
    + “Ready for assessment” – this confirms that you are the owner and you want to start the assessment process
    + “Risk Not Applicable” – this means that you are owner, but you don’t think the risk is applicable for this use case. Remember that the risk was auto-populated based on the questionnaire responses, but on closer inspection, it might not be relevant after all.
1. Click on the **Ready for Assessment** option. <img src="./assets/image_052.png">
1. On the *confirmation screen*, click **Continue**. <img src="./assets/image_053.png">
1. The Risk is now in the *Perform Risk Assessment* workflow stage.
1. Read the instruction and the Key Items in the right-hand panel. <img src="./assets/image_054.png">
1. Some definitions to help you with this task:
    + Inherent likelihood = How likely is it that this risk occurs *if you do not* take any mitigating actions?
    + Residual likelihood = How likely is it that this risk occurs *after you’ve taken* mitigating actions?
    + Inherent impact = If the risk occurs, how big is the impact (financial, reputational etc.) *if you do not* take any mitigating actions?
    + Residual impact = If the risk occurs, how big is the impact (financial, reputational etc.) *after you’ve taken* mitigating actions?
    + These are well-known risk management concepts.
1. In the *Risk Assessment* section, update the field *Inherent Impact* to **Medium**. <img src="./assets/image_055.png">
1. Update the field *Inherent Likelihood* to **High**. <img src="./assets/image_056.png">
1. Notice that the field *Inherent Risk Rating* is automatically updated based on your inputs. This is an automated calculation that combines the *Likelihood* and *Impact* assessments into a single rating. <img src="./assets/image_057.png">
1. In the *Key Items* list in the right hand panel, you are also asked to describe the *Mitigation Strategy* – what is your plan to reduce or even remove this risk?

    The answer here of course depends on the specific risk on which you are working. In my screenshots I am working on the “Attribute inference attack” risk. For this risk, my strategy might be to “Implement a guardrail that detects behavior that would indicate an attribute inference attack.”.

1. Enter an appropriate **text** for your risk in the *Mitigation Strategy* field. <img src="./assets/image_058.png">
1. After you’ve done that, notice that in the *Key Items* list, this field now gets a green completion mark. <img src="./assets/image_059.png">
1. Update the field *Residual Impact* to **Low**.
1. Update the field *Residual Likelihood* to **Medium**. <img src="./assets/image_060.png">
1. Notice that the field *Residual Risk Rating* is automatically calculated based on your inputs.
1. **Save** the information that you have entered. <img src="./assets/image_061.png">
1. Under the **Action** button, select **Assessment Complete**. <img src="./assets/image_062.png">
1. On the *confirmation screen*, enter a **Comment** of “I have assessed the risk. The suggested mitigation strategy is expected to reduce the Residual Risk Rating to Medium.”, then click on **Continue**. <img src="./assets/image_063.png">
1. Notice the following:
    + The *Status* field is set to “Approved”.
    + Your *workflow comment* is saved with a date stamp and your username appended. <img src="./assets/image_064.png">
1. As mentioned, there is another dedicated workflow that drives this. Let’s have a look at that one.
1. **Close** the tab with the Risk you have just assessed.
1. **Do not close** the tab with the list of Risks from your use case.

## Complete the assessment for all risks

Depending on how your answered the risk identification questions, you might have quite a long list of Risks to work through. For simplicity in this lab, consider:

1. Doing 2 or 3 risks purposefully: seriously consider the likelihood and impact fields and come up with a realistic mitigation strategy.
    + Open the Risk object
    + Action button &rarr; Start Model Risk Assessment &rarr; Continue
    + Action button &rarr; Ready for Assessment &rarr; Continue
    + Set *Inherent Impact* and *Inherent Likelihood* fields
    + Enter a text for *mitigation strategy*.
    + Set *Residual Impact* and *Residual Likelihood* fields
    + Save
    + Action button &rarr; Assessment Complete
    + Enter a comment, Continue and close tab
1. After doing this a few times:
    + Go to the tab that shows the **Risks for your use case**.
    + **Select** all the Risks you have not yet worked on, and click on **Bulk Update** in the toolbar. <img src="./assets/image_065.png">
    + In the *Bulk Update* panel, select the field **Status** and set the value to **Approved**, then click on **Update**. <img src="./assets/image_066.png">
    + On the *Confirmation* screen, select **Confirm**. <img src="./assets/image_067.png">
    + After a few seconds you will get this notification screen: <img src="./assets/image_068.png">
    + This batch approach is not a recommended approach in real life.
1. When all Risks are assessed, close the tab that shows the **Risks for your use case**.

## Continue the Use Case Request workflow

1. Go to the tab that shows **your use case**.
1. We can now move on from the *Risk Assessment* stage of the workflow.
1. On the **Action** button, click on **Submit for stakeholder review**. <img src="./assets/image_069.png">
1. On the *Confirmation* window, click on **Continue**. <img src="./assets/image_070.png">
1. Notice the following on your use case:
    + *Status* = Awaiting Use Case Approval
    + *Workflow stage* = Stakeholder Review
    + You are still the *assignee*
    + The *due date* is 5 days from now
    + Two reviews have been added in the *Use Case Approval* section. <img src="./assets/image_071.png">
1. Let’s have a look at these reviews next.

---

➡️ **Next Step:** [Use Case Reviews](./use-case-reviews.md)

---

[← Back to main guide](../../README.md)<br>
[← Back to directory](../../guides-directory.md)
