# Automator workflow

Adds a `Create Slim.cat Link` service to OS X with the default keyboard shortcut of `Cmd+Shift+2`.

It will create a link with a one hour expiry, and will show a notification with the resulting link.

## Usage

* Select text or link
* `Cmd+Shift+2` or right click -> Services -> Create Slim.cat Link
* Wait for notification to pop up in the top right
* Share link

## Installation

```bash
mkdir -p ~/Library/Services
git clone https://github.com/slim-cat/automator-service ~/Library/Services/Slim.cat.workflow
# Reload Services
/System/Library/CoreServices/pbs

# One liner
mkdir -p ~/Library/Services && git clone https://github.com/slim-cat/automator-service ~/Library/Services/Slim.cat.workflow && /System/Library/CoreServices/pbs -update
```
