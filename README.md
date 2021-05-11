# Identity Proofing User Guide

## SecZetta Identity Proofing

As enterprise organizations increasingly grant access to facilities, data, and systems to an ever-expanding number of third-party users, it becomes imperative for them to prove that these people are in fact who they claim to be.  

### IDProofing

With SecZetta’s IDProofing it’s possible to easily invoke large scale or individual identity verification during the onboarding process or at any time throughout the identity lifecycle. 

### Goal of the Document

This document is designed to familiarize users with IDProofing features and functionality.


## Understanding the Tool

IDProofing can be configured to leverage mobile carrier records or the combination of a government issued photo ID (see below) and a live selfie to confirm that users are who they claim to be.  When enabled, IDProofing shows as an action within the Third-Party Identity Risk workflow engine.  A user may be prompted to prove their identity during onboarding or at any point during their lifecycle.  



## Before Using the System

There are two available methods of ID Proofing withing SecZetta: **Mobile Match** and **Government ID Verification**. Before you begin using IDProofing, please ensure you understand which way you'll be asked to verify your identity and ensure you'll be able to meet system requirements below: 

### SMS Cabable Device - Mobile Match and Government ID Verification
You will need to be able to receive SMS messages so you will need to have a device capable of receipt and enough service to receive.

### Mobile Support - Government ID Verification

Mobile support does not require a special application.  You will need a mobile device with a camera, and access to a mobile browser.  Please see below for further details on compatibility:

|Device Type |OS Version            |Release Date  |
|:-----------|:---------------------|--------------|
|Android	   |5.0 Lollipop or newer |November 2014 |
|iOS	       |12.0 or newer         |September 2018|


### Recommended Browsers - Government ID Verification

|Device Type |Recommended Browser|
|:-----------|-------------------|
|Android     |Chrome             |
|iOS		     |Safari             |


### Supported Document Types - Government ID Verification

Below are the types of documents that can be leveraged to verify user identity details with the Government ID flow.  This service works for roughly 200 countries and 5000 specific types of documents. 

|Document Type           |Supported?|
|:-----------------------|:---------|
|Unknown	               |No        |
|Passport                |Yes       |
|Visa                    |Yes       |
|Drivers License	       |Yes       |
|Identification Card     |Yes       |
|Permit           	     |Yes       |
|Currency	               |No        |
|Residence Document      |No        |
|Travel Document         |Yes       |
|Birth Certificate 	     |No        |
|Vehicle Registration    |No        |
|Other	                 |No        |
|Weapon License          |No        |
|Tribal Identification   |No        |
|Voter Identification    |No        |
|Military	               |Yes       |
|Consular Identification |Yes       |


## Using the System

Identity Proofing will either be initiated as part of an onboarding workflow or you will be contacted to verify your identity by the organization that holds your profile.  Either way, you will be directed to a page within SecZetta where you will select to begin the identity proofing process.

#### In the browswer

- **Click 'Verify My Identity'**
<img src="https://github.com/cchristensen-sz/IdentityProofing/blob/81b5395408fbbc092960212754532fce123a2391/img/Screen%20Shot%202021-05-10%20at%208.41.38%20PM.png" width="50%"/>



- **Select your country**

<img src="https://github.com/cchristensen-sz/IdentityProofing/blob/ea442120a1cf09dfb35cfcd1175db7e312d753e9/img/Screen%20Shot%202021-05-10%20at%208.41.59%20PM.png" width="30%"/>



At this point there are 3 potential verification processes that you may encounter:

1. Mobile Match
2. Government ID Verification
3. Mobile Match fail over to Government ID Verification

Each will be outlined below.

### Mobile Match

### Government ID Verification

- **Select the type of identification** that you'd like to use during the verification process

<img src="https://github.com/cchristensen-sz/IdentityProofing/blob/c79fbe9e78f6722b24b6fb8d6c222c036454c346/img/Screen%20Shot%202021-05-10%20at%208.42.26%20PM.png" width="30%"/>



- **Enter the mobile number** where you wish to receive the SMS notification for continuing with the image capture process

<img src="https://github.com/cchristensen-sz/IdentityProofing/blob/c79fbe9e78f6722b24b6fb8d6c222c036454c346/img/Screen%20Shot%202021-05-10%20at%208.42.54%20PM.png" width="30%"/>



- When you are redirected to your phone, **DO NOT** close your browser window.  You will come back here to complete the verification.

<img src="https://github.com/cchristensen-sz/IdentityProofing/blob/c79fbe9e78f6722b24b6fb8d6c222c036454c346/img/Screen%20Shot%202021-05-10%20at%208.43.14%20PM.png" width="30%"/>


#### On Your Device

- **Click on the link within the SMS message**
<img src="https://github.com/cchristensen-sz/IdentityProofing/blob/1eca0f225fcb9eae2710d35c8e417cf7bbaebfb2/img/SMS.jpg" width="30%"/>



- After reviewing directions **Click 'Start'**
<img src="https://github.com/cchristensen-sz/IdentityProofing/blob/00becd908fb3607babebc5cb8ebe41b899fd02db/img/Begin%20capture%20process.png" width="30%"/>



- Follow on screen prompts and **Click 'Capture Using Your Browser Camera'**
<img src="https://github.com/cchristensen-sz/IdentityProofing/blob/848a7d5add8d1fda1dae36edfe3130373e61d927/img/Front%20ID%20Image.png" width="30%"/>


- **Allow the application to access the camera**. The verification requires no special apps to be installed, but in order to successfully capture images of your ID and your selfie you will have to grant temporary access to the camera via your mobile browser.
<img src="https://github.com/cchristensen-sz/IdentityProofing/blob/848a7d5add8d1fda1dae36edfe3130373e61d927/img/Allow%20Camera%20Access.jpg" width="30%"/>


- **Capture Image**.  If you are using your drivers license or ID this will be the image of the front of your ID.  If you are using your passport this will be the imgage the photo page.  Follow on screen prompts to properly align the image and verify image meets requirements before submitting.  If your image does not meet one of the requirements please review the [Tips and Tricks](https://github.com/cchristensen-sz/IdentityProofing/blob/cac396a002e52069745c8147ce5fbf471945b1ac/img/tips_and_tricks.pdf) document and try again.  Once all requirements have been met, **Click 'Save and Next'**
<img src="https://github.com/cchristensen-sz/IdentityProofing/blob/0b5c9132b7c0bf4eb5eff3fdd8bf766fa171059c/img/Front%20of%20ID.png" width="30%"/> <img src="https://github.com/cchristensen-sz/IdentityProofing/blob/0b5c9132b7c0bf4eb5eff3fdd8bf766fa171059c/img/Front%20of%20ID.png" width="30%"/>


- If you used an ID or a drivers license, you will now begin the process of capturing the image of the back of the document. **CLick on 'Capture Using Your Browser Camera'** to take the second photo.
<img src="https://github.com/cchristensen-sz/IdentityProofing/blob/38de26c7dace4fa4754aff8db93700bd35399abe/img/Back%20of%20ID%20start.png" width="30%"/>
<img src="https://github.com/cchristensen-sz/IdentityProofing/blob/38de26c7dace4fa4754aff8db93700bd35399abe/img/Back%20of%20ID%20Submit.png" width="30%"/>

- Once an acceptable image has been captured, **Click 'Save and Next'**

- **Capture Seflie** by following on screen prompts.  **Click 'Capture Using Your Phone Camera'**. Once captured, if the image is acceptabale you will be redirected back to the browswer window where the ID Proofing process was initiated.




### Mobile Match fail over to Government ID Verification

## Troubleshooting 



