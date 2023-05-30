<!--- Paystack PR Template 2018 -->

Description
-----------
<!--- Describe your changes in detail -->

Motivation and Context
----------------------
<!--- Why is this change required? What problem does it solve? -->
<!--- You can link to a Clubhouse bug or Slack message -->

How Has This Been Tested?
-------------------------
<!--- Please describe in detail how you tested your changes. -->
<!--- Include details of your testing environment, and the tests you ran to -->
<!--- see how your change affects other areas of the code, etc. -->
- [ ] Added Unit Tests
- [ ] Tested Locally
- [ ] Tested on Staging

Acceptance Criteria
-------------------
<!--- Describe the acceptance criteria for this feature using a checklist -->
<!--- This should generally be things we can confirm your tests have covered -->
<!--- For example: -->
<!--- Endpoint should accept: bank, account_number, first_name, last_name -->
- [ ] Endpoint should accept: bank, account_number, first_name, last_name

Screenshots (if appropriate)
----------------------------

Types of changes
----------------
<!--- What types of changes does your code introduce? Put an `x` in all the boxes that apply: -->
- [ ] Bug fix (non-breaking change which fixes an issue)
- [ ] New feature (non-breaking change which adds functionality)
- [ ] Breaking change (fix or feature that would cause existing functionality to change)

Checklist
---------
<!--- Go over all the following points, and put an `x` in all the boxes that apply. -->

- [ ] My pull request addresses exactly one patch/feature.
- [ ] I have created a branch for this patch/feature.
- [ ] Each individual commit in the pull request is meaningful. (Please rebase, removing useless commits if not)
- [ ] I have added tests to cover my changes.
- [ ] All new and existing tests passed.
- [ ] My code follows the code style of this project.
- [ ] My change requires change(s) to the environment.
    <!--- Describe the environment changes if any-->
- [ ] My change requires change(s) to the database.
    <!--- Describe the database changes if any-->
    - [ ] I have added a migration file.
- [ ]  My code adds a new endpoint and/or changes the payload/response of an existing endpoint
    - [ ]  Add/Update endpoint on Postman Workspace Collection
        - Update the request body with new fields if applicable
        - Save new examples, if applicable
        - Add details about new fields to description of Postman request
        - Publish updated collection
    - [ ]  Add updated collection link to PR Description
    - [ ]  Ensure it has been checked by the owner of associated codebase (e.g Wale for Paystack API)
- [ ] Other information.
