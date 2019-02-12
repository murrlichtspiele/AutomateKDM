# AutomateKDM
Downloading and unpacking mail attachments in a mailbox subfolder
# Use case
This script is intended to download KDMs (key delivery messages) for cinema servers from a mail server, unpack them (they are usually packaged in zip files) and ingest them into the cinema server via FTP or SSH. This script is under development at the moment!
## TO-DO:
- Write a attachment parsers for IMAP servers that downloads new KDMs (download works. Distinction between old and new is yet to be implemented.)
- Unpack the ZIP files into a work directory.
- Find out how to automate the ingest process.
  - Server can be started via WOL. FTP can put KDMs on the local drive. Ingest via SSH possible?
  - How to start the projector, aka wake him from sleep? (IMB needed for KDM ingest to work)
- Send a conformation mail with the newly ingested KDMs (EXTRA: Add the expiration dates in the mail.)  

