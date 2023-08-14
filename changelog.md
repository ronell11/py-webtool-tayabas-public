# Changelog
--------------------------------
--------------------------------
## [Unreleased] = 2023-08-12
## [Duration] 1:00 pm - 11:00 pm

### Added
- ccro encoder module
    - edit process, schedule process
    - render exact data in printing per application

### Note
- test deploy on PaaS(Platform as a service) server
    - heroku


--------------------------------
--------------------------------
## [Unreleased] = 2023-08-11
## [Duration] 10:00 am - 8:30 pm

### Added
- ccro encoder module
    - read/write base64 images of document uploads(birth certificate, cenomar, id, etc.)
    - minor update/changes in manage/view page of application
    - minor update/changes in ccro related table structure

### In Progress
- Peso module(design preparation, testing components)([Author.Arjay])

### Note
- researching different cloud server for python deployment(production)
    - aws(elastic beanstalk)
    - microsoft azure
    - google cloud(app engine)
    
--------------------------------
--------------------------------
## [Unreleased] = 2023-08-10
## [Duration] [onsite] 8:00 am - 6:00 pm 

### Added
- ccro encoder module
    - birth certificate Manage/View page
    - death certificate(table/model), base on exact google forms of tayabas
        - exact print layout([Author.Arjay])
    - test printing(ok)[legal size paper 8.5 x 14]


--------------------------------
--------------------------------
## [Unreleased] = 2023-08-09
## [Duration] 9:00 am - 1:00 pm, 4pm - 9:00 pm

### Added
- ccro encoder module
    - index page(viewing of all ccro related form applications)
    - marriage license(table/model), base on exact google forms of tayabas
        - Manage/View application page
        - exact print layout([Author.Arjay])
    - birth certificate(table/model), base on exact google forms of tayabas
        - exact print layout([Author.Arjay])
    - various changes in table structure, codebase

### Changed
- index page table filters changed from dropdown(status,type) to searchfield(Transaction Number)
    

--------------------------------
--------------------------------
## [Unreleased] = 2023-08-08
## [Duration] 9:00 am - 7:00 pm

### Added
- Per department admin account registration
    - peso admin, cswd admin, cho admin, ccro admin
- activity logging
    - account registration
    
### Changed
- User-access level changed from 2 to 3
    1. superadmin(executive level)
    2. admin(depatment head/office head)
    3. encoder(department staff/office staff)

### Removed
    - Phone removed as required field in account registration

### Note
- superadmin can register all account level
- admin can only register encoder account
    
--------------------------------
--------------------------------
## [Unreleased] = 2023-08-07

### note
- no codebase update(collab meeting @ tayabas city hall)

--------------------------------
--------------------------------
## [Unreleased] = 2023-08-07
## [Duration] 12:00 am - 9:00 am, 1:00 pm - 6:00 pm

### Added
- CSWD request list table filter
    - request type(e.g. health, education)
    - request priority(e.g. senior, pwd)
- Test Deploy(PythonAnywhere)(http://ronell11.pythonanywhere.com/)

### In Progress
- CSWD related module
- SUPERADMIN dashboard

### Changed
- CSWD manage request page
    - tab navigation instead of single page

### To Be Added

- CSWD request case study
--------------------------------
--------------------------------
## [Unreleased] = 2023-08-06
## [Duration] 12:00 am - 11:00 am

### Added
- staff account edit details
- CSWD login
    - redirect to cswd module
    - list all pending request in cswd index page
    - action button to manage request
        - Print Receipt/Letter of Acknowledgment(proof of received financial assistance)

### In Progress
- CSWD related module

### To Be Added

- CSWD request approve/decline process
- CSWD request list with filters/searchbar

--------------------------------
--------------------------------
## [Unreleased] = 2023-08-05
## [Duration] 1:00 am - 7:00 am

### Added
- staff registration
- staff listview
    - data-tables
    - Searchbar, Dropdown quicksearch(role, status)

### In Progress
- [ ] Test deploy(Google Cloud Platform)
- [x] Test deploy(PythonAnywhere)

### To Be Added

- Staff Management Page
    - Edit Details
    - Change account status/permission
--------------------------------
--------------------------------
## [Unreleased] = 2023-08-03 - 2023-08-04
## [Duration] [onsite] 7:00 pm - 6:55 am 

### Added
- bootstrap template(paid)
- Login Page
    -built-in django/python login authentication

### To Be Added

- Staff Management Page
    - Viewing of account(data-tables)
    - Adding/Register Staff Accounts(Modal)

--------------------------------
--------------------------------
## [Unreleased] = 2023-08-03
## [Duration] [onsite] 1:00 am - 2:41 am 

### Note

- checklist.md Progress Tracking

--------------------------------
--------------------------------
## [Unreleased] = 2023-08-01
## [Duration] [onsite] X:XX - 6:00 am 

### Added

- Initial Bootstrap Design
- Test Connection to MySql(Database)
- Test User Authentication/User Login

### Note

- Setup Django/Python project
- README.md Project Scope

### To Be Fixed/To Be Added

- User Session
    * Redirect to index page when already authenticated
    * Redirect to login page when not authenticated

--------------------------------
--------------------------------


