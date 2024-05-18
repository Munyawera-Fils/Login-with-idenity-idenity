# Login-with-idenity-idenity

To get the code, please open above App.jsx file.

This is  the Explanation of the code you will see in App.jsx



# State Variables:

isLoggedIn: Tracks whether the user is logged in.
principal: Stores the user's principal ID when logged in.
AuthClient Initialization:

# authClientPromise:

A promise that resolves to an AuthClient instance.

# signIn Function:

Creates an AuthClient instance.

Defines the Internet Identity URL based on the environment.
Logs in the user and updates the identity.

# signOut Function:

Logs out the user and clears the identity.

# updateIdentity Function:

Updates the state with the user's principal and sets the identity for the example_backend actor.

# useEffect Hook:

Checks the user's login status on component mount and updates the state accordingly.

# Conditional Rendering:

Renders a sign-in button if the user is not logged in.
Renders a welcome message and sign-out button if the user is logged in.

# How to Use:

Sign In: Clicking the "Sign In" button triggers the signIn function, logging the user in and updating the state.
Sign Out: Clicking the "Sign Out" button triggers the signOut function, logging the user out and updating the state.
This example integrates the login/logout functionality with a simple React component and updates the UI based on the user's authentication status.

Copyright 
# ICP RWANDA
