# When is Basic Authorization used vs. Bearer Authorization?
The Basic and Digest authentication schemes are dedicated to the authentication using a username and a secret (see RFC7616 and RFC7617). The Bearer authentication scheme is dedicated to the authentication using a token and is described by the RFC6750.

# What does the JSON Web Token package do?
transmitting information between parties as a JSON object.

# What considerations should we make when creating and storing a SECRET?
1-Never store unencrypted secrets in .git repositories.
2-Don’t share your secrets unencrypted in messaging systems like slack.
3-store secrets safely.
4-Restrict API access and permissions.

--------------------------------------

# Term
encryption: is the process of taking plain text, like a text message or email, and scrambling it into an unreadable format — called “cipher text.” This helps protect the confidentiality of digital data either stored on computer systems or transmitted through a network like the internet

token : . This string of characters that results from the encryption .

bearer:provides all of the tools to build, run and manage API integrations.


JSON Web Token :is an easy way to secure an API. ... This token includes some personal data, such as username or email address. Then, this token is signed server-side (to prevent token integrity), and sent back to the user.

