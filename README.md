<div align="center">
<img width="700" src="https://github.com/Imranr2/NUSPM/blob/main/README_Images/transparentlogo.png" alt="NUSPM Logo">
</div>
<h1 align="center">Your one-stop solution for tutorial management</h1>
<h2 align="center"><a href="https://nuspm.netlify.app/">Click here to get started!</a></h2>

<h3><strong>Proposed Level of Achievement:</strong> Gemini</h3>
<br/>
<h2><strong>Project Scope</strong></h2>
<p>A webapp that allows students to connect and find better tutorial slots.

NUSPM enables students to create swap requests to trade their tutorial slot for a more desirable one. Students are also able to initiate swap requests with other students. This solves the current issue which involves asking on multiple platforms(Telegram, Reddit etc…) which is troublesome and inefficient.

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

<table>
  <tr>
    <th>Feature</th>
    <th>Specifications</th>
  </tr>
  <tr>
    <td>Frontend Register/Login page</td>
    <td>
    Set up the 2 pages to allow users to create accounts and login
    <br/>
    <br/>
      <div align="center">
        <kbd>
          <img src="https://github.com/Imranr2/NUSPM/blob/main/README_Images/Login.png" alt="Login">
        </kbd>
        <p><strong>Login</strong></p>
      </div>
      <br/>
      <br/>
      <div align="center">
        <kbd>
          <img src="https://github.com/Imranr2/NUSPM/blob/main/README_Images/Register.png" alt="Register">
        </kbd>
        <p><strong>Register</strong></p>
      </div>
    </td>
  </tr>
  <tr>
    <td>Backend API and Database</td>
    <td>
      Set up backend API and database for user registration and login
    </td>
  </tr>
  <tr>
    <td>JSON Web Token(JWT) for Authentication</td>
    <td>
      Users can create an account, login and are assigned a JWT after authentication. Pages are inaccessible to users who are not logged in and they will be redirected to the login page
    </td>
  </tr>
</table>

<h3><strong>Milestone 2: Home, Marketplace, Your Swap and Offers
</strong></h3>

