---
description: Test the content before publishing it with the Test option
---

# How to perform a test

It is recommended to use the tool's test feature in order to preview the content before impacting a wide range of users.

## How to test content before publishing it

The CMS is divided into two parts: the configuration of entry points lists and the configuration of the entry points themselves.

The way to test the content is practically the same in both cases: whenever changes are made or at the end of the process of creating a new element. The Test option is then enabled in the CMS.

### Configure a test

The option to create a test is shown when changes are made i.e. when there is something to test. You can also test content that you have just created and whose result you need to visualize before impacting x number of users.

#### Testing entry points lists

- If the list is in draft mode, the test option is shown when saving the changes but without publishing them. Click **Test** to create a test for that list.

{% hint style = "warning" %} Note that if you create a test when the list is in **DRAFT** mode, the list automatically changes to **PAUSED** state. {% endhint %}

- If the list is published or paused, the test option is shown when you make changes to that list. In that case, click **Save and start test** to save those changes and start a test.

In both cases it indicates:

**Test description**: add a description that helps you identify what you are testing, what the changes are.

**Novum user IDs (optional)**: add one or more user IDs, separated only by commas (without spaces), in which you want to perform tests. This is an optional field.

Click **Create test**.

![](.gitbook/assets/Create_test.png)

{% hint style = "info" %} **How to get the user ID**

1. Make sure you have the Enterprise version of the app downloaded.
2. Open the app
3. Shake the phone
4. Access the "Authentication" section
5. the number you need is the one in the **User ID** field {% endhint %}

#### Testing an entry point

Unlike lists, you cannot test an entry point that is in draft mode.

For entry points in published status, make the changes you need to test and click the **Save and start test** option. Indicate:

**Test description**: add a description that helps you identify what you are testing, what the changes are, etc.

**Novum user IDs (optional)**: add one or more user IDs, separated only by commas (without spaces), in which you want to perform tests. This is an optional field.

Click **Create test**.

![](.gitbook/assets/Create_test.png)

### How to publish the content of a test

First, you'll know that there is a test ongoing for a list of entry points if you see the **TEST** status tag:

![Detalle de la etiqueta TEST en una lista de entrypoints](https://github.com/nazaretcaballo-CX/entrypoints-CMS/blob/ES/en-US/.gitbook/assets/detalle_test_tag.png?raw=true)

To publish the content of a test, access the list of entry points for which that test is running.

When you open the list, the content appears divided into two tabs. This allows you to see, at all times, the content prior to the test and the content of the test itself.

![Detalle de la etiqueta TEST en una lista de entrypoints](https://github.com/nazaretcaballo-CX/entrypoints-CMS/blob/ES/en-US/.gitbook/assets/detalle_pestan%CC%83as_test.png?raw=true)

 

{% hint style = "warning" %} You can only make changes to the content if you are in the **Test** tab. Use the other tab to see the content prior to the changes that you made for the test. {% endhint %}

When you have made sure that the content in the **Test** tab, in all the steps, is the content you want to apply, click **Publish**. Click **Yes** when the confirmation message appears.

![](.gitbook/assets/Detalle_Publish.png)

Click **Close** to return to the main entry point lists screen, **Entry point Lists**.

{% hint style = "success" %} :thumbsup: On the main screen, you can check that the **TEST** tag has disappeared in the list status. {% endhint %}

### How to delete a test

If you decide to discard the changes after testing the content of an entry points list, you need to access the entry points list that the ongoing test applies to.

Click **Continue** until you reach the **Preview &amp; Validate** step, and then click **Delete test**.

![](.gitbook/assets/Detalle_DeleteTest.png)

When you delete a test, all the changes that you had made to the entry points list will be deleted. The content will then be created as it was previously.

### How to add, remove or modify the Novum User IDs of a test

If you need to edit the test in order to add, remove or modify the users who can view a certain test, you need to access that list.

In the **Test** tab you can see, in the **Overview** step, the information related to the test: the description, who started it and the date on which it was created.

Click on ![](.gitbook/assets/editar_icono.png)to modify user numbers. You can also do this to add new user IDs or delete those which already exist. Click **Save** to save the changes.

![](.gitbook/assets/Change_test_IDs.gif)
