# project automation tests

uses https://github.com/marketplace/actions/assign-to-one-project

workflow:
1. issue is created through templates at https://github.com/mchelen-gov/project-automation-test/issues/new/choose
1. issue is automatically assigned a label from the template
1. issue is automatically added to a project based on label
*Note: there is some delay while the bot runs, can be monitored at https://github.com/mchelen-gov/project-automation-test/actions*



