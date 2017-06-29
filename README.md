Linux Security Modules
----------------------

A collection of three simple linux security modules, more for learning and experimentation than for serious use.

* [whitelist](security/whitelist/)
   * Only allow execution of commands with xattr present.
* [hashcheck](security/hashcheck/)
   * Only allow execution of commands with xattr containing valid SHA1sum of binaries.

Finally the more serious module [can-exec](security/can-exec/) which invokes a user-space helper to decide if commands can be executed.


## Documentation

I wrote a couple of blog posts which might provide more background,
and they are listed below (in order oldest to most recent):

* https://blog.steve.fi/so_i_accidentally_wrote_a_linux_security_module.html
* https://blog.steve.fi/linux_security_modules__round_two_.html
* https://blog.steve.fi/yet_more_linux_security_module_craziness___.html
