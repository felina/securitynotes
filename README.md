Security Notes
=============

General Security Notes that need to be covered before release

Forgotten Password Vulnerability
- When giving the option for users to reset their password we ask them for the email address they signed up with. However,
  a lot of sites do this very stupidly and confirm that a password reset has been sent to the email address specified only   if it is in the database. We should not do this. What we do is confirm that a password reset has been sent even if the 
  email is not in the databse. If you don't understand why the normal way that websites carry this out is a problem just 
  ask.
