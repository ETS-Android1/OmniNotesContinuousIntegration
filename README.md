# OmniNotes repository with CI workflow
This repository contains a version of the Android open-source application named Omni-Notes. A workflow using GitHub acions has been set up, that automatically builds and unsigned apk of the application after each push to the repository. Then it uploads the apk as an artifact and send a workflow_dispatch event to another repository, that will test the generated apk.
 
