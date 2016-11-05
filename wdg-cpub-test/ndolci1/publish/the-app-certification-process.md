---
Description: When you are finished creating your app's submission and click Submit to the Store, it enters the certification step.
title: The app certification process
ms.assetid: 0DCB4344-224D-4E5A-899F-FF7A89F23DBC
---

# The app certification process


When you are finished creating your app's submission and click **Submit to the Store**, it enters the certification step. This process usually is completed within a few hours, though in some cases it may take longer. Here's a look at what happens during the certification step.

-   **Preprocessing:** After you successfully upload the app's packages and submit the app for certification, the packages are queued for testing. We'll display a message if we detect any errors during preprocessing. For more info on possible errors, see [Resolve submission errors](resolve-submission-errors.md).
-   **Certification:** During this phase, several tests are conducted:

    -   **Security tests:** This first test checks your app's packages for viruses and malware. If your app fails this test, you'll need to check your development system by running the latest antivirus software, then rebuild your app's package on a clean system.
    -   **Technical compliance tests:** Technical compliance is tested by the Windows App Certification Kit. (You should always make sure to [test your app with the Windows App Certification Kit](https://msdn.microsoft.com/library/windows/apps/mt186449) before you submit it to the Store.)
    -   **Content compliance:** The amount of time this takes varies depending on how complex your app is, how much visual content it has, and how many apps have been submitted recently. Be sure to provide any info that testers should be aware of in the [Notes for certification](notes-for-certification.md) page.

    After the certification process is complete, you'll get a certification report telling you whether or not your app passed certification. If it didn't pass, the report will indicate which test failed or which [policy](https://msdn.microsoft.com/library/windows/apps/dn764944) was not met. After you fix the problem, you can create a new submission for your app to start the certification process again.

-   **Release:** When your app passes certification, it's ready to move to the to the **Publishing** process. If you've indicated that your submission should be published as soon as possible, this will happen right away. If you've specified that it should not be released until a certain date, we'll wait until that date, unless you click the link to **Change release date**. If you've indicated that you want to publish the submission manually, then we won't publish it until you indicate that we should by clicking the button to **Publish now**, or if you click the link to **Change release date** and pick a specific date.
-   **Publishing:** Your app's packages are digitally signed to protect them against tampering after they have been released. Once this phase has begun, you can no longer cancel your submission or change its release date.

After successfully going through the steps above, your submission will be available in the Windows Store for customers to download.

**Note**  We also conduct spot checks of apps after they've been published so we can identity potential problems and ensure that your app complies with all of the [Windows Store Policies](https://msdn.microsoft.com/library/windows/apps/dn764944). If we find any problems, you'll be notified about the issue and how to fix it, if applicable, or if it has been removed from the Store.

 

 

 




