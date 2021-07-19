<div align="center">
<img width="700" src="https://github.com/Imranr2/NUSPM/blob/main/readme_markup/Logo.png?raw=true" alt="NUSPM Logo">
</div>
<h1 align="center">Your one-stop solution for tutorial management</h1>
<h2 align="center"><a href="https://nuspm.netlify.app/">Click here to get started!</a></h2>

<h3><strong>Proposed Level of Achievement:</strong> Gemini</h3>
<br>
<h2><strong>Project Scope</strong></h2>
<p>A webapp that allows students to connect and find better tutorial slots.

NUSPM enables students to create swap requests to trade their tutorial slot for a more desirable one. Students are also able to initiate swap requests with other students. This solves the current issue which involves asking on multiple platforms(Telegram, Reddit etc…) which is troublesome and inefficient.

<div align="center">
  <kbd>
     <img src="https://github.com/Imranr2/NUSPM/blob/main/readme_markup/Flow%20Chart.png?raw=true" alt="Flow Chart">
  </kbd>
  <p><strong>Flow Chart</strong></p>
</div>
</p>
<h2><strong>Motivation</strong></h2>
<p>Imagine that you were allocated a tutorial slot that does not fit in your timetable. At this point, you are feeling stressed out as you might not be able to secure your desired tutorial slot and might be forced to drop the module. You also have no way of knowing if there is another student willing to swap with your slot. Also due to the covid situation, it is difficult to reach out to other students taking the same module and you might be left with an undesirable slot even after the first add/swap tutorial exercise. What if there was a website that you can use to find potential swaps before the round starts? This will immensely alleviate the stress that you are having. Welcome to NUSPM, a website where you can create requests for swaps and also view requests created by other students who are facing the same problem.
</p>
<h2><strong>Aim</strong></h2>
<p>We hope to create a more seamless tutorial swapping exercise as well as create a less stressful experience for all students through our web-application where all students can gather on a single platform to look for their preferred tutorial slots, which helps make timetable planning a better experience.
</p>
<h2><strong>Tech Stack</strong></h2>
<ol>
<li>ReactJS (Frontend)
</li>
<li>Ruby on Rails (Backend)</li>
<li>PostgreSQL (Database)
</li>
<li>NUSMods (Source for module information)
</li>
</ol>
<h2><strong>User Stories</strong></h2>
<ol>
  <li>As a student who wants to swap their tutorial slot for another, I want to be able to view all possible options.
</li>
  <li>As a student, I would also want to create swap requests to improve my chances of finding a desired tutorial slot.</li>
  <li>As a student, I want to be able to update or delete my swap preference.</li>
  <li>As a student, I want to be able to view the details of the slot that is available.
</li>
</ol>
<h2><strong>Project Scope</strong></h2>
<p>A webapp that allows students to connect and find better tutorial slots.

NUSPM enables students to create swap requests to trade their tutorial slot for a more desirable one. Students are also able to initiate swap requests with other students. This solves the current issue which involves asking on multiple platforms(Telegram, Reddit etc…) which is troublesome and inefficient. As such, the project can be divided into 3 core features:

<ol>
<li>User Authentication - Keep track of users
</li>
<li>Create Swap and Marketplace - Allow users to create swap requests of their own as well as search for potential swaps by others
</li>
<li>Swaps and Offers - Allow users to view and manage their current swaps and offers
</li>
</ol>
</p>

<h3><strong>Milestone 1: User Authentication</strong></h3>
<ol>
<li>Frontend Register/Login page<br/>

Set up the 2 pages to allow users to create accounts and login

<div align="center">
  <kbd>
     <img src="https://github.com/Imranr2/NUSPM/blob/main/README_Images/Login.png" alt="Login">
  </kbd>
  <p><strong>Login</strong></p>
</div>

<div align="center">
  <kbd>
     <img src="https://github.com/Imranr2/NUSPM/blob/main/README_Images/Register.png" alt="Login">
  </kbd>
  <p><strong>Register</strong></p>
</div>

