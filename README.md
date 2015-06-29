# HistoricalNewspapersCorpus
This Git repository is an experiment in providing access to a large corpus of OCRed text using GitHub.


##AVAILABLE CONTENT:

The repository currently holds a subset of the Europeana Newspaper corpus. Additional content will be available soon, and eventually the complete Europena Newspapers Corpus will be made publicly accessible.

The first objective is to host in GitHub the following three newspaper titles, including all the published issues that have been digitized:


**Jaunākās Ziņas**

Available Years: 1911-1936

Source Library: National Library of Latvia

Licence for Text: https://creativecommons.org/publicdomain/mark/1.0/

Searchable at : http://www.theeuropeanlibrary.org/tel4/newspapers/title/3000059923367

Status in GitHub repository: **Available**

**Berliner Tageblatt**

Available Years: 1878-1929

Source Library: Staatsbibliothek zu Berlin

Licence for Text: https://creativecommons.org/publicdomain/mark/1.0/

Searchable at: http://www.theeuropeanlibrary.org/tel4/newspapers/title/3000096302605

Status in GitHub repository: *Not yet available*


**L'Univers (National Library of France)**

Available Years: 1867-1920

Source Library: National Library of France

Licence for Text: https://creativecommons.org/publicdomain/mark/1.0/

Searchable at : http://www.theeuropeanlibrary.org/tel4/newspapers/title/3000113983483

Status in GitHub repository: *Not yet available*



##FOLDER STRUCTURE:

The corpus is structured in the repository accorgin to the following folder structure:

-- README.md (this file)

-- Newspaper Title

    |

    ---- Descriptive Metadata (Metadata Record describing the Newspaper Title, in Dublin Core)

    ---- Descriptive Metadata (Metadata Record describing the Newspaper Title, in EDM - Europeana Data Model)

    ---- YEAR (yyyy)

    |     |

    |     ----- Newspaper Issue (folder name based on the issue's date of publication: yyyymmdd)

    |          |

    |          ---- Descriptive Metadata (Metadata Record describing the Newspaper Issue, in Dublin Core)

    |          ---- Descriptive Metadata (Metadata Record describing the Newspaper Issue, in EDM - Europeana Data Model)

    |          ---- Full-text files (inside a ZIP archive, in ALTO format) (not yet available)

    |          ---- Full-text files (inside a ZIP archive, in plain text format)

    |     ----- Newspaper Issue (yyyymmdd)

    |     ...

    |     ----- Newspaper Issue (yyyymmdd)

    |     ...

    |     ----- Newspaper Issue (yyyymmdd)

    |     ...

    ---- YEAR (yyyy)

    |     ...

    ---- YEAR (yyyy)

    ...



## CONTACT:


Alastair Dunning <Alastair.Dunning@theeuropeanlibrary.org>
 