<table>
  <tr>
    <th>Feature </th>
    <th>Specifications</th>
  </tr>
  <tr>
    <td>
      Home - Navigation Bar
    </td>
    <td>
      Upon logging in, users are brought to the home page. The navigation bar at the top of the page allows users to switch between pages and also consists of the notification system for users to track updates on their statuses.
      <br/>
      <br/>
      <div align="center">
        <kbd>
          <img src="https://github.com/Imranr2/NUSPM/blob/main/README_Images/Navbar.png" alt="Navbar">
        </kbd>
        <p><strong>Register</strong></p>
      </div>
    </td>
  </tr>
  <tr>
    <td>
      Home - Introductory Video
    </td>
    <td>
      The video gives a quick introduction of the web application and how to use it to create and initiate swap requests, as well as accepting requests from other users.
      <br/>
      <br/>
      <div align="center">
        <kbd>
          <img src="https://github.com/Imranr2/NUSPM/blob/main/README_Images/Homepage.png" alt="Home">
        </kbd>
        <p><strong>Register</strong></p>
      </div>
    </td>
  </tr>
  <tr>
    <td>
      Create Swap
    </td>
    <td>
      On the Create Swap page, users are able to create their own swap request where they will input their module code, slot type, current slot and desired slots.<br/>
      The module information is retrieved from NUSMods which guarantees the accuracy of the information for users. If the user is open to multiple tutorial slots, they can select more than one in the options. Users can only create 1 swap request per module for a given slot type, making the swap requests easy to view and manage. Upon successful creation of a swap, they can click on the link to go to the Marketplace to look for potential swaps.<br/>
      <br/>
      <div align="center">
        <kbd>
          <img src="https://github.com/Imranr2/NUSPM/blob/main/README_Images/CreateSwap.png" alt="Create Swap">
        </kbd>
        <p><strong>Create Swap</strong></p>
      </div>
    </td>
  </tr>
  <tr>
    <td>
      Marketplace
    </td>
    <td>
      On the Marketplace page, users can key in their current slot details and search for swap requests from other users that desire the slot they currently have.
      <br/>
      <br/>
      <div align="center">
        <kbd>
          <img src="https://github.com/Imranr2/NUSPM/blob/main/README_Images/MarketplaceSearchBar.png" alt="Marketplace Search Bar">
        </kbd>
        <p><strong>Marketplace Search Bar</strong></p>
      </div>
      <br/>
      <br/>
      If the user finds a slot they prefer, they click on it and follow a few simple steps to initiate the offer to the other user.
      <br/>
      <br/>
      <div align="center">
        <kbd>
          <img src="https://github.com/Imranr2/NUSPM/blob/main/README_Images/Marketplace.png" alt="Marketplace">
        </kbd>
        <p><strong>Step 1: Key in their slot details and search for potential swaps<br/></strong></p>
      </div>
      <br/>
      <br/>
      <div align="center">
        <kbd>
          <img src="https://github.com/Imranr2/NUSPM/blob/main/README_Images/MarketplaceD0.png" alt="Marketplace First Dialog">
        </kbd>
        <p><strong>Step 2: Choose the swap that they have created</strong></p>
      </div>
      <br/>
      <br/>
      <div align="center">
        <kbd>
          <img src="https://github.com/Imranr2/NUSPM/blob/main/README_Images/MarketplaceD1.png" alt="Marketplace Second Dialog">
        </kbd>
         <p><strong>Step 3: Confirm the details of the swap and initiate</strong></p>
      </div>
      <br/>
      <br/>
      This sends the offer to the other parties where they can accept or reject the offer.<br/><br/>
      A key feature of this process is that users do not need to have a swap created beforehand to initiate the offer. The details they keyed in to search previously is auto filled in for them if they do not have a swap yet and the swap is created on the spot.
      <br/>
      <br/>
      <div align="center">
        <kbd>
          <img src="https://github.com/Imranr2/NUSPM/blob/main/README_Images/MarketplaceAutoCreate.png" alt="Marketplace Auto Create Dialog">
        </kbd>
      </div>
    </td>
  </tr>
  <tr>
    <td>
      Your Swaps and Offers
    </td>
    <td>
      On the Your Swaps page, users can view all their swaps and offers in the 5 tabs, namely:
      <br/>
      <br/>
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
      </ol>
      <br/>
      <br/>
       <div align="center">
        <kbd>
          <img src="https://github.com/Imranr2/NUSPM/blob/main/README_Images/YourSwapTabs.png" alt="Your Swap and Offers Tabs">
        </kbd>
      </div>
      <br/>
      <br/>
    </td>
  </tr>
</table>

<h3><strong>Milestone 3: Responsiveness, Notification System, UI updates, Bug fixes</strong></h3>

