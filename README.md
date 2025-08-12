# ns8-etherpad

[Etherpad](https://etherpad.org/) is a highly customizable open source online editor providing collaborative editing in really real-time.

## Install

Instantiate the module with:

    add-module ghcr.io/mrmarkuz/etherpad:latest 1

## Configure

Configure the FQDN and browse to `https://<FQDN>`

## Uninstall

To uninstall the instance:

    remove-module --no-preserve etherpad1

## Update

To Update the instance:

    api-cli run update-module --data '{"module_url":"ghcr.io/nethserver/etherpad:latest","instances":["etherpad1"],"force":true}'
