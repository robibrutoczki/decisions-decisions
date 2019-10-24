# decisions-decisions
###I dont understand this :The Code is working but when i try to submit,it said :Not Handles Bad or good password.
Please help !



// These variables are defined as null for now
// and will be updated by your if statements:
var accessGranted = null;
var reason = null;

function checkAdmin(adminEnabled, password){
    // Any code indented inside these curly braces
    // will be executed when the function is called
    // Copy the if statement here and use it as your starting point:
    if(adminEnabled === false){
    accessGranted=false ;reason="Admin not enabled";}

else {
  if(password==='blah'){accessGranted=true;reason="goodPassword!";}
else {accessGranted=false;reason="Wrong password";}
}}
    


// This line will call your checkAdmin() function.
// Experiment with different values to check your work!
checkAdmin(true, 'blah');

// These lines will log your updated variables to the console
console.log('Access Granted:', accessGranted);
console.log('Reason:', reason);
