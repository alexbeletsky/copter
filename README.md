# Copter.io

The web development is currently in *Front End Era*. Backbone, Angular, React (you name it) based applications are adopted and developed by companies who’s goal to provide superior user experience in browser.

*Pure* front-end applications and *no-backend* movement requires an easy to use front-end (static) applications hosting and management.

Copter.io provides a service for hosting static applications in cool way. No more FTP uploads, pure `git` management + `cli` for configuration. We provide value for developers who work on frontend applications using HTML/CSS/JS and require a platform to host their apps.

## What type of projects?

* Single Page Applications - utilizing modern front end development frameworks and consuming data of HTTP API's.

* Static Pages - landing pages, marketing sites, blogs, galleries.

* Static Resources - JavaScript, images, CSS deployed on CDN for fastest possible access.

## How to use?

As simple as you use GitHub.

Create empty `git` repository,

```bash
$ git init
```

Install copter cli,

```bash
$ npm install -g copter-cli
```

Generate single page app with Yeoman,

```bash
$ yo generate angular-static
```

Commit code to git,

```bash
$ git add . && git commit -m "my static application"`
```

Create new application,

```bash
$ copter create
copter.io: front-end deployment tool

---> creating new application "funky-rabbit-mx12.copter.io"...
---> application created, 1 install, nginx server

Success: you application created and will be available at,

http://funky-rabbit-mx12.copter.io

To deploy app to staging,

	$ git push staging master

To deploy app to production,

	$ git push production master
```

Deploy application to stage, to just see the changes,

```bash
$ git push staging master
```

Open browser and hit [http://funky-rabbit-mx12.copter.io](http://funky-rabbit-mx12.copter.io)

## Anything else?

Yes, we are open source organization all `copter.io` code is available on [GitHub](https://github.io/copter) under MIT? licence and you are free to use for your needs.

We are charging only for hosting and support.