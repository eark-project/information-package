##Validation of IP compliance with the Common Specification

Hélder Silva has created a small Java command-line tool (by wrapping KEEPS IP manipulation library) that allows to validate a ZIP or folder based SIP (common specification v0.13 syntactic validation) and get an HTML report.
No validation against schemas is attempted in any step of the validation.

Dependencies: Java 8

Where to download it:

https://github.com/keeps/commons-ip/releases/tag/v0.12alpha_for_validation

https://github.com/keeps/commons-ip/releases/download/v0.12alpha_for_validation/commons-ip-1.0.0-alpha12-jar-with-dependencies.jar

Command-line syntax:

java -jar commons-ip-1.0.0-alpha12-jar-with-dependencies.jar "PATH_TO_SIP_ZIP_OR_FOLDER" "PATH_TO_HTML_VALIDATION_REPORT" "TRUE_IF_SIP_SHOULD_BE_DELETED_IN_THE_END"

How to execute (i.e. an example):

java -jar commons-ip-1.0.0-alpha12-jar-with-dependencies.jar "/home/hsilva/Git/eark-information-package/examples/DNA SIP example 1/IP.AVID.RA.18006/" "/home/hsilva/xLinks/Git/roda/validation.html" "false"

PS: no, we will not release a graphical version of it, but you might send feedback from using it or if the tool states things that are not actually true against common specification v0.13;
PS2: it isn't 100% complete, but it's better than nothing.
