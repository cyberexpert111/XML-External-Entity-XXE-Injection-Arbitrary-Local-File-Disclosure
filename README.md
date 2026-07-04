# XML-External-Entity-XXE-Injection-Arbitrary-Local-File-Disclosure
By injecting a malicious XML document containing an external entity, I was able to force the server to process a local file reference. The application returned the contents of the requested system file in the HTTP response, confirming **Arbitrary Local File Disclosure**.
