This folder is a fork of https://github.com/OpenNetworkingFoundation/EAGLE-Open-Model-Profile-and-Tools/tree/UmlYangTools.
Every modification made here, is necessary for the 2. ONF MWTN PoC and will be reported to the original project.


# UML to YANG Mapping Tool
This UML to YANG Mapping Tool is developed according to the mapping rules defined in onf2015.261_Mapping_Gdls_UML-YANG.04 by OpenNetworkFoundation(ONF) IMP group.

Version 1.0: Initial version.

Version 1.1: Fix some bugs in version 1.1.

Version 1.2:

-Fix the bug that the tool cannot recognize "uml:UseCase" and "uml:Actor".

-Support both uml and xml files as input. (Thanks for Martin Skorupski's contribution!) 

-Support the notification mapping.

-Support the “support” and “condition” mappings.

-Support the “isOrdered” “valueRange” “passedByReference” mappings for attribute.

-Support the “lifecycle stereotypes” mapping.

-Flexible “key” adding function: the user can assign “key” value of an object by writing the “key” information in key.cfg file.

-Error alert function: cross-reference among “yang module” files. 

-Translated undefined data types in UML to “string” type in YANG.

-Allow translation of some other heading format of UML file.

-Add some complex datatype mapping.

-Add the function that allow illegal characters to be translated to legal characters in YANG identifiers.

Please read "UML-Yang Mapping Tool User Guide-v1.2" for instructions to run the tool.
