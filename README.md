# Hands on assignments for Rails
A small set of hands-on assignments on rails for interview candidates.

## Instructions: 
 - All the solutions should be stored in a public git repository. It can be [github](github.com), [gitlab](gitlab.com) or anything else but clone-able publicly. Send us only the repository path.
  - There is a `README.md` or `README.txt` in the repository. This can contain your notes to the evaluator, how to run if its not default etc. 
  - Each solution is placed in a git branch with prefix sol_N, so that `git checkout sol_2` will take us to the solution for question number 2.
  - Commit everything to the respository e.g. archives (zips, tars), binaries etc. 
  - Rails is running on production mode.
  - Extra files which do not belong to the rails home can be placed in separate folders and documented in `README`.
  - If it was impossible to finish, its okay to have it incomplete, just update the `README` in that case. During evaluation, points are given also to approach if the solution is not complete.

### Mandatory questions

#### 1. Create a rails application which shows `Hello Cloudronics!` on index page
#### 2. Update the index page so that a user can upload a file with "upload" button. Store the file to `/tmp` on the disk
#### 3. Update the upload from above so that, one could only upload XLSX files. If the XLSX is of the following format (shown below), then print the `worker's ` description in a pop-up box/the same page itself. Any xlsx other than this format should pop-up/display `not compatible error`

SLNO | Id | Description
--- | --- | --- 
1. | Admin | Administrator
2. | worker | Worker user
3. | user | normal user
4. | anonymous | anonymous user

 
### Optional questions

#### 1. Configure mod passenger to the above 3. with apache. Have the working config files (which are not in rails home) under $REPOSITORY_DIR/passenger/ directory
#### 2. Configure and generate assets pipeline for the above application. If there are any extra files used (which are not in rails home) please place them under $REPOSITORY_DIR/assets-pipeline/
#### 3. Write unit tests (any framework) for the above