# extBrPortAdd
Contains the plugin.sh , for openstack networking-odl
This change is needed to test OS br-ex and add port happening from ODL. For ODL to do this, we comment out the br-ex addition in OS and also add the provider_mappings with the string. 
The local.conf also should be updated with ODL_PROVIDER_MAPPINGS=br-ex:eth3