</li>
<li>Backend API and Database<br/>

Set up backend API and database for user registration and login

</li>
<li>JSON Web Token(JWT) for Authentication<br/>

Users can create an account, login and are assigned a JWT after authentication. Pages are inaccessible to users who are not logged in and they will be redirected to the login page

</li>
</ol>

<h3><strong>Milestone 2: Home, Marketplace, Your Swap and Offers
</strong></h3>

<ol>
<li>Home - Navigation Bar<br/>

Upon logging in, users are brought to the home page. The navigation bar at the top of the page allows users to switch between pages and also consists of the notification system for users to track updates on their statuses.

<!-- edit this -->
<div align="center">
  <kbd>
     <img src="https://github.com/Imranr2/NUSPM/blob/main/README_Images/Login.png" alt="Navbar">
  </kbd>
  <p><strong>Navbar</strong></p>
</div>

</li>
<li>Home - Introductory Video<br/>

The video gives a quick introduction of the web application and how to use it to create and initiate swap requests, as well as accepting requests from other users.

<!-- edit -->
<div align="center">
  <kbd>
     <img src="https://github.com/Imranr2/NUSPM/blob/main/README_Images/Login.png" alt="Homepage">
  </kbd>
  <p><strong>Homepage</strong></p>
</div>

</li>
<li>Create Swap<br/>

On the Create Swap page, users are able to create their own swap request where they will input their module code, slot type, current slot and desired slots.<br/>
The module information is retrieved from NUSMods which guarantees the accuracy of the information for users. If the user is open to multiple tutorial slots, they can select more than one in the options. Users can only create 1 swap request per module for a given slot type, making the swap requests easy to view and manage. Upon successful creation of a swap, they can click on the link to go to the Marketplace to look for potential swaps.

<div align="center">
  <kbd>
     <img src="https://github.com/Imranr2/NUSPM/blob/main/README_Images/CreateSwap.png" alt="Create Swap">
  </kbd>
  <p><strong>Create Swap</strong></p>
</div>

</li>
<li>Marketplace

On the Marketplace page, users can key in their current slot details and search for swap requests from other users that desire the slot they currently have.

<div align="center">
  <kbd>
     <img src="https://github.com/Imranr2/NUSPM/blob/main/README_Images/MarketplaceSearchBar.png" alt="Marketplace Search Bar">
  </kbd>
  <p><strong>Marketplace Search Bar</strong></p>
</div>
If the user finds a slot they prefer, they click on it and follow a few simple steps to initiate the offer to the other user.<br/>
<div align="center">
  <kbd>
     <img src="https://github.com/Imranr2/NUSPM/blob/main/README_Images/Marketplace.png" alt="Marketplace">
  </kbd>
  <p><strong>Step 1: Key in their slot details and search for potential swaps<br/></strong></p>
</div>

<div align="center">
  <kbd>
     <img src="https://github.com/Imranr2/NUSPM/blob/main/README_Images/MarketplaceD0.png" alt="Marketplace First Dialog">
  </kbd>
</div>
Step 2: Choose the swap that they have created<br/>
<div align="center">
  <kbd>
     <img src="https://github.com/Imranr2/NUSPM/blob/main/README_Images/MarketplaceD1.png" alt="Marketplace Second Dialog">
  </kbd>
</div>
Step 3: Confirm the details of the swap and initiate<br/>
This sends the offer to the other parties where they can accept or reject the offer.<br/>
<br/>
A key feature of this process is that users do not need to have a swap created beforehand to initiate the offer. The details they keyed in to search previously is auto filled in for them if they do not have a swap yet and the swap is created on the spot.
<div align="center">
  <kbd>
     <img src="https://github.com/Imranr2/NUSPM/blob/main/README_Images/MarketplaceAutoCreate.png" alt="Marketplace Auto Create Dialog">
  </kbd>
</div>
</li>

