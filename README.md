# NUSPM

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
<p>Imagine that you were allocated a tutorial slot that does not fit in your timetable. At this point, you are feeling stressed out as you might not be able to secure your desired tutorial slot and might be forced to drop the module. You also have no way of knowing if there is another student willing to swap with your slot. Also due to the covid situation, it is difficult to reach out to other students taking the same module and you might be left with an undesirable slot even after the first add/swap tutorial exercise. What if there was a website that you can use to find potential swaps before the round starts? This will immensely alleviate the stress that you are having. Welcome to NUSPM, a website where you can create requests for swaps and also view requests created by other students who are facing the same problem.</p>
<h2><strong>Aim</strong></h2>
<p>We hope to create a more seamless tutorial swapping exercise as well as create a less stressful experience for all students through NUSPM.</p>
<h2><strong>User Stories</strong></h2>
<ol>
  <li>As a student who wants to swap their tutorial slot for another, I want to be able to view all possible options.
</li>
  <li>As a student, I would also want to create swap requests to improve my chances of finding a desired tutorial slot.</li>
  <li>As a student, I want to be able to update or delete my swap preference.</li>
  <li>As a student, I want to be able to view the details of the slot that is available and see the impact of the swap on my timetable.
</li>
</ol>
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
  <li>Replace login with NUS Authentication Service</li>
  <li>Improve UI</li>
  <li>Error handling</li>
  <li>Loading Screens</li>
</ol>
