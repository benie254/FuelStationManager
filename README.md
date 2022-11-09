# FuelStationManager #
This is a documentation for a fuel station management app developed in a private repo. The documentation will highlight the app's top features and its behavior-driven development. 

### Author ###
[Benson Langat](https://github.com/benie254)

### Description ###
This station management app is complete with CRUD functionalities, and generated with Angular & Django. It enables users to record daily fuel station logs, view, edit/update, and delete the logs. Standard users can do the following: 

Upon authentication  | Technical features
------------------------ | ------------------------
Add logs  | Search tool with filter
View daily/all logs  | Loader
View log details  |  Notifier
Edit logs  |  Error handling
Request email report  |  Form validation
Print log report  |  Email service
Manage profile  |  Lazy loading

## Screenshot ##
<img src="https://user-images.githubusercontent.com/99865051/200730487-0ac8b052-344e-4c2d-b9cb-79d7516b4cf0.png">

##

## Screenshot ##
<img src="https://user-images.githubusercontent.com/99865051/200730672-c0edd761-f443-4e74-a078-fe89b81fd790.png">

##

## Behavior Driven Development (BDD)
**1. Landing Page**
   - OUTPUT: Navbar, Welcome guide, Footer
   
**2. Home**
   - INPUT: Click: Navbar: 'Home'
   - OUTPUT: Home page content
   - OUTPUT: Daily fuel summary 
   
**3. All Logs:** 
   - INPUT:  Click : Navbar : 'All Logs'
   - OUTPUT: All logs content
   - OUTPUT: All records in the database
   
**4. Logs Today:**
   - INPUT:  Click : Navbar : 'Logs Today'
   - OUTPUT: Dropdown-list: 'Petrol', 'Diesel', 'Gas'
   - OUTPUT: Divider
   - OUTPUT: Dropdown-list: 'Add Log', 'Add Mpesa', 'Add CreditCard'
   
**5. Petrol/Diesel/Gas:**
   - INPUT:  Click : Navbar : 'Logs Today': Dropdown-list: 'Petrol/Diesel/Gas'
   - OUTPUT: Today fuel logs page
   - OUTPUT: Today fuel logs 
   - OUTPUT: Add logs helper if none
   
**5. Add Log/Mpesa/CreditCard:**
   - INPUT:  Click : Navbar : 'Logs Today': Dropdown-list: 'Add Log/Mpesa/CreditCard'
   - OUTPUT: Add new records page
   - OUTPUT: Add new records form(s)
   
**6. User:**
   - INPUT:  Click : Navbar : 'Username'
   - OUTPUT: Dropdown-list: 'Profile', if superuser: 'Admin'
   - OUTPUT: Divider
   - OUTPUT: Dropdown-list: 'Report Incident', 'Contact Admin'
   - OUTPUT: Divider
   - OUTPUT: Dropdown-item: 'Logout'
   
**7. Profile:**
   - INPUT:  Click : Navbar : Username: Dropdown-list: 'Profile'
   - OUTPUT: User profile page 
   - OUTPUT: App guide
   - OUTPUT: Announcements 
   - OUTPUT: User logs
   - OUTPUT: Calendar
   - OUTPUT: Footer: Toggle btn: 'Profile details'
   
**8. Profile Details:**
   - INPUT:  Click : Profile Footer : Toggle btn: 'Profile details'
   - OUTPUT: Sidebar
   - OUTPUT: Sidebar contents
   - OUTPUT: User details: 'Username', 'Email', 'Site name'
   - OUTPUT: Divider
   - OUTPUT: 'Change Password', 'Reset Password', 'Close'
   
**9. Change/Reset Password:**
   - INPUT:  Click : Profile Footer : Toggle btn: 'Profile details'
   - OUTPUT: Sidebar
   - INPUT:  Click: 'Change Password'
   - OUTPUT: Change password page
   - OUTPUT: Change password form 
   - INPUT: Click: 'Reset Password'
   - OUTPUT: Reset password page
   - OUTPUT: Reset password form
   
**10. Admin:**
   - INPUT:  Click : Navbar: Username: Dropdown-list: 'Admin'
   - OUTPUT: Admin platform
   
**11. Report Incident:**
   - INPUT:  Click : Navbar: Username: Dropdown-list: 'Report Incident'
   - OUTPUT: Report Incident page
   - OUTPUT: Reporting incidents guide
   - OUTPUT: Report incident form
  
**12. Contact Admin:**
   - INPUT:  Click : Navbar: Username: Dropdown-list: 'Contact Admin'
   - OUTPUT: Contact Admin page
   - OUTPUT: Contact admin form

**13. Footer**
   - OUTPUT: Footer
   - OUTPUT: 'Company name & copyright', 'Management', 'Incidents'
   - INPUT:  'Management'
   - OUTPUT: Contact Admin page 
   - INPUT:  'Incidents'
   - OUTPUT: Report Incident page 
   - 
**14. Logout:**
   - INPUT:  Click : Navbar: Username: Dropdown-list: 'Logout'
   - OUTPUT: Redirect: Login Page
   - OUTPUT: Login form
   - OUTPUT: Navbar: 'Login', 'Sign Up'
   - OUTPUT: Footer: Disabled: 'Company name & copyright', 'Management', 'Incidents' 

## Technologies Used 
* [Angular](https://angular.io/)
* [Django](https://www.djangoproject.com/)
* [Django Rest Framework](https://www.django-rest-framework.org/)

### Other Resources 
* [Sendgrid](https://sendgrid.com)
* [Bootstrap](https://getbootstrap.com/)
* [Adobe Color Wheel](https://color.adobe.com/)
* [Google Fonts](https://fonts.google.com)
* [Paaatterns!](https://products.ls.graphics/paaatterns/)
* [FontAwesome](https://fontawesome.com/)

## Contact 
Reach me through [mail](mailto:davinci.monalissa@gmail.com) or [LinkedIn](https://www.linkedin.com/in/benson-langat-fullstack-developer)

## License 
*Copyright (c) 2022* ***Benson Langat***

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.*

###
Copyright (c) 2022 **Benson Langat**

[Python](https://www.python.org/) version 3.10.4