<li>Your Swaps and Offers<br/>
On the Your Swaps page, users can view all their swaps and offers in the 5 tabs, namely:
<ol>
<li>Current Offers (Offers sent to the user). In the Current Offers tab, users can either accept or reject the offers they receive.<br/>
</li>
<li>Current Swaps (Swaps created by the user that are not completed yet). In the Current Swaps tab, users can edit or delete the swap that they have created.<br/>
</li>
<li>Pending Offers (Offers sent by the user that are pending). In the Pending Offers tab, users can withdraw their offers.<br/>
</li>
<li>Completed Swaps (Swaps created by the user that are completed). In the Completed Swaps tab, users can free up the swap, which removes the offer that is already completed (users are recommended to communicate with the other party in the event this option is needed).<br/>
</li>
<li>Rejected Offers (Offers sent by the user that are rejected). In the Rejected Offers tab, users can view their rejected offers.
</li>
<div align="center">
  <kbd>
     <img src="https://github.com/Imranr2/NUSPM/blob/main/README_Images/YourSwapTabs.png" alt="Your Swap and Offers Tabs">
  </kbd>
</div>
</ol>
</li>
</ol>

<h3><strong>Milestone 3: Responsiveness, Notification System, UI updates, Bug fixes</strong></h3>

<ol>
<li>
Responsive layout for mobile devices and smaller screens<br/>
<ol>
<li>Navigation bar<br/>
Navbar displays icons on smaller screens
<div align="center">
  <kbd>
     <img src="https://github.com/Imranr2/NUSPM/blob/main/README_Images/ResponsiveNavbar.png" alt="Your Swap and Offers Tabs">
  </kbd>
</div>
</li>
<li>Search bar (Marketplace)<br/>
Change horizontal search bars to drawer
<div align="center">
  <kbd>
     <img src="https://github.com/Imranr2/NUSPM/blob/main/README_Images/MarketplaceDrawer.png" alt="Marketplace Search Drawer">
  </kbd>
</div>
</li>
<li>Your Swap and Offers<br/>
Changed tabs to display icons on smaller screens
<div align="center">
  <kbd>
     <img src="https://github.com/Imranr2/NUSPM/blob/main/README_Images/ResponsiveYourSwap.png" alt="Your Swap and Offer Tab Icons">
  </kbd>
</div>
</li>
</ol>
</li>
<li>Notification System<br/>
The notification system sends notifications to the users as follows: 
<ol>
<li>On accepting an offer/having an offer accepted by another user, users will receive a green success alert
<div align="center">
  <kbd>
     <img src="https://github.com/Imranr2/NUSPM/blob/main/README_Images/GreenNotif.png" alt="Success Notifications">
  </kbd>
</div>
</li>
<li>On creating/sending/receiving/editing swaps/offers, users will receive a blue info alert
<div align="center">
  <kbd>
     <img src="https://github.com/Imranr2/NUSPM/blob/main/README_Images/BlueNotif.png" alt="Info Notifications">
  </kbd>
</div>
</li>
<li>On rejecting/deleting/withdrawing swaps/offers, users will receive a red error alert.<br/>
<div align="center">
  <kbd>
     <img src="https://github.com/Imranr2/NUSPM/blob/main/README_Images/RedNotif.png" alt="Delete/Reject Notifications">
  </kbd>
</div>
The latest 10 notifications are shown to the users.

</li>
</ol>
</li>
<li>UI Updates
<ol>
<li>Added not found icons to inform users when there are no swaps available etc
</li>
<li>Display success/error alerts as well as loaders when a user is making a request to the backend API
</li>
<li>Standardised information displayed on cards throughout the site
</li>
<li>Marketplace/Create Swap: Disable autocomplete fields if no options are available. Fields are also disabled if the user has yet to select a module code/slot type
</li>
</ol>
</li>
<li>Bug fixes
<ol>
<li>Fixed incorrect positions of swap details in Your Swap and Offers page
</li>
<li>Fixed issue where alerts persist even after moving to a different page
</li>
</ol>
</li>
</ol>

