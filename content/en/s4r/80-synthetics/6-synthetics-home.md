---
title: 6. Synthetics Home Page
description: This section of the workshop will equip you with the basic understanding of the Synthetics UI
weight: 60
---
If you have not done so yet, select Splunk Synthetic from the menu bar on the right  
by selecting the (the robot icon) ![syntheticsMenu](../../images/synthetics-icon.png?classes=inline&height=25px)  

This will bring us to the Synthetic Home Page. It has 3 distinct sections that provide either useful information or allows you pick or create a Synthetic Test.

![Synthetic main](../../8-synthetics/images/synthetics-main.png?width=40vw)

* 1. Onboarding Pane, Here you will find video's and information related to Splunk Synthetics. (Can be closed by pressing the X, if space is a premium)
* 2. Test Pane, Here you find the list of all the test that are active in your org, and you can select them to see the results
* 3. Create Test Pane, This drop down pane allows you to create new Synthetic tests.

To continue out tour, lets look at the result of an automatic browser test.  
In the Test Pane, lick on the line that  This should give you a page similar to the one below:

![Synthetics-overview](../../8-synthetics/images/synthetics-test-overview.png?width=40vw)

This page will give you an overview of the performance of your site.

In the following exercise, we will create a new uptime test:
{{% notice title="Info" style="green" title="Exercise" icon="running" %}}

* On the Synthetic Tests Page, the Th first pane will show  the performance over the last day, 8 days and 30 days.  
  If the test is not running that long, The charts will be empty, but you can see that the Uptime trends
* In the screenshot you can see that we did not have a 100% success rate, This is due that the test started before the Frontend  application was fully initiated.
* find the test that failed.


 eck the drop-down box in Org Switcher Pane at the top to see if you have more than one Org assigned to you.

* Click on ![Settings](../../images/settings-icon.png?classes=inline&height=25px) in the main menu.
* At the bottom of the menu, click on either **Light**, **Dark** or **Auto** mode.
* Did you also notice this is where the  Sign out ![Sign Out](../images/sign-out-icon.png?classes=inline&height=25px) option is?
* Click ![Back to menu](../images/back-main-menu.png?classes=inline&height=25px) to go back to the Main Menu.

{{% /notice %}}
Lets continue to Infra mon and Run an exercise.