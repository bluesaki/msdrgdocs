# MSDRGDocumentation

MS-DRG App User Guide

This is a test 123
Testing nore tuff!!


# Header1
### Header 2
---

Paragrah 1

Paragrah 2

Para 3

_italic text_

__Bold Text__


Links

[Googles home page](https://google.com)

Image

![Unsplash image](https://unsplash.com/photos/GkS6GPZC5dk "unsplahx")


1. Apples
    1. qaz
    2. edcwsx
2. Orenges
3. Mango


| Name        | Item         | Price  |
| ----------- |:------------:| ------:|
| Holly       | Toot  brush  | $1.50  |
| Jim         | Tootpaste    | $7.50  |





# User Guide
MediRegs provides an integrated MS-DRG Grouper & Calculator that  simulates MS-DRG grouping and payment under the Inpatient Prospective Payment System (IPPS). The MS-DRG Analyzer upgrade extends the Grouper & Calculator functionality  to allow for batch processing of coding data and deeper payment analysis. These tools are excellent companions to the codebooks, payment books, and the Code Explorer tool.

## Background Information
The MS-DRG Grouper utilizes ICD diagnosis and procedure codes to group into Medicare Severity Diagnostic Related Groups (MS-DRG) under the Medicare Inpatient Prospective Payment System (IPPS). The grouper logic is provided by the Centers for Medicare and Medicaid Services (CMS); the interface to that logic allows entry of a claim manually or with a batch upload and results are provided on screen or in downloadable format.

The MS-DRG Calculator & Analyzer performs a provider-specific calculation of the MS-DRG assigned. The calculator logic uses the IPPS Final Rule Table 5 for MS-DRG weights, and the CMS IPPS Final Rules and PC-Pricer for provider variables.

_Note: Depending on the level of access you have subscribed to, up to 5 to 10 years of archives are available._


### Using the Integrated MS-DRG Grouper, Calculator, & Analyzer
When you first enter the calculator, you will have options based on your subscription level:
1. If you already know the MS-DRG codes, click on the Calculator link in the left menu for a simplified data entry panel.
2. If you want to group a single claim for which you have ICD diagnosis and procedure code, click on the Grouper link for a more detailed data entry panel.
Note: Users who have upgraded to the MS-DRG Analyzer also can group up to 200 claims at once using a simple .csv file upload feature.
3. If you want to perform more complex payment analyses, including outlier, state, county, per diem calculations or other comparisons, like between providers or discharge dates, click on the Analyzer link. 


# USING THE CALCULATOR TOOL

__To calculate payment by entering MS-DRG codes.__
If you already know the MS-DRG code(s), click on the Calculator link. The Calculator data entry panel allows you to enter Provider ID, Date of Service, and MS-DRG Code(s). Required fields are marked with a red asterisk. You can enter a single or multiple MS-DRG codes (separated by commas or spaces), and calculate the national unadjusted or provider-specific adjusted payment.

__Step-by-Step Instructions__

1. Enter the Provider ID by:
a. Typing the name of the hospital in the Enter Provider ID box. As you type, notice auto-suggest options that you can click on;
b. Click the National Unadjusted link above the entry box, if you want to calculate the national unadjusted rate; or,
c. Click on Defaults above the entry box to use the default provider. How to set up default providers is explained later in this document.
_TIP: Use the Search feature to identify a provider ID by Name, ID, Zip, State, City, County or Address. After entering your search term, select the appropriate provider._
2. Enter one or more MS-DRG(s) in the MS-DRG Code input box separated by commas or spaces. Click on the Search link to search by MDC or MS-DRG that auto-suggests based on your search. You can select a single code or a list of codes and have the option to either append or replace the selected code to the code input box.
3. Select the date of service, admit date to the discharge date, utilizing the calendar feature.
4. The Length of Stay will be automatically calculated, based on the date of service.
5. Apply COVID-19 Adjustment. This payment adjustment only applies to claims that have a discharge date after January 26, 2020. The default is No.
6. Apply Transfer Adjustment. Select no, short-term acute, or post-acute transfer. The default is No.
7. Click Calculate. Results appear on the screen. Results can be exported to PDF or XLS format by using the Export button above the Results.
8. Favorite the search parameters, via “Add to Favorites” to re-execute in the future.
9. To start over, click the Reset button to clear all entered values and results.

__Output-Results__

__Provider Information__
This summarizes how the hospital is generally paid, along with the dates of the stay.

__MS-DRG Payment Information__
You see the provider-specific payment rate for each MS-DRG, with the calculation broken down into detail.