<h2><strong>Feature Limitations
</strong></h2>
<p>Although the system works as intended, there are still some limitations which we will be addressing in the following section.
</p>
<h3><strong>NUS Authentication Service
</strong></h3>
<p>NUSPM is not integrated with NUS Authentication Service, hence malicious users can create accounts using other students emails causing them to not be able to create an account</p>
<h3><strong>Luminus API
</strong></h3>
<p>NUSPM is not integrated with the LUMINUS API. This means users can create offers/swaps for modules that they are not enrolled in, which can be misleading for other users.
</p>
<h3><strong>In App notification
</strong></h3>
<p>The in app notification is not ‘real-time’ and does not refresh in cases such as other users accepting the user’s offers. The notifications component currently refreshes on page switching.
</p>
<h3><strong>External Notification System
</strong></h3>
<p>Users are only notified of offers through in app notifications as no emails are sent out to the users
</p>
<h3><strong>Responsiveness
</strong></h3>
<p>NUSPM was not tested with many different mobile devices. There is insufficient testing on mobile devices thus user experience may vary across different mobile devices and they are recommended to use the web application. It is also not compatible with Safari.
</p>
<h3><strong>Delay in NUSMods API call
</strong></h3>
<p>NUSPM queries the NUSMods API for all the module information and does not save the information into the backend. This can cause a delay in the retrieval of information when displaying to the autocomplete boxes.
</p>

<h2><strong>Unified Modelling Language (UML) Diagrams
</strong></h2>
<p>
The diagram below illustrates the activities users could perform on the web application.<br/>
<!-- behaviour -->
Firstly, users register and login with their accounts, where they are brought to the home page, which features a video going through the usage of the application. Next, they can proceed to the Create Swap page to post their swap request for others to view, or head to the Marketplace to search for swaps other users posted. Subsequently, they can head over to the Your Swap and Offers page to check the status of their swaps/offers, as well as performing follow up actions such as accepting offers from other users. THe notification system serves to notify users about any changes they make as well as incoming offers.<br/>
Next, we have the component tree of the web application illustrating it’s structure.
<!-- component -->
The main part of our web application are the pages(Login, Home etc..), these all contain the Navigation Bar, as well as their respective sub components. 
</p>

<h2><strong>Entity Relationship Diagram (ERD)
</strong></h2>
<!-- erd and some explanation -->

<h2><strong>User Experience
</strong></h2>
<!-- some explanation -->

<h2><strong>Response to Milestone Evaluations
</strong></h2>
<h3><strong>Milestone 1</strong></h3>
<p><strong>Suggestion/Question:</strong>
Is there anything to stop people from creating multiple accounts?
</p>
<p><strong>Response:</strong>
No. We are currently not integrated with NUS Authentication Service. However we have implemented a REGEX to only match valid NUS email addresses
</p>
<p><strong>Suggestion/Question:</strong>
I want to be able to view the details of the slot that is available and see the impact of the swap on my timetable.
</p>
<p><strong>Response:</strong>
We have decided to not go through with this feature as we believe it is too complex to implement.
</p>
<p><strong>Suggestion/Question:</strong> Poster was too wordy/informative and words were too small
</p>
<p><strong>Response:</strong> We decided to only leave the wireframes in the poster and deleted all the text.
</p>
<p><strong>Suggestion/Question:</strong>Implement a password recovery system
</p>
<p><strong>Response:</strong> We are thinking about it
</p>
<p><strong>Suggestion/Question:</strong>
If a user accepts an offer, will all other offers for the same module be automatically rejected? Conversely, what if one of the user's offers is accepted? Will the user's other offers automatically be withdrawn?
</p>
<p><strong>Response:</strong> Consider the following scenario with 2 users A and B:
B sends an offer to A and many other users. A also sends offer to many other users. In the event that A accepts the offer from B, all offers that were sent out by A and B will be automatically withdrawn. However, all other offers that were received by A and B will not be automatically rejected. Users A and B would have to manually reject these offers.
</p>
<p><strong>Suggestion/Question:</strong>In app notification system
</p>
<p><strong>Response:</strong> We will be working on the system after Milestone 2
</p>

