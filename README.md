# Office Suites Test

Microsoft Office has been the established office suite for decades.
This repository aims to compare other office suites against the online version of MS Office to evaluate how capable of a replacements they are.
The test files have been downloaded from the internet.

## Rules
1. Scoring is done based on 5 - 1, where **5 is full compatibility** and **1 is no compatibility**, **0 means that the file cannot be opened**.
2. The score cannot go lower than 0.
3. Points are deducted for 1 type of issue - this means if multiple pictures are misaligned there is still only 1 point deducted as it is one type of issue.
4. Screenshots of the base document are shown in the table.
5. Screenshots are always made at 100% scale of the document.
6. If there are discrepancies additional screenshots are shown and a description is provided.
7. At the end of each section the total score is provided -> the higher, the better compatibility.

# Point deductions

|            | Small Formatting Issue | Big Formatting Issue | Small Visual Issue | Big Visual Issue | File cannot be opened |
|------------|------------------------|----------------------|--------------------|------------------|-----------------------|
| Deductions | 1                      | 2                    | 0.5                | 1                | 5                     |


### Word
#### File Type: doc
[1.doc](Test%20Files/Word/DOC/1.doc)

|                 | **MS Office Online (MS 360)**                                                                                                                        | **Only Office**                                             | **Libre Office**                                             | **WPS Office**                                       |
|-----------------|------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------|--------------------------------------------------------------|------------------------------------------------------|
| **Main**        | ![1-doc-ms-main.png](Screenshots/1-doc/MS360-main.png)                                                                                               | ![1-doc-of-main.png](Screenshots/1-doc/OnlyOffice-main.png) | ![1-doc-lo-main.png](Screenshots/1-doc/LibreOffice-main.png) | ![1-doc-lo-main.png](Screenshots/1-doc/WPS-main.png) |
| **Differences** | ![1-doc-ms-diff.png](Screenshots/1-doc/MS360-diff.png)                                                                                               | ![1-doc-of-diff.png](Screenshots/1-doc/OnlyOffice-diff.png) | ![1-doc-lo-main.png](Screenshots/1-doc/LibreOffice-diff.png) | ![1-doc-lo-main.png](Screenshots/1-doc/WPS-diff.png) |
| **Comments**    | To edit this .doc file MS Office Online had to convert to .docx, in view mode the file looks good, but in editing mode some pictures are misaligned. | No visible discrepancies, but UI is zoomed in.              | No visible discrepancies                                     | No visible discrepancies                             |
| **Score**       | 4                                                                                                                                                    | 5                                                           | 5                                                            | 5                                                    |

[2.doc](Test%20Files/Word/DOC/2.doc)

|                 | **MS Office Online (MS 360)**                       | **Only Office**                                               | **Libre Office**                                                | **WPS Office**                                  |
|-----------------|-----------------------------------------------------|---------------------------------------------------------------|-----------------------------------------------------------------|-------------------------------------------------|
| **Main**        | ![MS360-main.png](Screenshots/2-doc/MS360-main.png) | ![OnlyOffice-main.png](Screenshots/2-doc/OnlyOffice-main.png) | ![LibreOffice-main.png](Screenshots/2-doc/LibreOffice-main.png) | ![WPS-main.png](Screenshots/2-doc/WPS-main.png) |
| **Differences** | -                                                   | -                                                             | -                                                               | -                                               |
| **Comments**    | No visible discrepancies                            | No visible discrepancies, but UI is zoomed in.                | No visible discrepancies                                        | No visible discrepancies                        |
| **Score**       | 5                                                   | 5                                                             | 5                                                               | 5                                               |

| **File Type Score** | **MS Office Online (MS 360)** | **Only Office** | **Libre Office** | **WPS Office** |
|---------------------|-------------------------------|-----------------|------------------|----------------|
| **_DOC_**           | 9                             | 10              | 10               | 10             |


#### File Type: docx
[1.docx](Test%20Files/Word/DOCX/1.docx)

