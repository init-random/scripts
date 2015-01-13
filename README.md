Scripts

comactivity  
  A script set to run in cron.hourly which appends to comactivity.log the date and hour. This may be used
  log when your computer was on, which may be helpful when trying to determine if you were working on a
  certain day.
  
new-project  
  Under $HOME/projects this will initialize a set of directories and files for the project. 
  Usage: new-project <proj-name>
  The project will be initialized under $HOME/projects/<proj-name>.

pdfcat  
  Concatenate PDF files.
  Usage: pdfcat <pdf-file> [pdf-file...]
  
rvi
   Run a remote vim server under servername INSTANCE invoking rvi [file] will start a new instance of
   vim. If the server is running rvi will attach all script parameters to the running instance.
