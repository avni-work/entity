# 3rd August 2021

**Minutes of Meeting**

1. Cypress is being used for Automation of the testing in all the teams
2. Currently Night watch is being maintained to make it stable and work well for the existing test scenarios
3. Patrick and Riyaz have good knowledge on Cypress. Divya & Rai are learning and implementing it in their projects.
4. Cypress doesn’t allow cross platform integration, esp. with Keycloak, and it is challenge currently.
5. Cypress has limitation of only one browser, Chrome.
6. All the teams will be using same repo for Cypress scripts/project.
7. GitHub actions need to be implemented separately for individual teams.
8. Currently the QA Guild is not done however, the team meet / communicate between selves over call or chat and discuss on the required topics.
9. In Cypress, for customized reports we can take the required subscriptions which will cost around $200 / Year.
10. Currently there is no need to write the manual test cases in each team and this can be done, if required.
11. There is no documentation available on the QA process. All the Demo items should be in Test env.
a. The QA process followed is, Developer Check-in -> Staging (DEV Env) -> UX Assurance -> Ready for QA (DEV Env) -> QA in Progress (DEV Env) -> Done -> Prod Release -> Closed.
12. Test and Prod env should be same enough so that any Prod bug raised can be validated in TEST env.
13. In Assets and Entities team, the testing is done in Dev env. However, Relationships team does the testing in Test env.
14. Riyaz is pushing the code from Dev to Test and from Test to Prod envs. May be relationships team can follow the same i.e. QA pushing the builds from Dev to Test and from Test to Prod.

**Action Items**

1. Riyaz to work Jason (and Sateesh & Jinghua) to understand the Bugs (Ops / Prod / Internal / Sentry) raised and generate a metrics for reporting.
2. Sateesh to setup a monthly Guild meeting to discuss on the status of the metrics, tools and processes and any other topics.
3. Sateesh / Jyoti to discuss with the relationships team to follow the QA process which other teams are following.
a. Can testing to be done in Dev env?
b. Can QA push the builds between the envs (Dev to Test to Prod)?

---