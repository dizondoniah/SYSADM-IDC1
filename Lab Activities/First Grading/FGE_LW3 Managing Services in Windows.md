+----------------------------------+------------------------+----------+
| ![](vertopal_                    |                        |          |
| 7eab67cd10a74758a6d7e157e6cef2d9 |                        |          |
| /media/image1.png){width="2.4in" |                        |          |
| height="0.5881944444444445in"}   |                        |          |
|                                  |                        |          |
| SCHOOL OF INFORMATION AND        |                        |          |
| TECHNOLOGY                       |                        |          |
+----------------------------------+------------------------+----------+
| NAME: Doniah Camille G. Dizon    | DATE                   |          |
|                                  | PERFORMED:08/28/2024   |          |
+----------------------------------+------------------------+----------+
| Section:IDC1                     | DATE SUBMITTED:        |          |
|                                  | 08/28/2024             |          |
+----------------------------------+------------------------+----------+

# SYSADM1 -- Managing Services in Windows

# Requirement: 

-   A virtual machine running Linux and Windows OS

    **Services** are background processes that run independently of user
    interactions in Windows. They provide essential system functions,
    such as network connectivity, printing, and time synchronization.
    This lab will guide you through the process of managing services
    using the Services app.

# Instructions:  {#instructions .list-paragraph}

1.  Open the Start menu and search for \"Services\"

2.  Familiarize yourself with the columns, including Service Name,
    Display Name, Status, and Startup type.

3.  Right-click on a service and select \"Start\", \"Stop\", or
    \"Restart\". Fill out the table below

  -----------------------------------------------------------------------------------------------------------------------------
  **Status**   **Name of         **Screenshot**
               Service**         
  ------------ ----------------- ----------------------------------------------------------------------------------------------
  Start        Adobe Version Cue ![](vertopal_7eab67cd10a74758a6d7e157e6cef2d9/media/image2.png){width="3.9120450568678917in"
               CS4               height="2.9753029308836396in"}

                                 

  Stop         Adobe Version Cue ![](vertopal_7eab67cd10a74758a6d7e157e6cef2d9/media/image3.png){width="3.8125in"
               CS4               height="2.2825470253718287in"}

  Restart      Adobe Version Cue ![](vertopal_7eab67cd10a74758a6d7e157e6cef2d9/media/image4.png){width="3.869948600174978in"
               CS4               height="2.0208333333333335in"}

  Pause                          
  -----------------------------------------------------------------------------------------------------------------------------

4.  Select five network services, right-click to view its properties.
    Modify the startup setting to Manual.

> **SS**:
>
> BitLocker Drive Encryption Service
>
> ![](vertopal_7eab67cd10a74758a6d7e157e6cef2d9/media/image5.png){width="4.336887576552931in"
> height="4.191516841644795in"}
>
> Adobe Version Cue CS4
>
> ![](vertopal_7eab67cd10a74758a6d7e157e6cef2d9/media/image6.png){width="3.7509722222222224in"
> height="4.0571730096237975in"}
>
> Block Level Backup Engine
>
> ![](vertopal_7eab67cd10a74758a6d7e157e6cef2d9/media/image7.png){width="3.7916666666666665in"
> height="3.6145833333333335in"}
>
> Client License Service
>
> ![](vertopal_7eab67cd10a74758a6d7e157e6cef2d9/media/image8.png){width="3.8242082239720037in"
> height="4.047217847769029in"}
>
> Capability Access Manager Service
>
> ![](vertopal_7eab67cd10a74758a6d7e157e6cef2d9/media/image9.png){width="4.521464348206474in"
> height="5.167387357830271in"}

5.  Explore the \"General\", \"Recovery\", and \"Log On\" tabs to
    understand additional service settings.

6.  Create a batch file that will be added as a new service later on.
    Refer to the batch file code below.

> ![](vertopal_7eab67cd10a74758a6d7e157e6cef2d9/media/image10.png){width="4.808325678040245in"
> height="2.0055664916885387in"}

7.  Save the batch file in Z:\\lastname_timer.bat

> ![](vertopal_7eab67cd10a74758a6d7e157e6cef2d9/media/image11.png){width="7.011395450568679in"
> height="4.479792213473316in"}

8.  Use the sc command to add timer.bat service in the command line
    interface.

> *sc create BatchTimerService binPath= \"path_to_your_batch_file.bat\"
> start= auto*
>
> *net start BatchTimerService*
>
> **Replace path_to_your_batch_file.bat with the actual path to your
> batch file.**

9.  Verify that BatchTimerService has been added to the services.

> **SS:**
> ![](vertopal_7eab67cd10a74758a6d7e157e6cef2d9/media/image12.png){width="4.402128171478565in"
> height="4.387024278215223in"}

10. **Testing the Service:** Now, if you open a new command prompt, you
    should see the timer countdown without requiring your interaction.
    Once the timer finishes, you\'ll see the \"Timer finished!\"
    message.

> **SS:**
> ![](vertopal_7eab67cd10a74758a6d7e157e6cef2d9/media/image13.png){width="6.323799212598425in"
> height="2.6670384951881014in"}

**Rubric**

  ---------------------------------------------------------------------------------------
  **Criteria**      **Excellent       **Good (7)**    **Needs          **Unsatisfactory
                    (10)**                            Improvement      (1)**
                                                      (3)**            
  ----------------- ----------------- --------------- ---------------- ------------------
  Understanding of  Demonstrates a    Shows a solid   Has a basic      Shows little or no
  Services          deep              understanding   understanding of understanding of
                    understanding of  of services,    services, but    services.
                    the concept of    but may lack    may struggle     
                    services, their   some depth in   with specific    
                    roles, and their  specific areas. concepts.        
                    importance in                                      
                    Windows.                                           

  Service           Successfully      Demonstrates    Can perform      Struggles to
  Management Skills starts, stops,    proficiency in  basic service    perform even basic
                    restarts, and     managing        management       service management
                    configures        services, but   tasks, but may   tasks.
                    services using    may encounter   need assistance  
                    the Services app. minor           or guidance.     
                                      difficulties.                    

  Custom Service    Successfully      Can create a    Has limited      Cannot create a
  Creation          creates and       custom service, experience with  custom service.
                    manages a custom  but may         creating custom  
                    service using the encounter minor services.        
                    appropriate tools difficulties or                  
                    and techniques.   require                          
                                      assistance.                      

  Problem-Solving   Demonstrates      Can effectively May require      Struggles to
                    strong            troubleshoot    assistance to    troubleshoot and
                    problem-solving   and resolve     troubleshoot     resolve issues.
                    skills when       most issues     some issues.     
                    encountering      related to                       
                    challenges or     service                          
                    errors.           management.                      

  Documentation and Provides clear    Documents the   Provides basic   Does not provide
  Reporting         and concise       lab activities  documentation,   any documentation
                    documentation of  adequately, but but may be       or reporting.
                    the lab           may lack some   disorganized or  
                    activities,       detail or       incomplete.      
                    including         clarity.                         
                    relevant                                           
                    screenshots and                                    
                    observations.                                      

  **Score:**        **50 /50**                                         
  ---------------------------------------------------------------------------------------