<table>
  <tr>
    <th>
      Feature
    </th>
    <th>
      Specifications
    </th>
  </tr>
  <tr>
    <td>
      Responsive layout for mobile devices and smaller screens
    </td>
    <td>
    <ol>
      <li><strong>Navigation bar</strong><br/>
        Navbar displays icons on smaller screens
        <br/>
        <br/>
        <div align="center">
          <kbd>
            <img src="https://github.com/Imranr2/NUSPM/blob/main/README_Images/ResponsiveNavbar.png" alt="Your Swap and Offers Tabs">
          </kbd>
        </div>
      </li>
      <br/>
      <br/>
      <li><strong>Search bar (Marketplace)</strong><br/>
        Change horizontal search bars to drawer
        <br/>
        <br/>
        <div align="center">
          <kbd>
            <img src="https://github.com/Imranr2/NUSPM/blob/main/README_Images/MarketplaceDrawer.png" alt="Marketplace Search Drawer">
          </kbd>
        </div>
      </li>
      <br/>
      <br/>
      <li><strong>Your Swap and Offers</strong><br/>
        Changed tabs to display icons on smaller screens
        <br/>
        <br/>
        <div align="center">
          <kbd>
            <img src="https://github.com/Imranr2/NUSPM/blob/main/README_Images/ResponsiveYourSwap.png" alt="Your Swap and Offer Tab Icons">
          </kbd>
        </div>
      </li>
      <br/>
      <br/>
      <li>
        <strong>Edit Profile</strong><br/>
        Changed tabs to display icons on smaller screens
        <br/>
        <br/>
        <div align="center">
          <kbd>
            <img width="300" src="https://github.com/Imranr2/NUSPM/blob/main/README_Images/ChangePasswordSmall.png" alt="Edit Profile Icons">
          </kbd>
        </div>
      </li>
    </ol>
    </td>
  </tr>
  <tr>
    <td>
      Notification System
    </td>
    <td>
    The notification system sends notifications to the users as follows: 
    <br/>
    <br/>
      <ol>
        <li>On accepting an offer/having an offer accepted by another user, users will receive a green success alert
        <br/>
        <br/>
          <div align="center">
            <kbd>
              <img src="https://github.com/Imranr2/NUSPM/blob/main/README_Images/GreenNotif.png" alt="Success Notifications">
            </kbd>
          </div>
        <br/>
        <br/>
        </li>
        <li>On creating/sending/receiving/editing swaps/offers, users will receive a blue info alert
        <br/>
        <br/>
          <div align="center">
            <kbd>
              <img src="https://github.com/Imranr2/NUSPM/blob/main/README_Images/BlueNotif.png" alt="Info Notifications">
            </kbd>
          </div>
        <br/>
        <br/>
        </li>
        <li>On rejecting/deleting/withdrawing swaps/offers, users will receive a red error alert.
        <br/>
        <br/>
          <div align="center">
            <kbd>
              <img src="https://github.com/Imranr2/NUSPM/blob/main/README_Images/RedNotif.png" alt="Delete/Reject Notifications">
            </kbd>
          </div>
          <br/>
          The latest 10 notifications are shown to the users.
        <br/>
        <br/>
        </li>
      </ol>
    </td>
  </tr>
  <tr>
    <td>
      Change Password
    </td>
    <td>
      Users can change their password by keying in their old password and a new password twice. A check is done in the backend to ensure that the password matches before updating the password
      <br/>
      <br/>
      <div align="center">
        <kbd>
          <img src="https://github.com/Imranr2/NUSPM/blob/main/README_Images/ChangePassword.png" alt="Change Password">
        </kbd>
      </div>
    </td>
  </tr>
  <tr>
    <td>
      About
    </td>
    <td>
      Users can get additional information on the website through the about page
      <br/>
      <br/>
      <div align="center">
        <kbd>
          <img src="https://github.com/Imranr2/NUSPM/blob/main/README_Images/About.png" alt="About">
        </kbd>
      </div>
    </td>
  </tr>
  <tr>
    <td>
      UI Updates
    </td>
    <td>
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
    </td>
  </tr>
  <tr>
    <td>
      Bug fixes
    </td>
    <td>
      <ol>
        <li>Fixed incorrect positions of swap details in Your Swap and Offers page
        </li>
        <li>Fixed issue where alerts persist even after moving to a different page
        </li>
      </ol>
    </td>
  </tr>
</table>

<h2><strong>Behaviour Diagram
</strong></h2>
<p>
The diagram below illustrates the activities users could perform on the web application.
<br/>
<br/>

<div align="center">
  <kbd>
    <img src="https://github.com/Imranr2/NUSPM/blob/main/README_Images/Behaviour%20Diagram.png" alt="Behaviour Diagram">
  </kbd>
