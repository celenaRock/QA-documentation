# QA-documentation

# writing-documentation

## Gamestop Test Plan

## Introduction:
1. Purpose: purpose of document and short summary of the main sections
2. Project overview: Brief description of the project and software to be tested
3. Intended audience: Who are they and what is their role in the testing process
* May also include methods to be used, brief description of out-of-scope items, and related documents such as Requirements

## Test Strategy
1. Test objectives: What will you test and why, what is in and out of scope. Common test types: Module, Integration, Acceptance, Beta
2. Test assumptions: Conditions that must be true in order to successfully test 
   * Realistic data is available
   * Skills and knowledge of testing resources are adequate
   
3. Test principles: 
   * Test processes will be well defined but flexible
   * Test environment and data will match production
   * Testing will be divided in phases that build sequentially
   
4. Data approach: Describe the data that will be loaded or not loaded for tests
5. Scope and levels of testing: UAT
   * Validates business logic
   * Performed by end users
   * Test team will write tests based on input from business analyst and end users
   * Testing will be performed after all other testing is complete
   
6. Estimated effort and resources: List all activities to be performed by the QA team, along with estimated effort hours

## Execution Strategy
1. Entry and exit criteria: 
   * Example Entry: All test data is loaded into the environment 
   * Example Exit: Pass rate of 95% of test scripts
   
2. Test cycles: How many cycle will be executed along with the objective for each. 
   * Example: Functional testing will occur in two cycles
   * The first cycle identifies critical defects
   * The second cycle identifies medium and low defects and validates corrections for first cycle defects
   
3. Defect management: 
   * Identify how defects are identified and labeled: critical, high, medium)
   * tracking tools (JIRA, etc.)
   * What needs to be documented when opening a defect
   * Roles and responsibilities
   
4. Metrics: Outline metrics to be reported and frequency
   * Weekly: % complete, % pass, % fail
   * Weekly: Status report
   * Daily: Critical defects
   
5. Defect tracking and reporting: Define the process/flow for tracking and reporting defects

## Test Management Process
1. Test management tool: Provide details about tools used to manage tests
   * Location
   * Permissions required
   * Reports
   
2. Test design process
   
3. Test execution process
   * Tester executes each step in the test case
   * Mark status as Pass or Fail
   * Raise defects as needed
   * Participate in Triage meetings to help route defects as appropriate
   
4. Test risks and mitigation factors: Call out risks and mitigation plans
   * Resources (people and money)
   * Schedule
   * Scope
   * Defects
5. Communications plan: How will communication happen and who will be involved
   * Meetings
   * Emails
   * Status reports
   * In-tool communications
   
6. Roles: Identify roles on the project, with name and contact information
   * Project manager
   * QA lead
   * QA team
   * Business analyst
   * Development lead
   * Development team
   * Stakeholders

## Test Environment
1. Location of software to be tested
2. Permissions
3. Hardware and software required for testers
4. Contact information for support

