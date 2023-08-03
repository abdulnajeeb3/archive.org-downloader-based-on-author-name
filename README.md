![made-with-python](https://img.shields.io/badge/Made%20with-Python3-brightgreen)

<!-- LOGO -->
<br />
<p align="center">
  <img src="https://user-images.githubusercontent.com/54740007/108192715-e5958c80-7114-11eb-8240-e884895bb45f.png" alt="Logo" width="80" height="80">

  <h3 align="center">Archive.org-downloader-based-on-author-name</h3>

  <p align="center">
    Python3 script to download archive.org books based on author names in PDF format


    Changing something here once again

    Changing something here in feature 2 branch

    <br />
    </p>
</p>


## About The Project

There are many great books available on https://openlibrary.org/ and https://archive.org/, however, you can only borrow them for 1 hour to 14 days and you don't have the option to download it as a PDF to read it offline or share it with your friends. I created this program to solve this problem and retrieve the original book based on author name in pdf format for FREE!

Of course, the download takes a few minutes depending on the number of pages and the quality of the images you have selected. You must also create an account on https://archive.org/ for the script to work.


## Getting Started
To get started you need to have python3 installed. If it is not the case you can download it here : https://www.python.org/downloads/

### Installation
Make sure you've already git installed. Then you can run the following commands to get the scripts on your computer:
   ```sh
   git clone https://github.com/MiniGlome/Archive.org-Downloader.git
   cd Archive.org-Downloader
   ```
The script requires the modules `requests`, `tqdm`, `pandas`, `internetarchive` and `img2pdf`, you can install them all at once with this command:
```sh
pip install -r requirements.txt
```
   
## Usage
After installing the requirements you can start executing the cells in the `Archive_book_downloader_by_author_name.ipynb`

There is logging available in the cells of the notebook and the comments available on each cell should help you guide in getting the program to run successfully.

## Getting the metadata
The script also allows you to get the metadata for the books downloaded, after successful download of the books you can execute the cells at the end of the notebook to get the required metadata for the books that you have downloaded
