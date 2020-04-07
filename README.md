# PyPDF2

PyPDF2 is a pure-python PDF library capable of splitting, merging together, cropping, and transforming the pages of PDF files. It can
retrieve text and metadata from PDFs.

The attached script allows us to extract text information from PDF files stored in a directory called RQPS to text files in other directory.

From my experience with this library, I have noted the following ideas:
- Advantages: 
    - Gives out results instantly.
    - Can decrypt secured documents if you have the password.

- Disadvantages: 
    - Don't identifies all the characters.
    - Add spaces and nonexistent characters.
    - Deal only with text content, not with text contained in images.
    - Sometimes adds unnecessary spaces between a word's characters.
