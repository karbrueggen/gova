gova
====
PDS_VERSION_ID               = PDS3                                           
FILE_RECORDS                 = 96                                             
RECORD_TYPE                  = "FIXED_LENGTH"                                 
RECORD_BYTES                 = 2880                                           
                                                                              
DATA_SET_ID                  = "DI/EAR-C-KECK1LWS-3-9P-IMAGES-PHOT-V1.0"      
PRODUCT_ID                   = "DI_9P_KECK1LWS_EDR_IMG_FOCUS0062"             
PRODUCT_NAME                 = "                                              
  9P/TEMPEL1 RAW MID-IR IMAGES FROM KECK1 LWS, FOCUS0062.FIT"                 
PRODUCT_CREATION_TIME        = 2004-12-10T09:25:48                            
TARGET_NAME                  = "BETA ANDROMEDAE"                              
INSTRUMENT_HOST_NAME         = "KECK I 10M TELESCOPE"                         
INSTRUMENT_NAME              = "KECK I LONG WAVELENGTH SPECTROGRAPH (IR)"     
START_TIME                   = 2000-08-21T10:53:45.57                         
STOP_TIME                    = "UNK"                                          
EXPOSURE_DURATION       = 27.0043 <SECOND> /*Time on target without overhead*/
                                                                              
RIGHT_ASCENSION              = 17.432917 <DEGREE>                             
DECLINATION                  = 35.620552 <DEGREE>                             
AIRMASS                      = 1.2679                                         
FILTER_NAME                  = "12.5_MICRON"                                  
TARGET_HELIOCENTRIC_DISTANCE = 2.547 <AU>                                     
TARGET_GEOCENTRIC_DISTANCE   = 1.667 <AU>                                     
PHASE_ANGLE                  = 13.93 <DEGREE>                                 
NOTE                         = "                                              
  Fernandez et al. (2003) note that the sky condition on this                 
  night was 'thin cirrus' and data taken this night were the                  
  most useful of this data set. Right ascension and delicnation are J2000.    
  "                                                                           
                                                                              
^FITS_HEADER                 = "FOCUS0062.FIT"                                
^ARRAY                       = ("FOCUS0062.FIT", 5)                           
                                                                              
OBJECT     = FITS_HEADER                                                      
  HEADER_TYPE        = "FITS"                                                 
  BYTES              = 11520                                                  
  RECORDS            = 4                                                      
  INTERCHANGE_FORMAT = "BINARY"                                               
  DESCRIPTION        = "                                                      
    Original FITS header supplied with the data. FITS format is               
    defined in NASA/Science Office Standards Technology 100-1.0.              
    "                                                                         
END_OBJECT = FITS_HEADER                                                      
                                                                              
OBJECT     = ARRAY                                                            
  NAME               = "IMAGE_6D"                                             
  INTERCHANGE_FORMAT = "BINARY"                                               
  AXES               = 6                                                      
  AXIS_ITEMS         = (128,128,2,1,2,1)                                      
  AXIS_NAME          = ("COLUMNS", "ROWS", "CHOP BEAMS",                      
                        "CHOP SETS", "NOD BEAMS", "FINAL NOD SETS")           
  AXIS_ORDER_TYPE    = "FIRST_INDEX_FASTEST"                                  
  START_BYTE         = 11521                                                  
                                                                              
  OBJECT     = ELEMENT                                                        
    DATA_TYPE = "MSB_INTEGER"                                                 
    BYTES     = 4                                                             
    NAME      = "DATA COUNT"                                                  
    MAXIMUM   = 5528250                                                       
    MINIMUM   = 0                                                             
  END_OBJECT = ELEMENT                                                        
END_OBJECT = ARRAY                                                            
                                                                              
END                                                                           
