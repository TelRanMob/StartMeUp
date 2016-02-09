Please, add to this folder Server tests and environments.
Here is the template for test and environement names:
<JiraTaskNumber>_Environement.json
<JiraTaskNumber>_ServerTest.json

Here is the workflow:
1. Intercept request
2. Save it to your collection. Add all necessary scripts and tests. Save files
3. Create environement. Add necessary variables. Make your tests really automated
3. Export yourcollection and environement into repository's Servertest folder, using name templates. 