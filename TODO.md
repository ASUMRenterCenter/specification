# To Do

* [ ] Documentation on use of UUIDs

Organization

* An updated definition of organization is required
* Year Incorporated - vocabulary talks about 'Date Incorporated' no year
* tax_id - very US specific way of organisation identification
* Legal Status - lacks a codelist where it would be relatively easy to provide one?

Program

* Do program's need alternative names? How often is this an issue?

Service at Location

* I had to add service_id to the table schema
* I had to provide a new definition of e-mail and URL here, assuming these fields were provided for exception cases (e.g. e-mail or the service at this location is different from e-mail at another location).

Required Documents

* These exist in the schema but aren't mentioned elsewhere in the documentation

Eligibility

* The current enum is probably too restrictive for many purposes. We should look for or create a codelist for this

Metadata

* The last action time is a timestamp in docs but date in schema

