# PhoneGap Build Starter Application

> A example application to get started with PhoneGap Build and push notifications.

## Usage

### Run Application

    /www/index.html

### Run Tests

    /www/spec.html

### PhoneGap/Build

Create a new app with the following repository:

    https://github.com/Puship/phonegap-puship-start.git

## Updating the Application

The application is based on the [Phonegap phonegap-start][phonegap-start] app.

### 1. Update the Source

    cp cordova-app-hello-world/www www/

__Do not replace `www/config.xml`.__

__Do not replace `www/img/logo.png`.__

### 2. Update index.html

Replace `<h1>PhoneGap</h1>` with `<h1>Puship Example</h1>`.

### 3. Update PhoneGap Version

    <preference name="phonegap-version" value="x.x.x" />

### 4. Commit

    $ git commit -am "Version x.x.x"

### 5. Tag

    $ git tag x.x.x

[phonegap-start]: http://github.com/phonegap/phonegap-start

