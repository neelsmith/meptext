#meptext#

Build project for Churik and Smith article on design of Venetus A.

Source text is in citedown (that is, markdown with extensions for CITE architecture URNs). The gradle build uses the cd2md library to convert the citedown source to pure markdown, and includes a task to copy the resulting markdown to an appropriate location for formatting using leanpub's on line service.