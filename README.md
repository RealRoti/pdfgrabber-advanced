# What is this?
This is an unofficial fork from [PDFGrabber](https://github.com/FelixFrog/pdfgrabber), a vendor-agnostic script is used to download pdfs (and covers) from different services.

# Disclaimer
This script is provided "as is", without any type of warranty. I am not responsible of any harm that this may cause.
Even though this script exists, you are responsibile of the PDFs generated. Check if the backup of books is legal in your country.
Redistribution of PDFs is highly discouraged and not supported by the Author.

# Updates

Last update: **13 sept 2024**

## Services update

| **service**                      | **last sync to original version** | **additional info**                                                       |
|----------------------------------|-----------------------------------|---------------------------------------------------------------------------|
| MyLim                            | Up to date                        |                                                                           |
| Pearson Reader+ / Pearson+       | Up to date                          |                                                                           |
| bSmart / HoepliAcademy+          | Up to date                          |                                                                           |
| Mondadori HUB Scuola             | Up to date                         |                                                                           |
| Zanichelli                       | 27/02/2024                        | removed from the original version, not updated anymore, but still working |
| MEE2 / Blinklearning             | Up to date                         |                                                                           |
| easyeschool                      | Up to date                          |                                                                           |
| Oxford Learner’s Bookshelf       | Up to date                         |                                                                           |
| Laterza diBooK                   | Up to date                          |                                                                           |
| Raffaello Player                 | Up to date                          |                                                                           |
| Cambridge GO                     | Up to date                          |                                                                           |
| Palumbo Editore - Saggi Digitali | Up to date                         |                                                                           |
| Cengage Read                     | Up to date                          |                                                                           |
| Oxford Reading Club              | Up to date                         |                                                                           |
| Sanoma My Place                  | Up to date                        |                                                                           |


# Installation
1. download the latest version of [Python](https://www.python.org/downloads/)
    - on windows, when installing though the set up wizard, make sure to select the checkbox to add python to `PATH`
    - on linux and macos, use your package manager of choice (`brew install python3` or `apt install python3`, etc...)
2. downlaod the pdfgrabber repo
    - using git: `git clone https://github.com/RealRoti/pdfgrabber-advanced`
    - manually: download the zip (green button labeled "code") and extract it
3. open your local clone of pdfgrabber
4. open the terminal in that directory and run:
    1) `pip install -r requirements.txt` (takes care of installing every needed libraries)
    2) run the script
        - `python3 main.py` (linux and macos) 
        - `py main.py` (windows)
5. once inside the pdfgrabber CLI:
    - press `r`: register a new account
    - choose what to do (it's listed):
       - to download a book: press `d` and follow the instructions.
       - the output file will be `files/<service>/<book name>.pdf`


# Support
Please consider supporting the original project (not me!):

[![liberapay](https://liberapay.com/assets/widgets/donate.svg)](https://liberapay.com/flx/donate)

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/Z8Z4PCZUI)

Also [Satispay](https://www.satispay.com/app/match/link/user/S6Y-CON--A7BC8CDF-2EF5-40B7-884C-FDAB482CA8ED)


