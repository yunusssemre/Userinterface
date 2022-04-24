# Userinterface

# <h1>__UI specification document__

At the beginnig, there will three sections in the page:Top bar ,User information,New user form

The top bar will be used for three operations. The operations and their purposes are as follows.

   - __New user button__ : When the new user clicks the button, it is expected to activate the new user add panel on the same page.
   - __Hide disabled users checkbox__ : When this checkbox is checked, it is expected to remove disabled users from the user list.
   - __Save user button__ : This button saves the data of the user who has filled in the new user panel completely and correctly .

In the user information section, there will be a table containing the information of the registered users and this table is expected to have the following information.

  - __User ID__ : the IDs are filtered from large to small or small to large.
  - __User Name__ : User Name is string variable. It sorts alphabetically from  A to Z or Z to A.
  -	__User E-mail__ : Email is string variable. It sorts alphabetically from A to Z or Zto A.
  -	__User Enabled__ : User Status is boolean variable. Boolean working principle is true or false. So it sorts enabled to disabled or disabled to enabled.
    

In the new user panel, it is expected that there will be a form  that allows to collect the necessary information of the user who has not been registered before.The necessary information is as follows.

  -	__Username Textbox__ : The username of the user to be registered is entered here.
  -	__Display Name Textbox__ : The phone number of the user to be registered is entered here.
  -	__Phone Textbox__ : The phone number of the user to be registered is entered here.
  -	__Email Textbox__ : The email of the user to be registered is entered here.
  -	__User Role Menu__ : This field list all user roles. the user can be registered either as a Guest or Admin or SuperAdmin.
  -	__User Status Checkbox__ : If the user is an active user, then this is marked. After all the necessary boxes are filled in, click the save user button and the page is refreshed. The new user switches to the user list.







