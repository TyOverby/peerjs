peerjs-browserify
=================

Modified the developer build of peer.js to be able to run using browserify.

You can get the package from npm.

To use, add the package "peerjs-browserify-unofficial" to your dependencies.  

See https://github.com/TyOverby/webrtc-test for an example project.

Future Plans
============

You will notice that I have the 'unnoficial' suffix on the package name.  
This is because I'm not a contributor to the peerjs project.  

Here are a few ways I could see this working out in the future.

1. I become a contributor to the official peer.js project and maintain the 
   browserify branch and npm registery.
2. I submit patches to the 'master' branch of peer.js in order to make their builds 
   browserify/node.js compliant.
3. I do what I did with this release, and keep updating the "peerjs-browserify-unofficial"
   registery whenever peer.js releases a new version.
4. ???
