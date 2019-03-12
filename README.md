# netbox-fields
Documentation of the relatonship and dependancies of fields in NetBox

## Conventions Used
* Sections (with ## headers) correspond to tabs in the Netbox navigation bar. Trees within each section start with the lowest-order object (the lowest order object has nothing that depends on it in order to exist). Note that the IPAM section has multiple lowest-level objects.
* All available fields are listed under each object.
* A '\*' indicates that this field is required in order to create the object.
* In order to avoid duplicating information, fields that reference other sections contain a reference to that section instead of that object's available fields. (e.g., a Tenant may be assigned to a Rack, but the availble fields for the Tenant object are listed only under the Organization section).
* Tenant Group is listed under the Tenant object, though it is technically a field under several other objects. Selecting a Tenant Group merely narrows the list of Tenants that can be assigned, so this document represents Tenant Group as a field under Tenant to avoid Tenant Group appearing multiple times in a single tree.
