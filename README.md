Download Link: https://assignmentchef.com/product/solved-itis-cs-5180-assignment1-tip-calculator
<br>
In this assignment you will build your first Android application. You will get familiar with common Android components and how to interact with them. You will build a single activity Tip Calculator application.

<strong>Figure 1, Application User Interface </strong>

<strong>Part 1 : Building the Interface </strong>

The interface should be created to match the user interface (UI) presented in Figure 1. You will be using layout files, strings.xml, and drawable files to create the user interface. The layout XML file can be modified through the raw xml, or through the GUI tools provided within eclipse. To build the UI, please follow the following tasks:

<ol>

 <li>Your application should have an application launcher icon, please select your launcher icon to represent your app.</li>

 <li>The string values used for the text labels, button labels and hints should be read from the strings.xml file and should not be hardwired in the layout file.</li>

 <li>Use an EditText component for the user to enter the bill total value. The EditText component should be setup to limit the bill total value to only positive numbers. When the application starts the bill total EditText should be empty, and should display the hint message “Enter Bill Value” as indicated in Figure 1.</li>

 <li>Use a RadioGroup containing RadioButtons to enable the user to pick from the tip options 10%, 15%, 18% and Custom. When the application starts the 10% tip choice should be selected.</li>

 <li>Use the SeekBar to enable the user to pick a custom tip value, the maximum custom tip value should be set to 50%. When the application starts the custom tip value should be set to 25%. On the right of the SeekBar use a TextView to display the current progress of the SeekBar, which represents the current custom tip value.</li>

 <li>Use TextView components for creating the tip and total values. When the application starts the tip and total values should be both set to 0.00.</li>

 <li>Finally, create the Exit button, note that the text for the button should be retrieved from the string.xml file.</li>

</ol>

<strong>Part 2 : Event Handlers and App Behavior (MainActivity) </strong>

In this part you will build the required logic for the tip calculator app. The requirements are as follows:

<ol>

 <li>The tip radio buttons should enable the user to select one of tip options. If a tip option is selected the tip and total values should be calculated and update based on the selected tip option and the bill total. See Figure 2(a).</li>

 <li>If the user updates or edits the bill total the tip and total values should be updated to reflect their new values.</li>

 <li>If the bill total is empty, then tip and total values should be set to 0.00. In addition, use the setError() method to display an error message informing the user to “Enter Bill Total”. See Figure 2(c)</li>

 <li>When the custom SeekBar is changed the current custom tip progress should be updated to show the SeekBar progress. If the custom tip option is selected, then the tip and total values should be calculated based on the current custom tip progress.</li>

 <li>The application should be finished if the Exit button is clicked.</li>

</ol>

15% option                                custom option                             total is empty.

<strong>Figure 2, Application Screen Shots</strong>