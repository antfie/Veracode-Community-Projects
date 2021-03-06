Veracode Community Open Source Projects
=======================================

A collection of useful open source projects that integrate with the Veracode APIs to automate scanning, results retrieval and other tasks. 

These projects are community contributed and not supported by Veracode. For a list of supported projects, please see the listing of projects on [Veracode.com](https://www.veracode.com/products/core-platform-and-architecture/apis-and-plugins).

Automating common Veracode Platform tasks
-----------------------------------------
* [VcodeAutoMitigate](https://github.com/brian1917/vcodeAutoMitigate) ([Brian1917](https://github.com/brian1917/)) - Command line app that mitigates flaws in Veracode based on CWE, scan type, and specific text in the description.

* [VcodeMitigationExpire](https://github.com/brian1917/vcodeMitigationExpire) ([Brian1917](https://github.com/brian1917/)) - Utility designed to be run on a regular cadence (e.g., weekly cron job) to expire mitigations. The types of mitigations, expiration references, and other settings are controlled in a JSON config file.

* [Veracode Break the Build by Severity](https://github.com/christyson/Veracode-Break-The-Build-By-Severity) ([Christyson](https://github.com/christyson/)) - This project contains three python scripts useful for working with Veracode projects in a build pipeline to break the build if any findings of a given severity or higher are found.

* [Veracode mitigation copier](https://github.com/brian1917/veracode-mitigation-copier) ([Brian1917](https://github.com/brian1917/)) - Copies mitigations from one Veracode profile to another if it's the same flaw based on the following flaw attributes: issueid, cweid, type, sourcefile, and line. The script will copy all proposed and accepted mitigations for the flaw. The script will skip a flaw in the copy_to build if it already has an accepted mitigation.

* [Veracode BCA Builder](https://github.com/brian1917/veracode-bca-builder) ([Brian1917](https://github.com/brian1917/)) - Shell script to generate the BCA package to scan an iOS app.

* [Veracode Sandbox Mitigated Unique Findings](https://github.com/ctcampbell/veracode-sandbox-mitigated-unique-findings) ([Ctcampbell](https://github.com/ctcampbell)) - This script will pull all open findings across all sandboxes for all applications and calculate which mitigated (proposed, accepted, or rejected) findings only exist in a single sandbox, and therefore may be deleted when the sandbox is deleted.

Developer tools
---------------

* [Ansible](https://github.com/telusdigital/ansible-veracode-scanner) ([Telus Digital](https://github.com/telusdigital)) - allows uploading and scanning with Veracode from Ansible, with an option to send results to a Slack channel

* [Bamboo](https://gitlab.com/buzzcode/Bamboo-Veracode) ([Buzzcode](https://gitlab.com/buzzcode/)) - full featured Bamboo plugin including configuration UI, wait for scan to complete, and "break the build" functionality

* [Bamboo/Jira](https://github.com/buildcom/VeracodeAtlassianPlugin) ([Buildcom](https://github.com/buildcom/)) - provides a pair of simple plugins for upload and results handling from within Bamboo, and a lightweight script to create Jira issues (archived project)

* [CircleCI](https://github.com/unregistered436/veracode-integrations/tree/master/shell-script) ([Unregistered436](https://github.com/unregistered436)) - Veracode Upload and Scan Shell Script, originally written for CircleCI but can be used for any build system that can run a shell script in bash.

* [ConcourseCI, Gitlab, Travis](https://github.com/ctcampbell/veracode-ci-examples) ([Ctcampbell](https://github.com/ctcampbell)) - Example configurations for integrating Veracode scanning in various continuous integration systems.

* [Concourse (Veracode-Resource)](https://github.com/cardinal-health/veracode-resource) ([Cardinal Health](https://github.com/cardinal-health)) - A concourse resource-type to allow publishing and retrieving scan results from Veracode.

* [Dynamic Scan and Wait for Result](https://github.com/christyson/dynamic-scan-and-wait-for-result) ([Christyson](https://github.com/christyson/)) - Extends the Java API Wrapper to provide "break the build" style scanning. Includes instructions on how to integrate this workflow into Jenkins.

* [easy_sast](https://github.com/seisollc/easy_sast) - A [docker container](https://hub.docker.com/r/seiso/easy_sast) for use in CI pipelines which integrates with Veracode's static analysis tool.

* [Flowdock](https://github.com/brian1917/vcodeFlowdockNotifier) ([Brian1917](https://github.com/brian1917/)) - Utility designed to be run in a build process after a Veracode scan to notify a Flowdock flow that the scan completed. Optional to include policy compliance info in notification.

* [Gradle](https://github.com/calgaryscientific/veracode-gradle-plugin) ([CalgaryScientific](https://github.com/calgaryscientific), based on [Kctang](https://github.com/kctang/)) - Set of Gradle tasks, usable either as a command line submission tool or integrated as part of a continuous integration build process, to perform Veracode submission for applications and scan results for flaws.

* [Insomnia](https://github.com/ctcampbell/insomnia-plugin-veracode-hmac) ([Ctcampbell](https://github.com/ctcampbell/)) - Adds an HMAC authentication header to Veracode API requests in Insomnia.

* [Jenkins (Jenkins Shell)](https://github.com/ian-c-leonard/veracode_jenkins_shell) ([Ian C Leonard](https://github.com/ian-c-leonard)) - unofficial Veracode shell integration for Jenkins Freestyle projects.

* [Postman pre-request authentication header](https://gist.github.com/ctcampbell/c82d895b0940c08408fb1800aa6718b0) ([Ctcampbell](https://github.com/ctcampbell/)) - Postman pre-request to add Veracode HMAC header.

* [PowerShell](https://github.com/unregistered436/veracode-integrations/tree/master/powershell) ([Unregistered436](https://github.com/unregistered436)) - PowerShell script for pushing binaries to Veracode using Java API.

* [Slack](https://github.com/ctcampbell/veracode-slack-slash-command) ([Ctcampbell](https://github.com/ctcampbell)) - AWS Lambda commands that provide the ability to access Veracode application and build information from Slack.

* [Sbt-veracode](https://github.com/sullis/sbt-veracode) ([Sullis](https://github.com/sullis/)) - sbt plugin for Veracode.

* [SonarQube](https://gitlab.com/buzzcode/SonarQube-Veracode) ([Buzzcode](https://gitlab.com/buzzcode)) - Unofficial Veracode plugin for SonarQube.

* [Veracode QuickScan](https://github.com/relaxnow/veracode-quick-scan) ([relaxnow](https://github.com/relaxnow)) - PHP example of how to connect to the APIs, scan a couple of files and get results.

* [veracode-tools](https://github.com/ctcampbell/veracode-tools) ([Ctcampbell](https://github.com/ctcampbell)) - Docker image with all Veracode tools pre-installed. 

* [Veracode Upload and Scan Shell Script](https://github.com/christyson/Veracode-Upload-and-Scan-Shell-Script) ([Christyson](https://github.com/christyson/)) - A shell script to upload and scan a application (zip or war etc.) and create the application if necessary. Uses Curl and hmac headers.

* [XebiaLabs Release Veracode Plugin](https://github.com/xebialabs-community/xlr-veracode-plugin) ([XebiaLabs-Community](https://github.com/xebialabs-community)) - XL Release for Veracode test automation.


Results collection and display
------------------------------

* [Excel (XLS)](https://github.com/Komiblanka/Veracode2xls), [(XLSX)](https://github.com/Komiblanka/Veracode2xlsx) ([Komiblanka](https://github.com/Komiblanka/))- Python scripts to format Veracode XML results into Excel workbook formats for easier human consumption.

* [Hygieia](https://github.com/mickfeech/hygieia_veracode_collector) ([Mickfeech](https://github.com/mickfeech/)) - Veracode scan collector and parser for the [Hygieia dashboard](https://github.com/Hygieia/ExecDashboard).

* [JupiterOne](https://github.com/JupiterOne/jupiter-integration-veracode) ([JupiterOne](https://github.com/JupiterOne/)) - A JupiterOne managed integration for Veracode.

* [JupiterOne Graph Veracode](https://github.com/JupiterOne/graph-veracode) ([JupiterOne](https://github.com/JupiterOne/)) - A graph conversion tool for Veracode.

* [SCA Extractor](https://github.com/brian1917/vcodeSCAExtractor) ([Brian1917](https://github.com/brian1917)) - Creates a CSV file with open source vulnerability (SCA) findings for all builds in the input file.

* [Stats](https://github.com/ctcampbell/veracode-stats) ([Ctcampbell](https://github.com/ctcampbell)) - Summary statistics for a Veracode account on the command line.

* [Veracode Report Converter (CSV)](https://github.com/dipsylala/VeracodeReportConverter-Windows) ([Dipsylala](https://github.com/dipsylala/)) - .NET Framework utility to extract useful data from Detailed Report XML file into CSV format

* [Veracode Report Converter - Portable (CSV)](https://github.com/dipsylala/VeracodeReportConverter-Portable) ([Dipsylala](https://github.com/dipsylala/)) - .NET Core utility to extract useful data from Detailed Report XML file into CSV format

* [veracode-to-csv](https://github.com/ctcampbell/veracode-to-csv) ([Ctcampbell](https://github.com/ctcampbell)) - This script outputs one CSV file per scan per application profile visible in a Veracode platform account. The output can be imported into  Splunk for further analysis.

Sample CI/CD configuration files
---------------------------
* [Veracode Azure YML Samples](https://github.com/Clintpollock/VeracodeAzureYMLSamples/) ([Clintpollock](https://github.com/Clintpollock)) - Samples of Azure YML files that work with Veracode scanning
* [Veracode Dynamic Analysis Azure Sample](https://github.com/jphillips-vc/Veracode-Dynamic-Analysis-Azure-Example) - ([Jphillips-vc](https://github.com/jphillips-vc/)) - Veracode Dynamic Analysis Azure Sample including script based authentication, and ISM configuration.
* [veracode-scripts](https://gitlab.com/aszaryk/veracode-scripts) - Various example scripts for Jenkins and GitLab pipelines, including both static and dynamic examples.

Application vulnerability correlation
-------------------------------------

* [DefectDojo](https://github.com/DefectDojo/django-DefectDojo) - DefectDojo is an open-source application vulnerability correlation and security orchestration application. DefectDojo supports importing Veracode results.

HMAC Signing libraries
----------------------
Projects in this category implement HMAC digest signing, which is required to use Veracode APIs that use a [Veracode ID and Key](https://help.veracode.com/reader/lsoDk5r2cv~YrwLQSI7lfw/Z70twkx761Oc2RjWUDAWFA). Also see the Postman and Insomnia examples above in Developer Tools.

* [auth.js](https://gist.github.com/ThibaudLopez/fe1baeaa4461cbf0bfa8fd258ff43243) - Veracode custom HMAC request signing algorithm (used for API authorization), written in JavaScript -- uses Web Crypto API instead of the Node Crypto library

* [PythonHMAC](https://github.com/veracode/veracode-python-hmac-example) - simple example of usage of the Veracode API signing library provided in the Veracode Help Center

* [NodeJS](https://gist.github.com/mrpinghe/f44479f2270ea36bf3b7cc958cc76cc0) - NodeJS lib, written in JavaScript, to generate authorization header with Veracode API Key and ID. Sample usage in the comment of the gist

* [vcodeHMAC](https://github.com/brian1917/vcodeHMAC) ([Brian1917](https://github.com/brian1917/)) - Go package that creates an authorization header using Veracode API Key and ID.

* [vcodeHMAC-CLI](https://github.com/brian1917/vcodeHMAC-CLI) ([Brian1917](https://github.com/brian1917/)) - CLI tool to generate an authorization header for Veracode APIs using API ID and Key. Given an HTTP method and URL, and the location of your Veracode API credentials file, you will get the value of an Authorization header printed out for piping into curl, httpie, or other scripting uses.

* [veracode-go-hmac-authentication](https://github.com/antfie/veracode-go-hmac-authentication) ([antfie](https://github.com/antfie/)) - A simple Go package that follows the format of the existing HMAC Authentication Examples found at https://help.veracode.com/reader/LMv_dtSHyb7iIxAQznC~9w/CUv4heF9z9tOBnZ1uiB8UA.

* [Using curl and openssl to access the Veracode API endpoint](https://gist.github.com/m9aertner/7ae804a5297617456f81c8b5a3a9305b) ([m9aertner](https://gist.github.com/m9aertner)) - short article illustrating use of built-in shell tools to handle HMAC signing and send API requests from the command line.

API wrappers
------------

* [Go wrapper](https://github.com/brian1917/vcodeapi) ([Brian1917](https://github.com/brian1917)) - Wrapper written in Go for easy use of Veracode APIs

* [node-veracode-api-client](https://github.com/m4l1c3/node-veracode-api-client) ([M4l1c3](https://github.com/m4l1c3/)) - Node.js API client.

* [veracode-api (Ruby)](https://github.com/mort666/veracode-api) ([Mort666](https://github.com/mort666/)) - Ruby Wrapper for the Veracode API.

* [veracode-api-clients](https://github.com/jourzero/veracode-api-clients) ([Jourzero](https://github.com/jourzero/)) - Client code using the Veracode REST and XML APIs. Includes handlers for Veracode Dynamic Analysis scanning.

Other integrations
------------------

* [Bash shell](https://github.com/aparsons/Veracode) ([Aparsons](https://github.com/aparsons/)) - Bash script for scanning a directory of code with the Veracode platform.

* [F5 WAF](https://github.com/julz0815/veracode-dynamic-2-F5-waf-export) ([Julz0815](https://github.com/julz0815/)) - Transforms Veracode dynamic result files into the F5 generic scanner result format for import into the F5 web application firewall.

* [verapi](https://github.com/fsclyde/verapi) ([Fsclyde](https://github.com/fsclyde/)) - Lambda function for automating Veracode static scans

* [veracode-api (Node)](https://github.com/kinichahau87/veracode-api) ([Kinichahau87](https://github.com/~kinichahau87)) - Node.js package for automating Veracode scanning from the command line.

* [Veracode-cli](https://github.com/adidas/veracode-cli) ([Adidas](https://github.com/adidas)) - Automated way to check application status and DevSecops compliance.

* [Veracode Notifier](https://github.com/ctcampbell/veracode-notifier) ([Ctcampbell](https://github.com/ctcampbell)) - Lambda function that sends a message to a web hook, for instance for use with Slack

Secure coding examples
----------------------

* [Secure cryptography examples for Java](https://github.com/1MansiS/java_crypto) ([1MansiS](https://github.com/1MansiS/)) - Code samples showing how to use the Java Crypto API securely. Accompanying code for the [Java Crypto blog series](https://www.veracode.com/blog/research/how-get-started-using-java-cryptography-securely).


Insecure applications
---------------------

* [VeraDemo](https://github.com/jtsmith2020/verademo-java) ([Jtsmith2020](https://github.com/jtsmith2020/)) - Sample insecure application written in Java and Javascript, showing vulnerabilities in realistic Java code.

* [NodeGoat](https://github.com/buzzcode/NodeGoat) ([Buzzcode](https://github.com/buzzcode/)) - NodeGoat, built w/CircleCI, showing how to use a yaml file to scan w/Veracode.
