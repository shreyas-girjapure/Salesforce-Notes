### Apex PMD

#### Installation
1. Download PMD zip from [PMD Home Page](https://pmd.github.io/)
1. Add `C:\pmd-bin-6.49.0\bin` path in the environment variables/ System Variables in your system. Note : Path will be relative [Optional]
3. You must have java set up in you machine

#### Execution
1. `pmd -d C:\Programming\Salesforce\IDFC-Dev\force-app\main\default\classes  -R C:\Programming\Salesforce\IDFC-Dev\ruleset.xml -format summaryhtml --report-file C:\Programming\Salesforce\IDFC-Dev\index.html`
2. Or copy path where `pmd.bat` file is and open cmd in the bin's path.
3. Run this changing respective parameters `pmd.bat -d "D:\classes-scan" -R D:\pmd-bin-6.49.0\ruleset.xml -f summaryhtml  --report-file "D:\pmdReport.html"` 
4. -d is for providing directory to look into
5. -R is the ruleset we are currently using ruleset from LWC recipe of salesforce.
6. --report-file is where the output report is stored
7. There has to be already an existing html file where output can be written into
[Had issues while writing so created a new file for this `index.html` ]