<h3><strong>Milestone 2</strong></h3>
<p><strong>Suggestion/Question:</strong> The poster could cut out some of the features that are less informative (eg account creation, confirmation) so that the main idea of the app is conveyed more quickly through the poster. 
</p>
<p><strong>Response:</strong> The poster has been reworked for milestone 3 to be less informative and instead focus on showcasing the key features and functionality
</p>
<p><strong>Suggestion/Question:</strong>  However, when I change my current slot all my desired slots disappear, which might be a little troublesome for the user if they accidentally made a mistake in keying their current slot.
</p>
<p><strong>Response:</strong> We have taken this feedback into account. Currently when changing the current slot, it does not empty out the desired slots textfield. If the current slot that is chosen is present in the desired slot textfield, it will be filtered out instead
</p>
<p><strong>Suggestion/Question:</strong> Also, when I go to another page and then go back to the create swap page, sometimes the success message persists.
</p>
<p><strong>Response:</strong> This was an issue with the way we implemented our redux. We have updated our redux and this bug no longer persists
</p>
<p><strong>Suggestion/Question:</strong> There is no success message here with actions though e.g. when I'm accepting an offer, or when I sent a swap request. / I'm wondering if you would intend to have some in-app notifications to let the user know that their offer has been accepted or rejected.
</p>
<p><strong>Response:</strong> We have implemented the in app notification system which notifies the user when he accepts or sends an offer.
</p>

<p align="center">
<kbd>
  <img width="600" src="https://github.com/Imranr2/NUSPM/blob/main/readme_markup/Register%20Page.png?raw=true" alt="Register Page">
</kbd>
<kbd>
  <img width="600" src="https://github.com/Imranr2/NUSPM/blob/main/readme_markup/Sign%20In%20Page.png?raw=true" alt="Sign In Page">
</kbd>
</p>
<table>
  <tr>
    <th>Feature Specifications</th>
    <th>Progress</th>
  </tr>
  <tr>
    <td>
      <strong>Register</strong>
      <br/>
      <br/>
      Users have to sign up to use the site.
      <br/>
      <br/>
      For existing users, clicking the Login here button will redirect them to the login page where they can log in.
      <br />
      An error alert will be displayed in the following cases :
     <ul>
        <li>Existing User</li>
        <li>Password length < 8</li>
        <li>Password and password confirmation do not match</li>
      </ul>
    </td>
    <td rowspan="2">
      Completed
    </td>
  </tr>
  <tr>
    <td>
      <strong>Sign In</strong>
      <br/>
      <br/>
      Allows user to sign in.
      <br/>
      <br/>
      Users that are not logged in are only able to access the sign up page and the landing page.
      First time users can click the Sign up here button where they will be redirected to create an account.
      <br/>
      <br/>
      An error alert will be displayed if the user keys in invalid credentials.
      <br/>
      <br/>
      Upon signing in successfully, users will be redirected to the homepage.
    </td>
  </tr>
</table>
<p align="center">
  <kbd>
    <img width="600" src="https://github.com/Imranr2/NUSPM/blob/main/readme_markup/Create%20Swap%20Page.png?raw=true" alt="Create Swap Page">
  </kbd>
</p>
<table>
  <tr>
    <th>Feature Specifications</th>
    <th>Progress</th>
  </tr>
  <tr>
    <td>
      <strong>Create Swap</strong>
      <br/>
      <br/>
      Users are able to create their own swap request where they will input their module code, slot type, current slot and desired slots.
      <br/>
      <br/>
      Users are allowed to select multiple desired slots.
      <br/>
      <br/>
      All the options displayed are fetched from NUSMods API.
      <br/>
      <br/>
      Users are only allowed to create 1 swap request per module code for a given slot type.
      <br/>
      <br/> 
      An error alert will be displayed if a user attempts to create a swap request for the same module code and slot type.
      <br/>
      <br/>
      Once a swap request is created, an alert will be displayed with a hyperlink which will redirect the user to view his/her created swaps
    </td>
    <td>
      Completed
    </td>
  </tr>
