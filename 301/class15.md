#### What is OAuth?

protocol used for authorization

#### Give an example of what using OAuth would look like.

Signing up for application using your google account redirects you to sign in for authorization

#### How does OAuth work? What are the steps that it takes to authenticate the user?

Website requests OAuth, website redirects user, User authorizes request sending access token to website
#### What is OpenID?

Open standard protocol

#### What is the difference between authorization and authentication?

* Authorization what are you aloud to do, 
* Authentication are you who you say you are

#### What is Authorization Code Flow?

Obtain access token on behalf of user

#### What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?

Authorization Code Flow that helps to protect against certain types of security threats

#### What is Implicit Flow with Form Post?

As an alternative to the Authorization Code Flow, OAuth 2.0 provides the Implicit Flow, which is intended for Public Clients, or applications which are unable to securely store Client Secrets. While this is no longer considered a best practice for requesting Access Tokens, when used with Form Post response mode, it does offer a streamlined workflow if the application needs only an ID token to perform user authentication.

#### What is Client Credentials Flow?

With machine-to-machine (M2M) applications, such as CLIs, daemons, or services running on your back-end, the system authenticates and authorizes the app rather than a user. For this scenario, typical authentication schemes like username + password or social logins don't make sense. Instead, M2M apps use the Client Credentials Flow (defined in OAuth 2.0 RFC 6749, section 4.4).

#### What is Device Authorization Flow?

With input-constrained devices that connect to the internet, rather than authenticate the user directly, the device asks the user to go to a link on their computer or smartphone and authorize the device.

#### What is Resource Owner Password Flow?

Though we do not recommend it, highly-trusted applications can use the Resource Owner Password Flow, which requests that users provide credentials (username and password), typically using an interactive form. 

[Home](https://shiloh206.github.io/reading-notes)