</div>
<br/>
<br/>
Firstly, users register and login with their accounts, where they are brought to the home page, which features a video going through the usage of the application. Next, they can proceed to the Create Swap page to post their swap request for others to view, or head to the Marketplace to search for swaps other users posted. Subsequently, they can head over to the Your Swap and Offers page to check the status of their swaps/offers, as well as performing follow up actions such as accepting offers from other users. THe notification system serves to notify users about any changes they make as well as incoming offers.<br/>
Next, we have the component tree of the web application illustrating it’s structure.
<br/>
<br/>
<h2><strong>React Front End Component Tree
</strong></h2>
<div align="center">
  <kbd>
    <img src="https://github.com/Imranr2/NUSPM/blob/main/README_Images/Component%20Tree.png" alt="Component Tree">
  </kbd>
</div>
<br/>
<br/>
The main part of our web application are the pages(Login, Home etc..), these all contain the Navigation Bar and Footer, as well as their respective sub components.

</p>

<h2><strong>Entity Relationship Diagram (ERD)</strong></h2>

<p>
The following is an ERD for our backend.
<div align="center">
  <kbd>
    <img src="https://github.com/Imranr2/NUSPM/blob/main/README_Images/ERD2.png" alt="ERD">
  </kbd>
</div>
  A user can have many swaps, offers and notifications. Notifications is polymorphic and is associated with any model that is declared as a notifiable. Notifiable type takes in a string which in our case would be either 'Swap' or 'Offer' while Notifiable ID takes in an integer corresponding to the id of the Swap/Offer.
</p>

<h2><strong>Testing 
</strong></h2>

<p>We mainly used Dogfooding and manual testing to test our app.
</p>

<table>
  <tr>
    <th>
      Methods
    </th>
    <th>
      Details
    </th>
  </tr>
  <tr>
    <td>
      Dogfooding
    </td>
    <td>
      After developing a new feature, we would test the app by going through the entire workflow of a typical user. From registering to creating a swap and initiating a swap.
      We would check for any unexpected bugs along the way and find ways to troubleshoot before testing the workflow again. 
      <br/>
      After doing tests in the development environment, we would push our app to our hosting servers and go through the workflow again. We have experienced multiple situations where features work in development but not in production and have decided to always test our app in development as well as production before continuing.
    </td>
  </tr>
   <tr>
    <td>
      Insomnia
    </td>
    <td>
      We mainly used Insomnia to test our REST API whenever a new route was added. Afterwards, we would create a simple page on our front-end with enough functionality to test the new route. For example, when we added a create swap route in our backend, we made a simple page with a few text fields and a button to ensure that the route is working properly.
    </td>
  </tr>
</table>

<h2><strong>User Experience</strong></h2>

<p>
  After the testing we have conducted on our system, we identified several issues and have made changes to enhance the user experience.
  This helps to minimise the possibility of users making mistakes leading to a negative experience.
