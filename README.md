# CienciaVitaeXMLparser

Ciencia Vitae is the mandatory CV platform for FCT grantees.

This repo contains a Ciencia Vitae XML export parser, that saves the content in a table format.

## Pre-requisites

To get an XML export file compatible with this project:

&#49;. open https://www.cienciavitae.pt/ and log into your account

&#50;. once in there, navigate to export page using the menu in the top rigth corner
<img width="1537" alt="Screen Shot 2024-01-12 at 10 49 18 PM" src="https://github.com/omarcostahamido/CienciaVitaeXMLparser/assets/18335360/21fc27a8-9b20-436d-bfd7-c3abe683917f">

&#51;. on the "export cv" page, follow the settings from the image below before exporting. Most importantly, choose export format as xml.
![Screen Shot 2024-01-12 at 10 50 24 PM](https://github.com/omarcostahamido/CienciaVitaeXMLparser/assets/18335360/40fe20e1-3240-47a5-a5b6-07cc322e14e1)

## How to use

- get all Ciencia Vitae XML exports ready on a local folder
- open https://iimpaqct.uc.pt/cvxp on your browser
- click `Choose Files` and select all the xml files you want to parse
  - a popup will appear if there is an error loading the files
  - otherwise, a green `PARSE!` button will appear
- click the `PARSE!` button and wait a couple seconds for the file procesing to complete
  - a log of the files will appear, showing all keys and values with indentation
  - a blue `copy!` button will also appear
- click any other button (`identity`, `degrees`, `outputs`, `services`, or `distinctions`) to change the page/tab
- click the `copy!` button to automatically select the current tab and copy it to clipboard
  - note: before moving to another tab, make sure to de-select the text first (see [issue #9](https://github.com/omarcostahamido/CienciaVitaeXMLparser/issues/9))
- feel free to paste the clipboard content into google spreadsheets, excel, or numbers app

## Acknowledgements

See also [ORCID-API](https://github.com/omarcostahamido/ORCID-API).

This tool was developed by [OCH](https://omarcostahamido.com) at [CEIS20](https://www.uc.pt/iii/ceis20) in collaboration with [Olga Solovova](https://www.cienciavitae.pt//611C-0376-19FA).
