# Automator workflow

Adds a `Create Slim.cat Link` service to OS X with the default keyboard shortcut of `Cmd+Shift+2`.

## Installation

```bash
mkdir -p ~/Library/Services
git clone https://github.com/slim-cat/automator-service ~/Library/Services/Slim.cat.workflow
# Reload Services
/System/Library/CoreServices/pbs

# One liner
mkdir -p ~/Library/Services && git clone https://github.com/slim-cat/automator-service ~/Library/Services/Slim.cat.workflow && /System/Library/CoreServices/pbs -update
```