</table>
<p align="center">
  <kbd>
    <img width="600" src="https://github.com/Imranr2/NUSPM/blob/main/readme_markup/Current%20Offer%20Tab.png?raw=true" alt="Current Offers">
  </kbd>
  <kbd>
    <img width="600" src="https://github.com/Imranr2/NUSPM/blob/main/readme_markup/Current%20Swap%20Tab.png?raw=true" alt="Current Swaps">
  </kbd>
  <kbd>
    <img width="600" src="https://github.com/Imranr2/NUSPM/blob/main/readme_markup/Current%20Swap%20Edit%20Dialog.png?raw=true" alt="Edit Swap">
  </kbd>
  <kbd>
    <img width="600" src="https://github.com/Imranr2/NUSPM/blob/main/readme_markup/Current%20Swap%20Delete%20Dialog.png?raw=true" alt="Delete Swap">
  </kbd>
  <kbd>
    <img width="600" src="https://github.com/Imranr2/NUSPM/blob/main/readme_markup/Pending%20Offer%20Tab.png?raw=true" alt="Pending Offers">
  </kbd>
  <kbd>
    <img width="600" src="https://github.com/Imranr2/NUSPM/blob/main/readme_markup/Pending%20Offer%20Dialog.png?raw=true" alt="Withdraw Pending Offer">
  </kbd>
  <kbd>
    <img width="600" src="https://github.com/Imranr2/NUSPM/blob/main/readme_markup/Completed%20Swap%20Tab.png?raw=true" alt="Completed Swaps">
  </kbd>
  <kbd>
    <img width="600" src="https://github.com/Imranr2/NUSPM/blob/main/readme_markup/Rejected%20Offer%20Tab.png?raw=true" alt="Rejected Offers">
  </kbd>
</p>
<table>
  <tr>
    <th>Feature Specifications</th>
    <th>Progress</th>
  </tr>
  <tr>
    <td>
      <strong>Your Swaps and Offers</strong>
      <br/>
      <br/>
      User can view all his open, completed swaps requests as well as current, pending and rejected offers
    </td>
    <td rowspan="6">
      Completed
    </td>
  </tr>
  <tr>
    <td>
      <strong>Current Offers</strong>
      <br/>
      <br/>
      This tab displays all the offers that the user has received. The details reflected corresponds to the initiators
    </td>
  </tr>
   <tr>
    <td>
      <strong>Current Swaps</strong>
      <br/>
      <br/>
       In this tab users are able to view all the swaps that is not yet completed. Users are able to edit their swap details as well as delete them. When a user deletes the swap, all offers will be withdrawn and rejected.
    </td>
  </tr>
   <tr>
    <td>
      <strong>Pending Offers</strong>
      <br/>
      <br/>
      This tab displays all the offers that were sent out to other users. Upon clicking on the swap, a dialog will open to display the users current slot details and the desired slot details along with a withdraw button. The withdraw button allows the user to withdraw his offer.
    </td>
  </tr>
   <tr>
    <td>
      <strong>Completed Swaps</strong>
      <br/>
      <br/>
      This tabs shows the details of the users new tutorial slots. The email of the other user will also be displayed for further communication. Users are able to delete the swap or change its status to open.
    </td>
  </tr>
   <tr>
    <td>
      <strong>Rejected Offers</strong>
      <br/>
      <br/>
      This tab displays all the offers that were rejected by other users.
    </td>
  </tr>
</table>
<p align="center">
  <kbd>
    <img width="600" src="https://github.com/Imranr2/NUSPM/blob/main/readme_markup/Marketplace.png?raw=true" alt="Marketplace">
  </kbd>
  <kbd>
    <img width="600" src="https://github.com/Imranr2/NUSPM/blob/main/readme_markup/Marketplace%20Choose%20Swap%20Dialog.png?raw=true" alt="Marketplace Choose Swap">
  </kbd>
  <kbd>
    <img width="600" src="https://github.com/Imranr2/NUSPM/blob/main/readme_markup/Marketplace%20Create%20Swap%20Dialog.png?raw=true" alt="Marketplace Create Swap">
  </kbd>
  <kbd>
    <img width="600" src="https://github.com/Imranr2/NUSPM/blob/main/readme_markup/Marketplace%20Initiate%20Swap%20Dialog.png?raw=true" alt="Marketplace Initiate Swap">
  </kbd>