|                 | **MS Office Online (MS 360)**                                                                                                                                                | **Only Office**                                                                                                                                                                                            | **Libre Office**                                                                                                                                                                                                 | **WPS Office**                                                                                                                                                   |
|-----------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Main**        | ![MS360-main.png](Screenshots/1-docx/MS360-main.png)                                                                                                                         | ![OnlyOffice-main.png](Screenshots/1-docx/OnlyOffice-main.png)                                                                                                                                             | ![LibreOffice-main.png](Screenshots/1-docx/LibreOffice-main.png)                                                                                                                                                 | ![WPS-main.png](Screenshots/1-docx/WPS-main.png)                                                                                                                 |
| **Differences** | ![MS360-diff1.png](Screenshots/1-docx/MS360-diff1.png)<br/>![MS360-diff2.png](Screenshots/1-docx/MS360-diff2.png)<br/>![MS360-diff3.png](Screenshots/1-docx/MS360-diff3.png) | ![OnlyOffice-diff1.png](Screenshots/1-docx/OnlyOffice-diff1.png)<br/>![OnlyOffice-diff2.png](Screenshots/1-docx/OnlyOffice-diff2.png)<br/>![OnlyOffice-diff3.png](Screenshots/1-docx/OnlyOffice-diff3.png) | ![LibreOffice-diff1.png](Screenshots/1-docx/LibreOffice-diff1.png)<br/>![LibreOffice-diff2.png](Screenshots/1-docx/LibreOffice-diff2.png)<br/>![LibreOffice-diff3.png](Screenshots/1-docx/LibreOffice-diff3.png) | ![WPS-diff1.png](Screenshots/1-docx/WPS-diff1.png)<br/>![WPS-diff2.png](Screenshots/1-docx/WPS-diff2.png)<br/>![WPS-diff3.png](Screenshots/1-docx/WPS-diff3.png) |
| **Comments**    | The file had to be converted in order to be edited. In edit mode some pictures are misaligned. Also table is not showing correctly.                                          | Table is not showing correctly, although the rest of the layout is correct. UI is zoomed in.                                                                                                               | The formatting is correct, but there is a weird gray color behind the capital letter, the table is not showing correctly.                                                                                        | It is the only office suite that displayed the document "wide", although all screenshots are made on the same equipment. Full compatability.                     |
| **Score**       | 3                                                                                                                                                                            | 4                                                                                                                                                                                                          | 2.5                                                                                                                                                                                                              | 5                                                                                                                                                                |

[2.docx](Test%20Files/Word/DOCX/2.docx)

|                 | **MS Office Online (MS 360)**                                                                                     | **Only Office**                                                      | **Libre Office**                                                       | **WPS Office**                                                                                                 |
|-----------------|-------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------|------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------|
| **Main**        | ![MS360-main.png](Screenshots/2-docx/MS360-main.png)                                                              | ![OnlyOffice-main.png](Screenshots/2-docx/OnlyOffice-main.png)       | ![LibreOffice-main.png](Screenshots/2-docx/LibreOffice-main.png)       | ![WPS-main.png](Screenshots/2-docx/WPS-main.png)                                                               |
| **Differences** | ![MS360-diff1.png](Screenshots/2-docx/MS360-diff1.png)<br/>![MS360-diff2.png](Screenshots/2-docx/MS360-diff2.png) | ![OnlyOffice-diff1-2.png](Screenshots/2-docx/OnlyOffice-diff1-2.png) | ![LibreOffice-diff1-2.png](Screenshots/2-docx/LibreOffice-diff1-2.png) | ![WPS-diff1-2.png](Screenshots/2-docx/WPS-diff1-2.png)                                                         |
| **Comments**    | Big formatting issue - pictures totally misaligned.                                                               | Formatting looks good, but footer is missing                         | No visible discrepancies                                               | Formatting mostly ok, but even though the font is correct it looks very slim and more space between the lines. |
| **Score**       | 3                                                                                                                 | 4                                                                    | 5                                                                      | 4                                                                                                              |

[3.docx](Test%20Files/Word/DOCX/3.docx)

|                 | **MS Office Online (MS 360)**                          | **Only Office**                                                  | **Libre Office**                                                   | **WPS Office**                                             |
|-----------------|--------------------------------------------------------|------------------------------------------------------------------|--------------------------------------------------------------------|------------------------------------------------------------|
| **Main**        | ![MS360-main.png](Screenshots/3-docx/MS360-main.png)   | ![OnlyOffice-main.png](Screenshots/3-docx/OnlyOffice-main.png)   | ![LibreOffice-main.png](Screenshots/3-docx/LibreOffice-main.png)   | ![WPS-main.png](Screenshots/3-docx/WPS-main.png)           |
| **Differences** | ![MS360-diff1.png](Screenshots/3-docx/MS360-diff1.png) | ![OnlyOffice-diff1.png](Screenshots/3-docx/OnlyOffice-diff1.png) | ![LibreOffice-diff1.png](Screenshots/3-docx/LibreOffice-diff1.png) | ![LibreOffice-diff1.png](Screenshots/3-docx/WPS-diff1.png) |
| **Comments**    | No discrepancies                                       | Split onto second line                                           | Split onto second line                                             | Larger spacing between the lines                           |
| **Score**       | 5                                                      | 4.5                                                              | 4.5                                                                | 4.5                                                        |

