# Nick Mashburn (nmashburn6) Individual Project - CS6440 Fall 2020

Want to give this a try on your own?

[The easiest way is to use this link](https://launch.smarthealthit.org/?auth_error=&fhir_version_1=r4&fhir_version_2=r3&iss=&launch_ehr=1&launch_url=https%3A%2F%2Fnickmashburn.github.io%2Fihi-individual-project%2Flaunch.html&patient=f3159bbe-e6af-4b36-b91a-3ab69e3bcae9&prov_skip_auth=1&provider=&pt_skip_auth=1&public_key=&sb=&sde=&select_encounter=1&sim_ehr=1&token_lifetime=15&user_pt=)

If you have a problem with the link provided above, you can use these steps to deploy the app manually. 

1. Clone this Github repository into a new public repository. 
2. Navigate to “Settings” in the new repository. 
3. Scroll down to the GitHub Pages section of the page.
4. Select “main” or "master" in the Branch dropdown under Source, root in the folder dropdown, and click “Save”.
5. Copy the URL provided after clicking Save to your clipboard. 
6. Navigate to the SMART App Launcher (a sandbox environment)        https://launch.smarthealthit.org/?auth_error=&fhir_version_1=r4&fhir_version_2=r4&iss=&launch_ehr=1&launch_url=&patient=&prov_skip_auth=1&provider=&pt_skip_auth=1&public_key=&sb=&sde=&sim_ehr=1&token_lifetime=15&user_pt=
7. Below “Launch Type” (top left of the page) select “Provider EHR Launch”
8. Select the checkbox that appears next to “Simulate launch within the EHR user interface” directly below the Provider EHR Launch checkbox. 
9. Enter this Patient ID in the Patient(s) box roughly halfway down the page. This provides a direct link to a Patient record that is confirmed to have A1c Observations. F3159bbe-e6af-4b36-b91a-3ab69e3bcae9
10. Select “R3 (STU3)” in the FHIR Version dropdown on the top right of the page. 
11. In the App Launch URL field on the bottom of the page, enter the link copied from Step 5. Append “launch.html” to the end of it. 
12. Click “Launch App!”. You will now be able to use the app as outlined in this paper. 
