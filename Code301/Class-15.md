# Authentication

[Home](../index.md)

## What is OAuth

1. What is OAuth?
   A way in which unrelated websites can allow a user to stay authenticated while browsing between them without sharing the password/actual credentials from the initial logon

2. Give an example of what using OAuth would look like.
   When you logon to a certain website, it asks if you'd like to logon through another service like google. If so, it redirects you to that website for authentication and then sends you back to their website authenticated and good to go.

3. How does OAuth work? What are the steps that it takes to authenticate the user?
   > The first website connects to the second website on behalf of the user, using OAuth, providing the user’s verified identity.
   > The second site generates a one-time token and a one-time secret unique to the transaction and parties involved.
   > The first site gives this token and secret to the initiating user’s client software.
   > The client’s software presents the request token and secret to their authorization provider (which may or may not be the second site).
   > If not already authenticated to the authorization provider, the client may be asked to authenticate. After authentication, the client is asked to approve the authorization transaction to the second website.
   > The user approves (or their software silently approves) a particular transaction type at the first website.
   > The user is given an approved access token (notice it’s no longer a request token).
   > The user gives the approved access token to the first website.
   > The first website gives the access token to the second website as proof of authentication on behalf of the user.
   > The second website lets the first website access their site on behalf of the user.
   > The user sees a successfully completed transaction occurring.
   > OAuth is not the first authentication/authorization system to work this way on behalf of the end-user. In fact, many authentication systems, notably Kerberos, work similarly. What is special about OAuth is its ability to work across the web and its wide adoption. It succeeded with adoption rates where previous attempts failed (for various reasons).

4. What is OpenID?
   Initially OpenID was an authorization framework to gain access to multiple websites. But after if almost disappeared it reapeared as a authorization service for OAuth.

## Authorization and Authentication flows

1. What is the difference between authorization and authentication?
   Authentication is prooving your identity. Authorization is using your identity to access certain priveledges.

2. What is Authorization Code Flow?
   It's a way that an authenticated user can gain access to their proprietary documents.

3. What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?
   It's a way that an authenticated user can gain access to their proprietary documents with an additional layer of verification

4. What is Implicit Flow with Form Post?
   An alternative to authorization code flow for public clients.

5. What is Client Credentials Flow?
   This is a way for machines to authenticate themselves when they are communicating without a human in between.

6. What is Device Authorization Flow?
   When devices do not have convenient text input they ask the user to go to a link on their computer or smart phone in order to authenticate themself.

7. What is Resource Owner Password Flow?
   This is used directly with the user's password and username.

## Things I wanted to know more about

I need to get a better understanding of OAuth and Auth0. I'm sure the lecture will help me clear things up.