[4.docx](Test%20Files/Word/DOCX/4.docx)

|                 | **MS Office Online (MS 360)**                                                                                            | **Only Office**                                                  | **Libre Office**                                                   | **WPS Office**                                                       |
|-----------------|--------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------|--------------------------------------------------------------------|----------------------------------------------------------------------|
| **Main**        | ![MS360-main.png](Screenshots/4-docx/MS360-main.png)                                                                     | ![OnlyOffice-main.png](Screenshots/4-docx/OnlyOffice-main.png)   | ![LibreOffice-main.png](Screenshots/4-docx/LibreOffice-main.png)   | ![WPS-main.png](Screenshots/4-docx/WPS-main.png)                     |
| **Differences** | ![MS360-diff1.png](Screenshots/4-docx/MS360-diff1.png)                                                                   | ![OnlyOffice-diff1.png](Screenshots/4-docx/OnlyOffice-diff1.png) | ![LibreOffice-diff1.png](Screenshots/4-docx/LibreOffice-diff1.png) | ![WPS-diff1.png](Screenshots/4-docx/WPS-diff1.png)                   |
| **Comments**    | The table is shown as bullet-point 2, all other office suites have counted it as 1, so I'm guessing MS360 didi it wrong. | No visible discrepancies                                         | No visible discrepancies                                           | Formatting looks good, but in some places the font seems to be wrong |
| **Score**       | 4                                                                                                                        | 5                                                                | 5                                                                  | 4.5                                                                  |

| **File Type Score** | **MS Office Online (MS 360)** | **Only Office** | **Libre Office** | **WPS Office** |
|---------------------|-------------------------------|-----------------|------------------|----------------|
| **_DOCX_**          | 15                            | 17.5            | 17               | 18             |


| **Total Score**      | **MS Office Online (MS 360)** | **Only Office** | **Libre Office** | **WPS Office** |
|----------------------|-------------------------------|-----------------|------------------|----------------|
| **DOC** + **_DOCX_** | 24                            | 27.5            | 27               | 28             |

### Excel
#### File Type: xls
[1.xls](Test%20Files/Excel/XLS/1.xls)

|                 | **MS Office Online (MS 360)**                   | **Only Office**                                               | **Libre Office**                                                | **WPS Office**                                  |
|-----------------|-------------------------------------------------|---------------------------------------------------------------|-----------------------------------------------------------------|-------------------------------------------------|
| **Main**        | ![WPS-main.png](Screenshots/1-xls/WPS-main.png) | ![OnlyOffice-main.png](Screenshots/1-xls/OnlyOffice-main.png) | ![LibreOffice-main.png](Screenshots/1-xls/LibreOffice-main.png) | ![WPS-main.png](Screenshots/1-xls/WPS-main.png) |
| **Differences** | Visible in main picture                         | Visible in main picture                                       | Visible in main picture                                         | Visible in main picture                         |
| **Comments**    | No visible discrepancies                        | Missing columns (dates)                                       | No visible discrepancies                                        | No visible discrepancies                        |
| **Score**       | 5                                               | 3                                                             | 5                                                               | 5                                               |

| **File Type Score** | **MS Office Online (MS 360)** | **Only Office** | **Libre Office** | **WPS Office** |
|---------------------|-------------------------------|-----------------|------------------|----------------|
| **_XLS_**           | 5                             | 3               | 5                | 5              |

#### File Type: xlsx
[1.xlsx](Test%20Files/Excel/XLSX/1.xlsx)

