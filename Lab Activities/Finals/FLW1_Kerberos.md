+----------------------------------+------------------------+----------+
| ![](vertopal_                    |                        |          |
| f4826bafd74048cbae53d28713ea26a1 |                        |          |
| /media/image1.png){width="2.4in" |                        |          |
| height="0.5881944444444445in"}   |                        |          |
|                                  |                        |          |
| SCHOOL OF INFORMATION AND        |                        |          |
| TECHNOLOGY                       |                        |          |
+----------------------------------+------------------------+----------+
| NAME: Doniah Camille Dizon       | DATE                   | /50      |
|                                  | PERFORMED:11/6/2024    |          |
+----------------------------------+------------------------+----------+
| Section:IDC1                     | DATE                   |          |
|                                  | SUBMITTED:11/6/2024    |          |
+----------------------------------+------------------------+----------+

# SYSADM1 -- Kerberos Basics

Research Activity

1.  What is Kerberos, and why is it used?

> \- A **Kerberos** is a system or router that provides a gateway
> between users and the internet. Therefore, it helps prevent cyber
> attackers from entering a private network. It is a server, referred to
> as an "intermediary" because it goes between end-users and the web
> pages they visit online.

2.  What are the main components of Kerberos?

\- The main components of Kerberos are: \
 

-   **Authentication Server (AS): **\
    > The Authentication Server performs the initial authentication and
    > ticket for Ticket Granting Service. \
    >  

-   **Database:** \
    > The Authentication Server verifies the access rights of users in
    > the database. \
    >  

-   **Ticket Granting Server (TGS):** \
    > The Ticket Granting Server issues the ticket for the Server

3.  What is a \"ticket\" in Kerberos, and why is it important?

> \- Kerberos uses the concept of *tickets *to keep passwords from being
> transmitted in the clear and to provide users the convenience of a
> single log-on to access multiple services and hosts.

4.  What is a Kerberos \"realm,\" and what is its purpose?

> \- Kerberos realms are a way of logically grouping resources and
> identities that use Kerberos. Your realm is the home of your Kerberos
> identity and your point of entry to the network resources controlled
> by Kerberos.

5.  How does Kerberos authenticate a user?

> \- During authentication, Kerberos stores the specific ticket for each
> session on the end-user\'s device. Instead of a password, a
> Kerberos-aware service looks for this ticket. Kerberos authentication
> takes place in a Kerberos realm, an environment in which a KDC is
> authorized to authenticate a service, host, or user. 

6.  What does each component (KDC, TGS, AS) contribute to the
    authentication process?

-   A ticket-granting server (TGS) that connects the user with the
    service server (SS)

-   A key distribution center (KDC) to authenticate and verify user
    identities.

-   An authentication server (AS) that performs the initial
    authentication

7.  How does a ticket improve security compared to repeated password
    logins?

\- Kerberos tickets enhance security over repeated password logins by
minimizing the exposure of user credentials and providing a more secure
and efficient way to authenticate users in a network environment.

References

<https://www.geeksforgeeks.org/kerberos/>

<https://web.mit.edu/kerberos/kfw-4.1/kfw-4.1/kfw-4.1-help/html/kerberos_terminology.htm#:~:text=Kerberos%20realms%20are%20a%20way,Windows%2C%20realms%20are%20called%20domains>.

<https://www.fortinet.com/resources/cyberglossary/kerberos-authentication#:~:text=A%20KDC%20involves%20three%20aspects,that%20performs%20the%20initial%20authentication>

<https://web.mit.edu/kerberos/krb5-1.18/doc/>
