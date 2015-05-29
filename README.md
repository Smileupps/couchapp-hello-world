# Hello world Couchapp, with Bootstrap!
https://github.com/Smileupps/couchapp-hello-world

## Purpose 
This couchapp shows how to serve static websites directly from CouchDB, using the *_attachments* field/folder of CouchDB design documents. All files and folders contained within *_attachments* may be served as static HTTP resources from your own domain, by simply wiring them using two simple rewriting rules (*rewrites field*).

## Install / Run

### Easy, fast install

This app is part of [Smileupps Ready to Run Examples](https://www.smileupps.com/wiki). This means installation is as simple as:

1. Installing [Free Smileupps CouchDB Hosting](https://www.smileupps.com/store/apps/couchdb) from Smileupps App Store
2. Checking your activation e-mail, which contains links to run it, access or edit its source code.

### Manual install

* **Prerequisite: Apache CouchDB**. You can download it from the [CouchDB official homepage](http://couchdb.apache.org)

1. Download this repository to your local disk
2. Upload this back to your own CouchDB instance, using a [CouchDB deployment tool](https://www.smileupps.com/wiki)
3. Choose a domain name to serve your app
4. Configure your DNS settings to point domain name to your CouchDB instance ip address. 
5. Forward incoming HTTP/S connections to CouchDB port or use a proxy to forward only requests to the above domain.
6. configure your CouchDB vhosts configuration to forward your domain to this app design document
