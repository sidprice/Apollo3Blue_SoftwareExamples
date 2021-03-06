================================================================================
                               apollo3-wdt
================================================================================


Copyright (C) 2013-2017, Fujitsu Electronics Europe GmbH or a               
subsidiary of Fujitsu Electronics Europe GmbH.  All rights reserved.        
                                                                            
This software, including source code, documentation and related             
materials ("Software"), is owned by Fujitsu Electronics Europe GmbH or      
one of its subsidiaries ("Fujitsu").
                                                                            
If no EULA applies, Fujitsu hereby grants you a personal, non-exclusive,    
non-transferable license to copy, modify, and compile the                   
Software source code solely for use in connection with Fujitsu's            
integrated circuit products.  Any reproduction, modification, translation,  
compilation, or representation of this Software except as specified         
above is prohibited without the express written permission of Fujitsu.      
                                                                            
Disclaimer: THIS SOFTWARE IS PROVIDED AS-IS, WITH NO                        
WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING,                        
BUT NOT LIMITED TO, NONINFRINGEMENT, IMPLIED                                
WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A                             
PARTICULAR PURPOSE. Fujitsu reserves the right to make                      
changes to the Software without notice. Fujitsu does not assume any         
liability arising out of the application or use of the Software or any      
product or circuit described in the Software. Fujitsu does not              
authorize its products for use in any products where a malfunction or       
failure of the Fujitsu product may reasonably be expected to result in      
significant property damage, injury or death ("High Risk Product"). By      
including Fujitsu's product in a High Risk Product, the manufacturer        
of such system or application assumes all risk of such use and in doing     
so agrees to indemnify Fujitsu against all liability.                       


================================================================================
History
** Date        Ver       Initials          Description
 **   - 2019-08-29  V1.0  MSc  Automatic Created
**   - 2019-08-30  V1.1  MSc             Startup for IAR corrected

Supported toolchain versions


ARM        5.11
IAR        7.30
iSYSTEM    9.12.213
Segger     4.1
================================================================================

This example demonstrates the watchdog peripheral with use of AMA3BEVBs LEDs. 

In normal operation, the application is executing a binary counter updated every 500ms.

After 5 seconds an application stall is simulated, with interrupt generated after 2 seconds 
flickering LED9. After additional 1 second the WDT will reset.

================================================================================

================================================================================ 
EOF (not truncated) 
================================================================================ 
 
