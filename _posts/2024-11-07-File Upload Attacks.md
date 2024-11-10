---
title: File Upload Attacks
tags: Cybersecurity HackTheBox

---

Learnings from File Upload vulnerability.

The module tackles about what is the file upload vulnerability, the types of filters usually used and why they are utilized, 
and how to mitigate these kinds of vulnerabilities.

File Upload vulnerability utilizes nonvalidated file uploads to execute malicious code. These can be in the example of uploading
a PHP script that wasn't validated by the website which in turn can cause damage such as exploitation of certain data.

There are different filters discussed in the module.

Client Side Filter- This is where files are filtered through a function such as Javascript. 

This happens on the server side:
Blacklist - This is where certain file extensions are not allowed to be uploaded. This relates file extensions that are not what the site requires.
Whitelist - these are the files allowed to be uploaded.
Type filters - This involves the type of file being uploaded.
Mime Type Filters - This involves the format of the filter.

The module also discussed the ways this can be prevented such as extension and content validation, and Upload Disclosure.



