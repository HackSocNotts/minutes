# HackSoc Metting Minutes
PDFs are to be published on the HackSoc SU Page

# Instructions
1. Duplicate the Template Directory
2. Rename Duplicate Directory to date of meeting
3. Add Date
4. Add present and absent members. Use a `~` to spearate first an surname.
    - Chair should be wrapped in `\chair{}`
    - Members are listed in `hacksoc.min` update this to reflect current commitee if needed
    - Also present should be non-committee members and should __NOT__ be in `hacksoc.min`
5. Add annoucnements as items in the `Announcements` section
5. Add reports as subsections in the `Reports` section
    - Make sure to add item lists with `\begin{hiddensubitems}` `\end{hiddensubitmes}` for details
6. Add `Old Business` items if needed or just delete the section
    - use `\priormins` if inclined to show that the last set of mintues were approved
7. Add agenda items that aren't annoucnements are reports to `New Business`
8. Place agreed next meeting date or range in `\nextmeeting{}`
9. Typset and commit.