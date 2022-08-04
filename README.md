# CloudReader
cross platform (most probably a progressive web app) pdf reader with sync

V1.0
- create account (Google Auth)
- upload/download a pdf document (API gateway -> lambda -> S3 -> CDN)
- web app to view pdf (client <-> CDN)
- remembers your last page (GoogleId + pdfId + PageIndex)
