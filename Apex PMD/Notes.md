### Apex PMD

#### Installation
1. Download PMD zip from [PMD Home Page](https://pmd.github.io/)
1. Add `C:\pmd-bin-6.49.0\bin` path in the environment variables/ System Variables in your system. Note : Path will be relative
2. You must have java set up in you machine

#### Execution
1. pmd -d C:\Programming\Salesforce\IDFC-Dev\force-app\main\default\classes  -R C:\Programming\Salesforce\IDFC-Dev\ruleset.xml -format summaryhtml --report-file C:\Programming\Salesforce\IDFC-Dev\index.html
2. -d is for providing directory to look into
3. -R is the ruleset we are currently using ruleset from LWC recipe of salesforce.
4. --report-file is where the output report is stored
5. There has to be already an existing html file where output can be written into
[Had issues while writing so created a new file for this `index.html` ]