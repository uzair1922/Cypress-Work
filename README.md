# Cypress-Work
# Drips Class

The Drips class is a JavaScript class that extends the functionality of the Emails class by providing additional methods for verifying various behaviors related to drip campaigns.

## Installation

No installation is required as this is a standalone JavaScript class.

## Usage

1. Import the required functions and the Drips class:

```javascript
import { interceptGqlRequest, generateRandomName } from "../../../utils/helpers";
import Emails from "../.."; // Make sure to provide the correct relative path to the Emails class
import Drips from "./Drips"; // Make sure to provide the correct relative path to the Drips class
Create an instance of the Drips class, passing the required parameters to the constructor:
javascript
Copy code
const drips = new Drips({ EMAIL_TYPES: ... }); // Provide the required EMAIL_TYPES parameter
Use the available methods to verify different behaviors related to drip campaigns. For example:
javascript
Copy code
drips.verifyAddNewEmailToDripSequence();
Methods
The Drips class provides the following methods:

verifyAddNewEmailToDripSequence(): Verifies the behavior of adding a new email to a drip sequence.
verifySettingsModalToggleBehaviour(): Verifies the behavior of the settings modal toggle.
verifySettingsModalSelectListBehaviour(): Verifies the behavior of selecting a list in the settings modal.
verifyEditScheduleTimeModalInputMain(): Verifies the behavior of editing the schedule time using an input field.
verifyEditScheduleTimeModalSelectMain(): Verifies the behavior of editing the schedule time using a select dropdown.
verifyDeleteDripEmailFromMain(): Verifies the behavior of deleting a drip email from the main view.
verifyEditDripEmailFromMain(): Verifies the behavior of editing a drip email from the main view.
verifyReportDripEmailFromMain(): Verifies the behavior of reporting a drip email from the main view.
verifyDuplicateDripEmailFromMain(): Verifies the behavior of duplicating a drip email from the main view.
verifyDeactivateDripEmailFromMain(): Verifies the behavior of deactivating a drip email from the main view.
verifyActivateRouteDripEmailFromMain(): Verifies the behavior of activating a route drip email from the main view.
verifyEditDripCampaignName(): Verifies the behavior of editing the drip campaign name.
Contributing
Contributions to this project are not accepted as this code is specific to a particular use case.