</p>
<table>
  <tr>
    <th>Feature Specifications</th>
    <th>Progress</th>
  </tr>
  <tr>
    <td>
      <strong>Marketplace</strong>
      <br/>
      <br/>
      Allows users to view swap requests created by other users.
      <br/>
      <br/>
      Users are to select the module code, slot type and their current slot from the autocomplete options given.
      <br/>
      <br/>
      Users are only allowed to view modules that are available on NUSMods.
      <br/>
      <br/>
      The type and current slot selected is filtered based on module details obtained from NUSMods(For example, if a module only has recitation and laboratory then the slot type options will only consist of rec and lab). Upon changing the module code, selected slot type and current slot will be cleared to prevent unnecessary requests.
    </td>
    <td rowspan="5">
      Completed
    </td>
  </tr>
  <tr>
    <td>
      <strong>Marketplace Dialog</strong>
      <br/>
      <br/>
      If the user has created a swap compatible with the one chosen on the marketplace, the create button would be disabled and the user has to select the created swap before clicking next.
      <br/>
      <br/>
      Else, if the user has not created a swap yet, the create button would be enabled for the user to click on. A create dialog will be displayed for the user to create a swap (see next)
    </td>
  </tr>
  <tr>
    <td>
      <strong>Create dialog</strong>
      <br/>
      <br/>
      Details of the swap that is created matches the inputs selected during the search and the user is unable to change the details of the swap. Upon clicking confirm, the swap will be created and a new dialog will be displayed for the user to confirm the offer (see next)
    </td>
  </tr>
  <tr>
    <td>
      <strong>Offer Details</strong>
      <br/>
      <br/>
      Upon clicking Initiate, an offer will be created.
    </td>
  </tr>
  <tr>
    <td>
      <strong>Offer page</strong>
      <br/>
      <br/>
      The current user will be able to view the offer on the pending tab of your swaps and offers page. The recipient of the offer will be able to view it on his/her current offers tab
    </td>
  </tr>
</table>

<h2><strong>Features to be completed by Milestone 3</strong></h2>
<ol>
  <li>Improve UI</li>
  <li>Error handling</li>
  <li>Loading Screens</li>
</ol>

<h2><strong>Problems Encountered</strong></h2>
<table>
  <tr>
    <th>Problems</th>
  </tr>
  <tr>
    <td>
      <strong>Authentication error on every request sent to heroku</strong>
      <br/>
      <br/>
      We were using rails secret key base to decode and encode the JWT during development. This caused any request sent to heroku to be unautorised. We found out that we should be using Heroku's SECRET_KEY_BASE during production
    </td>
  </tr>
  <tr>
    <td>
      <strong>Handling multiple asynchronous calls</strong>
      <br/>
      <br/>
      We were fetching data from our backend to display on the page. However, since the api calls were asynchronous, the webpage would show nothing at first and display the data once the API call is done. We decided to connect pages to redux state for loading to display a loader while calls are not yet completed.
    </td>
  </tr>
  <tr>
    <td>
      <strong>React not maintaining useState variables across different components when making API calls in a separate component which exports the variables</strong>
      <br/>
      <br/>
      We were planning to fetch data at the start of a page such that components. We solved the issue by passing down information as props as well as only making the calls in the components the information was required in.
    </td>
  </tr>
  <tr>
    <td>
      <strong>Styling issues</strong>
      <br/>
      <br/>
      Locating the correct location to target the props of components such that they are modified correctly was difficult as the Material-UI components are composed of many other components. The solution was to spend more time reading the documentation and experimenting.
    </td>
  </tr>
</table>
