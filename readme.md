<!--
# * * * * * * * * * * * * * * * * * * * * * * * * * * * * *
#  Title: Setup form generator                            *
#  Author: Shashank Shrivastav                            *
#  Email: contactshashank10@gmail.com                     *
#  Date: 2023                                             *
#  Code version: 2.0                                      *
#  Availability: https://github.com/GodOfPerceptionn      *
# * * * * * * * * * * * * * * * * * * * * * * * * * * * * *
-->

`Update :`
1. `Graph Ql is now available`
2. `Easy execution`

Setup form generator:

With the help of this script, you may create setup forms with minimal user input.

Your system has Python 3.9 or a later version installed.

This tool is created only for macOs.

Instructions:

1. Extract the application on `Desktop`. Don't Extract it on any other location.

2. Right-click on the application and click on `Show Package Contents`.

3. Navigate to Contents > Resources.

4. Inside `Resources` run `Packages_installer.sh`. This will install all the required packages, It needs to run once.

5. Now in same folder, open `input.json` file and fill the details according to API documentation as required and save the same file by pressing `command + c`. Read input_file_filling_doc.md for more information about fields.

6. Now run the application.

7. Tool will genrate all the required setup form files in a folder on `Desktop`

> Note: If the favicon is missing from the source url, an error may appear for the svg file. In that situation, you must manually retrieve the svg file.

> Note: Custom authentication flow requires manual change in .clj file so go through the proper documantation.

> Note: Please go through all the documantation gernrated specially .clj file once after genration.

> Note: For any query, error or suggestions please contact to `contactshashank10@gmail.com`.
