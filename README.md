Email Me
============================

Just a simple helper and config to email the developer when something happens. Saves some steps.


Setup
----------------------------

1. Install Sparks at [GetSparks.org](http://getsparks.org)
3. Edit **config/email_me.php** with whatever email addresses you want to include in your emails.

Usage
----------------------------

Load Spark 

    $this->load->spark('email_me/x.x.x');

Email yourself

    email_me('a message');
    
More options

    email_me('a message', 'a subject', 'someone_else@test.com');


----------------------------

Changelog
----------------------------

**1.0.0**

* Initial Release