|                 | **MS Office Online (MS 360)**                          | **Only Office**                                                  | **Libre Office**                                                   | **WPS Office**                                                |
|-----------------|--------------------------------------------------------|------------------------------------------------------------------|--------------------------------------------------------------------|---------------------------------------------------------------|
| **Main**        | ![MS360-main.png](Screenshots/1-xlsx/MS360-main.png)   | ![OnlyOffice-main.png](Screenshots/1-xlsx/OnlyOffice-main.png)   | ![LibreOffice-main.png](Screenshots/1-xlsx/LibreOffice-main.png)   | ![WPS-main.png](Screenshots/1-xlsx/WPS-main.png)              |
| **Differences** | ![MS360-diff1.png](Screenshots/1-xlsx/MS360-diff1.png) | ![OnlyOffice-diff1.png](Screenshots/1-xlsx/OnlyOffice-diff1.png) | ![LibreOffice-diff1.png](Screenshots/1-xlsx/LibreOffice-diff1.png) | ![WPS-diff1.png](Screenshots/1-xlsx/WPS-diff1.png)            |
| **Comments**    | No visible discrepancies                               | Missing reference                                                | Missing reference                                                  | Missing reference + field not fully visible without expansion |
| **Score**       | 5                                                      | 4                                                                | 4                                                                  | 3.5                                                           |

[2.xlsx](Test%20Files/Excel/XLSX/2.xlsx)

|                 | **MS Office Online (MS 360)**                                                                                    | **Only Office**                                                                                                                      | **Libre Office**                                                                                                                         | **WPS Office**                                                                                           |
|-----------------|------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------|
| **Main**        | ![MS360-main.png](Screenshots/2-xlsx/MS360-main.png)                                                             | ![OnlyOffice-main.png](Screenshots/2-xlsx/OnlyOffice-main.png)                                                                       | ![LibreOffice-main.png](Screenshots/2-xlsx/LibreOffice-main.png)                                                                         | ![WPS-main.png](Screenshots/2-xlsx/WPS-main.png)                                                         |
| **Differences** | ![MS360-diff1.png](Screenshots/2-xlsx/MS360-diff1.png)<br>![MS360-diff2.png](Screenshots/2-xlsx/MS360-diff2.png) | ![OnlyOffice-diff1.png](Screenshots/2-xlsx/OnlyOffice-diff1.png)<br>![OnlyOffice-diff2.png](Screenshots/2-xlsx/OnlyOffice-diff2.png) | ![LibreOffice-diff1.png](Screenshots/2-xlsx/LibreOffice-diff1.png)<br>![LibreOffice-diff2.png](Screenshots/2-xlsx/LibreOffice-diff2.png) | ![WPS-diff1.png](Screenshots/2-xlsx/WPS-diff1.png)<br>![WPS-diff2.png](Screenshots/2-xlsx/WPS-diff2.png) |
| **Comments**    | No visible discrepancies                                                                                         | No visible discrepancies                                                                                                             | No visible discrepancies                                                                                                                 | Missing references                                                                                       |
| **Score**       | 5                                                                                                                | 5                                                                                                                                    | 5                                                                                                                                        | 4                                                                                                        |

[3.xlsx](Test%20Files/Excel/XLSX/3.xlsx)

|                 | **MS Office Online (MS 360)** | **Only Office** | **Libre Office** | **WPS Office** |
|-----------------|-------------------------------|-----------------|------------------|----------------|
| **Main**        |                               |                 |                  |                |
| **Differences** |                               |                 |                  |                |
| **Comments**    |                               |                 |                  |                |
| **Score**       |                               |                 |                  |                |

[4.xlsx](Test%20Files/Excel/XLSX/4.xlsx)

|                 | **MS Office Online (MS 360)** | **Only Office** | **Libre Office** | **WPS Office** |
|-----------------|-------------------------------|-----------------|------------------|----------------|
| **Main**        |                               |                 |                  |                |
| **Differences** |                               |                 |                  |                |
| **Comments**    |                               |                 |                  |                |
| **Score**       |                               |                 |                  |                |

[5.xlsx](Test%20Files/Excel/XLSX/5.xlsx)

|                 | **MS Office Online (MS 360)** | **Only Office** | **Libre Office** | **WPS Office** |
|-----------------|-------------------------------|-----------------|------------------|----------------|
| **Main**        |                               |                 |                  |                |
| **Differences** |                               |                 |                  |                |
| **Comments**    |                               |                 |                  |                |
| **Score**       |                               |                 |                  |                |

| **File Type Score** | **MS Office Online (MS 360)** | **Only Office** | **Libre Office** | **WPS Office** |
|---------------------|-------------------------------|-----------------|------------------|----------------|
| **_XLSX_**          |                               |                 |                  |                |

| **Total Score**      | **MS Office Online (MS 360)** | **Only Office** | **Libre Office** | **WPS Office** |
|----------------------|-------------------------------|-----------------|------------------|----------------|
| **XLS** + **_XLSX_** |                               |                 |                  |                |

### Powerpoint