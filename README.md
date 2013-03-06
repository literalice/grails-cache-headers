# Grails Plugin: Cache Headers (patched) #

This is a patched "cache-headers" grails plugin to replace logging libraries or etc.

## Install ##

    //Build.groovy

    grails.project.dependency.resolution = {
        // ...
        repositories {
            // For the plugin
            mavenRepo "http://repository-monochromeroad.forge.cloudbees.com/release"
        }

        // ...
        plugins {
            build ":cache-headers:1.1.5.p1"
        }
    }

## Usage ##

See http://grails.org/plugin/cache-headers

