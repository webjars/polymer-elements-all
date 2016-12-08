# Webjar for all Polymer Elements

This repository contains a Webjar-packaged snapshot of all available official Polymer Elements, using the official Polymer Element catalog bower definition.

Life is too short to sift through the Polymer Elements catalog, and bower does not play nicely with Spring Boot and other smart dependency environment.

This Webjar uses the Maven frontend plugin [https://github.com/eirslett/frontend-maven-plugin] and downloads an official
stable set of Polymer Elements versions from the bower repositories. No guarantee is offered as to the general compatibility between the different elements.

You might still want to prefer bower if you want to remain on the bleeding edge of Polymer element evolution and have full control of the dependencies, as well as a more discerning build (all in all, the resulting JAR is about 15 Mb).