</p>
<table>
  <tr>
    <th>
      Issue
    </th>
    <th>
      Changes
    </th>
  </tr>
  <tr>
    <td>
      Each user can create multiple swap requests with the same details, resulting in a clutter for both the Marketplace and Your Swap pages
    </td>
    <td>
      Updated backend to ensure that a user is unable to create a swap request with the same module code and slot type
    </td>
  </tr>
   <tr>
    <td>
      In the create swap page, changing the module code/slot type does not clear the current slot and desired slot fields. This allows users to create meaningless swap requests with non-existent tutorials
    </td>
    <td>
      Changing these values clears the fields, thus users can only create swaps with relevant details
    </td>
  </tr>
  <tr>
    <td>
      If a user edits/deletes a swap requests, the change will also be reflected on the offers sent/received by the user. This causes other users to have irrelevant offers.
    </td>
    <td>
      Editing/Deleting swap requests now withdraws all offers the user initiated and rejects all offers sent to the user, thus users will not be misled by irrelevant offers.
    </td>
  </tr>
  <tr>
    <td>
      Given a tutorial slot A. If a user accepts an offer for A, all offers sent out/ received by the user for slot A will still be present which can lead to confusion amongst users.
    </td>
    <td>
      After the user accepts the offer for slot A, all offers the user sent out for slot A will be withdrawn, while offers received by the user for slot A will have to be manually rejected. 
    </td>
  </tr>
  <tr>
    <td>
      When initiating a swap in the marketplace, users can either create a swap or select a swap they have already created. If a user tries to create a swap with the same details as the one created before, this will lead to an error.
    </td>
    <td>
      Users are no longer able to choose the option to create a swap if they had already done so, and have to choose the swap created beforehand to proceed.
    </td>
  </tr>
  <tr>
    <td>
      Swaps shown on the Marketplace are not removed even after an offer has been initiated by the user, potentially leading to multiple offers initiated to the same user. Furthermore, offers that have been accepted/rejected still remain on the marketplace.
    </td>
    <td>
      Marketplace correctly filters for only swaps that the user has not sent an offer to before and are open for swapping.
    </td>
  </tr>
  <tr>
    <td>
      Swaps can be edited to have the same module code and slot type. This leads to a user having 2 swap requests with the same details
    </td>
    <td>
      Swaps now cannot be edited to have the same module code and slot type
    </td>
  </tr>
  <tr>
    <td>
      When initiating an offer in the marketplace, if a user has not created a swap beforehand, the user would be prompted to create a swap. Initially, the user is able to select the module code, slot type, current slot and desired slots. This allows malicious users to send meaningless offers.
    </td>
    <td>
      Now users are only able to select their desired slots, with the default slot that they entered during the search. The module code, slot type and current slot will match the slot details of the other user
    </td>
  </tr>

</table>

<h2><strong>Technical Details</strong></h2>

<table>
  <tr>
    <th>Details</th>
    <th>Justifications</th>
  </tr>
  <tr>
    <td>
      Redux
    </td>
    <td>
      We used redux to track the states of our app such as tracking if a user is authenticated or if a request is currently being made to the backend. Initially, we had a shared state to track all the different actions (create/edit/delete) for a specific model. For example, if a user creates or edit a swap, the same shared state (success) is updated. To fix this issue, we separated the state for each action (createSuccess, searchSuccess etc…), allowing us to have more control over particular states. 
      <br/>
      <br/>
      <div align="center">
        <kbd>
          <img src="https://github.com/Imranr2/NUSPM/blob/main/README_Images/Redux.png" alt="Redux" width='500'>
        </kbd>
        <p><strong>Change in state</strong></p>
      </div>
      <br/>
      <br/>
      Before this update, if a user were to search for a swap in the marketplace, the shared success state would be updated to true. If the user navigates to the create swap page before the success state resets to false, a success alert will be displayed to the user even though the user has not performed any actions. With the new change, the searchSuccess and createSuccess are updated separately hence removing this bug.
    </td>
  </tr>
  <tr>
    <td>
      Polymorphic Associations
    </td>
    <td>
      We implemented in app notifications where users will be alerted when they perform an action such as creating/editing/deleting. We wanted the swap and offer models to have notifications associated with them. Instead of creating a separate notification model such as OfferNotification/SwapNotification, we decided to use polymorphic associations. We created a single Notification model that takes in a notifiable type as a string (‘Offer’/’Swap’) and a notifiable id as an integer to reference the model in the database.This allows any model that is declared as notifiable to have notifications. This would also allow any future models to have notifications without creating an extra model each time.
    </td>
  </tr>
  <tr>
    <td>
      Notification Creation in Backend
    </td>
    <td>
      Instead of sending a create notification post request to our backend every time a user performs an action, we handled this process in our backend. For example, if a user sends a post request to create a swap, a notification would be created as well without explicitly sending another post request to create the notification.
    </td>
  </tr>
</table>

<h2><strong>Trickier Features and how we implemented it 
</strong></h2>

