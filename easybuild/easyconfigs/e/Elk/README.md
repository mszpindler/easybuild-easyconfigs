# Elk instructions

  * [Elk home page](https://elk.sourceforge.io/)
  

## EasyBuild
  
  * [Support in the EasyBuilders repository](https://github.com/easybuilders/easybuild-easyconfigs/tree/develop/easybuild/easyconfigs/e/Elk)
  
  * There is no support for Elk in the CSCS repository.
  
  
### Version 8.4.6 for CPE 21.12

  * Own development
  
  * Some scripts copied in the regular EasyBuilders EasyConfig are not installed
    in this version.
    
### Version 8.4.30 for CPE 22.06

  * Straightforward port of the 8.4.6 EasyConfig.
  
  * A few from the scripts from the `utilities` subdirectory are now included,
    but not `utilities/xps` as that still contains uncompiled C code so it is
    not clear what should be copied there or be built that is not yet built.