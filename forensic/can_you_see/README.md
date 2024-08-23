# Can you see

## EASY

in this challange you will get file zip `unknown.zip`. In this file you'll get `ukn_reality.jpg`.
with hint 

>How can you view the information about the picture?

>If something isn't in the expected form, maybe it deserves attention?

To solve this chall you can use `exiftool` that used to look metadata of file.

![solved](https://private-user-images.githubusercontent.com/124356996/360962129-3cbafda0-efcd-4dcb-8506-5058c2f9b087.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjQ0MjM2OTcsIm5iZiI6MTcyNDQyMzM5NywicGF0aCI6Ii8xMjQzNTY5OTYvMzYwOTYyMTI5LTNjYmFmZGEwLWVmY2QtNGRjYi04NTA2LTUwNThjMmY5YjA4Ny5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwODIzJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDgyM1QxNDI5NTdaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT0xZjQ4MDkzZmQzZTRmZjNjODUxYmMwMWExZTA1ZmVkODY1ZDM2NDdhMTM5ZGUwMDM3ZGFiNGVmNWJhZTFkZTkwJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.bVv4g2glhqmFEGhs3M_7H21UYxqVwz9MTO3bWFVkjnU)

As you can see, in the metadata there's a base64 string, we can decode it and get the flag.

## FLAG

>picoCTF{ME74D474_H!DD3N_********}