<p>This section goes deeper into the features that we felt were more complex
</p>

<table>
  <tr>
    <th>
      Feature
    </th>
    <th>
      Implementation
    </th>
  </tr>
  <tr>
    <td>
      Initiating an offer
    </td>
    <td>
      We needed to implement a process where users can initiate a swap with other users. There were 2 ways we could go about this, we could create multiple pages for each step or render different dialogs for each step. We decided to go with the latter as we felt it was better in terms of user experience. This was tricky as we had to maintain many different states. For example, if a user has already created a swap we have to send a get request to get all his swaps. This was so that he could select the tutorial to perform the swap with another user. Otherwise, we render the dialog for the user to create a swap where we send a post request and store the response to be displayed later. When a user initiates, we have to send a post request and as well as a get request update the marketplace to remove said swap to prevent spamming. 
    </td>
  </tr>
   <tr>
    <td>
      Re-rendering page on change
    </td>
    <td>
      We needed to find a way to re-render a users swaps and offers after any changes (edit/delete). We ran into an issue where the useEffect only runs when the page renders for the first time but not when any changes occur. First, we tried to add a dependency array where any changes to the dependencies would cause the useEffect to run again. However, it sends a request to the backend infinitely as React doesn’t take arrays as dependencies. We finally solved this issue by connecting the redux states to the components and using said states as dependencies. Whenever the state changes, a get request will be sent to re-render the page.
    </td>
  </tr>
</table>

<h2><strong>Feature Limitations
</strong></h2>

<p>Although the system works as intended, there are still some limitations which we will be addressing in the following section.
</p>

<table>
  <tr>
    <th>
      Limitation
    </th>
    <th>
      Details
    </th>
  </tr>
  <tr>
    <td>
      NUS Authentication Service
    </td>
    <td>
      NUSPM is not integrated with NUS Authentication Service, hence malicious users can create accounts using other students emails causing them to not be able to create an account
    </td>
  </tr>
   <tr>
    <td>
      Luminus API
    </td>
    <td>
      NUSPM is not integrated with the LUMINUS API. This means users can create offers/swaps for modules that they are not enrolled in, which can be misleading for other users.
    </td>
  </tr>
   <tr>
    <td>
      In App notification
    </td>
    <td>
      The in app notification is not ‘real-time’ and does not refresh in cases such as other users accepting the user’s offers. The notifications component currently refreshes on page switching.
    </td>
  </tr>
   <tr>
    <td>
      External Notification System
    </td>
    <td>
      Users are only notified of offers through in app notifications as no emails are sent out to the users.
    </td>
  </tr>
   <tr>
    <td>
      Responsiveness
    </td>
    <td>
      NUSPM was not tested with many different mobile devices. There is insufficient testing on mobile devices thus user experience may vary across different mobile devices and they are recommended to use the web application. It is also not compatible with Safari.
    </td>
  </tr>
   <tr>
    <td>
      Delay in NUSMods API call
    </td>
    <td>
      NUSPM queries the NUSMods API for all the module information and does not save the information into the backend. This can cause a delay in the retrieval of information when displaying to the autocomplete boxes.
    </td>
  </tr>
</table>

<h2><strong>Response to Milestone Evaluations
</strong></h2>

