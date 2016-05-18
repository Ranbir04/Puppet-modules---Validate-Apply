# Puppet-modules---Validate-Apply

Validate .pp file

Once you have written a puppet file (.pp), you need to validate it for syntax errors using the below command via Git CMD/Start command prompt with Puppet:

puppet parser validate <file path>

E.g: puppet parser validate d:\BitBucket\projects\puppet\sql\manifests\osql.pp

 

Apply Module on local system

To test locally if the puppet module will work as expected, include the manifest class in examples\init.pp file and run the below command:

puppet apply <local path of examples\init.pp> --modulepath <local path of puppet project>

E.g.: puppet apply d:\BitBucket\projects\puppet\sql\examples\init.pp --modulepath d:\BitBucket\projects\puppet

