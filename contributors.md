## How To Contribute

- If you are a member, please select from the instructions below.
- To become a member reach out to our advisors:
  - Arman (abilge@uw.edu) or Dr. Alavares (stay.alvares@bellevuecollege.edu)

### How To Add New Strain Sequences

#### Select New Sars-Cov2 Strain
1. Navigate a web browser to the [World Health Organization](https://www.who.int/activities/tracking-SARS-CoV-2-variants).
2. Scroll down to the "Currently circulating variants of interest" table.
3. Find a row and copy the first column (Pango lineage) value.

#### Find NCBI Nucleotide Page
4. Open a new browser tab and navigate to NCBI's SARS-CoV-2 [Data Hub](https://www.ncbi.nlm.nih.gov/labs/virus/vssi/#/virus?SeqType_s=Nucleotide&VirusLineage_ss=Severe%20acute%20respiratory%20syndrome%20coronavirus%202,%20taxid:2697049).
5. Scroll down until you see the "Pango lineage" menu item on the left.
6. Select the "Pango lineage" filter and paste the value from step #3.
7. If the value is recognized a sub-menu will appear from which you can select the same value. If not, then try another "Pango lineage" value from [World Health Organization](https://www.who.int/activities/tracking-SARS-CoV-2-variants). This will open a new table of strain variants to the left.
8. Select any row and click on the first column link ("Accesion" ID). This will open a sub-menu from the left.
9. Click the link (Accession ID) at the top and it will open a "Nucleotide" page for the strain you just selected.

#### Download FASTA File
10. From the strain's NCBI nucleotide page (opened in step #9), click the dropdown "Send to" link on the right. This opens a dropdown sub-form.
11. Click the "Format" dropdown and select the "FASTA" item from the list that appears.
12. Click the "Create File" button and the FASTA file will download to your computer as a file name "sequence.fasta".
13. Find the downloaded "sequence.fasta" file on your computer. It may have been downloaded to your Downloads folder.
14. Rename the file to the Accession ID and keep the ".fasta" file ending.

#### Download Nucleotide Page Text
15. From the same NCBI nucleotide page (opened in step #9) select (aka highlight) all of the text using your favorite method:
    - Mac shortcut - command + A
    - PC shortcut - ctrl + A
    - Use the web browser's "Edit" menu and select "Select All"
16. Copy the all the highlighted text using your favorite method:
    - Mac shortcut - command + C
    - PC shortcut - ctrl + C
    - Use the web browser's "Edit" menu and select "Copy"
17. Open a text editor application on your computer (e.g. Word or a coding IDE if you have one).
18. Create a new file and name it the Accession ID.
19. Paste all of the selected nucleotide page content into the new file.
20. Save the file as a text file with a ".txt" file ending.

#### Upload FASTA File To Github
21. Open our Biology Club [Github page](https://github.com/bcbioclub).
22. Select the "Repositories" tab and open the [covid19-notebooks repo](https://github.com/bcbioclub/covid19-notebooks).
23. In the list of folders, select the "fasta_files" folder.
24. Look at the list of Accession IDs and make sure yours is not already there. If it is, download .fasta and .txt files for another strain.
25. Click the "Add file" dropdown button on the right to open the dropdown sub-menu and select the "Upload files" option.
26. Follow the instructions on the page to add your selected strain's downloaded FASTA file.
27. Click "Commit changes" to upload your FASTA file.

#### Upload Text File To Github
28. Go to our Biology Club Github [covid19-notebooks repo](https://github.com/bcbioclub/covid19-notebooks).
29. In the list of folders, select the "ncbi_pages" folder.
30. Look at the list of Accession IDs and make sure yours is not already there. If it is, download .fasta and .txt files for another strain.
31. Click the "Add file" dropdown button on the right to open the dropdown sub-menu and select the "Upload files" option.
32. Follow the instructions on the page to add your selected strain's downloaded text (.txt) file.
33. Click "Commit changes" to upload your FASTA file.

#### Congratulations
You have contributed a new strain to our COVID-19 research.



