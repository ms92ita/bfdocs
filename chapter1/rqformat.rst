Request formatting
==================

Our services supports the SSL encryption using standard HTTPS mwthods such as GET and POST.

When submitting input parameters with your request, these are encoded either in the query string for GET requests, or in the body of a POST request using commonplace url encoding of key-value pairs (application/x-www-form-urlencoded).

As described above in the Introduction, or service supports the ODATA standard, so the default response data format implements the AtomPub format., but you can use other formats as JSON or XMLincluding the appropriate Accept header (Accept: application/json) or the OData paramenter $format in the query string.