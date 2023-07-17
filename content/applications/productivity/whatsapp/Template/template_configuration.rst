=========================
Get Started with WhatsApp
=========================


Template Configuration
======================

Access your *Preferences* and choose how you would like your notifications to be handled.

.. image:: 1.png
   :align: center
   :alt: View of the preferences page for Odoo Discuss

Name Field: This field is used to specify the name or title of the WhatsApp template. It helps identify the type or purpose of the template.

Applies To Field: The "Applies To" field is used to determine which module of the template is applied to.

Phone Fields:  It is a field selector which can store any fields which can store the phone number

Template Type : There are 3 types of template type
	1 Authentication
	2 Marketing
	3 Utility

Language Field: The "Language" field is used to specify the language in which the WhatsApp template is written. It ensures that the message is sent in the appropriate language for the recipient.

Template Name : The template name is automatically generated when the stage is set to Draft and cannot be modified once created.


Footer Message Field: The "Footer Message" field describes the text that appears in the footer of the WhatsApp template preview section. It can contain additional information or a closing message.

| Header Type Field: This field determines the type of header used in the WhatsApp template. There are five possible options:

.. image:: 2.png
   :align: center
   :alt: View of an inbox message and its action options in Odoo Discuss

	3.Text: The header consists of a text message. Only one variable is used within the header, or no variables at all.

.. image:: 3.png
   :align: center
   :alt: View of an inbox message and its action options in Odoo Discuss

	Image: The header includes an image, which must be in JPEG or PNG format.
   Video: The header includes a video, which can be in either MP4 or 3GP format.

.. image:: 4.png
   :align: center
   :alt: View of an inbox message and its action options in Odoo Discuss

	Documents: there are two types available : Static Template Header and Report.
   Static Template Header
.. image:: 7.png
   :align: center
   :alt: View of an inbox message and its action options in Odoo Discuss

   Report
.. image:: 6.png
   :align: center
   :alt: View of an inbox message and its action options in Odoo Discuss


	Location: If the template includes location information, there are three fields:

		Location Name: This field is used to specify the name or title of the location.

		Location Address: Here, you can provide the address of the particular location.

		Latitude and Longitude: These two values together enable the identification of specific points or places on the globe.

.. image:: 8.png
   :align: center
   :alt: View of an inbox message and its action options in Odoo Discuss

   Footer Message Field: The "Footer Message" field describes the text that appears in the footer of the WhatsApp template preview section. It can contain additional information or a closing message.

.. image:: 15.png
   :align: center
   :alt: View of an inbox message and its action options in Odoo Discuss


WhatsApp Message View
=====================

In the body page of a WhatsApp template, you write the content that will be displayed to the recipient. Within this content, variables can be used.
Variables are represented by such as {{1}}, {{2}}, and so on.

.. image:: 1.png
   :align: center
   :alt: View of discuss’s panel emphasizing the titles channels and direct messages in Odoo Discuss

In the button page of the template, there are three types of buttons available:

	Visit Website: This button allows the recipient to visit a website directly. There are two types of Visit Website buttons:

		Static: A static Website leads to the same website for all recipients who receive the template.
				
		Dynamic: A dynamic website provides a dynamically generated link

   call Number: This button enables the recipient to make a direct call from within the WhatsApp preview section. When clicked, it initiates a phone call to the specified number.

	Quick Reply: Quick Reply are used predefined responses or quick replies.

.. image:: 14.png
   :align: center
   :alt: View of discuss’s panel emphasizing the titles channels and direct messages in Odoo Discuss


In the variable page of a WhatsApp template, you can define variables that are used within the body,header or button of the template.

	Name: The name field is automatically displayed.

	Sample Value: The sample value field is where you can provide an example value based on the variable type.

	Type Field: The type field allows you to specify the type of data that the variable represents. There are five different types available:

		User Name: This type is used to display the user name of the current user who receives the template.

		User Mobile: This type is used to display the phone number of the current user who receives the template.

		Free Text: With this type, you can enter any text value, and it will be displayed in the WhatsApp Message. It allows for custom messages or information.

		Portal Link: This type is used when you want to include a link to a specific portal or website. It enables dynamic linking within the template.

		Fields of Model: This type allows you to reference fields or variables from a specific data model.


.. image:: 10.png
   :align: center
   :alt: View of discuss’s panel emphasizing the titles channels and direct messages in Odoo Discuss
