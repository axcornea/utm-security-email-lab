# Security course email confirmation lab (#8)

The main goal of this lab consists of implementing an application letting user to register and sending a registration
confirmation email.

## Running locally

## Prerequisites

To run this application locally use need to have the following tools installed on your workstation:
* JDK 11+ (OpenJDK used during development)

### Configuration

This application requires a set of SMTP credentials to run. During development, I have used SMTP credentials from
Mailgun.

Fill the following variables inside the `src/main/resources/application.yml` file:

* `smtp_host`
* `smtp_port`
* `smtp_username`
* `smtp_password`
* `email_sender`

### Running

Run the following command inside the root of this repository:

```bash
# *nix
> ./gradlew bootRun

# Windows
> .\gradlew.bat bootRun
```

The application will start in a few seconds and will be accessible under `http://localhost:8080/` web page.

## Demo

[App demo video](https://vimeo.com/655764902/6740917f07)
