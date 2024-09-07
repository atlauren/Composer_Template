# Script-only package template for JAMF Composer

This repo is a template for files and folders comprising a script-only macOS package, for use within JAMF Composer.
1. Rename the main folder to your intended package name: `com.domain.scriptonly`
2. Rebame the folder under `ROOT/tmp/` to match your package name: `ROOT/tmp/com.domain.scriptonly`
3. Edit the `postflight` script as needed.
4. Drag the main folder to JAMF Composer's Sources.
5. Compile.

Iterate steps 3 and 5 as needed.
