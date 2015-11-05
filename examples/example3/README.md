# Example 1

Example of a SIP, AIP and DIP of the following scenario:

TODO scenario description

## Submission (SIP)
The producer wishes to submit a text document accompanied by metadata in Dublin Core format.

The text document was originally created in Microsoft Word 97-2004 format (.doc)
and was later converted by the producer to the Microsoft Word Open XML format (.docx).

Both formats are to be sent to the archive.

The SIP comes with no PREMIS information and no schemas.

TODO link to SIP and explain its content

## Ingest: SIP to AIP process

On the SIP to AIP process the SIP was copied under the submission folder of the AIP.
Also, PREMIS was generated for files and schemas were added.

On ingest a preservation event was created to document the action performed on the ingest.

Also, after ingest, a file format migration was performed on the object,
converting the Word file into a PDF.

But, as users required a version of the documents that would be easier to reuse,
another representation was created, migrating the original Word document into a
OpenOffice text document (.odt).

## Archival (AIP)

TODO link to the AIP and explain its content

## Dissemination (DIP)

A user requests access to the information on this AIP. The formats it requests are
PDF for presentation reliability and OpenOffice for ease to reuse.

TODO describe the dissemination use case
TODO link to the DIP and explain its content
