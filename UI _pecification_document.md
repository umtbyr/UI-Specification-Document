#UI Specification Document

*HEADER(
    -New User button (blue button with a plus sign text color = white)
        ->Adds new user to the User Table

    -Hide Disabled User checkbox (text color = black)
        ->Hides the Disabled users in the User Table

    -Save User button (blue button with white check sign text color = white)
        ->Saves user to the User Table(If given information is sufficent)
        ->It shows a message if given information is not adequate 
)

*USER INFORMATION TABLE(
    Displays users informations

    -4 columns (ID, User Name, Email, Enabled) 
    -column color = blue
    -Each column is scrollabe in itself 
    -Filling the left half of the screen(height stars from the header)
    -Header's text color = white
    -Information's text color = black

    
)

*NEW USER FORM(
    Collects data from the user

    -Requires 6 pieces of information(Username, Display Name, Phone,
    Email, User Roles(dropdown list which includes : Guest, Admin, SuperAdmin), Enabled(checkbox))
    -text color = black
    -Filling the right half of the screen(height stars from the header)
)