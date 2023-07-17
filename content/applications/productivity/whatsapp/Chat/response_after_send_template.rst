===================================
Configure ICE servers with whatsapp
===================================

Odoo Discuss uses WebRTC API and peer-to-peer connections for voice and video calls. If one of the
call attendees is behind a symmetric NAT, you need to configure an ICE server to establish a
connection to the call attendee. To set up an ICE server, first, create a Twilio account for video
calls, and then, connect that Twilio account to Odoo.

Create a Twilio account
=======================

First, go to `Twilio <https://www.twilio.com>`_ and click :guilabel:`Sign up` to create a new
Twilio account. Next, enter your name and email address, create a password, and accept Twilio's
terms of service. Then, click :guilabel:`Start your free trial`. Verify your email address with
Twilio, as per their instructions.

Next, enter your phone number into Twilio. Then, Twilio will send you an SMS text message
containing a verification code. Enter the verification code into Twilio to verify your phone
number.

After that, Twilio redirects to a welcome page. Use the following list to answer Twilio's
questions:

- For :guilabel:`Which Twilio product are you here to use?`, select :guilabel:`Video`.
- For :guilabel:`What do you plan to build with Twilio?`, select :guilabel:`Other`.
- For :guilabel:`How do you want to build with Twilio?`, select :guilabel:`With no code at all`.
- For :guilabel:`What is your goal today?`, select :guilabel:`3rd party integrations`.

.. image:: test_servers/download.jpeg
   :align: center
   :alt: The whatsapp welcome page.

If necessary, change the billing country. Finally, click :guilabel:`Get Started with Twilio`.
