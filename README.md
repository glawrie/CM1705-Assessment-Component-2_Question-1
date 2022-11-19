# CM1705-Assessment-Component-2_Question-1

Version control provides a structured approach to recording edits made to a project and allows the project to be returned to a previous version.  To manually control versions of files, a person might copy their original file into another directory and add a suffix to the file name  (e.g. "version 2" or that day's date).  This approach is common because it is simple, but it is also prone to errors.  It is easy to lose track of changes between files, accidentally write to the wrong file or copy over the wrong files (Chacon, S. and Straub, B. 2022).  For version control to be implemented effectively in modern software development projects, a Version Control System (VCS) must be used to keep track of, manage, add commentary, and secure changes to files (Davis, A.L., 2020).

From the perspective of an individual developer, a VCS provides an environment to easily keep a track of developments in  their code and provides insurance against system crashes or data loss (GeeksforGeeks, 2022). 

A VCS is of particular importance for teams of developers where there are multiple people concurrently working on the same project.  Each team member works on and edits their own copy of the files, and it is up to the individual to decide when to share them with the rest of the team.  Where two developers have committed changes that conflict with each other, the VCS will highlight where the conflict occurs and the team can make a decision about how best to merge or discard the changes (W3schools.in, no date).

There are three types of VCS: 

•	Local VCSs, such as Source Code Control System (SSCS), were the first type created.  They tracked changes made to files in a single database that was stored locally on a computer which meant teamwork was difficult and issues with the computer could result in work being lost (Tsitoara, M., 2020).

•	Centralised VCSs, such as Apache Subversion (SVN), work by storing change history on a single server.  This allows for teamwork and provides a way to monitor how projects are progressing, however, centralised VCSs are subject to server errors resulting in work being lost (Collins-Sussman, B., W., B. and Michael, C., 2004). 

•	Distributed VCSs contain multiple repositories. In distributed VCSs, each user has their own repository and working copy which greatly lowers the chance of losing information.  The most commonly used distributed VCS is Git which can be utilised through GitHub.  Git makes branching and merging easy as the entire codebase and history of a project will be available on every developer’s computer.  Each time a user edits the project, a new snapshot of the project is created (a "branch") and the changes in the branch will only be committed to the central repository ("main branch") after they have been reviewed and approved (through a "pull request") (Tsitoara, M, 2020).  As Git is popular among developers, GitHub is a great way to ensure that projects are accessible to other developers and teams (Loeliger, J. and McCullough, M., 2012).  

References

Chacon, S. and Straub, B., (2022).  Pro Git.  Apress. P. 10 [Available at: https://git-scm.com/book/en/v2 ] (last accessed 18 November 2022)

Collins-Sussman, B., W., B. and Michael, C., (2004). Version Control with Subversion. O'Reilly Media, Inc.., Sebastopol, CA. pp. 1 – 21  [Available at:  https://books.google.co.uk/books?hl=en&lr=&id=v1rN2MJ81JUC&oi=fnd&pg=PR4&dq=subversion+cvs&ots=n-h6b0mDDh&sig=oSDeET0BVVN7fwf3QMKS0x8GzM4&redir_esc=y#v=onepage&q&f=false ] (last accessed 16 November 2022)

Davis, A.L., (2020). Version Control. In: Modern Programming Made Easy. Apress, Berkeley, CA. pp. 127 – 130 https://doi-org.ezproxy.rgu.ac.uk/10.1007/978-1-4842-5569-8_16 (last accessed 16 November 2022)

GeeksforGeeks, (2022). Version Control Systems [Available at: https://www.geeksforgeeks.org/version-control-systems/#:~:text=Benefits%20of%20the%20version%20control%20system%3A%201%20Enhances,through%20traceability%20to%20every%20small%20change%2C%20More%20items ] (last accessed 16 November 2022) 

Loeliger, J. and McCullough, M., (2012). Version Control with Git. O'Reilly Media, Inc., Sebastopol, CA. pp. 1 - 7 [Available at: https://books.google.co.uk/books?hl=en&lr=&id=aM7-Oxo3qdQC&oi=fnd&pg=PR3&dq=git&ots=3awiIDQit9&sig=vR4NVIh4Y_Lbx9YV1K_HFHloNjw&redir_esc=y#v=onepage&q=git&f=false ] (last accessed 16 November 2022)

Tsitoara, M., (2020). Version Control Systems. In: Beginning Git and GitHub. Apress, Berkeley, CA. pp. 3 -18. [Available at: https://doi-org.ezproxy.rgu.ac.uk/10.1007/978-1-4842-5313-7_1 ] (last accessed 16 November 2022)

W3schools.in, (no date). Version Control [Available at: https://www.w3schools.in/git/version-control ] (last accessed 16 November 2022)
