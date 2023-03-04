# :gem: Optical Character Recognition of Receipt using Google Tesseract

Invoices and Receipts are an essential aspect of any trade between two parties, be it between companies or between roadside stores and a consumer. Manually reconciling digital invoices is very time-consuming and can also cause manual human errors.

Extracting information from any document is an uphill task and involves a combination of object classification and object localisation.

OCR digitisation addresses the challenge of automatically extracting, which plays a critical role in streamlining document-intensive processes and office automation in many financial, accounting, and taxation areas.


## :round_pushpin: Dataset

I've used a receipt image to recognize and extract text.

## :round_pushpin: Implementation

   ### :nazar_amulet: Part 1 : Image Segmentation using Open CV
   
   1. Locate receipt contour on the photo
   2. Crop image to the receipt contour
   3. Apply perspective restoration
   
   ### :nazar_amulet: Part 2 : Text Extraction by Google Tesseract
   
   1. Get a scanned version of receipt by restoring perspective (done in the previous notebook)
   2. Apply OCR to find all texts within image
   3. Find grand total as the largest number among recognized texts.
   
   
## :round_pushpin: Results

<p align="center">
  <img width="450" height="250" src="https://user-images.githubusercontent.com/66861391/222886568-15f318cb-1b90-4deb-b852-b28668453980.png">
  </p>
  
  <p align="center">
  <img width="450" height="250" src="https://user-images.githubusercontent.com/66861391/222886589-65ba5684-79b3-4a23-af0a-8f8e44b7a137.png">
  </p>
  
