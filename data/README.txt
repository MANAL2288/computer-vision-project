Dataset — Project 3: Barcode & QR Code Scanner and Localizer
=============================================================
Course      : Introduction to Computer Vision
Institution : ESIN, UIR — Spring 2026
Instructor  : Ilias TOUGUI
=============================================================

Contents
--------
This folder contains the input images used to test the
scanner pipeline. All images were found or captured manually.

Image sources:
  - Photos taken with a smartphone (real product barcodes)
  - Screenshots of QR codes displayed on screens
  - Downloaded sample images (libre/open licence)
  - Synthetically generated QR codes with controlled noise and uneven
  lighting (to demonstrate Non-Linear Filtering concepts)

Input images (13):
  Barcodes (1D):
  - BarCode_QRCode.png  : image with 1D barcode + QR code (mixed)
  - Barcode1.jpeg       : real product barcode photo (smartphone)
  - BarCode2.jpg        : EAN-13 product barcode
  - BarCode3.jpg        : EAN-13 product barcode
  - BarCode4.jpg        : EAN-13 product barcode
  - BarCode5.jpeg       : EAN-13 product barcode
  - BarCode6.jpeg       : real product barcode photo
  - BarCode7.jpeg       : real product barcode photo

  QR Codes (2D):
  - QRCode1.png         : QR code with salt-and-pepper noise
                          (demonstrates Median Filter — Non-Linear Filtering)
                          Sans Median : non decodable
                          Avec Median : decode "1005"
  - QRCode2.jpg         : QR code (standard)
  - QRCode3.jpg         : QR code (standard)
  - QRCode4.png         : QR code with uneven lighting
                          (demonstrates Adaptive Threshold — Non-Linear Filtering)
  - QRCode5.png         : QR code (standard)

Code types present:
  - QRCODE : square matrix codes (URL, text, numeric payloads)
  - EAN_13 : standard 13-digit retail product barcode
  - UPC_A  : 12-digit North American retail barcode

=============================================================
Group Members:
  - IKRAM OIALILI
  - MANAL SAWLI
  - SAOUSAN ELHAROUCHI
=============================================================