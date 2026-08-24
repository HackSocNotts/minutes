# HackSoc Metting Minutes
PDFs are to be published on the HackSoc SU page.

# Instructions
1. Duplicate the template directory 
2. Rename the duplicate directory to date of meeting in the format YYYY-MM-DD
3. Add date
4. Save file into the relevant year folder
5. Add present and absent members. Use a `~` to separate first name and surname.
    - Chair should be wrapped in `\chair{}`
    - Members are listed in `hacksoc.min` - update this to reflect current committee if needed
    - Also present should be non-committee members and should __NOT__ be in `hacksoc.min`
6. Add announcements as items in the `Announcements` section
7. Add reports as subsections in the `Reports` section
    - Make sure to add item lists with `\begin{hiddensubitems}` `\end{hiddensubitmes}` for details
8. Add `Old Business` items if needed or just delete the section
    - use `\priormins` if inclined to show that the last set of minutes were approved
9. Add agenda items that aren't announcements or reports to `New Business`
10. Place agreed next meeting date or range in `\nextmeeting{}`
11. Typeset and commit.
