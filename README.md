
# Markdown → Google Doc (Colab)

This project converts meeting notes written in Markdown into a **well-formatted Google Doc** using the **Google Docs API**.  
It runs seamlessly in **Google Colab**, handling headings, bullets, checkboxes, mentions, and footers automatically.

----------

## Deliverables

-   **Public GitHub Repository:** [GitHub Repo Link](https://github.com/spshah1701/markdown-googledoc-converter)
-   **Included Files:**
    -   `Markdown_to_GoogleDoc.ipynb` — working Colab notebook    
    -   `meeting.md` — sample markdown input file
        



## Brief Description

The notebook authenticates with Google APIs, parses Markdown content, and programmatically builds a formatted Google Doc with:

-   **Headings (H1–H3)** for titles, sections, and subsections  
-   **Bulleted lists and nested indentation**    
-   **Markdown checkboxes (`- [ ]`) → Google Docs checkboxes**
-   **Bold blue highlights for `@mentions`**    
-   **Styled footer (gray italic for “Meeting recorded by”, “Duration”)**
    


## Setup Instructions

1.  Open the notebook in **Google Colab**.   
2.  Upload your meeting notes file as `meeting.md` to `/content/`.    
3.  Run all cells sequentially.    
4.  Authenticate your Google account when prompted.
    


## Required Dependencies

`google-api-python-client==2.147.0` 

The notebook installs it automatically.

##  How to Run in Colab

1.  Click **Run All** in Colab.
    
2.  Follow the **Google authentication** popup.
    
3.  Wait for the “Document formatted” message.
    
4.  The notebook prints a **Google Docs link**, click to view your formatted document.
