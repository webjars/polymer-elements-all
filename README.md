# Webjar for all Polymer Elements

This repository contains a Webjar-packaged snapshot of all available official Polymer Elements, using the official Polymer Element catalog bower definition.

Life is too short to sift through the Polymer Elements catalog, and bower does not play nicely with Spring Boot and other smart dependency environment.

This Webjar uses the Maven frontend plugin [https://github.com/eirslett/frontend-maven-plugin] and downloads an official
stable set of Polymer Elements versions from the official Polymer Elements catalog (if it's good enough for publishing, 
it must be good enough for development).

You might still want to prefer bower if you want to remain on the bleeding edge of Polymer element evolution.

