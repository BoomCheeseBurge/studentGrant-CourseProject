# Student Grant Management

## Built on PHP 8.3 with Bootstrap5.

This project was part of a course project that manages student grant proposal for research journal/conference on a national and international level.

This project was developed with PHP using MariaDB RDBMS (MySQL database) and Apache2 webserver (in XAMPP).

## Roles

1. Admin User

2. Manager User

3. Engineer User

Any finished maintenances are archived in the maintenance history section.

## Web-Application Sections

The project consist of the following sections based on the user role's POV:

* __Homepage__

__All authenticated users__ can see a button to apply for their unpublished research/journals.

* __Application Form__

Users can apply for grant proposal using this form.

* __Grant List__

Users can view their own grant proposals and track which reviewer stage they are in, or requested for change or denied.

* __Grant Applicants__

Reviewers can view the grant applicants in a table according to the status of the grant.

The stages of grant proposal review can be seen as follows.

## National Level

1. __First Reviewer__

This stage of the review is done by the __Head of Study Program__ for this publication level.

2. __Second Reviewer__

This stage of the review is done by the __Student and Alumni Affairs (SAA)__ for this publication level.

3. __Third Reviewer__

This stage of the review is done by the __Deputy Rector IV__ for this publication level.

## International Level

1. __First Reviewer__

This stage of the review is done by the __Head of Study Program__ for this publication level.

2. __Second Reviewer__

This stage of the review is done by the __Central for Research and Support (CRCS)__ for this publication level.

3. __Third Reviewer__

This stage of the review is done by the __Deputy Rector IV__ for this publication level.

* __Grant Progress__

Users can track the progress of a single grant proposal from this page.

## Testing

Considering the relatively small size of the project and tight deadline, testing were performed manually that tests the common workflow of the web-application used by each user roles.

## Future Improvements

- [ ] :x: Organize the project structure using MVC principles.
- [ ] :x: Add pagination, show/hide columns, and sortable column functionalities to the table.
- [ ] :x: Perform proper testing using PHPUnit.

## Third-Party Library

The third-party library used was only Bootstrap to quickly stylize elements and use web components with ease.

__External Source__

* Bootstrap ( 5.2.3 )

---

A dummy database has been provided in .sql format to test out the web-app. The following are the credentials of the dummy users:

  1. Student User
  
  Email: brandonjohnlyc@gmail.com (FET Student)
  
    Pass = brandon
  
  Email: lolieh@gmail.com (FOE Student)
  
    Pass = lolieh
  
  ------------

  2. Faculty Member User/Head of Study Program
  
  Email: chen@gmail.com (Faculty Member for FET)
  
    Pass: chen
  
  Email: chow@gmail.com (Faculty Member for FOE)
  
    Pass: stephen
  
  Email: doe@gmail.com (HoSP for FET)
  
    Pass: john
  
  Email: chiang@gmail.com (HoSP for FOE)
  
    Pass: david
  
  ------------

  3. CRCS (Center for Research and Scholarship)
  
  Email: hunt@gmail.com (CRCS)
  
    Pass: ethan
  
  ------------

  4. SAA (Student Affairs and Administration)
  
  Email: neeson101@gmail.com (SAA)
  
    Pass: liam

------------

Email: polo@gmail.com (ViceRectorIV)

Pass: marco [3829486b93ec44395f0b980424bae9b6fb07b7bc]
