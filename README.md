# Salesforce Adapter

The Salesforce adapter provides support for integrating data and control actions between
[Salesforce](http://www.salesforce.com/) and Vantiq.

## Dependencies

The Salesforce adapter must be used with either the 
[MuleSoftt connector](https://github.com/Vantiq/vantiq-connector-MuleSoft)
or the [Zapier connector](https://github.com/Vantiq/vantiq-connector-Zapier).

## Install

This adapter consists of a data component that supports importing data from Salesforce and a 
control component that supports triggering actions in Salesforce.

The Salesforce adapter can be imported into a Vantiq namespace through the CLI:

    % git clone https://github.com/Vantiq/vantiq-adapter-Salesforce.git
    % vantiq -s <profile> import

where `<profile>` provides the credentials for the Vantiq CLI.

## Tutorial

The following tutorial walks through a simple example of installing and using the Salesforce
adapter.

1. Install the [Vantiq connector common](https://github.com/Vantiq/vantiq-connector-common).

2. Install the [MuleSoft connector](https://github.com/Vantiq/vantiq-connector-MuleSoft).

3. Install this Salesforce adapter.
