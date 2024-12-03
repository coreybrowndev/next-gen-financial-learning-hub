## what kind of server is needed.
- Windows and Linux
- .NET Server

## where to put which file/folder.
- 1st - dotnet publish -c Release -r linux-x64 --self-contained false -o ./publish
- this will generate a publish folder
- place the publish -> /var/www/myapp
- on the linux server

## how to start/stop the system.
- For our system you need to utilize docker 
- stopping - docker compose down
- starting - docker compose up

## how to troubleshoot if something goes wrong.
- potential build error during running of tests using dotnet test
  - navigate to NextGenFinancialLearningHub.Api.Tests
    - remove bin and obj folders
    - enter rm -rf bin obj
    - re-run tests

## Where to find the source of errors, if logged.
- All errors log to terminal, console 

## What are the most critical/vulnerable pieces that can fail?
- Uploading exisiting data to database
