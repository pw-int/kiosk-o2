### TheKiosk - [CZ O2-Mobile] HTML for DIMOCO ###

Markup project created by figma design.

Figma link [url](https://www.figma.com/file/YfCFui9BV58bXJZoyofPMK/Czech-Republic-O2-The-Kiosk-(via-Dimoco)-subscription-flow-design-%5BPIN%2BHE%5D?type=design&node-id=0-1&mode=design&t=J6PbSRDipUHvIExB-0 "Figma link")

Demo 3g link [url](https://pw-int.github.io/kiosk-o2/ "Demo 3g link")

Demo otp link [url](https://pw-int.github.io/kiosk-o2/otp.html "Demo otp link")


## Project structure ##

*src* directory contains source files, like styles, js, and html. Once project is compiled, the *dist* directory will be created and it should be used for the production project.

### Install nodeenv ###

**nodeenv** used to isolate the node versions on the system 

    pip3 install nodeenv

Create a virtualenv with the 18 nod version

    nodeenv -n 18.12.1 env

Active it 

    . env/bin/activate

### How to start the dev server for development? ###

    npm ci
    npm run dev


### How to build the assets? ###

    npm run build

