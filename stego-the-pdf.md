# The PDF

We found this document on a website, and there seems to be something redacted. Could you help us figure out what they tried to hide?

File: flag.pdf

# Solution

We have gotten a pdf file, which by the looks of it just contains an image. The image is very similar to the "Stego - The Image".

![](stego-the-pdf-01.png)

Using "strings" we see there are two image objects in the PDF file.

Open the file in Inkscape and see... Since the page contains two laysers, we can hide and unhide them to see what we get...

Hiding the top layer shows the flag on the background image.

![](stego-the-pdf-02.png)

Flag: RSXC{PDF_REDACTION_NOT_WORKING}