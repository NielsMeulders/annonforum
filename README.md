# Annonymous Conversations App

Annonymous Forum Conversations for talking about whatever you want., by [Tory Adams][] with [Orchestrate.io][].

## Install

The Annonforum is built using [node.js][], so you'll need to [install it][node.js] if you don't have it already.

Then, in a terminal, do this:

    git clone git@github.com:BEZEI2K/annonforum.git
    cd annonforum
    # install dependencies
    npm install
    # add settings; replace ... with your credentials

    export ORCHESTRATE_API_KEY=...
    # run the app!
    npm start

Your annonforum app is now running on <http://localhost:3000>.

## Getting Credentials

Don't know where to get your `ORCHESTRATE_API_KEY`? Follow along:

### Orchestrate.io

1. [Sign up](https://dashboard.orchestrate.io/sessions/login) for Orchestrate.io
2. Create an application.
3. See that value under `API Keys`? That's your `ORCHESTRATE_API_KEY`.
4. `echo 'you did it' | say`

## Resources

[node.js]: http://nodejs.org/
[Annon Forum App]: http://www.annonforum.com/
[Orchestrate.io]: http://orchestrate.io/
