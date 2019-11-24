# Blueprism-GDPR-SAR-Blueprism
GDPR SAR app using Blue Prism RPA tool
The General Data Protection Regulation (EU) 2016/679 (GDPR) is a regulation in EU law on data protection and privacy for all individual citizens of the European Union (EU) and the European Economic Area (EEA). It also addresses the transfer of personal data outside the EU and EEA areas.
Under the GDPR, individuals have the right to obtain confirmation that their data is being processed and access to their personal data. A Subject Access Request (SAR) is the statuary mechanism by which individuals may exercise these rights to access their personal data and verify the lawfulness of the processing. 
Problem Statement :

To handle the Subject Access Requests (SARs) effectively within the allowed and legal timeframe is a challenge for most of the employers. The amount of information held about individual (wherever in Organization and in whichever form like personnel file, internal memorandums, meeting notes or simply email correspondence) can be vast. Understanding from the outset how to respond to an SAR is crucial because failing to respond can expose the business to a claim, fines, enforcement action and reputational damage
The Solution
RPA Solution (through Blue Prism tool) for Catering SARs:
To serve the SARs, a solution/process using RPA tool Blue Prism, is built. The process (so called BOT) accesses a master spreadsheet containing user’s email and/or other details (if provided) which is kept at the location where BOT can access it. Then the BOT iterate through all the rows of spreadsheet one by one, queries database table(s) to fetch the user’s details and share the fetched details with user (requestor) via email. Finally, a report is shared with Controller of the process to inform about the status of the SARs to state if details were found or not with-in organization’s database (this report is optional, which can be switched off by changing an Environment Variable).

