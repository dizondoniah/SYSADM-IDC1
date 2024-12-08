+----------------------------------+------------------------+----------+
| ![](vertopal_                    |                        |          |
| a480ff658f2d41ab9b226dd010238ba7 |                        |          |
| /media/image1.png){width="2.4in" |                        |          |
| height="0.5881944444444445in"}   |                        |          |
|                                  |                        |          |
| SCHOOL OF INFORMATION AND        |                        |          |
| TECHNOLOGY                       |                        |          |
+----------------------------------+------------------------+----------+
| NAME: Dizon, Doniah Camille G.   | DATE                   |          |
|                                  | PERFORMED:09/11/2024   |          |
+----------------------------------+------------------------+----------+
| Section:IDC1                     | DATE                   |          |
|                                  | SUBMITTED:09/11/2024   |          |
+----------------------------------+------------------------+----------+

# SYSADM1 -- Managing Services in Linux

# Requirement: 

-   A virtual machine running Linux

![](vertopal_a480ff658f2d41ab9b226dd010238ba7/media/image2.png){width="4.135416666666667in"
height="1.8020833333333333in"}

Complete this lab as follows:

1.  Use the service --status-all command to list all active and inactive
    services.

List down active and inactive services in the table below. Provide five
(5) services for each column.

  -----------------------------------------------------------------------
  **Active**                             **Inactive**
  -------------------------------------- --------------------------------
  alsa-utils                             anacron

  apport                                 apparmor

  cron                                   bluetooth

  dbus                                   rsync

  kmod                                   saned
  -----------------------------------------------------------------------

SS:
![](vertopal_a480ff658f2d41ab9b226dd010238ba7/media/image3.png){width="7.027083333333334in"
height="4.600694444444445in"}![](vertopal_a480ff658f2d41ab9b226dd010238ba7/media/image4.png){width="6.990972222222222in"
height="2.683015091863517in"}

2.  Start the Bluetooth service using the systemctl command.

Ex. sudo systemctl start httpd

![](vertopal_a480ff658f2d41ab9b226dd010238ba7/media/image5.png){width="4.359946412948381in"
height="1.1875in"}

3.  Check the status of the Bluetooth service. What is its status?

-The status is inactive

SS:

![](vertopal_a480ff658f2d41ab9b226dd010238ba7/media/image6.png){width="4.354774715660542in"
height="2.0940419947506563in"}
![](vertopal_a480ff658f2d41ab9b226dd010238ba7/media/image7.png){width="7.027083333333334in"
height="2.31875in"}

4.  Check the status of the cups services. Since when was it running?

-Since Wed 2024-09-11 00:07:30, 52 mins ago.

SS:
![](vertopal_a480ff658f2d41ab9b226dd010238ba7/media/image8.png){width="7.027083333333334in"
height="3.3993055555555554in"}

5.  Stop cups

![](vertopal_a480ff658f2d41ab9b226dd010238ba7/media/image9.png){width="6.417562335958006in"
height="0.29170713035870516in"}

6.  Verify if the service was stopped.

![](vertopal_a480ff658f2d41ab9b226dd010238ba7/media/image10.png){width="7.027083333333334in"
height="3.526388888888889in"}

7.  Restart the cups services

![](vertopal_a480ff658f2d41ab9b226dd010238ba7/media/image11.png){width="6.730106080489938in"
height="1.5418821084864391in"}

8.  Verify if the service was restarted.

![](vertopal_a480ff658f2d41ab9b226dd010238ba7/media/image12.png){width="7.027083333333334in"
height="3.870833333333333in"}
