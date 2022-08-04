# CloudReader
cross platform (most probably a progressive web app) pdf reader with sync

V1.0
1. create account (Google Auth)
2. upload/download a pdf document (API gateway -> lambda -> [(DB), (S3 -> CDN)])
3. web app to view pdf (client <-> CDN)
   
   3.1. viewing PDF [PDFJS by Mozilla](https://mozilla.github.io/pdf.js/examples/)
   
   3.2. CRUD your last page API (API Gateway -> lambda -> DB)
 
 Questions:-
 1. can we just download a page and not entire page of PDF
