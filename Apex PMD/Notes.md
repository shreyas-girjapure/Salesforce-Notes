### Apex PMD

#### Installation
1. Installation is straightforward , need to add path in the system environment variable
2. You must have java set up in you machine

#### Execution
1. pmd -d C:\Programming\Salesforce\IDFC-Dev\force-app\main\default\classes  -R C:\Programming\Salesforce\IDFC-Dev\ruleset.xml -format summaryhtml --report-file C:\Programming\Salesforce\IDFC-Dev\index.html
2. -d is for providing directory to look into
3. -R is the ruleset we are currently using ruleset from LWC recipe of salesforce.
4. --report-file is where the output report is stored