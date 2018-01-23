This is IXP Package NSO place it in your NSO package Directory
In order to get this working you may need to recompile the package before loading the package in NSO

From the packages/IXP-PEERING/src/ dir
"make clear" 
"make"

Once done load up the NSO console and reload packages.
ncs_cli -u admin -C
'packages reload'
