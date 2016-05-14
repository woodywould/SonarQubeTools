# SonarQubeTools

##Generating reports from SonarQube

As SonarQube reporting plugins are quite expensive, here's some ways to query the SonarQube rest APIs to generate useful summaries and reports.

http://localhost:9000/api/issues/search?componentRoots=your.component.root&severities=BLOCKER,CRITICAL&facets=severities&ps=500&s=SEVERITY
