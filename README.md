# vendor-manifest-synaptics-astra
Vendor layer manifest for synaptics-astra

## Build Steps
```bash
repo init -u "https://github.com/smuthu065/vendor-manifest-synaptics-astra/" -b develop -m rdke-synaptics-astra.xml
repo sync
MACHINE=synaptics-sl1680-rdke source ./scripts/setup-environment
bitbake lib32-vendor-test-image
```
