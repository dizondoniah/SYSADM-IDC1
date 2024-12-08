+----------------------------------+------------------------+----------+
| ![](vertopal_                    |                        |          |
| f67bb5cb7bed4c4cbfeb9feeaa944dda |                        |          |
| /media/image1.png){width="2.4in" |                        |          |
| height="0.5881944444444445in"}   |                        |          |
|                                  |                        |          |
| SCHOOL OF INFORMATION AND        |                        |          |
| TECHNOLOGY                       |                        |          |
+----------------------------------+------------------------+----------+
| NAME: Doniah Camille Dizon       | DATE                   | /50      |
|                                  | PERFORMED:10/16/2024   |          |
+----------------------------------+------------------------+----------+
| Section:IDC1                     | DATE                   |          |
|                                  | SUBMITTED:10/16/2024   |          |
+----------------------------------+------------------------+----------+

# SYSADM1 -- Setting Up Webserver

# Requirement: 

-   A virtual machine running Linux and Windows OS

    Task Instructions:

1.  Install IIS by adding it as a role, select necessary features,
    include monitoring tools

    ![](vertopal_f67bb5cb7bed4c4cbfeb9feeaa944dda/media/image2.png){width="7.027083333333334in"
    height="4.892361111111111in"}

2.  Create a website by opening IIS Manager

    -   Right-click on the server's name and select Internet Information
        Services Manager.

    -   Right-click on Sites and select Add Website.

    -   Enter a name, description, physical path (where your website
        files will reside), IP address, port, and host name.

        ![](vertopal_f67bb5cb7bed4c4cbfeb9feeaa944dda/media/image3.png){width="6.584722222222222in"
        height="5.041774934383202in"}

3.  Configure the Website:

    -   Right-click on your website and select Edit.

    -   Set the Default Document to the name of your main HTML file
        \>default.html

        ![](vertopal_f67bb5cb7bed4c4cbfeb9feeaa944dda/media/image4.png){width="6.03125in"
        height="4.010461504811898in"}

    -   Configure other settings as needed (e.g., SSL certificates,
        authentication)

4.  Create a Web Page:

    -   Create an HTML file in the physical path you specified.

        ![](vertopal_f67bb5cb7bed4c4cbfeb9feeaa944dda/media/image5.png){width="3.652083333333333in"
        height="1.52377624671916in"}

        ![](vertopal_f67bb5cb7bed4c4cbfeb9feeaa944dda/media/image6.png){width="5.041380139982502in"
        height="2.448698600174978in"}

    -   Save it as default.html or your preferred name.

        ![](vertopal_f67bb5cb7bed4c4cbfeb9feeaa944dda/media/image7.png){width="5.323030402449694in"
        height="3.8217027559055117in"}

5.  Test the Web Server:

    -   Open a web browser and enter the URL of your website (e.g.,
        http://localhost).

    -   You should see your web page displayed.

        ![](vertopal_f67bb5cb7bed4c4cbfeb9feeaa944dda/media/image8.png){width="5.292404855643045in"
        height="3.0108366141732286in"}

        Grading Rubric

  ------------------------------------------------------------------------------
  **Criteria**      **Points**   **Description**
  ----------------- ------------ -----------------------------------------------
  Web Server        15           Correctly installs IIS or another web server on
  Installation                   the virtual machine.

  Website           15           Successfully configures the website with the
  Configuration                  correct physical path, IP address, port, and
                                 default document.

  Successful Access 15           Successfully accesses the web page from the
                                 client computer using the correct URL.

  Troubleshooting   15           Demonstrates ability to troubleshoot common
                                 issues, such as network connectivity problems
                                 or configuration errors.

  Documentation     10           Provides clear and concise documentation of the
                                 installation, configuration, and testing
                                 process.

  Total             /70          
  ------------------------------------------------------------------------------
