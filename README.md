# JWNu
JWT style implementation on Nu Cypher. Supporting scopes, users, and other information on the Nu Cypher network.

# Concept

Web applications need to guaruntee user permissions. While you can do this using NuCypher individualistically, web applications need a way to verify information. With the advent of React and use of microservices, there needs to be a way to keep this information secure in transit.

This project aims to bring the Nu Cypher to web development for the Management of Secrets in a JSON Webtoken format. This token would ideally follow the [Branca](https://github.com/hako/branca) format and allow users to send information more securely over the Internet.

This way, nodes or servers could unencrypt information, verify claims stored in the NuCypher and begin integrating the Cypher into existing web projects.

# Proposed Technologies

- Rust
- Actix Web to create a central authority for testing and maybe production. Perhaps another project.
- NuBLS
- Python Nu technologies although I will want to learn about the Cypher and try to get it into Rust
- Python by extension
- Branca token concept from above

# Timeline

Starting sometime in Jaunary - May and ending whenever I can get it done. Help is appreciated

# Helping

Please fork and look at the project board.
