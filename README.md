# .github

This repository is used for storing workflow templates that can be used by other respositories in this organization.

#### IMPORTANT
##### This repository is required to be Public at this time. Do not store any sensitive data here until GitHub allows support for Private/Internal repositories to be used for shared workflows.
##### More information available here: [https://docs.github.com/en/actions/learn-github-actions/sharing-workflows-with-your-organization](https://docs.github.com/en/actions/learn-github-actions/sharing-workflows-with-your-organization)

# Workflows

| Name | Description | Notes |
|:--------------------:|:--------------------:|:--------------------:|
| ios-framework-pull-request.yml | Use this workflow for iOS Framework Pull Requests. This will run Build & Test as well as generate & log code coverage files. | Configured to not run for "Draft" Pull Requests. |
| ios-generate-xcframeworks.yml | Use this workflow to automatically generate XCFrameworks from Objective-C frameworks. You can generate XCFrameworks from multiple frameworks.  | Configured to automatically commit the generated XCFrameworks to a specified branch (Default=main). |
