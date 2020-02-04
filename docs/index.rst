.. Read the Docs Template documentation master file, created by
   sphinx-quickstart on Tue Aug 26 14:19:49 2014.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

DThreeLab Documentation
==================================================

Introduction
==================================================

**DThree Lab** is a software architectural platform which helps you develop other softwares without a single line of code.

We have 2 products to deliver.

* API for your current website/Mobile Apps/Software

Firstly, the homepage has four sections:- User Panel, App Developer, App Elements and Editable Mobile View.
User Panel shows you the options you have while working with a particular component. The components which are present in this user panel are the components which are to be dragged and dropped in order to make your software.
The next section is App Developer. This section shows you the actual component you are working upon. The component to be added will be picked from user panel, dragged and dropped in sub-type content present of the component currently opened in App developer section.
App Developer Section is followed by App Elements. This section contains actual elements of you app in hierarchical order. This is can be called you actual app. You can overview you app and every component you have added without opening it in this section.
The last one is the Editable Mobile View, which lets you see how you real app will look and work. The moment you save and deploy your app, you will be able to see changes in this section. This way you can decide your user interface as well as backend flow easily. 
* You can also just open a certain component by clicking it in the editable mobile view instead of searching it all your way in the App Elements Section. 
* Web view will allow you to see how you it will look like if you are creating a website or web-app.


Every component will have two types of contents: Static contents and Sub-type contents.
Static contents are the options available to edit the component itself, and it offers a variety of fields. The other one is Sub-type contents. It contains the other components which the current component will contain. The components dragged from the user panel are dropped in this region.

So, ready to build your own software? Let’s go..
First element of your app will be Elements. It is the first and the main component is Elements. It is the root of every parent containing server and UI. It contains two other main components :- 
User interface
Server

As it is the main and root component, deleting it will delete you whole app.

Front end of you app will be managed and created using User Interface component while backend will be handled under Server. Dthree labs make it easier for you to handle user interface and server simultaneously.
So, let’s get started with User Interface first.

.. contents:: Table of Contents

Contents:
==================

.. toctree::
   :maxdepth: 2
   
   authors
   usage
   root
   installation
   authors
   readme



Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