<table>
  <tr>
    <th>
      Milestone 1
    </th>
  </tr>
  <tr>
    <td>
      <p><strong>1. Suggestion/Question:</strong>
        Is there anything to stop people from creating multiple accounts?
      </p>
    </td>
  </tr>
  <tr>
    <td>
      <p><strong>Response:</strong>
        No. We are currently not integrated with NUS Authentication Service. However we have implemented a REGEX to only match valid NUS email addresses
      </p>
    </td>
  </tr>
  <tr>
    <td>
      <p><strong>2. Suggestion/Question:</strong>
        I want to be able to view the details of the slot that is available and see the impact of the swap on my timetable.
      </p>
    </td>
  </tr>
  <tr>
    <td>
      <p><strong>Response:</strong>
        We have decided to not go through with this feature as we believe it is too complex to implement.
      </p>
    </td>
  </tr>
  <tr>
    <td>
      <p><strong>3. Suggestion/Question:</strong> 
        Poster was too wordy/informative and words were too small
      </p>
    </td>
  </tr>
  <tr>
    <td>
      <p><strong>Response:</strong> 
        We decided to only leave the wireframes in the poster and deleted all the text.
      </p>
    </td>
  </tr>
  <tr>
    <td>
      <p><strong>4. Suggestion/Question:</strong>Implement a password recovery system
      </p>
    </td>
  </tr>
  <tr>
    <td>
      <p><strong>Response:</strong> We are thinking about it
      </p>
    </td>
  </tr>
  <tr>
    <td>
      <p><strong>5. Suggestion/Question:</strong>
        If a user accepts an offer, will all other offers for the same module be automatically rejected? Conversely, what if one of the user's offers is accepted? Will the user's other offers automatically be withdrawn?
      </p>
    </td>
  </tr>
  <tr>
    <td>
      <p><strong>Response:</strong> 
        Consider the following scenario with 2 users A and B:
        B sends an offer to A and many other users. A also sends offer to many other users. In the event that A accepts the offer from B, all offers that were sent out by A and B will be automatically withdrawn. However, all other offers that were received by A and B will not be automatically rejected. Users A and B would have to manually reject these offers.
      </p>
    </td>
  </tr>
  <tr>
    <td>
      <p><strong>6. Suggestion/Question:</strong>
        In app notification system
      </p>
    </td>
  </tr>
  <tr>
    <td>
       <p><strong>Response:</strong>
        We will be working on the system after Milestone 2
      </p>
    </td>
  </tr>
</table>

<table>
  <tr>
    <th>
      Milestone 2
    </th>
  </tr>
  <tr>
    <td>
      <p><strong>1. Suggestion/Question:</strong> 
        The poster could cut out some of the features that are less informative (eg account creation, confirmation) so that the main idea of the app is conveyed more quickly through the poster. 
      </p>
    </td>
  </tr>
  <tr>
    <td>
       <p><strong>Response:</strong> 
        The poster has been reworked for milestone 3 to be less informative and instead focus on showcasing the key features and functionality
      </p>
    </td>
  </tr>
  <tr>
    <td>
      <p><strong>2. Suggestion/Question:</strong>  
        However, when I change my current slot all my desired slots disappear, which might be a little troublesome for the user if they accidentally made a mistake in keying their current slot.
      </p>
    </td>
  </tr>
  <tr>
    <td>
       <p><strong>Response:</strong> 
        We have taken this feedback into account. Currently when changing the current slot, it does not empty out the desired slots textfield. If the current slot that is chosen is present in the desired slot textfield, it will be filtered out instead
      </p>
    </td>
  </tr>
  <tr>
    <td>
      <p><strong>3. Suggestion/Question:</strong> 
        Also, when I go to another page and then go back to the create swap page, sometimes the success message persists.
      </p>
    </td>
  </tr>
  <tr>
    <td>
       <p><strong>Response:</strong> 
        This was an issue with the way we implemented our redux. We have updated our redux and this bug no longer persists
      </p>
    </td>
  </tr>
  <tr>
    <td>
      <p><strong>4. Suggestion/Question:</strong> 
        There is no success message here with actions though e.g. when I'm accepting an offer, or when I sent a swap request. / I'm wondering if you would intend to have some in-app notifications to let the user know that their offer has been accepted or rejected.
      </p>
    </td>
  </tr>
  <tr>
    <td>
       <p><strong>Response:</strong> 
        We have implemented the in app notification system which notifies the user when he accepts or sends an offer.
      </p>
    </td>
  </tr>
</table>
