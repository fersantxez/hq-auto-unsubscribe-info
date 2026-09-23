# Privacy Policy

Effective September 22, 2026.

HQ Auto-Unsubscribe is a personal application operated by its owner on a private
server. It accesses only the Gmail account explicitly configured by its owner.

## Access and use

The application reads message content and headers to identify and authenticate
mailing-list unsubscribe instructions. It uses Gmail modification access to
apply status labels and remove processed messages from the inbox. Although that
Google permission also permits sending email, the application does not send
email or permanently delete messages.

## Storage

OAuth credentials are stored privately on the owner's devices and server.
Processing records contain message identifiers, list hashes, status, timestamps,
and non-content error codes. Email bodies, subjects, and unsubscribe URLs are
not intentionally retained in the processing database or application logs.

## Sharing

The application contacts Google to access Gmail. To unsubscribe, it contacts
the mailing-list provider using the unsubscribe URL or form supplied in the
message. Such requests may include recipient identifiers or tokens already
present in that message. Message content is not sent to an external AI provider.
Data is not sold or used for advertising or model training.

Use and transfer of information received from Google APIs adheres to the
[Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy),
including its Limited Use requirements.

## Control and retention

The owner can stop the service, revoke its access in Google Account settings,
and delete the local credentials and processing database at any time. Processing
records remain until the owner removes them. Archived messages remain in Gmail
and remain subject to the owner's Gmail retention choices.

Maintainer: [fersantxez](https://github.com/fersantxez).

[Home](index.html) | [Terms of use](terms.html)
