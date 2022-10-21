# K-pg_Setup
K-Pg boundary condition setup
Note: the case is located at `/glade/work/shixiongh/cases/kpg_waccm_test_v1`
After compared with the configuration that Clay proposed, we made below changes:
- ncdata = 'cw4_mi_cntrl.cam.i.0004-01-01-00000.nc' 
- comment the `prescribed_ozone_nl` module
- set `ext_frc_specifier = ''` 
- comment the `tropopause_climo_file`  

With above changes, we could get the case build-up and ready to run.  
Keep an eye on the issue...
