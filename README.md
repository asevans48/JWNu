# JWNu
JWT style implementation on Nu Cypher. Supporting scopes, users, and other information on the Nu Cypher network.

# Concept

Web applications need to guaruntee user permissions. While you can do this using NuCypher in a way reminiscent of early web applications, the use of frameworks such as React and modern way of using microservices demands something different.

This project aims to leverage the Nu Cypher to create a token similar to a JSON Web Token (JWT) . This token would ideally follow the [Branca](https://github.com/hako/branca) format and allow users to send information more securely over the Internet.

This way, nodes or servers could unencrypt information, verify claims stored in the NuCypher and begin integrating the Cypher into existing web projects.

# Proposed Technologies

- Rust
- Actix Web to create a central authority for testing and maybe production. Perhaps another project.
- NuBLS
- Python Nu technologies although I will want to learn about the Cypher and try to get it into Rust
- Python by extension
- Branca token concept from above

# Goals

1.) Implement a Rust Branca server
2.) Implement authentication for the central authority
3.) Integrate the Nu Cypher for registering users [use a UUID and store claims as in AWS Cognito]
4.) Integrate the Nu Cypher for storing claims [scopes, permissions]
5.) Dockerize the system for deployment
6.) Test on AWS EC2 instances

# Timeline

Starting sometime in Jaunary - May and ending whenever I can get it done. Help is appreciated

# Helping

Please fork and look at the project board.
