<a href="https://githubsfdeploy.herokuapp.com?owner=FinDockLabs&repo=https://github.com/FinDockLabs/GAD-contact-info-flow&ref=main">
  <img alt="Deploy to Salesforce"
       src="https://raw.githubusercontent.com/afawcett/githubsfdeploy/master/deploy.png">
</a>

# Flow: Add Contact address information to FinDock Gift Aid Declaration

A simple flow that triggers on the creation of a new Gift Aid Declaration (where Postcode or House Number are blank) to copy the address details (Postcode and House Number) to the fields on the GAD.

## Requirements

This flow assumes that you have FinDock and NPSP installed, along with the FinDock for NPSP package, and the Gift Aid for FinDock package. It also assumes you are using the default Mailing Address fields on the Contact, and it's those fields you want to use when populating the address information on the Gift Aid Declaration.

## Installation

Install the and activate the flow (GAD - Create). To deploy the flow to your Salesforce environment, you can:
- use `sfdx`.
- press the "Deploy to Salesforce" button at the top of this README and then press "Login to Salesforce" in the top right of your screen.
- any other deployment method you prefer.

## Notes

This is only meant to be a starter to get you going - feel free to customise this flow to meet the needs of your nonprofit with additional fields and actions.

This repository also include a new custom field on the Contact, and a Metadata Type to help extract the house number / first line of the address.

# Contributing

When contributing to this repository, please first discuss the change you wish to make via an issue or any other method with FinDock before making a change.

# Support

FinDock Labs is a non-supported group in FinDock that releases applications. Despite the name, assistance for any of these applications is not provided by FinDock Support because they are not officially supported features. For a list of these apps, visit the FinDock Labs account on Github. 

# License

This project is licensed under the MIT License - see the [LICENSE](/LICENSE) file for details
