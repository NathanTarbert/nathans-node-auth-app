## Node.js Example App with SSO & Directory Sync

This is a monorepo which showcases authenticating users via SSO and Directory Sync.
The two services we are using are WorkOS as the service provider and Okta as the identity provider.

![workos-app](https://github.com/NathanTarbert/nathans-node-auth-app/assets/66887028/a353505d-9a01-44c4-9939-d432b513c3bb)


## Clone the repo
```bash
$ https://github.com/NathanTarbert/nathans-node-auth-app.git
  ```

Change directories into the app

```sh
$ cd nathans-node-auth-app
```

## ENVs
copy the `example.env` to `.env` in each folder and fill in the values.

## Running the application

We will install all dependencies in each app and run two servers with one command.

```sh
$ npm run start:both
```

What you will see in the terminal is 

- http://localhost:8000 as the primary server to authenticate the SSO login

- http://localhost:8001 as the secondary server that will retrieve our users

Navigate to `localhost:8000` to begin loggin in. 


## Need help?

Reach out to me on [Twitter](https://twitter.com/nathan_tarbert) if you have any questions.
